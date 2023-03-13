---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration 界面. CSSStyleDeclaration 接口表示单个 CSS 声明块此接口可用于确定当前在块中设置的样式属性或在块中显式设置样式属性
type: docs
weight: 490
url: /zh/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration 接口表示单个 CSS 声明块。此接口可用于确定当前在块中设置的样式属性或在块中显式设置样式属性。

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | 声明块的可解析文本表示（不包括周围的大括号）。设置此属性将导致解析新值并重置声明块中的所有属性，包括删除或添加属性。 |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | 用于检索已在此声明块中显式设置的属性。使用此方法检索的属性的顺序不必是它们设置的顺序。此方法可用于迭代此声明块中的所有属性。 |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | 在此声明块中显式设置的属性数。有效索引的范围是 0 到 length-1（含）。 |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | 包含此声明块的 CSS 规则，如果此 CSSStyleDeclaration 未附加到 CSSRule，则为 null。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | 用于检索 CSS 属性值的对象表示，如果它已在此声明块中显式设置。如果该属性是速记属性，则此方法返回 null。速记属性值只能作为字符串访问和修改，使用 getPropertyValue 和 setProperty 方法。 |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | 如果属性已在此声明块中明确设置，则用于检索 CSS 属性（例如“重要”限定符）的优先级。 |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | 用于检索 CSS 属性的值（如果它已在此声明块中显式设置）。 |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | 如果已在此声明块中显式设置，则用于删除 CSS 属性。 |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | 用于在此声明块中设置具有默认优先级的属性值。 默认优先级不“重要”，即 String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | 用于在此声明块中设置属性值和优先级。 |

### 也可以看看

* interface [ICSS2Properties](../icss2properties/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


