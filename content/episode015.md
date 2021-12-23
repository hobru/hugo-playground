---
draft: false
title: "The One with Azure NetApp Files - Backup"
author: Ralf Klahr
author_link: https://www.linkedin.com/in/ralf-klahr-b0144913/
recipe_image: /images/episode015-thumb.jpg #The image for your recipe
image_width: 512
image_height: 288
date: 2020-10-30T14:02:02+01:00
tags: ["ANF", "Backup"] #tags for your recipe
tagline: "Episode #15"
YouTube: https://youtu.be/MvEzYu41Mko
Anchor: https://anchor.fm/saponazure/episodes/Episode-15---The-One-with-Azure-NetApp-Files---Backup-Ralf-Klahr-elpvmt
Apple: 
Spotify:  

# For ingredient subheadings (if you use them), please use the h4 header.  For print view I have those elements targeted
---


## Introduction

In the 15th episode of our unofficial SAP on Azure video podcast we talk about even more regions, Collecting and displaying niping network latency measurements with Azure Monitor and the Global Microsoft 365 Developer Bootcamps. Ralf Klahr will continue to talk about Azure NetApp Files focusing on Backup also going in the system and doing a demo.
#MadeInWalldorf

#### Links

* [Microsoft announces plans for first datacenter region in Greece as part of “GR for GRowth” digital transformation initiative](https://news.microsoft.com/europe/2020/10/05/microsoft-announces-plans-for-first-datacenter-region-in-greece-as-part-of-gr-for-growth-digital-transformation-initiative/)
* [Microsoft to establish its first datacenter region in Taiwan as a part of its “Reimagine Taiwan” initiative](https://news.microsoft.com/apac/2020/10/27/microsoft-to-establish-its-first-datacenter-region-in-taiwan-as-a-part-of-its-reimagine-taiwan-initiative/)
* [Microsoft expands its cloud offering in Brazil, creates plan to help job matching opportunities for up to 25 million workers and skilling platform for Brazilians with Ministry of Economy](https://news.microsoft.com/es-xl/microsoft-expands-its-cloud-offering-in-brazil-creates-plan-to-help-job-matching-opportunities-for-up-to-25-million-workers-and-skilling-platform-for-brazilians-with-ministry-of-economy/)
* [Collecting and displaying niping network latency measurements with Azure Monitor](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/collecting-and-displaying-niping-network-latency-measurements/ba-p/1833979)
* [Global Microsoft 365 Developer Bootcamps](https://developer.microsoft.com/en-us/microsoft-365/bootcamps)

### Slides from the session
* [Azure NetApp Files - Part 2 - Backup](Presentations/ANF_Training_Part_II.pdf)


#### Video Index

* 0:00 Intro
* 0:59 New Azure Regions
* 4:25 Collecting niping network latency measurements with Azure Monitor
* 6:27 Global Microsoft 365 Developer Bootcamps
* 8:20 Ralf Klahr
* 9:15 Azure NetAppFiles Backup 
* 11:12 Sizing Consideration 
* 13:10 Performance Considerations
* 14:05 Log Backup Performance
* 14:30 Data Backup Performance
* 15:54 Consolidating Backup Volumes
* 17:43 Backup Options
* 18:15 Volume Design Single Node
* 21:13 Backup parameter
* 22:57 NSG setup for HANA Studio
* 23:54 Azure CLI for ANF - List Volume
* 24:51 Snapshot Directory
* 32:18 hdbpersdiag - Check consistency of the datafile
* 35:54 When you revert older snapshots
* 38:17 Azure CLI for ANF - List Snapshots
* 38:47 azacsnap
* 40:52 Configure azacsnap
* 45:10 Backup Snapshot to Azure Block Blob 
* 51:59 Recovery Process SYSTEMDB
* 52:38 CRR - Cross Region Replication
