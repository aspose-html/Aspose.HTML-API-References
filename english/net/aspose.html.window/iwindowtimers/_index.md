---
title: IWindowTimers Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Window.IWindowTimers interface. Allows authors to schedule timer-based callbacks
type: docs
weight: 6140
url: /net/aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

Allows authors to schedule timer-based callbacks.

```csharp
public interface IWindowTimers
```

## Methods

| Name | Description |
| --- | --- |
| [ClearInterval](../../aspose.html.window/iwindowtimers/clearinterval/)(*int*) | Cancels the timeout set with setInterval() identified by handle |
| [ClearTimeout](../../aspose.html.window/iwindowtimers/cleartimeout/)(*int*) | Cancels the timeout set with setTimeout() identified by handle. |
| [SetInterval](../../aspose.html.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | Schedules a timeout to run handler every timeout milliseconds. Any arguments are passed straight through to the handler. |
| [SetTimeout](../../aspose.html.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | Schedules a timeout to run handler after timeout milliseconds. Any arguments are passed straight through to the handler. |

### See Also

* namespace [Aspose.Html.Window](../../aspose.html.window/)
* assembly [Aspose.HTML](../../)
