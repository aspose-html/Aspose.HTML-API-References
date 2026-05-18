---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "MarkdownSyntaxFactory विधि। बनाता है InlineLinkSyntaxNode"
type: docs

url: /hi/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

बनाता है [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | यह contentOpening. |
| contentClosing | MarkdownSyntaxToken | यह contentClosing. |
| declarationOpening | MarkdownSyntaxToken | यह declarationOpening. |
| गंतव्य | LinkDestinationSyntaxNode | यह गंतव्य. |
| शीर्षक | LinkTitleSyntaxNode | शीर्षक। |
| declarationClosing | MarkdownSyntaxToken | यह declarationClosing. |

### रिटर्न वैल्यू

यह InlineLinkSyntax.

### संबंधित देखें

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

बनाता है InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पाठ | String | यह लिंक टेक्स्ट। |
| गंतव्य | String | यह स्ट्रिंग डेस्टिनेशन। |
| शीर्षक | String | यह स्ट्रिंग टाइटल। |

### रिटर्न वैल्यू

यह LinkReferenceDefinitionSyntax.

### संबंधित देखें

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
