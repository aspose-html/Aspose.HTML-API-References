---
title: Class CSSValue
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.CSSValue klas. Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValueobject komt alleen voor in een context van een CSSeigenschap.
type: docs
weight: 340
url: /nl/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue-object komt alleen voor in een context van een CSS-eigenschap.

```csharp
public abstract class CSSValue : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Een tekenreeksrepresentatie van de huidige waarde. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Een code die het type waarde definieert. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Bepaalt of de opgegevenObject is gelijk aan deze instantie. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Retourneert een hash-code voor deze instantie. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Implementeert de operator ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Implementeert de operator !=. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | De waarde is een aangepaste waarde. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | De waarde is overgenomen en de cssText bevat "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | De waarde is een primitieve waarde en een instantie van de CSSPrimitiveValue-interface kan worden verkregen door bindingspecifieke castingmethoden te gebruiken op deze instantie van de CSSValue-interface. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | De waarde is een CSSValue-lijst en een instantie van de CSSValueList-interface kan worden verkregen door bindingspecifieke castingmethoden te gebruiken op deze instantie van de CSSValue-interface. |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


