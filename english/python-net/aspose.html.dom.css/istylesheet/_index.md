---
title: IStyleSheet class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.html.dom.css/istylesheet/
is_root: false
---

## IStyleSheet class

The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document.



The IStyleSheet type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/html/python-net/aspose.html.dom.css/istylesheet/type) | This specifies the style sheet language for this style sheet. The style sheet language is specified as a content type (e.g. "text/css"). |
| [disabled](/html/python-net/aspose.html.dom.css/istylesheet/disabled) | false if the style sheet is applied to the document. true if it is not. Modifying this attribute may cause a new resolution of style for the document. A stylesheet only applies if both an appropriate medium definition is present and the disabled attribute is false. So, if the media doesn't apply to the current user agent, the disabled attribute is ignored. |
| [owner_node](/html/python-net/aspose.html.dom.css/istylesheet/owner_node) | The node that associates this style sheet with the document. For HTML, this may be the corresponding LINK or STYLE element. For XML, it may be the linking processing instruction. For style sheets that are included by other style sheets, the value of this attribute is null. |
| [parent_style_sheet](/html/python-net/aspose.html.dom.css/istylesheet/parent_style_sheet) | For style sheet languages that support the concept of style sheet inclusion, this attribute represents the including style sheet, if one exists. If the style sheet is a top-level style sheet, or the style sheet language does not support inclusion, the value of this attribute is null. |
| [href](/html/python-net/aspose.html.dom.css/istylesheet/href) | If the style sheet is a linked style sheet, the value of its attribute is its location. For inline style sheets, the value of this attribute is null. |
| [title](/html/python-net/aspose.html.dom.css/istylesheet/title) | The advisory title. |
| [media](/html/python-net/aspose.html.dom.css/istylesheet/media) | The intended destination media for style information. |



### See Also
* module [`aspose.html.dom.css`](..)
