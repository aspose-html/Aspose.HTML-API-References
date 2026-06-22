---
title: "MarkdownSyntaxFactory.InlineLink"
second_title: "Справочник API Aspose.HTML для Java"
description: "MarkdownSyntaxFactory метод. Создает InlineLinkSyntaxNode"
type: docs

url: /ru/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Создает [`InlineLinkSyntaxNode`](../../inlinelinksyntaxnode/).

```java
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Элемент contentOpening. |
| contentClosing | MarkdownSyntaxToken | Элемент contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Элемент declarationOpening. |
| destination | LinkDestinationSyntaxNode | Элемент назначения. |
| заголовок | LinkTitleSyntaxNode | Заголовок. |
| declarationClosing | MarkdownSyntaxToken | Элемент declarationClosing. |

### Возвращаемое значение

Элемент InlineLinkSyntax.

### См. также

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineLink(String, String, String) {#inlinelink_1}

Создает InlineLink.

```java
public InlineLinkSyntaxNode InlineLink(String text, String destination, String title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст ссылки. |
| destination | String | Строка назначения. |
| заголовок | String | Строка заголовка. |

### Возвращаемое значение

Элемент LinkReferenceDefinitionSyntax.

### См. также

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
