---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML för .NET API Referens
description: TypeInfo metod. Denna metod returnerar om det finns en härledning mellan referenstypsdefinitionen dvs den TypeInfo som metoden anropas på och den andra typdefinitionen dvs den som skickas som parametrar.
type: docs
weight: 30
url: /sv/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Denna metod returnerar om det finns en härledning mellan referenstypsdefinitionen, dvs den TypeInfo som metoden anropas på, och den andra typdefinitionen, dvs den som skickas som parametrar.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeNamespaceArg | String | namnområdet för den andra typens definition |
| typeNameArg | String | namnet på den andra typens definition. |
| derivationMethod | UInt64 | typen av härledning och villkor som tillämpas mellan två typer, enligt beskrivningen i listan över konstanter i detta gränssnitt. |

### Returvärde

Om dokumentets schema är ett DTD eller inget schema är associerat med dokumentet kommer denna metod alltid att returnera false. Om dokumentets schema är ett XML-schema, kommer metoden att sannas om referenstypsdefinitionen härleds från den andra typdefinitionen enligt härledningsparametern. Om värdet på parametern är 0 (ingen bit är satt till 1 för parametern derivationMethod), kommer metoden att returnera true om den andra typens definition kan nås genom att upprepa valfri kombination av {base type definition}, {item type definition} , eller {member type definitions} från referenstypsdefinitionen.

### Se även

* class [TypeInfo](../)
* namnutrymme [Aspose.Html.Dom](../../typeinfo/)
* hopsättning [Aspose.HTML](../../../)


