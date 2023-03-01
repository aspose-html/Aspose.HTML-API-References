---
title: Class HugoFrontMatterSyntaxNode
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoFrontMatterSyntaxNode сорт. Определяет базовый класс HugoFrontMatterSyntaxNode
type: docs
weight: 4910
url: /ru/net/aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Определяет базовый класс HugoFrontMatterSyntaxNode

```csharp
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Получить первого ребенка. |
| abstract [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) { get; } | Получить и установить RootNode |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Получить последнего потомка. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Получить следующего брата. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Получить родительский узел. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Получить предыдущего брата. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Определяет интерфейс для приема посетителей. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Добавить дочерний узел. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Получить коллекцию дочерних узлов. |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params string[]) | Определяет интерфейс для поиска BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params string[]) | Определяет интерфейс для поиска T |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Получите главные мелочи. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Получить синтаксическое дерево. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Получить викторины. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Вставить перед узлом. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Удалить дочерний элемент. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Заменить дочерний узел. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Переопределить метод ToString. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Запись в MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Запись узлов в модуль записи текста. |

### Смотрите также

* class [BlockSyntaxNode](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* сборка [Aspose.HTML](../../)


