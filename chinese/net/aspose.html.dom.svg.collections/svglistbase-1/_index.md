---
title: Class SVGListBaseT
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.Collections.SVGListBase1T 班级. 该接口定义了所有 SVG 列表的基本列表
type: docs
weight: 1050
url: /zh/net/aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

该接口定义了所有 SVG 列表的基本列表。

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| 范围 | 描述 |
| --- | --- |
| T | 存储在列表中的项目类型。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html.dom.svg.collections/svglistbase-1/item/) { get; set; } | 返回列表中的第 indexth 项。 |
| [Length](../../aspose.html.dom.svg.collections/svglistbase-1/length/) { get; } | 列表中的项目数。 |
| [NumberOfItems](../../aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) { get; } | 列表中的项目数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendItem](../../aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | 在列表末尾插入一个新项目。 |
| [Clear](../../aspose.html.dom.svg.collections/svglistbase-1/clear/)() | 从列表中清除所有现有的当前项目，结果是一个空列表。 |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管和 - 可选 - 托管资源。 |
| [GetEnumerator](../../aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | 获取枚举器。 |
| [GetItem](../../aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | 从列表中返回指定的项目。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [Initialize](../../aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | 从列表中清除所有现有的当前项目并重新初始化列表以保存参数指定的单个项目。 |
| [InsertItemBefore](../../aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | 在列表的指定位置插入一个新项目。第一项是数字 0. |
| [RemoveItem](../../aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | 从列表中删除现有项目。 |
| [ReplaceItem](../../aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | 用新项目替换列表中的现有项目。 |

### 也可以看看

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* 命名空间 [Aspose.Html.Dom.Svg.Collections](../../aspose.html.dom.svg.collections/)
* 部件 [Aspose.HTML](../../)


