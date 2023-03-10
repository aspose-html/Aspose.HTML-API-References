---
title: IMediaList.AppendMedium
second_title: Aspose.HTML for .NET API Reference
description: IMediaList method. Adds the medium newMedium to the end of the list. If the newMedium is already used it is first removed
type: docs
weight: 40
url: /net/aspose.html.dom.css/imedialist/appendmedium/
---
## IMediaList.AppendMedium method

Adds the medium newMedium to the end of the list. If the newMedium is already used, it is first removed.

```csharp
public void AppendMedium(string newMedium)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newMedium | String | The new medium to add. |

### Exceptions

| exception | condition |
| --- | --- |
| DOMException | INVALID_CHARACTER_ERR: If the medium contains characters that are invalid in the underlying style language.NO_MODIFICATION_ALLOWED_ERR: Raised if this list is readonly. |

### See Also

* interface [IMediaList](../)
* namespace [Aspose.Html.Dom.Css](../../imedialist/)
* assembly [Aspose.HTML](../../../)
