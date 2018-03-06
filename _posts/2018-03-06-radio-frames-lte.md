---
layout: post
section-type: post
title: Title
category: Category
tags: [ 'tag1', 'tag2' ]
---

# What is a radio frame? 

There are two types of radio frames designed for the LTE: 

## Type-1 frame structure 

    * Frame structure is designed for Frequency Divion Duplex
    * Valid for both half duplex and full duplex modes
    * Radio Frame duration is usually 10ms
        * Consisting of 20 equally sized slots of 0.5ms each.
    * In full duplex mode, half of the subframes are available for downlink and the other half for uplink. 

## Type-2 frame structure 

    * Frame structure is designed for Time Division Duplex
    * Each radio frame is composed of 2 half frames 
    * Each half frame has a duration of 5ms 
        * Each half frame is divided into 5 subframes having 1ms.
