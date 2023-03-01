---
title: Class CSSValue
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.CSSValue klass. Representerar ett enkelt eller ett komplext värde. Ett CSSValueobjekt förekommer bara i en kontext av en CSSegenskap.
type: docs
weight: 340
url: /sv/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Representerar ett enkelt eller ett komplext värde. Ett CSSValue-objekt förekommer bara i en kontext av en CSS-egenskap.

```csharp
public abstract class CSSValue : DOMObject
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | En strängrepresentation av det aktuella värdet. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | En kod som definierar typen av värdet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Returnerar en hash-kod för denna instans. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Returnerar enString som representerar denna instans. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Implementerar operatorn ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Implementerar operatorn !=. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | Värdet är ett anpassat värde. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | Värdet ärvs och cssText innehåller "ärv". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | Värdet är ett primitivt värde och en instans av CSSPrimitiveValue-gränssnittet kan erhållas genom att använda bindningsspecifika castingmetoder på denna instans av CSSValue-gränssnittet. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | Värdet är en CSSValue-lista och en instans av CSSValueList-gränssnittet kan erhållas genom att använda bindningsspecifika castingmetoder på den här instansen av CSSValue-gränssnittet. |

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


