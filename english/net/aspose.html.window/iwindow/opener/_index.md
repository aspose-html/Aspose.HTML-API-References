---
title: IWindow.Opener
second_title: Aspose.HTML for .NET API Reference
description: IWindow Opener property. The opener IDL attribute on the Window object on getting must return the WindowProxy object of the browsing context from which the current browsing context was created its opener browsing context if there is one if it is still available and if the current browsing context has not disowned its opener otherwise it must return null. On setting if the new value is null then the current browsing context must disown its opener if the new value is anything else then the user agent must call the DefineOwnProperty internal method of the Window object passing the property name opener as the property key and the Property Descriptor  Value value Writable true Enumerable true Configurable true  as the property descriptor where value is the new value
type: docs
weight: 60
url: /net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

The opener IDL attribute on the Window object, on getting, must return the WindowProxy object of the browsing context from which the current browsing context was created (its opener browsing context), if there is one, if it is still available, and if the current browsing context has not disowned its opener; otherwise, it must return null. On setting, if the new value is null then the current browsing context must disown its opener; if the new value is anything else then the user agent must call the [[DefineOwnProperty]] internal method of the Window object, passing the property name "opener" as the property key, and the Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } as the property descriptor, where value is the new value.

```csharp
public IWindow Opener { get; }
```

### Property Value

The opener.

### See Also

* interface [IWindow](../)
* namespace [Aspose.Html.Window](../../../aspose.html.window/)
* assembly [Aspose.HTML](../../../)
