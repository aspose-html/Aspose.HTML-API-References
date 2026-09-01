---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Java용 Aspose.HTML API 참조"
description: "MarkdownSyntaxFactory 메서드. 생성합니다 InlineLinkSyntaxNode"
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

| Parameter | Type | 설명 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 그 contentOpening. |
| contentClosing | MarkdownSyntaxToken | 그 contentClosing. |
| declarationOpening | MarkdownSyntaxToken | 그 declarationOpening. |
| 대상 | LinkDestinationSyntaxNode | 그 대상. |
| 제목 | LinkTitleSyntaxNode | 그 제목. |
| declarationClosing | MarkdownSyntaxToken | 그 declarationClosing. |

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

InlineLink을 생성합니다.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| text | String | 링크 텍스트입니다. |
| 대상 | String | String 목적지입니다. |
| 제목 | String | String 제목입니다. |

### 반환 값

LinkReferenceDefinitionSyntax입니다.

### 또 보기

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
