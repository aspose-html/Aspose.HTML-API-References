---
title: Class NamedNodeMap
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Collections.NamedNodeMap 班级. 表示可以通过名称访问的属性集合
type: docs
weight: 40
url: /zh/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

表示可以通过名称访问的属性集合。

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | 返回地图中的第 index 个项目。如果索引大于或等于此映射中的节点数，则返回 null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | 此映射中的节点数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | 检索名称指定的节点。 |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | 检索由本地名称和命名空间 URI 指定的节点。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | 删除名称指定的节点。 |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | 删除由本地名称和名称空间 URI 指定的节点。 |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | 使用节点名称属性添加节点。如果具有该名称的节点已存在于此映射中，则将其替换为新节点。自己替换一个节点是没有效果的。 |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | 使用其名称空间 URI 和本地名称添加节点。如果具有该名称空间 URI 和该本地名称的节点已存在于此映射中，则它将被新节点替换。自己替换一个节点是没有效果的。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* 命名空间 [Aspose.Html.Collections](../../aspose.html.collections/)
* 部件 [Aspose.HTML](../../)


