---
title: Iverilog include file
layout: post
post-image: "http://www.icarus.com/eda/verilog/faq-title.png"
description: Error when compiling RTL with include
tags:
- Tools
---

# Iverilog include file



### The including file and module in testbench can't be found.

![](https://i.stack.imgur.com/g4eXf.png)

The original source list is below

![](https://i.stack.imgur.com/WYx3d.png)

### Fixed by adding  +incdir 

![](https://i.stack.imgur.com/oBjBk.png)
