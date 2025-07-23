---
title: MutationObserver Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Mutations.MutationObserver class. A MutationObserver object can be used to observe mutations to the tree of Node
type: docs
weight: 1130
url: /net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A `MutationObserver` object can be used to observe mutations to the tree of [`Node`](../../aspose.html.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## Constructors

| Name | Description |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Constructs a MutationObserver object and sets its [`MutationCallback`](../mutationcallback/) to callback. The callback is invoked with a list of MutationRecord objects as first argument and the constructed MutationObserver object as second argument. It is invoked after nodes registered with the [`Observe`](./observe/) method, are mutated. |

## Methods

| Name | Description |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Stops observer from observing any mutations. Until the observe() method is used again, observer’s callback will not be invoked. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.html.dom/node/)*) | Instructs the user agent to observe a given target (a node) and report any mutations based on the criteria given by options (an object). The options argument allows for setting mutation observation options via object members. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.html.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Instructs the user agent to observe a given target (a node) and report any mutations based on the criteria given by options (an object). The options argument allows for setting mutation observation options via object members. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | The method returns a copy of the record queue and then empty the record queue. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* namespace [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* assembly [Aspose.HTML](../../)
