---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Aspose.HTML for Java API 참조"
description: "MarkdownSyntaxFactory 메서드. InlineImageSyntaxNode를 생성합니다"
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

생성합니다 [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| altText | String | 대체 텍스트. |
| href | String | 이미지의 URL. |
| title | String | 제목. |

### 반환 값

이 InlineImageSyntax.

### 또 보기

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

생성합니다 [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 이 contentOpening. |
| contentClosing | MarkdownSyntaxToken | 이 contentClosing. |
| declarationOpening | MarkdownSyntaxToken | 이 declarationOpening. |
| destination | LinkDestinationSyntaxNode | 이 destination. |
| title | LinkTitleSyntaxNode | 제목. |
| declarationClosing | MarkdownSyntaxToken | 이 declarationClosing. |

### 반환 값

이 InlineImageSyntax.

### 또 보기

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
