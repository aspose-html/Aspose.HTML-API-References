---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events 包提供用于 DOM 更新相关事件的对象。它包括对与事件关联的特定上下文信息观察的订阅以及自定义事件的构建。"
type: docs

url: /zh/java/com.aspose.html.dom.events/
---
该 **com.aspose.html.dom.events** 包提供用于 DOM 更新相关的各种事件的对象。它包括对与事件关联的特定上下文信息观察的订阅以及自定义事件的构建。

## 类

| 类 | 描述 |
| --- | --- |
| [CustomEvent](./customevent/) | 使用 CustomEvent 接口的事件可用于携带自定义数据。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | 当请求的资源不可用时，会触发 DocumentLoadErrorEvent。 |
| [DOMEventHandler](./domeventhandler/) | 表示用于文档对象模型 (DOM) 事件处理的通用回调委托。 |
| [ErrorEvent](./errorevent/) | ErrorEvent 提供有关运行时发生的错误的上下文信息。 |
| [Event](./event/) | 用于向处理该事件的处理程序提供有关事件的上下文信息。 |
| [FocusEvent](./focusevent/) | FocusEvent 接口提供与焦点事件相关的特定上下文信息。 |
| [InputEvent](./inputevent/) | 当 DOM 被更新时，输入事件会作为通知发送。 |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent 接口提供与键盘设备相关的特定上下文信息。每个键盘事件使用一个值引用一个键。键盘事件通常针对具有焦点的元素触发。 |
| [MouseEvent](./mouseevent/) | MouseEvent 接口提供与鼠标事件相关的特定上下文信息。 |
| [UIEvent](./uievent/) | UIEvent 接口提供与用户界面事件相关的特定上下文信息。 |
| [WheelEvent](./wheelevent/) | WheelEvent 接口提供与滚轮事件相关的特定上下文信息。要创建 WheelEvent 接口的实例，请使用 WheelEvent 构造函数，并传入可选的 WheelEventInit 字典。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | DocumentEvent 接口提供一种机制，使用户能够创建实现支持的类型的 Event。预计在支持事件模型的实现中，DocumentEvent 接口将在实现 Document 接口的同一对象上实现。 |
| [IEventListener](./ieventlistener/) | 该接口是处理事件的主要方式。用户实现该接口并使用该方法在对象上注册其监听器。用户在完成监听后还应从中移除监听器。 |
| [IEventTarget](./ieventtarget/) | 在支持 DOM 事件模型的实现中，所有节点都实现了 EventTarget 接口。因此，可以通过在 Node 接口的实例上使用特定绑定的强制转换方法获取该接口。该接口允许在对象上注册和移除事件监听器，并向其分发事件。 |
