---
title: Interface ICSSRule
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.ICSSRule koppel. De CSSRuleinterface is de abstracte basisinterface voor elk type CSSstatement. Dit omvat zowel regelsets als atregels. Van een implementatie wordt verwacht dat deze alle regels behoudt die zijn gespecificeerd in een CSSstijlblad zelfs als de regel niet wordt herkend door de parser. Nietherkende regels worden weergegeven met behulp van deICSSUnknownRule interface.
type: docs
weight: 470
url: /nl/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

De CSSRule-interface is de abstracte basisinterface voor elk type CSS-statement. Dit omvat zowel regelsets als at-regels. Van een implementatie wordt verwacht dat deze alle regels behoudt die zijn gespecificeerd in een CSS-stijlblad, zelfs als de regel niet wordt herkend door de parser. Niet-herkende regels worden weergegeven met behulp van de!:ICSSUnknownRule interface.

```csharp
public interface ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | De ontleedbare tekstuele weergave van de regel. Dit weerspiegelt de huidige status van de regel en niet de oorspronkelijke waarde. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | Als deze regel binnen een andere regel staat (bijvoorbeeld een stijlregel binnen een @media-blok), is dit de bevattende regel. Als deze regel niet is genest binnen andere regels, retourneert dit null. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | De stijlpagina die deze regel bevat. |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | Het type regel, zoals hierboven gedefinieerd. De verwachting is dat binding-specifieke castingmethoden kunnen worden gebruikt om vanuit een instantie van de CSSRule-interface naar de specifieke afgeleide interface te casten die wordt geïmpliceerd door het type. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


