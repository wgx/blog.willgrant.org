---
layout: post
title: "I built the world's worst CMS"
date: 2021-03-18 00:00:00 -0000
---
In most content management systems (CMS) there's some kind of server-side datastore (usually a database) which stores the page content. A request to the front-end triggers an API call to pull the page content from the database.

I had an idea: what if the page content was part of the URL? So the link that you share around *is* the content itself?

Introducing: Anypage! 

The page content (header, subhead, body and footer) are encoded into a base64 string, and appended to the URL. The page loads, then grabs its own URL, decoding it and rendering it to the page. 

This is very hacky and probably horribly insecure but, with its own WYSWYG editor you can [create your own anypage](https://wgx.github.io/anypage/editor).