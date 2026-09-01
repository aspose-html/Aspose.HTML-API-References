---
title: "TypeInfo‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.TypeInfo‑klasse. De TypeInfo vertegenwoordigt een type dat wordt verwezen vanuit Element‑ of Attr‑knooppunten gespecificeerd in de schema's die aan het document zijn gekoppeld."
type: docs

url: /nl/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

De TypeInfo vertegenwoordigt een type dat wordt gerefereerd vanuit Element‑ of Attr‑knooppunten, gespecificeerd in de schema's die bij het document horen.

```java
public class TypeInfo : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) De naam van een type dat is gedeclareerd voor het gekoppelde element of attribuut, of null indien onbekend. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Haalt het type‑pakket op. Het pakket van het type dat is gedeclareerd voor het gekoppelde element of attribuut, of null als het element geen declaratie heeft of als er geen pakketinformatie beschikbaar is. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Deze methode geeft terug of er een afleiding bestaat tussen de referentietypedefinitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere typedefinitie, d.w.z. die welke als parameter wordt doorgegeven. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Als het schema van het document een XML‑schema is [XML Schema Part 1], vertegenwoordigt deze constante de afleiding door extensie. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Als het schema van het document een XML‑schema is [XML Schema Part 1], vertegenwoordigt deze constante de lijst. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Als het schema van het document een XML‑schema is [XML Schema Part 1], vertegenwoordigt deze constante de afleiding door restrictie wanneer complexe types betrokken zijn, of een restrictie wanneer eenvoudige types betrokken zijn. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Als het schema van het document een XML‑schema is [XML Schema Part 1], vertegenwoordigt deze constante de unie wanneer eenvoudige types betrokken zijn. |

### Zie ook

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
