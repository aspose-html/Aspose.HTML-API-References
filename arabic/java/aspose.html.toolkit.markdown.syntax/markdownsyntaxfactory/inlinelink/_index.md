---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "MarkdownSyntaxFactory طريقة. ينشئ InlineLinkSyntaxNode"
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
| destination | LinkDestinationSyntaxNode | ال destination. |
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
| text | String | نص الرابط. |
| destination | String | ال String الوجهة. |
| العنوان | String | ال String العنوان. |

### قيمة الإرجاع

ال LinkReferenceDefinitionSyntax.

### انظر أيضًا

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
