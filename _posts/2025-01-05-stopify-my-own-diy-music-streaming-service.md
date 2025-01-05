---
layout: post
title: "Stopify - my own DIY music streaming service"
date: 2025-01-05 00:00:00 -0000
---
My relationship with Spotify has changed over the years. I’ve had my account for 11 years and I’ve listened to over a million minutes of music. I’ve made playlists for 1,000s of people, discovered artists and whole genres and generally loved Spotify - and been an evangelist for it. 

Sadly, Spotify has completed its cycle of [enshitttification](https://en.m.wikipedia.org/wiki/Enshittification) and I’m going to leave. First it was the [terrible amounts they pay artists](https://www.un-wrapped.online/#start) and most recently it’s [the “ghost artists” controversy](https://harpers.org/archive/2025/01/the-ghosts-in-the-machine-liz-pelly-spotify-musicians/). I’ve been directly exposed to this second one personally. 

In 2019 I made a playlist called “Songs for Dogs to Sleep To” - for my dog Alfie. It got a few hundred followers, then a few thousand and it peaked at 9,000 followers. 9,000 dogs would be treated, daily, to soothing music I selected. 

Then, without warning, my playlist was hard-deleted by Spotify for “copyright infringement”. Several pleas to help and support yielded nothing. It was gone. Shortly replaced by Spotify’s own Songs for Dogs playlist. 

For new music discovery Spotify is still great - but I can do that with [Soundcloud](https://soundcloud.com/discover). For playing the “old favourites” - albums and artists I come back to again and again - I need my own streaming service. Join me on this adventure…

## Step 1: getting the media

I have a lot of vinyl, but that’s harder to digitise. In the attic there’s maybe 500 to 700 CD albums, so - while returning the Christmas tree to its resting place for the next 11 months - I retrieved many boxes and flight cases of CDs. 

(ADD:img boxes of CDs)

I have a few computers but my more recent ones don’t have an optical drive. Enter the HP Elitedesk! This bad boy has a DVD-RAM which can read CDs at 8x normal speed if needed. I installed EAC for Windows[link], and tweaked some settings: 1) auto-lookup the track info from a DB, 2) name the tracks %artist% %tracknum% %tracktitle% (in case I want to manipulate them later, and 3) eject when done with a beep. 

You would think that feeding hundreds and hundreds of CDs into a computer was a huge chore, but it really wasn’t that bad. If I was working in the office and the machine finished, I would swap CD and if I happen to be walking past the office, I could pop in and swap a CD. CD swapping has been the theme of Christmas 2024. 

I extracted the audio as WAV, uncompressed - the full 1:1 digital copy of the disc data. I figured this would allow me to do more accurate compression later if I needed to.

## Big problem 1: Spotify is ubiquitous. 

This is big-tech hegemony that we have allowed. 
I have Spotify in my car. I have Spotify in my kitchen on an Amazon speaker thing. I have Spotify in my living room on a Sonos system. How can I get my own DIY streaming system to work like this, with all my devices? This is a problem we need to solve. Later…

## Step 2: reliable storage

Storage is cheap. It used to be expensive to store data - but nowadays - storing terabytes (or even petabytes) is pretty cheap. My entire CD collection comes to about 250Gb uncompressed. My basic Dropbox plan includes 1Tb of storage: this should be easy. 

There’s a [backup strategy](https://en.wikipedia.org/wiki/Backup) called 3,2,1: Three copies of the data are made, the copies are stored on two different types of storage media and one copy of the data is sent offsite.

Three: SSD, HD and Cloud
Two: HD and Cloud
One: Cloud

So, I need to store the files on my SSD and also back them up to HD. Easy. And somehow copy them reliably to a cloud hosting service. Dropbox? I have an Amazon web services account, maybe S3?

Up next time: Adventures in the cloud. 

To be continued… 
