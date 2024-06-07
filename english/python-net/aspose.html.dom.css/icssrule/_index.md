---
title: ICSSRule class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 150
url: /aspose.html.dom.css/icssrule/
is_root: false
---

## ICSSRule class

The CSSRule interface is the abstract base interface for any type of CSS statement. This includes both rule sets and at-rules. An implementation is expected to preserve all rules specified in a CSS style sheet, even if the rule is not recognized by the parser. Unrecognized rules are represented using the [`ICSSUnknownRule`](/html/python-net/aspose.html.dom.css/icssunknownrule) interface.



The ICSSRule type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/html/python-net/aspose.html.dom.css/icssrule/type) | The type of the rule, as defined above. The expectation is that binding-specific casting methods can be used to cast down from an instance of the CSSRule interface to the specific derived interface implied by the type. |
| [css_text](/html/python-net/aspose.html.dom.css/icssrule/css_text) | The parsable textual representation of the rule. This reflects the current state of the rule and not its initial value. |
| [parent_style_sheet](/html/python-net/aspose.html.dom.css/icssrule/parent_style_sheet) | The style sheet that contains this rule. |
| [parent_rule](/html/python-net/aspose.html.dom.css/icssrule/parent_rule) | If this rule is contained inside another rule (e.g. a style rule inside an @media block), this is the containing rule. If this rule is not nested inside any other rules, this returns null. |



### See Also
* module [`aspose.html.dom.css`](..)
* class [`ICSSUnknownRule`](/html/python-net/aspose.html.dom.css/icssunknownrule)
