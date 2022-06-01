---
title: Setup VScode (incl Remote Development)
date: 2022-05-31 17:03:00 +1
categories: [documentation,code]
tags: [no-use,sample,practice]
author:
  name: Pwalo the Great
  link: https://pwalo.github.com
---

### Visual Studio Code and remote development extension

> **Info:** In this walk through we are setting up VScode on a Windows 11 environment with WSL2:Ubuntu already installed and up to date  
{: .prompt-info }  

#### Why the remote development extension  

This is personal choice, totally optional, and if you don't want to do it you will easily find other methods favoured by other people online

#### What is remote development used for  

In this environment it is used to access the filesystem used in WSL and can execute code inside WSL.  It is a efficient way of working that allows you to shut down your dev environment when not in use by just not running your WSL distro.  Oftentimes installing runtime environments in windows will have the undesired effect that it uses system resources even when you are not using it  

