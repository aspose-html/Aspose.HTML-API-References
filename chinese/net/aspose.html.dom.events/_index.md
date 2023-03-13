---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML for .NET API 参考
description: 的 Aspose.Html.Dom.事件命名空间为 任何与 DOM 更新相关的事件提供对象包括订阅 特定上下文信息observation 关联事件以及自定义事件构造.
type: docs
weight: 80
url: /zh/net/aspose.html.dom.events/
---
的 **Aspose.Html.Dom.事件**命名空间为 任何与 DOM 更新相关的事件提供对象。包括订阅 特定上下文信息observation 关联事件以及自定义事件构造.

## 课程

| 班级 | 描述 |
| --- | --- |
| [CustomEvent](./customevent/) | 使用CustomEvent接口的事件可以用来携带自定义数据。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | 的[`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/)当请求的资源不可用时发生。 |
| [DOMEventHandler](./domeventhandler/) | 代表事件处理的回调。 |
| [ErrorEvent](./errorevent/) | 的[`ErrorEvent`](../aspose.html.dom.events/errorevent/)提供有关运行时发生的错误的上下文信息。 |
| [Event](./event/) | 的[`Event`](../aspose.html.dom.events/event/)用于向处理事件的处理程序提供有关事件的上下文信息。 |
| [FocusEvent](./focusevent/) | FocusEvent 接口提供与焦点事件关联的特定上下文信息。 |
| [InputEvent](./inputevent/) | 每当更新 DOM 时，输入事件都会作为通知发送。 |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent 接口提供与键盘设备关联的特定上下文信息。每个键盘事件都使用一个值引用一个键。键盘事件通常针对具有焦点的元素。 |
| [MouseEvent](./mouseevent/) | MouseEvent 接口提供与鼠标事件关联的特定上下文信息。 |
| [UIEvent](./uievent/) | UIEvent 接口提供与用户界面事件关联的特定上下文信息。 |
| [WheelEvent](./wheelevent/) | WheelEvent 接口提供与车轮事件关联的特定上下文信息。要创建 WheelEvent 接口的实例，请使用 WheelEvent 构造函数，传递一个可选的 WheelEventInit 字典。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | 的[`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/)接口提供了一种机制，用户可以通过该机制创建一个[`Event`](../aspose.html.dom.events/event/)实现支持的类型。 |
| [IEventListener](./ieventlistener/) | 的[`IEventListener`](../aspose.html.dom.events/ieventlistener/)接口是处理事件的主要方法。 用户实现[`IEventListener`](../aspose.html.dom.events/ieventlistener/)接口并在一个上注册他们的听众[`EventTarget`](../aspose.html.dom/eventtarget/)使用[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/)method. 用户还应该删除他们的[`IEventListener`](../aspose.html.dom.events/ieventlistener/)从它的[`EventTarget`](../aspose.html.dom/eventtarget/)在他们完成使用 listener. 之后 |
| [IEventTarget](./ieventtarget/) | 的[`EventTarget`](../aspose.html.dom/eventtarget/)接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口。 该接口允许注册和删除事件侦听器一个[`EventTarget`](../aspose.html.dom/eventtarget/)并向其发送事件[`IEventTarget`](../aspose.html.dom.events/ieventtarget/). |


