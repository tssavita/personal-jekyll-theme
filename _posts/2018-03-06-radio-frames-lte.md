---
layout: post
section-type: post
title: What is a radio frame? 
category: Radio
tags: [ 'TDD', 'Time Division Duplex', 'FDD','Frequency Division Duplex', 'LTE' ]
---

# What is a radio frame? 

There are two types of radio frames designed for the LTE: 

## Type-1 frame structure 

This frame structure is designed for Frequency Division Duplex. It is valid for both half duplex and full duplex modes. One typical LTE frame length duration is 10 ms. It consists of 20 equally sized slots of 0.5ms each. Each sub-frame has 2 slots. Thus 1 frame has 10 sub-frames. In full duplex mode, half of the sub-frames are available for downlink and the other half for uplink. 

<p align=center>

![LTE Frame Structure](http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif)

</p>

## Type-2 frame structure 

This frame structure is designed for Time Division Duplex.
    * Frame structure is designed for Time Division Duplex
    * Each radio frame is composed of 2 half frames 
    * Each half frame has a duration of 5ms 
        * Each half frame is divided into 5 sub-frames having 1ms.

## Sources: 

* [http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif](http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif)
