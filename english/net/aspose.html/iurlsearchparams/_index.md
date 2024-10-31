---
title: IUrlSearchParams Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.IUrlSearchParams interface. Provides methods to work with URLs query string
type: docs
weight: 3970
url: /net/aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Provides methods to work with URLs query string.

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## Methods

| Name | Description |
| --- | --- |
| [Append](../../aspose.html/iurlsearchparams/append/)(string, string) | Appends a new name-value pair whose name is `name` and value is `value`. |
| [Delete](../../aspose.html/iurlsearchparams/delete/)(string) | Removes all name-value pairs whose name is `name`. |
| [Get](../../aspose.html/iurlsearchparams/get/)(string) | Returns value of the first name-value pair whose name is `name`. |
| [GetAll](../../aspose.html/iurlsearchparams/getall/)(string) | Returns all values whose name is `name`. |
| [Has](../../aspose.html/iurlsearchparams/has/)(string) | Checks if there is a name-value pair whose name is `name` in list. |
| [Set](../../aspose.html/iurlsearchparams/set/)(string, string) | Sets value of the first found name-value pair to the specified value and removes the others. If no name-value pairs with the specified name are found, new one will be appended to the list. |
| [Sort](../../aspose.html/iurlsearchparams/sort/)() | Sorts all name-value pairs, if any, by their names. |

### See Also

* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
