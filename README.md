# Welcome to Awesome-AV 🤘

**WORK IN PROGRESS! STAR ME AND COME BACK SOON**

The purpose of this list is collect the very best in modern software-focused technology resources for AV software pros. We're pushing boundaries here so don't expect to find a bunch of (.*)tron 😉

I'd love to see your contributions if you see something missing (there certainly will be) so feel free to drop an issue!

# The dream
Years ago I was responsible for a few thousand meeting spaces at a rather large global enterprise. It was chaos. Managing a heterogenous environment of 10,000+ endpoints is not for the feint of heart. Why? 

- No single-pane-of-glass...no tools in the industry were able to bring everything into one portal. So every time you need DATA or to TROUBLESHOOT something, you're collating that data yourself. IN YOUR HEAD. IN EXCEL. IN EMAILS. Blegh.
- Absolute LACK of standard monitoring / management protocols in AV devices...asl known as: "What do you mean I need to connect to a console over TCP xyz and send a HEX encoded string, then parse the response and push it to my monitoring platform?" Or perhaps "Wait, you don't support SNMP?"
- "Walled gardens". MOST AV manufacturers seems genuinely disinterested in working with eachother. While CONTROL specifications / APIs have generally become more open, MONITORING and MANAGEMENT interfaces are still relegated to vendor point tools, local web interfaces, and "weird" TCP interfaces.
- Lots of use of vendor desktop apps. Kill me now. "**I. AM. NOT. IN. THE. ROOM.**" I need to AUTOMATE my responses, not log into my laptop, connect to the vpn, open your horrible app, and then finally be able to fix something. 
- In general: AV systems are made to be managed by HUMANS still, not by robots. We should fix that...or at least learn how to work around it.
- More bullets are going to come to me, I know it...

# So, I learned Python
And that allowed me to do some MAGICAL things, like:
- Update the configuration of over 1000 Poly Trios in batches, and perform test calls with each phone, validating each phone was able to reach the designated platform (Zoom) and spitting out a list of all phones that failed. Doesn't seem all that cool to me now, but it changed my life. 

Python opened me up to superpowers I was unaware of before. But Python was just the start. Shortly after came Linux. With that I started learning sysadmin tools like Ansible, Bash, PowerShell (meh), netcat, grep & awk, expect, and many more this list will capture. Then the 2nd largest revelation of my career happend 🐳

# Enter Docker
Containers really changed the whole game for me. I'll spend lots of time on them in this repo I'm sure. They allowed me to take all of my newly aquired powers and make them PORTABLE. And that led me down the path I'm on today, using containers as the runtime for AV applications. More to come on this later. 

# The List
Let's kick this off!

## Operating systems
- Linux
    - Specifically just start with Ubuntu server and LOTS of Googling
- Windows 11
    - Perhaps a bit obvious, but it's actually great for devs now since they've added...
    - [WSL2](https://learn.microsoft.com/en-us/windows/wsl/about)! Run Ubuntu, Alma, etc right on your Windows machine. It's great for learning sysadmin tools. Not great for developing VM images 😉
- Mac
    - I used to be a big Mac user, but it's not part of my daily anymore. That being said, it's still a *nix kernel and most of the admin tools are going to work juuuusst fine on your sweet-ass MacBook pro. 

## Sysadmin Tools
- Bash
- Ping / Fping
- pinginfoview
- Netcat
- SSH
- nano
- grep
- awk
- expect
- httpie

## Software Languages
- Bash
- JavaScript
- Python

## Developer tools
- VS Code
- Docker
- GitHub

