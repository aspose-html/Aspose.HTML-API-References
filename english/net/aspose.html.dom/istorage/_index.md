---
title: IStorage Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.IStorage interface. This interface of the Web Storage API provides access to a particular domains session or local storage. See Web Storage specification https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage
type: docs
weight: 1110
url: /net/aspose.html.dom/istorage/
---
## IStorage interface

This interface of the Web Storage API provides access to a particular domain's session or local storage. See Web Storage specification: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Properties

| Name | Description |
| --- | --- |
| [Length](../../aspose.html.dom/istorage/length/) { get; } | Returns the number of key/value pairs. |

## Methods

| Name | Description |
| --- | --- |
| [Clear](../../aspose.html.dom/istorage/clear/)() | Removes all key/value pairs, if there are any. |
| [GetItem](../../aspose.html.dom/istorage/getitem/)(string) | Returns the current value associated with the given key, or null if the given key does not exist. |
| [Key](../../aspose.html.dom/istorage/key/)(long) | Returns the name of the nth key, or null if n is greater than or equal to the number of key/value pairs. |
| [RemoveItem](../../aspose.html.dom/istorage/removeitem/)(string) | Removes the key/value pair with the given key, if a key/value pair with the given key exists. |
| [SetItem](../../aspose.html.dom/istorage/setitem/)(string, string) | Sets the value of the pair identified by key to value, creating a new key/value pair if none existed for key previously. |

### See Also

* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)
