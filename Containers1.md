---
layout: post
title: Containers
permalink: /Containers1/
---

Containers Basic Tutorial
===================


Documents
-------------
Download Docker and Update CF commands
Files

 - PPT
 - Docker - [Here](https://github.com/docker/toolbox/releases/download/v1.10.0/DockerToolbox-1.10.0.exe)
 

Make sure CF is installed in your pc if yes issue the command in your CMD

> Command

> 64 bit

>- cf install-plugin https://static-ice.ng.bluemix.net/ibm-containers-windows_x64.exe
> 
> 32 bit
> 
>  - cf install-plugin https://static-ice.ng.bluemix.net/ibm-containers-windows_x86.exe

> 
#### </i> Installing Docker

 1. **Run** DockerToolbox.exe file
 2. Click next
 3. You can **unselect kitematic** since kitematic will not be used in this tutorial 
 4. Click next
 5. Click **Add docker to path**
 6. Click next
 7. Install Docker

#### </i> Setting up your Image 

Open a CMD interface and type the following

> cf login -a api.ng.bluemix.net
> cf ic login


After login enter the following command

> cf ic namespace set "new_name"