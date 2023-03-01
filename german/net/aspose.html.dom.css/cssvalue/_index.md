---
title: Class CSSValue
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Css.CSSValue klas. Repräsentiert einen einfachen oder komplexen Wert. Ein CSSValueObjekt kommt nur im Kontext einer CSSEigenschaft vor.
type: docs
weight: 340
url: /de/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Repräsentiert einen einfachen oder komplexen Wert. Ein CSSValue-Objekt kommt nur im Kontext einer CSS-Eigenschaft vor.

```csharp
public abstract class CSSValue : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Eine Zeichenfolgendarstellung des aktuellen Werts. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Ein Code, der den Werttyp definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Bestimmt, ob die angegebeneObject ist gleich dieser Instanz. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Gibt einen Hash-Code für diese Instanz zurück. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Implementiert den Operator ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Implementiert den Operator !=. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | Der Wert ist ein benutzerdefinierter Wert. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | Der Wert wird vererbt und der cssText enthält "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | Der Wert ist ein primitiver Wert und eine Instanz der CSSPrimitiveValue-Schnittstelle kann abgerufen werden, indem bindungsspezifische Umsetzungsmethoden für diese Instanz der CSSValue-Schnittstelle verwendet werden. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | Der Wert ist eine CSSValue-Liste und eine Instanz der CSSValueList-Schnittstelle kann abgerufen werden, indem bindungsspezifische Umsetzungsmethoden für diese Instanz der CSSValue-Schnittstelle verwendet werden. |

### Siehe auch

* class [DOMObject](../../aspose.html.dom/domobject/)
* namensraum [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Montage [Aspose.HTML](../../)


