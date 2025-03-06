---
title: ICSSImportRule Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.ICSSImportRule interface. The CSSImportRule interface represents a import rule within a CSS style sheet. The import rule is used to import style rules from other style sheets
type: docs

url: /java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

The CSSImportRule interface represents a @import rule within a CSS style sheet. The @import rule is used to import style rules from other style sheets.

```java
public interface ICSSImportRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) The read-only href property of the CSSImportRule interface returns the URL specified by the @import at-rule. |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) The read-only media property of the CSSImportRule interface returns a MediaList object, containing the value of the media attribute of the associated stylesheet. |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) The style sheet referred to by this rule, if it has been loaded. The value of this attribute is null if the style sheet has not yet been loaded or if it will not be loaded (e.g. if the style sheet is for a media type not supported by the user agent). |

### See Also

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
