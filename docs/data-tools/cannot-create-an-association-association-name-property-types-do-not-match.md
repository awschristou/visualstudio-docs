---
title: Property types do not match
description: 'Cannot create an association - property types do not match. View information about this Visual Studio Object Relational Designer (O/R Designer) message.'
ms.date: 11/04/2016
ms.topic: error-reference
author: ghogen
ms.author: ghogen
manager: mijacobs
ms.subservice: data-tools
---
# Cannot create an association &lt;association name&gt; - property types do not match

Cannot create an association \<association name> - property types do not match. Properties do not have matching types: \<property names>.

Associations are defined by the selected **Association Properties** in the **Association Editor** dialog box. Properties on each side of the association must be of the same data type.

The properties listed in the message do not have the same data types.

## To correct this error

1. Examine the message and note the properties called out in the message.

2. Click **OK** to dismiss the dialog box.

3. Inspect the **Association Properties** and select properties of the same data type.

4. Click **OK**.

## See also

- [LINQ to SQL tools in Visual Studio](../data-tools/linq-to-sql-tools-in-visual-studio2.md)
- [How to: Create an association between LINQ to SQL classes (O/R Designer)](../data-tools/how-to-create-an-association-relationship-between-linq-to-sql-classes-o-r-designer.md)