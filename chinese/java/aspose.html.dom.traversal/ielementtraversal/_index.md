---
title: "IElementTraversal 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal.IElementTraversal 接口。ElementTraversal 接口是一组只读属性，允许作者在文档中轻松地在元素之间导航。在符合 Element Traversal 的实现中，所有实现 Element 的对象也必须实现 ElementTraversal 接口。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal 接口是一组只读属性，允许作者在文档中轻松地在元素之间导航。在符合 Element Traversal 的实现中，所有实现 Element 的对象也必须实现 ElementTraversal 接口。

```java
public interface IElementTraversal
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) 返回当前作为此元素子节点的元素节点数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有后续的元素兄弟节点，则返回 null。 |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) 返回此元素的上一个兄弟元素节点。如果此元素在文档树中没有前面的元素兄弟节点，则返回 null。 |

### 另请参见

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
