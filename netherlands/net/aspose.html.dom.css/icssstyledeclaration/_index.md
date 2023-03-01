---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration koppel. De CSSStyleDeclarationinterface vertegenwoordigt een enkel CSSdeclaratieblok. Deze interface kan worden gebruikt om de stijleigenschappen te bepalen die momenteel in een blok zijn ingesteld of om stijleigenschappen expliciet binnen het blok in te stellen.
type: docs
weight: 490
url: /nl/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

De CSSStyleDeclaration-interface vertegenwoordigt een enkel CSS-declaratieblok. Deze interface kan worden gebruikt om de stijleigenschappen te bepalen die momenteel in een blok zijn ingesteld of om stijleigenschappen expliciet binnen het blok in te stellen.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | De ontleedbare tekstuele representatie van het declaratieblok (exclusief de omringende accolades). Als u dit attribuut instelt, wordt de nieuwe waarde geparseerd en worden alle eigenschappen in het declaratieblok opnieuw ingesteld, inclusief het verwijderen of toevoegen van eigenschappen. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Wordt gebruikt om de eigenschappen op te halen die expliciet zijn ingesteld in dit declaratieblok. De volgorde van de eigenschappen die met deze methode worden opgehaald, hoeft niet de volgorde te zijn waarin ze zijn ingesteld. Deze methode kan worden gebruikt om alle eigenschappen in dit declaratieblok te herhalen. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Het aantal eigenschappen dat expliciet is ingesteld in dit declaratieblok. Het bereik van geldige indexen is 0 tot en met lengte-1. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | De CSS-regel die dit declaratieblok bevat of null als deze CSSStyleDeclaration niet is gekoppeld aan een CSSRule. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Wordt gebruikt om de objectrepresentatie van de waarde van een CSS-eigenschap op te halen als deze expliciet is ingesteld binnen dit declaratieblok. Deze methode retourneert null als de eigenschap een verkorte eigenschap is. Afgekorte eigenschapswaarden kunnen alleen worden geopend en gewijzigd als tekenreeksen met behulp van de getPropertyValue- en setProperty-methoden. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Wordt gebruikt om de prioriteit van een CSS-eigenschap op te halen (bijv. de "belangrijke" kwalificatie) als de eigenschap expliciet is ingesteld in dit declaratieblok. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Wordt gebruikt om de waarde van een CSS-eigenschap op te halen als deze expliciet is ingesteld binnen dit declaratieblok. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Wordt gebruikt om een CSS-eigenschap te verwijderen als deze expliciet is ingesteld binnen dit declaratieblok. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Wordt gebruikt om een eigenschapswaarde in te stellen met standaardprioriteit binnen dit declaratieblok. Standaardprioriteit is niet "belangrijk", dwz String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Wordt gebruikt om een eigenschapswaarde en prioriteit in te stellen binnen dit declaratieblok. |

### Zie ook

* interface [ICSS2Properties](../icss2properties/)
* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


