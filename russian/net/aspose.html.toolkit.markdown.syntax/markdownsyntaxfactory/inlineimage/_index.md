---
title: MarkdownSyntaxFactory.InlineImage
second_title: Справочник по Aspose.HTML для .NET API
description: MarkdownSyntaxFactory метод. Создает объекты используя InlineImageSyntax.CreateInstance.
type: docs
weight: 210
url: /ru/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/
---
## InlineImage(string, string, string) {#inlineimage_1}

Создает объекты, используя InlineImageSyntax.CreateInstance.

```csharp
public InlineImageSyntaxNode InlineImage(string altText, string href, string title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| altText | String | Альтернативный текст. |
| href | String | URL-адрес изображения. |
| title | String | Название. |

### Возвращаемое значение

Синтаксис встроенного изображения.

### Смотрите также

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* сборка [Aspose.HTML](../../../)

---

## InlineImage(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlineimage}

Создает объекты, используя InlineImageSyntax.CreateInstance.

```csharp
public InlineImageSyntaxNode InlineImage(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Содержание Открытие. |
| contentClosing | MarkdownSyntaxToken | СодержаниеЗакрытие. |
| declarationOpening | MarkdownSyntaxToken | Декларация Открытие. |
| destination | LinkDestinationSyntaxNode | Назначение. |
| title | LinkTitleSyntaxNode | Название. |
| declarationClosing | MarkdownSyntaxToken | ДекларацияЗакрытие. |

### Возвращаемое значение

Синтаксис встроенного изображения.

### Смотрите также

* class [InlineImageSyntaxNode](../../inlineimagesyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* сборка [Aspose.HTML](../../../)


