---
title: "Node.Normalize"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。将此 Node 下子树的全部深度中的所有 Text 节点（包括属性节点）放入一种普通形式，其中仅有结构（例如元素、注释、处理指令、CDATA 区段和实体引用）分隔 Text 节点，即不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 normalize-characters 为 true，则此方法还会完全规范化 Text 节点的字符。"
type: docs

url: /zh/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

将此 Node 下子树的全部深度中的所有 [`Text`](../../text/) 节点（包括属性节点）放入“普通”形式，其中仅有结构（例如 [`elements`](../../element/)、[`comments`](../../comment/)、[`processing instructions`](../../processinginstruction/)、[`CDATA sections`](../../cdatasection/) 和 [`entity references`](../../entityreference/)）分隔 [`Text`](../../text/) 节点，即不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 [`Node.ownerDocument`](../ownerdocument/) 的 [`DOMConfiguration`](../../../com.aspose.html/configuration/) 对象的参数 “normalize-characters” 为 true，则此方法还会完全规范化 Text 节点的字符。

```java
public void Normalize()
```

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
