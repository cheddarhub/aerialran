---
layout: default
title: Timing
nav_order: 1
has_toc: false # on by default
has_children: false
comments: true
usetocbot: true
---
# {{ page.title }}
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---


# Theoretical Background
ORAN Specs, LLS Splits and Boundary Clocks


# Practical Deployment
There are several possible configurations which can be adopted for enabling the fronthual deployment for ORAN. The most common deployment involves a grandmaster which provides timing signal based on GNSS. In our deployment, we employ [VIAVI QG2 Multisync gateway](resources/PTPGuide.pdf). 
The QG2 Multi-Sync Gateway that provides IEEE 1588-2008 PTP grandmaster and BC functionality. QG2 is capable of getting its timing information from builtin GNSS receiver or 1pps/ToD input or IEEE 1588 PTP input. The QG2 provides output in the  1pps/ToD and [IEEE 1588-2008](https://standards.ieee.org/ieee/1588/4355/) PTP formats.

{: .note-title }
PPS
Pulse per second (PPS) signals are commonly employed to attain synchronisation between various components. The pps signal outputs a square pulse which has one rising edge per second. The devices synchronise using this rising edge. Since the timing offset between the rising edges can be ensured to be of the order of nano-seconds. It is possible to attain nano-second level synchronisation. 


# Security Issues 




# Post-Deployment Management






