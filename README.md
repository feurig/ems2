# EMS2

The purpose of ems2 is to create new monitor and console to remove some of the shortcomings of the origional ems framework. 

Major changes include:

* Syntax Changes
  1. 4 character keywords.
  2. hexidecimal timestamp (32 bit integer)
* Kernel Changes
  1. freeRTOS

## What is ems?
The Embedded Monitoring System is a way of developing embeded systems which may then be controlled monitored and updated using the same mechanism. EMS is initially deployed as an arduino based micontroller which talks to a python based console using a simple syntax.

 
## Reasons to rewrite.
Since ems was origionally written the processing power avaliable for less than $20 allows us to think about adding a real time operating system, file system based settings, and presets and other mechanisms that would not have been comfortable in an 8 bit restricted microcontroller. 

# MVP
EMS should support a minimal vocabulary and interaction between the console and monitor. This vocabulary should include the ability to query the device, set the time, and backup any setting and status as well as load new code to the device. 


