---
title: ErrorEvent
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 870
url: /net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

The ErrorEvent provides contextual information about an errors that occurred during runtime.

```csharp
public class ErrorEvent : Event
```

## Constructors

| Name | Description |
| --- | --- |
| [ErrorEvent](errorevent)(Exception) | Initializes a new instance of the [`ErrorEvent`](../errorevent) class. |
| [ErrorEvent](errorevent)(IDictionary&lt;string, object&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| [ColNo](colno) { get; } | The colno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the column number where the error occurred in the script. |
| [Error](error) { get; } | The error attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to null. Where appropriate, it is set to the object representing the error (e.g. the exception object in the case of an uncaught DOM exception). |
| [FileName](filename) { get; } | The filename attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty string. It represents the absolute URL of the script in which the error originally occurred. |
| [LineNo](lineno) { get; } | The lineno attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to zero. It represents the line number where the error occurred in the script. |
| [Message](message) { get; } | The message attribute must return the value it was initialized to. When the object is created, this attribute must be initialized to the empty string. It represents the error message. |

### See Also

* class [Event](../event)
* namespace [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->