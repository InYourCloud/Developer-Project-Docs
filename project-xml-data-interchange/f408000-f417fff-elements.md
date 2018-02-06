﻿---
title: f408000 - f417fff Elements
TOCTitle: f408000 - f417fff Elements
ms:assetid: cc4a5f30-5707-4861-8243-18bd138dcc95
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Bb968688(v=office.12)
ms:contentKeyID: 13188378
ms.date: 05/05/2014
mtps_version: v=office.12
f1_keywords:
- f408000 - f417fff elements
---

# f408000 - f417fff Elements

This content is outdated and is no longer being maintained. It is provided as a courtesy for individuals who are still using these technologies. This page may contain URLs that were valid when originally published, but now link to sites or pages that no longer exist.

An assignment-level enterprise custom field value.

    <f408000>
        CustomFieldValue
    </f408000>

## Parent Elements

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="bb968611(v=office.12).md">Assignment</a></p></td>
</tr>
</tbody>
</table>

## Occurrences

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum: 0</p>
<p>Maximum: 1 of each unique element name</p></td>
</tr>
</tbody>
</table>

## Text Value

A text value is required. The text specifies the enterprise custom field value for the assignment.


> [!NOTE]
> The text value must match the data type required by the custom field definition.


## Remarks

The name of the XML element that stores the enterprise custom field value corresponds to the hexadecimal representation of the custom field ID.

Table 1 lists the valid range of custom field IDs for assignment-level enterprise custom fields in both decimal and hexadecimal format.

Table 1. Assignment-level Enterprise Custom Field IDs

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Custom Field ID range (decimal)</p></th>
<th><p>Custom Field ID range (hexadecimal)</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>255885312-255950847</p></td>
<td><p>f408000-f417fff</p></td>
</tr>
</tbody>
</table>

For more information, see [Custom Field Data in XML](bb968687\(v=office.12\).md).

## See Also

#### Concepts

[Assignment Elements and XML Structure](bb968738\(v=office.12\).md)

[XML Schema for the Assignments Element](bb968414\(v=office.12\).md)
