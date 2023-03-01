---
title: Class MutationRecord
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Mutations.MutationRecord 班级. MutationRecord 表示单个 DOM 突变它是传递给的对象MutationObserver秒MutationCallback.
type: docs
weight: 990
url: /zh/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord 表示单个 DOM 突变。它是传递给的对象[`MutationObserver`](../mutationobserver/)秒[`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | 返回添加的节点。 |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | 返回已更改属性的本地名称，否则返回 null。 |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | 返回已更改属性的名称空间，否则返回 null。 |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | 返回添加或删除节点的下一个兄弟节点，或者为空。 |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | 返回值取决于类型。对于“attributes”，为变化前变化属性的值。 对于“characterData”，为变化前变化节点的数据。 对于“childList”，为null。 |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | 返回添加或删除节点的前一个兄弟节点，或为空。 |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | 返回删除的节点。 |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | 返回受突变影响的节点，具体取决于类型。对于“属性”，它是属性发生变化的元素。对于“characterData”，它是 CharacterData 节点。对于“childList”，它是子节点发生变化的节点。 |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | 如果它是属性突变则返回“attributes”，如果它是对 CharacterData 节点的突变则返回“characterData”，如果它是对节点树的突变则返回“childList”。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* 命名空间 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 部件 [Aspose.HTML](../../)


