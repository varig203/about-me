---
layout: post
title: (CANCELLED) Project Ares Server Info
date: 2024-04-13 13:54 -0700
tags: 
 - server
 - info
toc: true
pin: false
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

Like any decent server this has plugins. I will update this plugin list over time once more plugins support Folia (e.g. NoChatReports, ).

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

#### ProtocolLib

Just a dependancy for AEF (AnarchyExploitFixes).

### Spark

A profiler for the server, I will be using it for monitoring the server while away. For more info go to [spark github](https://github.com/lucko/spark)

## Hardware

So, the biggest thing for the server will be the hardware. Unlike my other servers, this one will be run locally.

### Main server hardware

The main server is my old PC.

- CPU: Ryzen 7 3700x (16) @4.2GHz
- MEM: 32 GB DDR4 3200MHz
- STOR: Unknown TB
- OS: Fedora Linux Server 39

### Test server hardware

The test server is my current PC.

- CPU: Ryzen 9 7900x (24) @5.7GHz
- MEM: 64 GB DDR5 6400MHz
- STOR: 2.5 TB (2500 GB)
- OS: Arch Linux x86_64
