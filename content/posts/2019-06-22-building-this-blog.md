---
template: post
title: Building This Blog
slug: /posts/building-this-blog
draft: false
date: 2019-06-22T23:51:27.043Z
description: >-
  For a while, I've had building a simple personal blog in mind. Finally, after
  bookmarking numerous comments, tweets and reddit threads from others on how
  they've set their own blogs up, I've done it myself. I think it's only
  appropriate that the few post on my new blog be slightly meta and about the
  blog itself, so... here it is! 
category: Webdev
tags:
  - GatsbyJS
  - Netlify
  - Blog
  - Webdev
  - NetlifyCMS
---
For a while, I've had building a simple personal blog in mind. Finally, after bookmarking numerous comments, tweets and reddit threads from others on how they've set their own blogs up, I've done it myself. I think it's only appropriate that the few post on my new blog be slightly meta and about the blog itself, so... here it is! 

## The Wishlist

- Github based workflow to keep everything open source and portable
- Hosted with Netlify (they are awesome and I can't live without PR Previews anymore! 🥰)
- Markdown based formatting to keep things simple (and compatible with [Notion.so](http://notion.so) where I log basically everything I do, including drafts of these posts)
- Simple. Like really really simple. I figure that if I over complicate this I'll probably never post or do anything with it.

# The Stack

## Netlify

This was a choice that I had predetermined I would use, but I do want to justify at least a little why I want to use it. I discovered Netlify when Erick and I were looking at how we were going to deploy the frontend of the HackerAPI that was built to handle registration and hackers for McHacks 6. After a couple false starts with Github Pages and [Surge.sh](http://surge.sh), we settled on Netlify because they had a good-enough free offering and it was the first host I could get working in the time available. Wow I'm happy it worked out that way. 

Over the next few months of maintaining that site on Netlify, I discovered that it was so much more than a standard static site host. It had countless helpful features that made everything just feel nicer. Preview builds from Github PR's? Yup. Asset optimization? Yup. Super easy SSL? Yup. Potentially most interesting for this project, Identity and Netlify CMS making adding and editing posts to this blog certified *Grandma Friendly*™️.

## Gatsby

Netlify has an *awesome* site that helped a bunch once I decided that JAMstack was the best option for me (yeah, there was a 0% chance of using Wordpress 😷). [staticgen.com](https://www.staticgen.com), lets users browse different static site generating frameworks by various criteria. From this it seemed clear that the popular choices were Jekyll, Gatsby, Hugo and Next.js (using Github stars as my measure of popularity). A quick message to my resident front end wizard and former colleague over at [HackMcGill](https://github.com/hackmcgill) [Erick](https://github.com/erickzhao) returned an overwhelming opinion to go Gatsby or go home. 

<shrug> Guess I'm going Gatsby. </shrug>

## Github

I'm not going to dignify this with a paragraph. I'm using Github for version control. 

# Wrapping up...

All in all, this isn't rocket science, it's pretty simple stuff but writing about what I picked was an simple excuse to find something to post first. Expect shorter stuff most of the time from here on out.
