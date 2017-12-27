---
title: WIA\_IPS\_PRINTER\_ENDORSER\_MAX\_GRAPHICS
description: The WIA\_IPS\_PRINTER\_ENDORSER\_MAX\_GRAPHICS property describes the maximum number of images that the Imprinter/Endorser item can print or endorse on each page.
ms.assetid: A8FB39D2-659C-45E9-BE5E-627E594B9D3A
keywords: ["WIA_IPS_PRINTER_ENDORSER_MAX_GRAPHICS Imaging Devices"]
topic_type:
- apiref
api_name:
- WIA_IPS_PRINTER_ENDORSER_MAX_GRAPHICS
api_location:
- Wiadef.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# WIA\_IPS\_PRINTER\_ENDORSER\_MAX\_GRAPHICS


The **WIA\_IPS\_PRINTER\_ENDORSER\_MAX\_GRAPHICS** property describes the maximum number of images that the Imprinter/Endorser item can print or endorse on each page. This property is useful when the Imprinter/Endorser item supports graphics upload via multi-page (TYMED\_MULTIPAGE\_FILE) file format transfers. This property is initialized and maintained by the WIA mini-driver, and is available with Windows 8 and later versions of Windows.

Property Type: VT\_UI4

Valid Values: WIA\_PROP\_NONE

Access Rights: Read-only

Remarks
-------

The **WIA\_IPS\_PRINTER\_ENDORSER\_MAX\_GRAPHICS** property is optional for the Imprinter/Endorser items that support graphics upload. When implemented, the property value **must be** greater than zero (0).

For more information about the TYMED\_MULTIPAGE\_FILE constant, see [**WIA\_IPA\_TYMED**](wia-ipa-tymed.md).

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Wiadef.h (include Wiadef.h)</td>
</tr>
</tbody>
</table>

## <span id="see_also"></span>See also


[**WIA\_IPA\_TYMED**](wia-ipa-tymed.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20WIA_IPS_PRINTER_ENDORSER_MAX_GRAPHICS%20%20RELEASE:%20%2811/13/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




