---
title: "MutationObserver 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.mutations.MutationObserver 类。对象可用于观察树的变更"
type: docs

url: /zh/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

对象可用于观察树的变更 [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | 构造一个 MutationObserver 对象并将其 [`MutationCallback`](../mutationcallback/) 设置为回调。回调会以 MutationRecord 对象列表作为第一个参数、构造的 MutationObserver 对象作为第二个参数被调用。它在使用 !:Observe(Node, IMutationObserverInit) 方法注册的节点发生变更后被调用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | 停止 observer 观察任何变更。直到再次调用 observe() 方法，observer 的回调才会被触发。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | 指示用户代理观察给定的目标（节点），并根据 options（对象）提供的条件报告任何变更。options 参数允许通过对象成员设置变更观察选项。 |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | 指示用户代理观察给定的目标（节点），并根据 options（对象）提供的条件报告任何变更。options 参数允许通过对象成员设置变更观察选项。 |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | 该方法返回记录队列的副本，然后清空记录队列。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
