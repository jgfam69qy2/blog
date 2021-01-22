---
title: This thing is still up, Who are you?
layout: post
---

So it has been a while, but I finally managed to write something. Mainly because I'm on vacations, and did a thing for myself, instead of he biddings of my employer.

I've been working on my DNS server (a raspberry with pihole and the cloudflare DoH proxy). The thing is, it was set up manually and in a write once way, meaning that if I had to update, improve, or even duplicate it, I would have to find out where all the files are and move them to the other sd card. Whereas now, albeit not fully automated, the services that have to run on the card are ephemeral containers, and most of of the settings sit inside of the sytemd unit files for them.

Sure I still have to setup the network, some packages and disable/enable some services. but that is easier, and can be automated in a later stage. Plus, I now know where everything is: a README.md in a git repo.

So. keep on committing.
Later.
