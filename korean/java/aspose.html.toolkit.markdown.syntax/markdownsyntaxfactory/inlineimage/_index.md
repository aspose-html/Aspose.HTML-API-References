---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Java용 Aspose.HTML API 참조"
description: "MarkdownSyntaxFactory 메서드. InlineImageSyntaxNode를 생성합니다"
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

생성합니다 [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| altText | String | 그 대체 텍스트. |
| href | String | 그 이미지의 URL. |
| 제목 | String | 그 제목. |

### 반환 값

그 InlineImageSyntax.

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

| Parameter | Type | 설명 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 그 contentOpening. |
| contentClosing | MarkdownSyntaxToken | 그 contentClosing. |
| declarationOpening | MarkdownSyntaxToken | 그 declarationOpening. |
| 대상 | LinkDestinationSyntaxNode | 그 대상. |
| 제목 | LinkTitleSyntaxNode | 그 제목. |
| declarationClosing | MarkdownSyntaxToken | 그 declarationClosing. |

### 반환 값

그 InlineImageSyntax.

### 또 보기

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
