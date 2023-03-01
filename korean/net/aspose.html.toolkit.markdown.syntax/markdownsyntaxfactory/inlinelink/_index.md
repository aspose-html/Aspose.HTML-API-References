---
title: MarkdownSyntaxFactory.InlineLink
second_title: .NET API 참조용 Aspose.HTML
description: MarkdownSyntaxFactory 방법. InlineLinkSyntax.CreateInstance. 를 사용하여 개체를 만듭니다.
type: docs
weight: 220
url: /ko/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

InlineLinkSyntax.CreateInstance. 를 사용하여 개체를 만듭니다.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | 내용열기. |
| contentClosing | MarkdownSyntaxToken | 콘텐츠를 닫는 중입니다. |
| declarationOpening | MarkdownSyntaxToken | 선언 열기. |
| destination | LinkDestinationSyntaxNode | 목적지. |
| title | LinkTitleSyntaxNode | 제목. |
| declarationClosing | MarkdownSyntaxToken | 선언을 닫습니다. |

### 반환 값

InlineLinkSyntax.

### 또한보십시오

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 집회 [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

InlineLink를 만듭니다.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| text | String | 링크 텍스트입니다. |
| destination | String | 문자열 대상입니다. |
| title | String | 문자열 제목입니다. |

### 반환 값

LinkReferenceDefinitionSyntax.

### 또한보십시오

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* 집회 [Aspose.HTML](../../../)


