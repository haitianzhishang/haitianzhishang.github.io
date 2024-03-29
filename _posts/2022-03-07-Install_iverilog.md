---
title: iverilog install
layout: post
post-image: "https://i.ytimg.com/vi/5Kync4z5VOw/mqdefault.jpg"
description: Install iverilog simulator and gtkwave wave viewer in Ubuntu
tags:
- Tools
---

# Iverilog simulator

------
## Add the universe repository in /etc/apt/source.list

```shell
sudo vim /etc/apt/sources.list
Add below repos in this file
deb http://archive.ubuntu.com/ubuntu/ edgy universe 
deb-src http://archive.ubuntu.com/ubuntu/ edgy universe
Then run
sudo apt-get update
sudo apt-get install iverilog
```

## PPA for Icarus verilog

```shell
sudo vim /etc/apt/sources.list
Add below repos in this file
deb http://ppa.launchpad.net/team-electronics/ppa/ubuntu jaunty main 
deb-src http://ppa.launchpad.net/team-electronics/ppa/ubuntu jaunty main
```

## Add repository key to system to avoid warnings

```shell
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 7FE97A0D3D7F2EA1
```

## Update the local repository cache and Install (update) the Icarus verilog package

```shell
sudo apt-get update
sudo apt-get install verilog
```

## Add a new PPA

```shell
sudo add-apt-repository ppa:team-electronics/ppa
sudo apt-get update
sudo apt-get install verilog
```

## Install gtkwave 

```shell
sudo apt-get install gtkwave
```

------

Details can be found at **[iverilog website](http://iverilog.icarus.com/ )**

