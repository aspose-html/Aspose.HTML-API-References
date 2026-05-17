---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة MarkdownSyntaxFactory. ينشئ InlineLinkSyntaxNode"
type: docs

url: /ar/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

ينشئ [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | ال contentOpening. |
| contentClosing | MarkdownSyntaxToken | ال contentClosing. |
| declarationOpening | MarkdownSyntaxToken | ال declarationOpening. |
| الوجهة | LinkDestinationSyntaxNode | الوجهة. |
| العنوان | LinkTitleSyntaxNode | العنوان. |
| declarationClosing | MarkdownSyntaxToken | ال declarationClosing. |

### قيمة الإرجاع

ال InlineLinkSyntax.

### انظر أيضًا

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

ينشئ InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | String | نص الرابط. |
| الوجهة | String | ال String destination. |
| العنوان | String | ال String title. |

### قيمة الإرجاع

ال LinkReferenceDefinitionSyntax.

### انظر أيضًا

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
