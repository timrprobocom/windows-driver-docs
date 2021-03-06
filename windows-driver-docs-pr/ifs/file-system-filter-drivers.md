---
title: File System Filter Drivers
author: windows-driver-content
description: File System Filter Drivers
ms.assetid: 9ea59c4a-d6be-4081-82e7-46539d0a1dbd
keywords:
- filter drivers WDK file system
- file system filter drivers WDK
- file system drivers WDK , filter drivers
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# File System Filter Drivers


<div class="alert">
<strong>Note</strong>   For optimal reliability and performance, we recommend using [file system minifilter drivers](filter-manager-and-minifilter-driver-architecture.md) instead of legacy file system filter drivers. Also, legacy file system filter drivers can’t attach to direct access (DAX) volumes. For more about file system minifilter drivers, see [Advantages of the Filter Manager Model](advantages-of-the-filter-manager-model.md). To port your legacy driver to a minifilter driver, see [Guidelines for Porting Legacy Filter Drivers](guidelines-for-porting-legacy-filter-drivers.md).
</div>
 

This section includes the following topics, which describe file system filter drivers:

-   [File System Fundamentals](file-system-fundamentals.md)
-   [Introduction to File System Filter Drivers](introduction-to-file-system-filter-drivers.md)
-   [Filtering IRPs and Fast I/O](filtering-irps-and-fast-i-o.md)
-   [Writing IRP Dispatch Routines](writing-irp-dispatch-routines.md)
-   [Using IRP Completion Routines](using-irp-completion-routines.md)
-   [Tracking Per-Stream Context in a Legacy File System Filter Driver](tracking-per-stream-context-in-a-legacy-file-system-filter-driver.md)
-   [Tracking Per-File Context in a Legacy File System Filter Driver](tracking-per-file-context-in-a-legacy-file-system-filter-driver.md)
-   [Blocking legacy file system filter drivers](blocking-file-system-filter-drivers.md)

 

 




