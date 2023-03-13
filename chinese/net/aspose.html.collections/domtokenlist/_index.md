---
title: Class DOMTokenList
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Collections.DOMTokenList 班级. DOMTokenList 类表示一组以空格分隔的标记与 JavaScript Array 对象一样它的索引从 0 开始 DOMTokenList 始终区分大小写
type: docs
weight: 20
url: /zh/net/aspose.html.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList 类表示一组以空格分隔的标记。与 JavaScript Array 对象一样，它的索引从 0 开始。 DOMTokenList 始终区分大小写。

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html.collections/domtokenlist/item/) { get; } | 按索引返回列表中的项目，如果索引大于或等于列表的长度，则返回 null。 |
| [Length](../../aspose.html.collections/domtokenlist/length/) { get; } | 返回一个 ulong，表示存储在此列表中的令牌数。 |
| [Value](../../aspose.html.collections/domtokenlist/value/) { get; set; } | 获取或设置相应属性的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.html.collections/domtokenlist/add/)(params string[]) | 将指定的标记添加到列表中。 |
| [Contains](../../aspose.html.collections/domtokenlist/contains/)(string) | 如果列表包含给定的标记则返回真，否则返回假。 |
| [GetEnumerator](../../aspose.html.collections/domtokenlist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [Remove](../../aspose.html.collections/domtokenlist/remove/)(params string[]) | 从列表中删除指定的标记。 |
| [Replace](../../aspose.html.collections/domtokenlist/replace/)(string, string) | 用新令牌替换现有令牌。如果第一个标记不存在则什么也不做. |
| [Supports](../../aspose.html.collections/domtokenlist/supports/)(string) | 如果给定标记在关联属性的支持标记中，则返回 true。 |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle)(string) | 如果令牌存在，则从列表中删除令牌，如果不存在，则将令牌添加到列表中。 |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle_1)(string, bool?) | 如果令牌存在，则从列表中删除令牌，如果不存在，则将令牌添加到列表中。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* 命名空间 [Aspose.Html.Collections](../../aspose.html.collections/)
* 部件 [Aspose.HTML](../../)


