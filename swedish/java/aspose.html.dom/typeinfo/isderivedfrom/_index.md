---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML för Java API-referens"
description: "TypeInfo-metod. Denna metod returnerar om det finns en härledning mellan referenstypdefinitionen, dvs. den TypeInfo som metoden anropas på, och den andra typdefinitionen, dvs. den som skickas som parameter"
type: docs

url: /sv/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Denna metod returnerar om det finns en härledning mellan referenstypdefinitionen, d.v.s. TypeInfo som metoden anropas på, och den andra typdefinitionen, d.v.s. den som skickas som parameter.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeNamespaceArg | String | paketet för den andra typdefinitionen |
| typeNameArg | String | namnet på den andra typdefinitionen. |
| derivationMethod | UInt64 | typen av härledning och villkor som tillämpas mellan två typer, enligt listan av konstanter som tillhandahålls i detta gränssnitt. |

### Returvärde

Om dokumentets schema är en DTD eller inget schema är associerat med dokumentet kommer denna metod alltid att returnera false. Om dokumentets schema är ett XML-schema kommer metoden att returnera true om referenstypdefinitionen är härledd från den andra typdefinitionen enligt derivationsparametern. Om parametervärdet är 0 (ingen bit är satt till 1 för derivationMethod‑parametern) kommer metoden att returnera true om den andra typdefinitionen kan nås genom att rekursivt gå igenom någon kombination av {bas-typdefinition}, {item-typdefinition} eller {medlemstypdefinitioner} från referenstypdefinitionen.

### Se även

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
