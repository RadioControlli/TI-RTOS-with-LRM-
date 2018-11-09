# TI-RTOS-with-LRM-
 TI-RTOS Overview TI-RTOS is a real-time operating system for TI microcontrollers. TI-RTOS enables faster development by eliminating the need for developers to write and maintain system software such as schedulers, protocol stacks and drivers. It combines a real-time multitasking kernel with additional middleware components including TCP/IP and USB stacks, a FAT file system, and device drivers, enabling developers to focus on differentiating their application. TI-RTOS provides a consistent embedded software platform across TI’s microcontroller devices, making it easy to port legacy applications to the latest devices.
 
# SIMPLELINK-EASYLINK
 
The CC13xx EasyLink API is a simple abstraction layer on top of the CC13xx RF Driver and is intended as a starting point for customers creating a proprietor Sub1G protocol. The EasyLink layer does not support any regional RF conformance such as Listen Before Talk required for the license free frequency band. Customers need to add support for the regional conformance that their product requires under the EasyLink API.
The API and examples are available in TIRTOS for SimpleLink MCU's version 2.14.03.28 and greater, which can be downloaded from: http://software-dl.ti.com/dsps/dsps_public_sw/sdo_sb/targetcontent/tirtos/index.html

For instruction on using the TIRTOS examples refer to C:\ti\tirtos_simplelink_<version>\docs\tirtos_cc13xx_cc26xx_Getting_Started_Guide.pdf.

The EasyLink Example can be found in the resource explorer under SimpleLink Wireless MCU->CC1310F128->CC1310 Development Kit->Driver Examples->TI Driver Examples->RF Examples:

- RF EasyLink Tx
- RF EasyLink Rx
- RF EasyLink Network Processor
- RF Wireless Sensor Network Concentrator
- RF Wireless Sensor Network Node

The required HW for running the examples is the CC1310DK: http://www.ti.com/tool/cc1310dk
