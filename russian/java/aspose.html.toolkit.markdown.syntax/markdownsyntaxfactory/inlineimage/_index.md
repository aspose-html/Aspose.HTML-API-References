---
title: "MarkdownSyntaxFactory.InlineImage"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод MarkdownSyntaxFactory. Создаёт InlineImageSyntaxNode"
type: docs

url: /ru/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(String, String, String) {#inlineimage_1}

Создаёт [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(String altText, String href, String title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| altText | String | Альтернативный текст. |
| href | String | URL изображения. |
| заголовок | String | Заголовок. |

### Возвращаемое значение

Элемент InlineImageSyntax.

### См. также

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Создаёт [`InlineImageSyntaxNode`](../../inlineimagesyntaxnode/).

```java
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Элемент contentOpening. |
| contentClosing | MarkdownSyntaxToken | Элемент contentClosing. |
| declarationOpening | MarkdownSyntaxToken | Элемент declarationOpening. |
| destination | LinkDestinationSyntaxNode | Элемент destination. |
| заголовок | LinkTitleSyntaxNode | Заголовок. |
| declarationClosing | MarkdownSyntaxToken | Элемент declarationClosing. |

### Возвращаемое значение

Элемент InlineImageSyntax.

### См. также

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* package [com.aspose.html.toolkit.markdown.syntax](../../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../../)
