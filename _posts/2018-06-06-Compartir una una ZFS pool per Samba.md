---
layout: post
title: "Compartir ZFS amb Samba"
date: 2018-06-06
categories: linux zfs samba centOS
---

La informació que he fet servir està extreta de [hiroom2](https://www.hiroom2.com/2016/05/18/ubuntu-16-04-share-zfs-storage-via-nfs-smb/) on explica com fer-ho en una màquina amb ubuntu.

* Per tal de poder compartir una zfs pool mitjançant samba el primer que necessitem és instaŀlar samba.
**Si ja tens samba al sistema pots pasar al seguent punt**

{% highlight shell %}

yum install -y samba

{% highlight shell %}

* Configuració:
