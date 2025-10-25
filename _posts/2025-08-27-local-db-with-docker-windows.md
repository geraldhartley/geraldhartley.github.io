---
layout: post
title: Configure a Local SQL Server Database using Docker
author: gerald-hartley
published: true
---

In this post, I'll be documenting the setup and configuration of a local SQL Server database using Docker for Windows

Once upon a time, having a local copy of the database involved installing a copy of SQL Server on your local machine. While it wasn't a complicated process, times have changed since then, especially with the advent of virtualisation options

In this instance, we'll be able to set up a virtualized SQL Server database on our local machine, all set up and ready to go within minutes. No messy installations and system footprint on your local machine, resources and system files are contained within their own environment. 



Prerequisites

1. Windows Subsystem for Linux (WSL2) - this will be used to host the Linux environment used to host dbt core
2. Docker for Windows - you can use this to spin up a database on your local machine before deploying to your Azure SQL Database
2. VS Code - IDE which will allow you to connect to your environment. We will use this to connect to our environment

Setup:
1. Setup your profile.yml file
2. Setup your dbt_project.yml file
3. Configure your VS code environment


