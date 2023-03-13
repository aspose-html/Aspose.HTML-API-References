---
title: Class TypeInfo
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.TypeInfo klass. TypeInfo representerar en typ som refereras från Element eller Attrnoder specificerad i scheman som är associerade med dokumentet.
type: docs
weight: 2530
url: /sv/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo representerar en typ som refereras från Element- eller Attr-noder, specificerad i scheman som är associerade med dokumentet.

```csharp
public class TypeInfo : DOMObject
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Namnet på en typ som deklarerats för det associerade elementet eller attributet, eller null om det inte är känt. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Hämtar typen namnutrymme. Namnutrymmet av typen som deklareras för det associerade elementet eller attributet eller null om elementet inte har deklaration eller om ingen namnområdesinformation är tillgänglig. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Denna metod returnerar om det finns en härledning mellan referenstypsdefinitionen, dvs den TypeInfo som metoden anropas på, och den andra typdefinitionen, dvs den som skickas som parametrar. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Om dokumentets schema är ett XML-schema [XML-schema del 1], representerar denna konstant härledningen genom förlängning. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Om dokumentets schema är ett XML-schema [XML-schema del 1], representerar denna konstant listan. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Om dokumentets schema är ett XML-schema [XML-schema del 1], representerar denna konstant härledning genom begränsning om komplexa typer är involverade, eller en begränsning om enkla typer är inblandade. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Om dokumentets schema är ett XML Schema [XML Schema Part 1], representerar denna konstant föreningen om enkla typer är inblandade. |

### Se även

* class [DOMObject](../domobject/)
* namnutrymme [Aspose.Html.Dom](../../aspose.html.dom/)
* hopsättning [Aspose.HTML](../../)


