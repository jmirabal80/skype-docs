﻿---
title: VideoPacketLossRate element (QualityPropertiesType complexType) 
TOCTitle: VideoPacketLossRate element
ms:assetid: 493f8d16-c335-cc90-355b-16c03e86a7fa
ms:mtpsurl: https://msdn.microsoft.com/library/Mt429340(v=office.16)
ms:contentKeyID: 68250782
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# VideoPacketLossRate element 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Average fraction lost, as specified in \[RFC3550\] section 6.4.1, computed over the duration of the session. This metric is reported for video streams when available. (packets/s)

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
<td><p>Not defined</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="VideoPacketLossRate" >
    
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
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

