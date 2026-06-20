---
title: "MutationRecord 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.mutations.MutationRecord 类。MutationRecord 表示单个 DOM 变更。它是传递给 MutationObservers 的 MutationCallback 的对象。"
type: docs

url: /zh/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord 表示单个 DOM 变更。它是传递给 [`MutationObserver`](../mutationobserver/) 的 [`MutationCallback`](../mutationcallback/) 的对象。

```java
public class MutationRecord : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) 返回添加的节点。 |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) 返回已更改属性的本地名称，否则返回 null。 |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) 返回已更改属性的命名空间，否则返回 null。 |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) 返回已添加或已移除节点的下一个兄弟节点，若无则返回 null。 |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) 返回值取决于类型。对于 "attributes"，返回更改前属性的值。对于 "characterData"，返回更改前节点的数据。对于 "childList"，返回 null。 |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) 返回已添加或已移除节点的前一个兄弟节点，若无则返回 null。 |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) 返回已移除的节点。 |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) 返回受变更影响的节点，取决于类型。对于 "attributes"，返回属性被更改的元素。对于 "characterData"，返回 CharacterData 节点。对于 "childList"，返回子节点被更改的节点。 |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) 如果是属性变更则返回 "attributes"，如果是对 CharacterData 节点的变更则返回 "characterData"，如果是对节点树的变更则返回 "childList"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
