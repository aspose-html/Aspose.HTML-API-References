---
title: ICSSImportRule class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.html.dom.css/icssimportrule/
is_root: false
---

## ICSSImportRule class

The CSSImportRule interface represents a @import rule within a CSS style sheet. The @import rule is used to import style rules from other style sheets.



The ICSSImportRule type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [href](/html/python-net/aspose.html.dom.css/icssimportrule/href) | The location of the style sheet to be imported. The attribute will not contain the "url(...)" specifier around the URI. |
| [media](/html/python-net/aspose.html.dom.css/icssimportrule/media) | A list of media types for which this style sheet may be used. |
| [style_sheet](/html/python-net/aspose.html.dom.css/icssimportrule/style_sheet) | The style sheet referred to by this rule, if it has been loaded. The value of this attribute is null if the style sheet has not yet been loaded or if it will not be loaded (e.g. if the style sheet is for a media type not supported by the user agent). |
| [type](/html/python-net/aspose.html.dom.css/icssimportrule/type) | The type of the rule, as defined above. The expectation is that binding-specific casting methods can be used to cast down from an instance of the CSSRule interface to the specific derived interface implied by the type. |
| [css_text](/html/python-net/aspose.html.dom.css/icssimportrule/css_text) | The parsable textual representation of the rule. This reflects the current state of the rule and not its initial value. |
| [parent_style_sheet](/html/python-net/aspose.html.dom.css/icssimportrule/parent_style_sheet) | The style sheet that contains this rule. |
| [parent_rule](/html/python-net/aspose.html.dom.css/icssimportrule/parent_rule) | If this rule is contained inside another rule (e.g. a style rule inside an @media block), this is the containing rule. If this rule is not nested inside any other rules, this returns null. |



### See Also
* module [`aspose.html.dom.css`](..)
* class [`ICSSRule`](/html/python-net/aspose.html.dom.css/icssrule)
