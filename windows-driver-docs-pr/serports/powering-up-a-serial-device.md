---
title: Powering Up a Serial Device
author: windows-driver-content
description: Powering Up a Serial Device
ms.assetid: 83f86da6-0acb-4cad-8856-e826c98c2182
keywords:
- Serial driver WDK , device power
- powering up serial devices WDK
- turning on serial devices WDK
- serial devices WDK , powering up
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Powering Up a Serial Device


## <a href="" id="ddk-powering-up-a-serial-device-kg"></a>


A serial device must be turned on (in the device power state **PowerDeviceD0**) for Serial to communicate with the device hardware. If the device is not turned on, Serial will attempt to turn on the device before the driver completes a request.

 

 




