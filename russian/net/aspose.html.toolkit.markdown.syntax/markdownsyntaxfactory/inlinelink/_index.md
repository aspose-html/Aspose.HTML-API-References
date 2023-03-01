---
title: MarkdownSyntaxFactory.InlineLink
second_title: Справочник по Aspose.HTML для .NET API
description: MarkdownSyntaxFactory метод. Создает объекты используя InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /ru/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Создает объекты, используя InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
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

Синтаксис встроенной ссылки.

### Смотрите также

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* сборка [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Создает встроенную ссылку.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст ссылки. |
| destination | String | Пункт назначения строки. |
| title | String | Заголовок строки. |

### Возвращаемое значение

Синтаксис LinkReferenceDefinition.

### Смотрите также

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* сборка [Aspose.HTML](../../../)


