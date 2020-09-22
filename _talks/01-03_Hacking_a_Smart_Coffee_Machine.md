---
layout: talk
title: "Hacking a Smart Coffee Machine"
details: true
track: 1
accepted: true
length: 45
timeslot:
  start: 2000-01-01 12:30:00
  end: 2000-01-01 13:15:00
speakers: 
  - name: Axelle Apvrille
    handle: cryptax
    photo: 
    bio: "Axelle Apvrille is principal security researcher at Fortinet. She specifically looks into mobile malware and smart devices (not always that smart...).

She is a frequent speaker at Virus Bulletin, Insomni'hack and Hack.lu. She has also spoken at BlackHat Europe, SSTIC, TROOPERS, DefCamp, BlackAlps, Hacktivity and yet other conferences.

She is the lead organizer of Ph0wn CTF, a Capture The Flag dedicated to smart devices. "
recording_uri: https://www.youtube.com/watch?v=EvRd3Z41Ff0
slides_uri: https://fortiguard.com/events/3595/bsides-munich-2020-hacking-your-smart-coffee-machine
---

This hack has a story: I organize a Capture The Flag dedicated to IoT, called Ph0wn (https://ph0wn.org).
For that CTF, we try to have at each edition a few visual and/or real hacks in challenges.
So, I bought an affordable connected coffee machine and then, the difficult part begins: investigate it and find something that can be turned into an interesting CTF challenge.
After some time, I got lucky and identified a feature which is not available from the official connected mobile application: customize the size of coffee cups.

### Outline
This talk is about hacking a Bluetooth Low Energy coffee maker.
The hacks are more substantial than just listing the exposed BLE services and characteristics, because the coffee machine features an authorization mechanism, with a rolling code, which is not common on BLE devices.

- Hardware teardown
- How the mobile app commands the coffee machine
- Customizing cup size
- Making the coffee machine accessible on the LAN
- Conclusion