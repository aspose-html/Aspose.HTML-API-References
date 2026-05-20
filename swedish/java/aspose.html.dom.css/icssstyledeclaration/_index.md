---
title: "ICSSStyleDeclaration gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration gränssnitt. CSSStyleDeclaration‑gränssnittet representerar ett objekt som är ett CSS‑deklarationsblock och exponerar stilinformation samt olika stilrelaterade metoder och egenskaper."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration‑gränssnittet representerar ett objekt som är ett CSS‑deklarationsblock och exponerar stilinformation samt olika stilrelaterade metoder och egenskaper.

Ett CSSStyleDeclaration‑objekt kan exponeras via tre olika API:er:

Via HTMLElement.style, som hanterar inline‑stilarna för ett enskilt element. Via [`CSSStyleSheet`](../icssstylesheet/)‑API:t. Till exempel returnerar document.styleSheets[0].cssRules[0].style ett `CSSStyleDeclaration`‑objekt för den första CSS‑regeln i dokumentets första stilark. Via Window.getComputedStyle(), som exponerar `CSSStyleDeclaration`‑objektet som ett skrivskyddat gränssnitt.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Används för att hämta de egenskaper som har satts explicit i detta deklarationsblock. Ordningen på de egenskaper som hämtas med denna metod behöver inte vara den ordning de sattes i. Denna metod kan användas för att iterera över alla egenskaper i detta deklarationsblock. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) Den skrivskyddade egenskapen returnerar ett heltal som anger antalet egenskaper som har satts explicit i detta CSS‑deklarationsblock. Intervallet för giltiga index är 0 till length‑1 inklusive. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) Den skrivskyddade egenskapen CSSStyleDeclaration.parentRule returnerar en CSSRule som är föräldern till detta stilblock, t.ex. en [`CSSStyleRule`](../icssstylerule/) som representerar stilen för en CSS‑selektor. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Används för att hämta objektrepresentationen av värdet för en CSS‑egenskap om den har satts explicit i detta deklarationsblock. Denna metod returnerar null om egenskapen är en förkortningsegenskap. Värden för förkortningsegenskaper kan endast nås och modifieras som Strängar, med metoderna getPropertyValue och setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Används för att hämta prioriteten för en CSS‑egenskap (t.ex. \"important\"‑kvalificeraren) om egenskapen har satts explicit i detta deklarationsblock. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | Metodgränssnittet CSSStyleDeclaration.getPropertyValue() returnerar en Sträng som innehåller värdet för en specificerad CSS‑egenskap. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | Metodgränssnittet CSSStyleDeclaration.removeProperty() tar bort en egenskap från ett CSS‑stildeklarationsobjekt. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | Metodgränssnittet CSSStyleDeclaration.setProperty() används för att sätta ett egenskapsvärde med standardprioritet i detta deklarationsblock. Standardprioriteten är inte \"important\", dvs. String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | Metodgränssnittet CSSStyleDeclaration.setProperty() används för att sätta ett egenskapsvärde med standardprioritet i detta deklarationsblock. Standardprioriteten är inte \"important\", dvs. String.Empty. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Se även

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
