---
layout: post
section-type: post
title: LTE Basics
category: Category
tags: [ 'tag1', 'tag2' ]
---

In cellular networks, a limited resources needs to be shared with all users so that full duplex communication is possible.

# Difference between TDD-LTE and FDD-LTE?

LTE is defined to support the paired spectrum(that evolved from the migration path for 3G) for FDD as well as the unpaired spectrum(that evolved from TD-SCDMA) for TDD. The TD-LTE is cheaper than FD-LTE since there is no need for a diplexer to isolate the receptions. In TD-LTE its possible to change the uplink and downlink ratio to suit the needs of the use case. In the case of FD-LTE, capacity depends on frequency allocation that is carried out by regulatory authorities, and hence it is more difficult to make a dynamic change. 

| TDD-LTE(TD-LTE) | FDD-LTE(FD-LTE) |
| --------------- | --------------- |
| TDD-LTE uses the unpaired spectrum(that evolved from TD-SCDMA) for TDD. | FDD-LTE uses the paired spectrum(that evolved from the migration path for 3G). | 
| TDD-LTE is cheaper than FDD-LTE because there is no need for a diplexer to isolate receptions. | FDD-LTE requires a diplexer. |
| In the TD-LTE it is possible to change the uplink and downlink ratio to suit the use cases. | In the case of FD-LTE, the capacity depends on frequency allocation is carried out by regulatory authorities, and hence it is more difficult to make a dynamic change. |

# What is a radio frame? 

There are two types of radio frames designed for the LTE: 

## Type-1 frame structure 

This frame structure is designed for Frequency Division Duplex. It is valid for both half duplex and full duplex modes. One typical LTE frame length duration is 10 ms. It consists of 20 equally sized slots of 0.5ms each. Each sub-frame has 2 slots. Thus 1 frame has 10 sub-frames. In full duplex mode, half of the sub-frames are available for downlink and the other half for uplink. 

<p align="center">
    <img src="http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif">
</p>

## Type-2 frame structure 

This frame structure is designed for Time Division Duplex. Each frame is 10ms long and consists of two half frames that are 5ms long. Each half frame is split into five sub-frames, each of which is 1ms long. 

## Sources: 

* [http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif](http://www.radio-electronics.com/images/type-1-lte-frame-structure.gif)
