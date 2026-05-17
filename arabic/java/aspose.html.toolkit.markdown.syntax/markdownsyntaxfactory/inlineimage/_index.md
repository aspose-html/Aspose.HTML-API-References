---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة MarkdownSyntaxFactory. ينشئ InlineImageSyntaxNode"
type: docs

url: /ar/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

ينشئ [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| altText | String | النص البديل. |
| href | String | عنوان URL للصورة. |
| العنوان | String | العنوان. |

### قيمة الإرجاع

الـ InlineImageSyntax.

### انظر أيضًا

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

ينشئ [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
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

الـ InlineImageSyntax.

### انظر أيضًا

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
