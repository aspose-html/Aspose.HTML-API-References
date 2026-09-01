---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML für Java API-Referenz"
description: "TypeInfo-Methode. Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenztypdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht"
type: docs

url: /de/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenztypdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeNamespaceArg | String | das Paket der anderen Typdefinition |
| typeNameArg | String | der Name der anderen Typdefinition. |
| derivationMethod | UInt64 | der Typ der Ableitung und die zwischen zwei Typen angewendeten Bedingungen, wie in der Liste der Konstanten in dieser Schnittstelle beschrieben. |

### Rückgabewert

Wenn das Schema des Dokuments ein DTD ist oder kein Schema dem Dokument zugeordnet ist, gibt diese Methode stets false zurück. Wenn das Schema des Dokuments ein XML Schema ist, gibt die Methode true zurück, wenn die Referenztypdefinition gemäß dem Ableitungsparameter von der anderen Typdefinition abgeleitet ist. Wenn der Wert des Parameters 0 ist (kein Bit ist für den Parameter derivationMethod auf 1 gesetzt), gibt die Methode true zurück, wenn die andere Typdefinition durch Rekursion einer beliebigen Kombination von {base type definition}, {item type definition} oder {member type definitions} aus der Referenztypdefinition erreicht werden kann.

### Siehe auch

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
