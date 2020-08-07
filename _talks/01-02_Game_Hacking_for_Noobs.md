---
layout: talk
title: "Rush B, Blyat! - Game Hacking for Noobs"
details: false
track: 1
accepted: true
length: 60
timeslot:
  start: 2000-01-01 11:45:00
  end: 2000-01-01 12:30:00
speakers: 
  - name: Philipp Schmied
    handle: CaptnBanana
    photo: 
    bio: "Servus! My name is Philipp and I do red teaming and penetration testing. My main interests are in the field of reverse engineering and exploit development. I'm blogging regularly about those topics at https://bananamafia.dev."
recording_uri: 
slides_uri: 
---

Over the past year I’ve noticed that many people are particularly interested in the field of multiplayer game hacking, since these kinds of blog posts get quite a few clicks on my blog.
Detailed information on this topic is hard to find on the internet, especially documentation of game hack source codes.
That’s the reason why I decided to create two game hacks myself, with the goal to share my knowledge afterwards.
Two hacks have been created for this purpose: A wallhack for the Quake3 engine based game Jedi Academy and an aimbot/NoFlash hack for Counter Strike: Global Offensive.
A wallhack let’s you see enemies through walls and an aimbot automatically aims at enemies.
With NoFlash flashbangs that block a person’s view are getting neutralized.

Knowledge in this field is relevant for various reasons:

 * A while ago, a professional CS:GO player was caught cheating with an aimbot during a live
tournament. This case has caught media attention and also started the discussion of private
and paid cheat subscription models, which have been around for quite some time in the
professional e-sport segment
 * Reverse engineering games and their internals, such as memory management, is fun and the
knowledge can be applied to various other things like malware analysis
 * I think the techniques to interfere with other process memory in order to alter program flow
is quite interesting :)

I’d like to share the knowledge I’ve gathered in this field and present my results at BSides Munich.


### Outline

1. Motivation: Why I think this topic is quite interesting
2. Setup: Technical prerequisites and tooling in order to get started with game hack development on both Windows and Linux
3. Internal Hacks On Windows
4. External Hacks on Linux
5. Other Techniques: For example using Frida to hook function calls using an injected JavaScript interpreter

