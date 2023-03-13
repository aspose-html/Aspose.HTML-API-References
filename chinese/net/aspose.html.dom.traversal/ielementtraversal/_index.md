---
title: Interface IElementTraversal
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.IElementTraversal 界面. ElementTraversal 接口是一组只读属性允许作者轻松地在文档中的元素之间导航在 Element Traversal 的一致性实现中所有实现 Element 的对象也必须实现 ElementTraversal 接口
type: docs
weight: 2480
url: /zh/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal 接口是一组只读属性，允许作者轻松地在文档中的元素之间导航。在 Element Traversal 的一致性实现中，所有实现 Element 的对象也必须实现 ElementTraversal 接口。

```csharp
public interface IElementTraversal
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | 返回作为该元素子元素的元素节点的当前数量。如果此元素没有节点类型为 1. 的子节点，则为 0 |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | 返回该元素的第一个子元素节点。如果此元素没有子元素，则为 null. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | 返回该元素的最后一个子元素节点。如果此元素没有子元素，则为 null. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有此元素之后的元素兄弟节点，则为 null. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | 返回该元素的前一个兄弟元素节点。如果此元素在文档树中没有出现在该元素之前的元素兄弟节点，则为 null. |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


