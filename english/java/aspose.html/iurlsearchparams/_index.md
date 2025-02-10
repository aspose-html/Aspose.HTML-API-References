---
title: IUrlSearchParams Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.IUrlSearchParams interface. Provides methods to work with URLs query String
type: docs
weight: 3970
url: /java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Provides methods to work with URLs query String.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Methods

| Name | Description |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Appends a new name-value pair whose name is `name` and value is `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Removes all name-value pairs whose name is `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Returns value of the first name-value pair whose name is `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Returns all values whose name is `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Checks if there is a name-value pair whose name is `name` in list. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Sets value of the first found name-value pair to the specified value and removes the others. If no name-value pairs with the specified name are found, new one will be appended to the list. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Sorts all name-value pairs, if any, by their names. |

### See Also

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
