---
layout: post
title: How to make an operating system
---
A lot of computer scientists or engineers wish they could write their own operating system and have such interesting experience, but a lot of them choose wrong ways to do that. In this article, we count some wrong ways, then we tell you what's the right way! 

## Wrong ways
* __Making a Linux distribution__ : 

This is what people do more than other ways, if you take a look at [DistroWatch](http://distrowatch.com), you'll find more than 1000 Linux distributions. Creating a Linux distribution is good, but when we want a working operating system with tools we need (e.g Kali Linux). Also, creating a distribution from scratch using [LFS](http://linuxfromscratch.org) can show you how a Linux system is built, but it doesn't show you how an _operating system_ works. 

* __Making builds of existing operating systems__ :

 This way is rare, but people do this to. This is just like making a Linux distribution, you never learn how that operating system works, you only learn how to build, and how to hack the existing operating system. Building [FreeBSD](http://freebsd.org) is cool and easy. Also, you can hack it every time you like, but it doesn't mean you understand what happens behind this operating system.

* __Thinking all operating system shall have GUI__ : 

This is the most __dangerous__ thought about an operating system. _Microsoft Windows_ or _Ubuntu_ or  _Apple OS X_ are most usual operating systems. All of them contain GUI, but if you read their history, you'll find all of them started with CLI (_Command Line Interface_), then the graphical interface added to them. Currently a lot of _*nix_ operating systems like __FreeBSD__ doesn't contain GUI by default. So, you don't need to think about GUI. 

## Right ways
* __Reading operating system references__ :

 This is the most important way in creating an operating system. Reading books, websites and other documents and references can help you find _what an operating system is_ and _how it works_. Websites like [OSDev](http://osdev.org) are the best references, because they're free, and have a good support on their forums and IRC channels. 

* __Learning useful programming languages__ :

A __useful__ language in this case is _the most suitable language for low-level programming_. The most common languages in operating system development are __C__ , __Assembly__, sometimes __Go__, and also in rare cases languages like __Rust__ or __Java__. 

* __Studying other projects__ :

There are thousands of projects done before you. You need to believe this! You can start with simple operating system projects like [BYOOS](https://github.com/prp-e/BYOOS) , [my16bitkernel](https://github.com/prp-e/my16bitkernel) and [MikeOS](http://mikeos.sourceforge.net). These projects are written in pure assembly, and you can learn assembly by studying source codes of these projects. Then you need to study more complex projects like [NanOS](https://github.com/nano-foundation/NanOS) , to learn more. After studying these projects, you can join one of them and help them improve their projects, or you can fork them and do what you want. After hacking and creating simple projects, you can start studying bigger projects like [Minix3](http://minix3.org). 

## Find your way
Now, you know where to start, we hope we could help you, and we hope you'll find your way after reading this article. 



