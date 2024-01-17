---
layout: post
date: 2024-01-17T15:22:06+0800
title: tips for arch linux
description: 
category: arch-linux
---

1. 休眠相关

    - 相关配置文件
        
        > /etc/systemd/logind.conf  
        > /etc/systemd/system/suspend@.service

    - 命令行

        > $ echo mem \| sudo tee /sys/power/state

    - 无操作时自动休眠
        > $ sudo vi /etc/systemd/logind.conf  
        > IdleAction=suspend  
        > IdleActionSec=1min  
    
    - 


