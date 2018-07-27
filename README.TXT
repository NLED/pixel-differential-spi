THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. 
EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES 
PROVIDE THE PROGRAM “AS IS” WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS 
FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE 
PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL 
NECESSARY SERVICING, REPAIR OR CORRECTION.

 Original Author: Jeffrey Nygaard
 Company: Northern Lights Electronic Design, LLC
 Date: July 26, 2018
 Contact: JNygaard@NLEDshop.com
 Copyright© 2018 by Northern Lights Electronic Design, LLC. All Rights Reserved
 
;=============          www.NLEDShop.com/miscproducts          ============
;=============     www.NorthernLightsElectronicDesign.com       ============

This work is licensed under a Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
https://creativecommons.org/licenses/by-nc/4.0/legalcode

Free to use for personal use, but please attribute the original author.

Commercial licenses versions are available for a donation of any amount. Contact JNygaard@NLEDshop.com for details.

================================================================================================================

Ready-made devices are available for purchase, and large batch manufacturing of any device can be requested.
Please see the webpage www.NLEDShop.com/miscproducts

NLED is available for custom design and manufacturing, please contact via phone or email to discuss your project.

================================================================================================================

Converts TTL SPI signals into differential signals and back to TTL SPI. Useful for long distance SPI communication with
various LED pixels and other unidirection SPI devices.

Minimum Input Voltage: 5 volts
Maximum Input Voltage: 12 volts
Current Consumption: < 80mA estimated

Jumper settings:
TERM1: Signal termination. Close jumper if that channel is receiving
TERM2: Signal termination. Close jumper if that channel is receiving
DIR-J: Sets transcievers for reception or transmission. Tie center pad to R to set for reception. Tie center pad to T for transmission.
TRANS-1-J: Selects transmission or reception for channel #1. Tie to T for transmit, or R for reception
TRANS-2-J: Selects transmission or reception for channel #2. Tie to T for transmit, or R for reception
VREG-J: If using 5 volt power input, close the jumper. If using an input voltage larger than 5 volts, leave jumper open. Max input voltage is 12 volts. 

BOM:
2x SN75176BDR - SOIC-8 - or equivelent differntial transceiver
1x AP2210K-5.0TRG1 - SOT-23-5 - 5 volt linear regulator
2x 120 ohm resistor - 0805 - termination resistors
1x 1uF to 10uF >=6.3vdc - 0805 - tank capacitance
1x 100pF >=6.3vdc - 0805 - voltage regulator bypass
2x 0.1uF >=6.3vdc - 0805 - transceiver decouple