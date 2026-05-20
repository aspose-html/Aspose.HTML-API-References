---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGLength method. Bevara samma underliggande lagrade värde men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var 0,5 cm och metoden anropades för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits skulle ändras till det numeriska värdet 5 och valueAsString skulle ändras till 5mm."
type: docs

url: /sv/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Behåll samma underliggande lagrade värde, men återställ den lagrade enhetsidentifieraren till den angivna unitType. Objektattributen unitType, valueInSpecifiedUnits och valueAsString kan modifieras som ett resultat av denna metod. Till exempel, om det ursprungliga värdet var "0.5cm" och metoden anropades för att konvertera till millimeter, så skulle unitType ändras till SVG_LENGTHTYPE_MM, valueInSpecifiedUnits ändras till det numeriska värdet 5 och valueAsString ändras till "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen att byta till (t.ex. SVG_LENGTHTYPE_MM). |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)Uppstår om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Utlöst när längden motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
