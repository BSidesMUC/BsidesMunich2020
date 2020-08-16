---
layout: talk
title: "The Art of bypassing endpoint protections for red teaming engagements"
details: false
track: 1
accepted: false
length: 45
timeslot:
  start: 2000-01-01 16:15:00
  end: 2000-01-01 17:00:00
speakers: 
  - name: Jameel Nabbo
    handle: jameel_nabbo
    photo: 
    bio: "Jameel Nabbo is the Founder of Bufferoverflows.net. Jameel has more than a decade of experience researching and working in the computer security space. He is a recognized industry speaker, having spoken at international security conferences. along with his passion for red teaming and source code analysis, Jameel works at Capgemini as a principal offensive security consultant."
recording_uri: 
slides_uri: 
---

In many red teaming engagements, the red team faces an important issue that can make their life difficult in terms of lateral movements or bypassing antiviruses since we're not in 2010. most of the organizations install antiviruses by design into their employee's computers as well as servers.


The current modern red teaming techniques require more skills and effort for creating shellcodes and gaining access to systems without being detected.
In this talk, I'll demonstrate (Advanced evasion techniques) that can by used by the red team in order to bypass modern end-point protection and signature-based detection along with shellcode development.
As some end-point protections now days uses machine learning algorithms at the top of signature-based detection and memory analysis. This makes our life as red teamers even harder when injecting a process or making syscalls.
Gaining access in certain stages, not that complex. However, maintaining our access to the compromised system makes the real challenge. Because this is exact path that Cyber criminals will follow when they gain access to any system.


In addition to the techniques of SMB related attacking techniques and methods. Running a malware and transferring files, running keyloggers is not done using only Meterpreter shells (This kind of post-exploitation just died)  since all of the shellcodes are easily detectable even when msfvenum, empire shells, powershells are encoded. That’s why it becomes more important to find new techniques and methods along with (FREE) tools to prevent being detected by the AV. 
I’ll put the spots about using .NET for creating FUD executables along with an explanation about kernel API calls and cryptography algorithms to prevent the signature-based detection mechanisms.


### Outline

 - Knowledge about end-point protection
 - Understanding of antivirus evasion techniques
 - Knowledge about Shellcode development
 - Understanding of Red team lateral movement
 - Understanding of how signature-based detection works

