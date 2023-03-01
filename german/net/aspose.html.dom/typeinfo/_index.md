---
title: Class TypeInfo
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.TypeInfo klas. Die TypeInfo stellt einen Typ dar auf den von Element oder AttrKnoten verwiesen wird die in den mit dem Dokument verknüpften Schemas angegeben sind.
type: docs
weight: 2530
url: /de/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

Die TypeInfo stellt einen Typ dar, auf den von Element- oder Attr-Knoten verwiesen wird, die in den mit dem Dokument verknüpften Schemas angegeben sind.

```csharp
public class TypeInfo : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Der Name eines für das zugeordnete Element oder Attribut deklarierten Typs oder null, falls unbekannt. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Ruft den Typnamensraum ab. Der Namensraum des für das zugeordnete Element oder Attribut deklarierten Typs oder null, wenn das Element keine Deklaration hat oder wenn keine Namensrauminformationen verfügbar sind. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Diese Methode gibt zurück, wenn es eine Ableitung zwischen der Referenztypdefinition, dh der TypeInfo, auf der die Methode aufgerufen wird, und der anderen Typdefinition, dh derjenigen, die als Parameter übergeben wird, gibt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Wenn das Schema des Dokuments ein XML-Schema [XML-Schema Teil 1] ist, repräsentiert diese Konstante die Ableitung durch Erweiterung. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Wenn das Schema des Dokuments ein XML-Schema [XML-Schema Teil 1] ist, repräsentiert diese Konstante die Liste. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Wenn das Schema des Dokuments ein XML-Schema [XML-Schema Teil 1] ist, stellt diese Konstante die Ableitung durch Einschränkung dar, wenn es sich um komplexe Typen handelt, oder um eine Einschränkung, wenn es sich um einfache Typen handelt. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Wenn das Schema des Dokuments ein XML-Schema [XML-Schema Teil 1] ist, stellt diese Konstante die Vereinigung dar, wenn es sich um einfache Typen handelt. |

### Siehe auch

* class [DOMObject](../domobject/)
* namensraum [Aspose.Html.Dom](../../aspose.html.dom/)
* Montage [Aspose.HTML](../../)


