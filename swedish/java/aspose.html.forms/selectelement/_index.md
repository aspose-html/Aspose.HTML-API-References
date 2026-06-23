---
title: "SelectElement‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.forms.SelectElement‑klass. SelectElement representerar en omslag som är associerad med HTMLSelectElement."
type: docs

url: /sv/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement representerar en omslag som är associerad med HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Hämtar elementets typ. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Representerar Id-attributet för input-elementet. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Representerar namn-attributet för input-elementet. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Returnerar en lista med alternativ |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Returnerar en lista med valda alternativ |
| [getType](../../com.aspose.html.forms/selectelement/type/) Typen av detta formulärkontroll. Detta är strängen "select-multiple" när attributet multiple är `true` och strängen "select-one" när `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Vid hämtning ska den returnera värdet för det första alternativelementet i listan med alternativ i trädordning som har sin markeringsstatus satt till true, om någon finns. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Denna metod tillåter att välja flera alternativ efter deras index. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Denna metod tillåter att välja flera alternativ efter deras värden. |

### Se även

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
