---
title: Class MutationObserver
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Mutations.MutationObserver 班级. 一个MutationObserver对象可用于观察树的突变Node.
type: docs
weight: 970
url: /zh/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

一个`MutationObserver`对象可用于观察树的突变[`Node`](../../aspose.html.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | 构造一个 MutationObserver 对象并设置它的[`MutationCallback`](../mutationcallback/)回调。 调用回调时将 MutationRecord 对象列表作为第一个参数，将构造的 MutationObserver 对象作为第二个参数。它在节点注册到!:Observe(Node, IMutationObserverInit)方法，都发生了变化。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | 阻止观察者观察任何突变。直到再次使用 observe() 方法，才会调用观察者的回调。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | 指示用户代理观察给定目标（节点）并根据选项（对象）给出的标准报告任何突变。 options 参数允许通过对象成员设置突变观察选项。 |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | 指示用户代理观察给定目标（节点）并根据选项（对象）给出的标准报告任何突变。 options 参数允许通过对象成员设置突变观察选项。 |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | 方法返回记录队列的副本，然后清空记录队列。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* 命名空间 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 部件 [Aspose.HTML](../../)


