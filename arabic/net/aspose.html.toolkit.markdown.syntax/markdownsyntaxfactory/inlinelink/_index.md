---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML لمرجع .NET API
description: MarkdownSyntaxFactory طريقة. إنشاء كائنات باستخدام InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /ar/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

إنشاء كائنات باستخدام InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | المحتوى الافتتاح. |
| contentClosing | MarkdownSyntaxToken | المحتوى الختام. |
| declarationOpening | MarkdownSyntaxToken | الإعلان الافتتاح. |
| destination | LinkDestinationSyntaxNode | الوجهة. |
| title | LinkTitleSyntaxNode | العنوان. |
| declarationClosing | MarkdownSyntaxToken | الإعلان الختامي. |

### قيمة الإرجاع

تركيب InlineLinkSyntax.

### أنظر أيضا

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* مساحة الاسم [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* المجسم [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

إنشاء InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| text | String | نص الارتباط. |
| destination | String | وجهة السلسلة. |
| title | String | عنوان السلسلة. |

### قيمة الإرجاع

الرابط LinkReferenceDefinitionSyntax.

### أنظر أيضا

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* مساحة الاسم [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* المجسم [Aspose.HTML](../../../)


