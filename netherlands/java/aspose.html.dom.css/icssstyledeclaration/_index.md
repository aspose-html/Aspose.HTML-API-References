---
title: "ICSSStyleDeclaration interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration interface. De CSSStyleDeclaration‑interface vertegenwoordigt een object dat een CSS‑declaratie‑blok is en stijl‑informatie en diverse stijlgerelateerde methoden en eigenschappen blootlegt."
type: docs

url: /nl/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

De CSSStyleDeclaration-interface vertegenwoordigt een object dat een CSS-declaratieblok is, en geeft stijl‑informatie en verschillende stijlgerelateerde methoden en eigenschappen weer.

Een CSSStyleDeclaration‑object kan worden blootgesteld via drie verschillende API’s:

Via HTMLElement.style, die de inline‑stijlen van een enkel element behandelt. Via de [`CSSStyleSheet`](../icssstylesheet/)‑API. Bijvoorbeeld, document.styleSheets[0].cssRules[0].style retourneert een `CSSStyleDeclaration`‑object voor de eerste CSS‑regel in het eerste stylesheet van het document. Via Window.getComputedStyle(), die het `CSSStyleDeclaration`‑object blootlegt als een alleen‑lezen interface.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Gebruikt om de eigenschappen op te halen die expliciet zijn ingesteld in dit declaratieblok. De volgorde van de opgehaalde eigenschappen met deze methode hoeft niet overeen te komen met de volgorde waarin ze zijn ingesteld. Deze methode kan worden gebruikt om over alle eigenschappen in dit declaratieblok te itereren. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) De alleen‑lezen eigenschap retourneert een geheel getal dat het aantal eigenschappen aangeeft die expliciet zijn ingesteld in dit CSS‑declaratieblok. Het bereik van geldige indexen is 0 tot en met length‑1. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) De alleen‑lezen eigenschap CSSStyleDeclaration.parentRule retourneert een CSSRule die de ouder is van dit stijlblok, bijv. een [`CSSStyleRule`](../icssstylerule/) die de stijl voor een CSS‑selector vertegenwoordigt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Gebruikt om de objectrepresentatie van de waarde van een CSS‑eigenschap op te halen als deze expliciet is ingesteld binnen dit declaratieblok. Deze methode retourneert null als de eigenschap een verkorte eigenschap is. Waarden van verkorte eigenschappen kunnen alleen als strings worden benaderd en gewijzigd, met behulp van de methoden getPropertyValue en setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Gebruikt om de prioriteit van een CSS‑eigenschap op te halen (bijv. de "important"‑qualifier) als de eigenschap expliciet is ingesteld in dit declaratieblok. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | De CSSStyleDeclaration.getPropertyValue()-methode‑interface retourneert een string die de waarde van een opgegeven CSS‑eigenschap bevat. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | De CSSStyleDeclaration.removeProperty()-methode‑interface verwijdert een eigenschap uit een CSS‑stijldeclaratie‑object. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | De CSSStyleDeclaration.setProperty()-methode‑interface wordt gebruikt om een eigenschapswaarde met standaardprioriteit in te stellen binnen dit declaratieblok. Standaardprioriteit is niet "important", d.w.z. String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | De CSSStyleDeclaration.setProperty()-methode‑interface wordt gebruikt om een eigenschapswaarde met standaardprioriteit in te stellen binnen dit declaratieblok. Standaardprioriteit is niet "important", d.w.z. String.Empty. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Zie ook

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
