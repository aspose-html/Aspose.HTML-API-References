---
title: ICSSStyleSheet class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 190
url: /aspose.html.dom.css/icssstylesheet/
is_root: false
---

## ICSSStyleSheet class

The CSSStyleSheet interface is a concrete interface used to represent a CSS style sheet i.e., a style sheet whose content type is "text/css".



The ICSSStyleSheet type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [owner_rule](/html/python-net/aspose.html.dom.css/icssstylesheet/owner_rule) | If this style sheet comes from an @import rule, the ownerRule attribute will contain the CSSImportRule. In that case, the ownerNode attribute in the StyleSheet interface will be null. If the style sheet comes from an element or a processing instruction, the ownerRule attribute will be null and the ownerNode attribute will contain the Node. |
| [css_rules](/html/python-net/aspose.html.dom.css/icssstylesheet/css_rules) | The list of all CSS rules contained within the style sheet. This includes both rule sets and at-rules. |
| [type](/html/python-net/aspose.html.dom.css/icssstylesheet/type) | This specifies the style sheet language for this style sheet. The style sheet language is specified as a content type (e.g. "text/css"). |
| [disabled](/html/python-net/aspose.html.dom.css/icssstylesheet/disabled) | false if the style sheet is applied to the document. true if it is not. Modifying this attribute may cause a new resolution of style for the document. A stylesheet only applies if both an appropriate medium definition is present and the disabled attribute is false. So, if the media doesn't apply to the current user agent, the disabled attribute is ignored. |
| [owner_node](/html/python-net/aspose.html.dom.css/icssstylesheet/owner_node) | The node that associates this style sheet with the document. For HTML, this may be the corresponding LINK or STYLE element. For XML, it may be the linking processing instruction. For style sheets that are included by other style sheets, the value of this attribute is null. |
| [parent_style_sheet](/html/python-net/aspose.html.dom.css/icssstylesheet/parent_style_sheet) | For style sheet languages that support the concept of style sheet inclusion, this attribute represents the including style sheet, if one exists. If the style sheet is a top-level style sheet, or the style sheet language does not support inclusion, the value of this attribute is null. |
| [href](/html/python-net/aspose.html.dom.css/icssstylesheet/href) | If the style sheet is a linked style sheet, the value of its attribute is its location. For inline style sheets, the value of this attribute is null. |
| [title](/html/python-net/aspose.html.dom.css/icssstylesheet/title) | The advisory title. |
| [media](/html/python-net/aspose.html.dom.css/icssstylesheet/media) | The intended destination media for style information. |


### Methods
| Method | Description |
| :- | :- |
| [insert_rule](/html/python-net/aspose.html.dom.css/icssstylesheet/insert_rule/#str-int) | Used to insert a new rule into the style sheet. The new rule now becomes part of the cascade. |
| [delete_rule](/html/python-net/aspose.html.dom.css/icssstylesheet/delete_rule/#int) | Used to delete a rule from the style sheet. |



### See Also
* module [`aspose.html.dom.css`](..)
* class [`IStyleSheet`](/html/python-net/aspose.html.dom.css/istylesheet)
