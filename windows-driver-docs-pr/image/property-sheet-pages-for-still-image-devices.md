---
title: Property Sheet Pages for Still Image Devices
author: windows-driver-content
description: Property Sheet Pages for Still Image Devices
ms.assetid: ef77e57d-f791-4afa-8d51-67e78b60cf57
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Property Sheet Pages for Still Image Devices


## <a href="" id="ddk-property-sheet-pages-for-still-image-devices-si"></a>


You can provide a DLL that creates device-specific property sheet pages. The Scanners and Cameras Control Panel calls the DLL's entry point when a user attempts to view the device's property sheet.

To cause this DLL to be installed and used, you must include a **PropertyPages** entry in your setup information (INF) file. This entry contains the DLL's file name and entry point name. For more information, see [INF Files for Still Image Devices](inf-files-for-still-image-devices.md).

 

 




