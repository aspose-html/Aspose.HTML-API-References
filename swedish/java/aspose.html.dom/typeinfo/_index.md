---
title: "TypeInfo-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.TypeInfo-klass. TypeInfo representerar en typ som refereras från Element- eller Attr-noder som anges i scheman som är associerade med dokumentet."
type: docs

url: /sv/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo representerar en typ som refereras från Element‑ eller Attr‑noder, specificerad i de scheman som är associerade med dokumentet.

```java
public class TypeInfo : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Namnet på en typ som deklarerats för det associerade elementet eller attributet, eller null om okänt. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Hämtar typpaketet. Paketet för den typ som deklarerats för det associerade elementet eller attributet eller null om elementet saknar deklaration eller om ingen paketinformation är tillgänglig. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Denna metod returnerar om det finns en derivation mellan referenstypdefinitionen, dvs. TypeInfo som metoden anropas på, och den andra typdefinitionen, dvs. den som skickas som parameter. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant derivationen genom utökning. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant listan. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant derivationen genom restriktion om komplexa typer är inblandade, eller en restriktion om enkla typer är inblandade. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Om dokumentets schema är ett XML-schema [XML Schema Part 1] representerar denna konstant unionen om enkla typer är inblandade. |

### Se även

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
