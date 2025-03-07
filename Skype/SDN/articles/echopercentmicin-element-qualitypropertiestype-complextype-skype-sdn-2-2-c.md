﻿---
title: EchoPercentMicIn element (QualityPropertiesType complexType) 
TOCTitle: EchoPercentMicIn element
ms:assetid: 16e4ae8e-31ed-f754-8805-3adc7a68dd25
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404751(v=office.16)
ms:contentKeyID: 68250664
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# EchoPercentMicIn element 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Percentage of time when echo is detected in the audio from the capture or microphone device prior to echo cancellation. This metric is reported for audio streams when available.

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
<td><p>xs:string</p></td>
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

    <xs:element name="EchoPercentMicIn"  type="xs:string">
    
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

