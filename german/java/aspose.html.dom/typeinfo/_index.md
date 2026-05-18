---
title: "TypeInfo-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.TypeInfo-Klasse. Der TypeInfo repräsentiert einen Typ, der von Element- oder Attr-Knoten referenziert wird, die in den mit dem Dokument verknüpften Schemata angegeben sind."
type: docs

url: /de/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

Die TypeInfo stellt einen Typ dar, der von Element‑ oder Attr‑Knoten referenziert wird und in den mit dem Dokument verbundenen Schemata angegeben ist.

```java
public class TypeInfo : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Der Name eines für das zugehörige Element oder Attribut deklarierten Typs, oder null, wenn unbekannt. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Gibt das Typ-Paket zurück. Das Paket des für das zugehörige Element oder Attribut deklarierten Typs oder null, wenn das Element keine Deklaration hat oder keine Paketinformationen verfügbar sind. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Diese Methode gibt zurück, ob eine Ableitung zwischen der Referenztypdefinition, d.h. dem TypeInfo, auf dem die Methode aufgerufen wird, und der anderen Typdefinition, d.h. der als Parameter übergebenen, besteht. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Wenn das Schema des Dokuments ein XML-Schema [XML Schema Part 1] ist, stellt diese Konstante die Ableitung durch Erweiterung dar. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Wenn das Schema des Dokuments ein XML-Schema [XML Schema Part 1] ist, stellt diese Konstante die Liste dar. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Wenn das Schema des Dokuments ein XML-Schema [XML Schema Part 1] ist, stellt diese Konstante die Ableitung durch Einschränkung dar, falls komplexe Typen beteiligt sind, oder eine Einschränkung, falls einfache Typen beteiligt sind. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Wenn das Schema des Dokuments ein XML-Schema [XML Schema Part 1] ist, stellt diese Konstante die Vereinigung dar, falls einfache Typen beteiligt sind. |

### Siehe auch

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
