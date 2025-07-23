---
title: ICSSImportRule Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSImportRule interface. The CSSImportRule interface represents a import rule within a CSS style sheet. The import rule is used to import style rules from other style sheets
type: docs
weight: 580
url: /net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

The CSSImportRule interface represents a @import rule within a CSS style sheet. The @import rule is used to import style rules from other style sheets.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | The location of the style sheet to be imported. The attribute will not contain the "url(...)" specifier around the URI. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | A list of media types for which this style sheet may be used. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | The style sheet referred to by this rule, if it has been loaded. The value of this attribute is null if the style sheet has not yet been loaded or if it will not be loaded (e.g. if the style sheet is for a media type not supported by the user agent). |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
