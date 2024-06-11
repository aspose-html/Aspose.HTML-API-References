---
title: ICSSKeyframesRule class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.dom.css/icsskeyframesrule/
is_root: false
---

## ICSSKeyframesRule class

The CSSKeyframesRule interface represents a complete set of keyframes for a single animation



The ICSSKeyframesRule type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [name](/html/python-net/aspose.html.dom.css/icsskeyframesrule/name) | This attribute is the name of the keyframes, used by the ‘animation-name’ property. |
| [css_rules](/html/python-net/aspose.html.dom.css/icsskeyframesrule/css_rules) | This attribute gives access to the keyframes in the list |
| [type](/html/python-net/aspose.html.dom.css/icsskeyframesrule/type) | The type of the rule, as defined above. The expectation is that binding-specific casting methods can be used to cast down from an instance of the CSSRule interface to the specific derived interface implied by the type. |
| [css_text](/html/python-net/aspose.html.dom.css/icsskeyframesrule/css_text) | The parsable textual representation of the rule. This reflects the current state of the rule and not its initial value. |
| [parent_style_sheet](/html/python-net/aspose.html.dom.css/icsskeyframesrule/parent_style_sheet) | The style sheet that contains this rule. |
| [parent_rule](/html/python-net/aspose.html.dom.css/icsskeyframesrule/parent_rule) | If this rule is contained inside another rule (e.g. a style rule inside an @media block), this is the containing rule. If this rule is not nested inside any other rules, this returns null. |


### Methods
| Method | Description |
| :- | :- |
| [append_rule](/html/python-net/aspose.html.dom.css/icsskeyframesrule/append_rule/#str) | The appendRule method appends the passed CSSKeyframeRule into the list at the passed key |
| [delete_rule](/html/python-net/aspose.html.dom.css/icsskeyframesrule/delete_rule/#str) | The deleteRule method deletes the CSSKeyframeRule with the passed key. If a rule with this key does not exist, the method does nothing |
| [find_rule](/html/python-net/aspose.html.dom.css/icsskeyframesrule/find_rule/#str) | The findRule method returns the rule with a key matching the passed key. If no such rule exists, a null value is returned |



### See Also
* module [`aspose.html.dom.css`](..)
* class [`ICSSRule`](/html/python-net/aspose.html.dom.css/icssrule)
