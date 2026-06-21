---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "MarkdownSyntaxFactory विधि। बनाता है InlineImageSyntaxNode"
type: docs

url: /hi/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

बनाता है [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| altText | String | वैकल्पिक पाठ। |
| href | String | छवि का URL। |
| शीर्षक | String | शीर्षक। |

### रिटर्न वैल्यू

यह InlineImageSyntax.

### संबंधित देखें

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

बनाता है [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | यह contentOpening. |
| contentClosing | MarkdownSyntaxToken | यह contentClosing. |
| declarationOpening | MarkdownSyntaxToken | यह declarationOpening. |
| गंतव्य | LinkDestinationSyntaxNode | गंतव्य. |
| शीर्षक | LinkTitleSyntaxNode | शीर्षक। |
| declarationClosing | MarkdownSyntaxToken | यह declarationClosing. |

### रिटर्न वैल्यू

यह InlineImageSyntax.

### संबंधित देखें

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
