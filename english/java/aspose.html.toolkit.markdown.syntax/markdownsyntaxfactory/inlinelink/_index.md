---
title: MarkdownSyntaxFactory.InlineLink
second_title: Aspose.HTML for Java API Reference
description: MarkdownSyntaxFactory method. Creates InlineLinkSyntaxNode
type: docs
weight: 220
url: /java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Creates [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | The contentOpening. |
| contentClosing | MarkdownSyntaxToken | The contentClosing. |
| declarationOpening | MarkdownSyntaxToken | The declarationOpening. |
| destination | LinkDestinationSyntaxNode | The destination. |
| title | LinkTitleSyntaxNode | The title. |
| declarationClosing | MarkdownSyntaxToken | The declarationClosing. |

### Return Value

The InlineLinkSyntax.

### See Also

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../markdownsyntaxfactory/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Creates InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | String | The link text. |
| destination | String | The String destination. |
| title | String | The String title. |

### Return Value

The LinkReferenceDefinitionSyntax.

### See Also

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../markdownsyntaxfactory/)
* package [Aspose.HTML](../../../)
