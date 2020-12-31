---
id: 257
title: 'GitDuck &#8211; Zoom for developers with real-time code sharing'
date: 2020-08-21T15:45:55+00:00
author: Get Freelancy
layout: post
guid: https://getfreelancy.com/?p=257
permalink: /gitduck-zoom-for-developers-with-real-time-code-sharing/
fifu_image_url:
  - https://i.imgur.com/YQaVt0G.png
fifu_image_alt:
  - GitDuck – Zoom for developers with real-time code sharing
ssb_old_counts:
  - 'a:5:{s:7:"twitter";i:0;s:9:"pinterest";i:0;s:7:"fbshare";i:0;s:6:"reddit";i:0;s:6:"tumblr";i:0;}'
ssb_total_counts:
  - "0"
ssb_cache_timestamp:
  - "446387"
image: https://i.imgur.com/YQaVt0G.png
categories:
  - Uncategorized
tags:
  - meeting
  - zoom
---
Hi everyone! We are Dragos and Thiago from [GitDuck,](https://gitduck.com) a Zoom alternative for developers with direct integration to the IDE so software developers can talk and collaborate in real-time.

The team was working on something completely different, a screen recording tool and we started to use it internally to record short videos of our code. At first it was just for quick code review sessions, but soon we found out that it was useful to also have video conferencing between team members. Essentially, we ended up creating a Zoom alternative.

After talking to almost 300 developers and learning that other people were facing similar collaboration issues we decided to focus 100% on building this tool. We are the first users and we use GitDuck internally for quick assistance, pair programming, code reviews or just discussing ideas.

It has the features you would expect in a video call tool — like audio, video chat and screen sharing, but the UX and the integrations were built exclusively for developers. You can easily share your code and do pair programming. We are building integrations for all the IDEs. This enables you to collaborate without screen sharing (so it&#8217;s faster and and consumes less bandwidth), directly from your IDE and independently of the IDE that other people are using.

Whenever you join a GitDuck meeting, your IDE extension wakes up and allows you to share your code with the other meeting participants (or join the already shared code from other meeting participant). When your peers join your code, they can see and edit your files in real-time, similar to the Google Docs experience. At any given point you can also go to your peers position so you can see in which file and line they are.

Check a 1 min demo: <https://gitduck.com/watch/5f1808919552aefe64ce0751>

GitDuck currently has integrations to VS Code and VSCodium, with future plans for implementing JetBrains IDEs. Sublime and other IDE platforms are also in the works.

It is important to mention security & privacy, something Zoom is notoriously lacking. We are the first users of the service so we focus a lot on building something that we would trust to use ourselves. All the files shared from your IDE are always shared via peer-to-peer and are end-to-end encrypted. No piece of code never touches our servers, so we never have access to your code.

All calls are encrypted and p2p (if 4 or less participants). If 5 or more people join we switch to a cloud infrastructure in order to maintain the quality, but the media are always encrypted and we never have access to your calls. You can read more about it here (https://gitduck.com/security) and we are always open for your suggestions to improve.