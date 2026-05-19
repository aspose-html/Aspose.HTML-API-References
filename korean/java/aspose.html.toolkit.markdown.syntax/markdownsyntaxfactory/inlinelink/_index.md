---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Aspose.HTML for Java API 참조"
description: "MarkdownSyntaxFactory 메서드. InlineLinkSyntaxNode를 생성합니다"
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

생성합니다 [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
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

InlineLinkSyntax입니다.

### 또 보기

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

InlineLink를 생성합니다.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 텍스트 | String | 링크 텍스트입니다. |
| destination | String | String 목적지입니다. |
| title | String | String 제목입니다. |

### 반환 값

LinkReferenceDefinitionSyntax입니다.

### 또 보기

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
