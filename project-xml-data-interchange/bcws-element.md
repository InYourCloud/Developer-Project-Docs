﻿---
title: BCWS Element
TOCTitle: BCWS Element
ms:assetid: 0e9e4541-0619-4545-bc05-63826397c10f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Bb968411(v=office.12)
ms:contentKeyID: 13188104
ms.date: 05/05/2014
mtps_version: v=office.12
f1_keywords:
- BCWS element
---

# BCWS Element

This content is outdated and is no longer being maintained. It is provided as a courtesy for individuals who are still using these technologies. This page may contain URLs that were valid when originally published, but now link to sites or pages that no longer exist.

BCWS is the budgeted cost of work scheduled.

For a Task, BCWS is the cumulative timephased costs up to the status date or today's date.

For a Resource, it is the rolled-up summary of a resource's BCWS values for all assigned tasks.

For an Assignment, it is the budgeted cost of work on the assignment.

For a Baseline in a Task, BCWS is the cumulative timephased baseline costs up to the status date or today's date.

For a Baseline in a Resource, it is the budgeted cost of the work performed by the resource.

For a Baseline in an Assignment, it is the budgeted cost of work on the assignment to the current date.

    <BCWS>
      DecimalValue
    </BCWS>

## Parent Elements

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><a href="bb968487(v=office.12).md">Task</a>, <a href="bb968715(v=office.12).md">Resource</a>, <a href="bb968611(v=office.12).md">Assignment</a>, <a href="bb968599(v=office.12).md">Baseline</a></p></td>
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
<p>Maximum: 1</p></td>
</tr>
</tbody>
</table>

## See Also

#### Concepts

[Task Elements and XML Structure](bb968475\(v=office.12\).md)

[XML Schema for the Tasks Element](bb968415\(v=office.12\).md)

[Resource Elements and XML Structure](bb968445\(v=office.12\).md)

[XML Schema for the Resources Element](bb968511\(v=office.12\).md)

[Assignment Elements and XML Structure](bb968738\(v=office.12\).md)

[XML Schema for the Assignments Element](bb968414\(v=office.12\).md)
