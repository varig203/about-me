---
layout: post
title: Project Ares Server Info
date: 2024-04-13 13:54 -0700
tags: 
 - server
 - info
toc: true
pin: true
img_path: assets/img/posts/anarchyserverpost/
<author_id>:
  name: <full name>
  url: <homepage_of_author>
---

This server will have an interesting twist to my regular style of SMP's. Instead this server will be an anarchy server and, this article will explain how it will all work.

![Folia Logo]({{ page.img_path }}folia.png){: .normal }
_Folia logo credits to [PaperMC/Folia](https://github.com/PaperMC/Folia)_

## Folia
That's right! This server runs on Folia which is a multithreaded Minecraft server made by the PaperMC team. Why Folia over any other server? Folia has been chosen due to the nature of this being an anarchy server and that I am expecting server sided lag to happen. You will not need any special client to open the server due the server being completely vanilla, gameplay wise. Java edition will be required until [GeyserMC](https://geysermc.org/) with [Floodgate](https://wiki.geysermc.org/floodgate/) can be implemented.

### How does it work?
Basically it splits up the world into regions so, in this case it would split the overworld into 4 regions handled by different threads. In vanilla each dimension is given a single thread.

## Rules
Well it is an anarchy server so anything is allowed right? Not exactly, breaking the law is not allowed (e.g. DDoS, Doxxing, etc). However, you are allowed to cheat and use hacked clients and say anything you want in chat as long it is legal.

### Quick rundown of rules:
1. Do not DDoS the server nor any of it's players. (Punishment: Permanent IP Ban)
2. Do not Dox anyone. (Punishment: Chat Ban)

## Server Plugins
Like any decent server this has plugins.

### Greentext
Self explanatory if you know what greentext is but if you don't, greentext is literally green text. To use this plugin just type. (Remove the curly braces)
```sh
>{Insert message here}
```

You are also able to make it orange.
```sh
>{Orange Message}
```

### MiniMOTD
This plugins whole purpose is to have a pretty looking MOTD that's it.

### Chunky
It's just a chunk pregenerator. Why was it added? To improve performance a bit more.

### AnarchyExploitsFixes
Way too large of a [feature list](https://hangar.papermc.io/Ginko/AnarchyExploitFixes#features). Basically it just fixes a bunch of bugs encountered on other anarchy servers like the NoCom exploit for example. I will disable some features of it though.

