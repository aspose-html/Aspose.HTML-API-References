---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration gränssnitt. CSSStyleDeclarationgränssnittet representerar ett enda CSSdeklarationsblock. Detta gränssnitt kan användas för att bestämma de stilegenskaper som för närvarande är inställda i ett block eller för att ställa in stilegenskaper uttryckligen inom blocket.
type: docs
weight: 490
url: /sv/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration-gränssnittet representerar ett enda CSS-deklarationsblock. Detta gränssnitt kan användas för att bestämma de stilegenskaper som för närvarande är inställda i ett block eller för att ställa in stilegenskaper uttryckligen inom blocket.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | Den tolkbara textrepresentationen av deklarationsblocket (exklusive de omgivande krulliga klammerparenteserna). Om du ställer in detta attribut kommer det att resultera i att det nya värdet analyseras och alla egenskaper i deklarationsblocket återställs, inklusive borttagning eller tillägg av egenskaper. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Används för att hämta egenskaperna som uttryckligen har ställts in i detta deklarationsblock. Ordningen på egenskaperna som hämtas med den här metoden behöver inte vara den ordning som de sattes in. Denna metod kan användas för att iterera över alla egenskaper i detta deklarationsblock. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Antalet egenskaper som har angetts uttryckligen i detta deklarationsblock. Intervallet av giltiga index är 0 till och med längd-1. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | CSS-regeln som innehåller detta deklarationsblock eller null om denna CSSStyleDeclaration inte är kopplad till en CSSRule. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Används för att hämta objektrepresentationen av värdet på en CSS-egenskap om den uttryckligen har ställts in i detta deklarationsblock. Denna metod returnerar null om egenskapen är en stenografisk egenskap. Egenskapsvärden för stenografi kan endast nås och ändras som strängar med metoderna getPropertyValue och setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Används för att hämta prioriteten för en CSS-egenskap (t.ex. det "viktiga" kvalet) om egenskapen har ställts in uttryckligen i detta deklarationsblock. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Används för att hämta värdet på en CSS-egenskap om den uttryckligen har ställts in i detta deklarationsblock. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Används för att ta bort en CSS-egenskap om den uttryckligen har ställts in i detta deklarationsblock. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Används för att ställa in ett egenskapsvärde med standardprioritet inom detta deklarationsblock. Standardprioritet är inte "viktigt", dvs String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Används för att ställa in ett egenskapsvärde och prioritet inom detta deklarationsblock. |

### Se även

* interface [ICSS2Properties](../icss2properties/)
* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


