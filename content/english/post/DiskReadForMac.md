---
title: "Disk Read For Mac"
date: 2021-08-26T15:57:15+08:00
draft: true

tags: ["disk", "mac", "ntfs"]
---

#### author: zengjie

- **open** `terminal.app`

- **run** `open /System/Applications/Utilities/Disk\ Utility.app`

- **read disk name and remember it**

- **run** `sudo vim /etc/fstab`

- **insert** `LABEL={disk name} none ntfs rw,auto,nobrowse`

- **run** `cd /Volumes/`

- **you can transmit data**
