﻿---
title: RecvNoiseLevel element (QualityPropertiesType complexType) 
TOCTitle: RecvNoiseLevel element
ms:assetid: fae4e247-001c-00ff-c6c0-444ca428eb6e
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170960(v=office.16)
ms:contentKeyID: 65855535
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# RecvNoiseLevel element 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Received noise level in units of dB that is reported for audio streams when available. Average energy level of received audio is classified as noise, mono signal or the left channel of stereo signal. (dB)


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:int</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="RecvNoiseLevel"  type="xs:int">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

