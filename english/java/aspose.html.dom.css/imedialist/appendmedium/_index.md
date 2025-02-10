---
title: IMediaList.AppendMedium
second_title: Aspose.HTML for Java API Reference
description: IMediaList method. Adds the medium newMedium to the end of the list. If the newMedium is already used it is first removed
type: docs
weight: 40
url: /java/com.aspose.html.dom.css/imedialist/appendmedium/
---
## IMediaList.AppendMedium method

Adds the medium newMedium to the end of the list. If the newMedium is already used, it is first removed.

```java
public void AppendMedium(String newMedium)
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
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
