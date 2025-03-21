---
title: ICSSRule.ParentRule
second_title: Aspose.HTML for .NET API Reference
description: ICSSRule ParentRule property. If this rule is contained inside another rule e.g. a style rule inside an media block this is the containing rule. If this rule is not nested inside any other rules this returns null
type: docs
weight: 20
url: /net/aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

If this rule is contained inside another rule (e.g. a style rule inside an @media block), this is the containing rule. If this rule is not nested inside any other rules, this returns null.

```csharp
public ICSSRule ParentRule { get; }
```

### Property Value

A [`CSSRule`](../) which is the type of the containing rules. If the current rule is inside a media query, this would return [`CSSMediaRule`](../../icssmediarule/). Otherwise it returns null.

### See Also

* interface [ICSSRule](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
