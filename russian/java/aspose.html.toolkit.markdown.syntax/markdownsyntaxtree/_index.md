---
title: "Класс MarkdownSyntaxTree"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree. Представляет дерево синтаксиса Markdown"
type: docs

url: /ru/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Представляет дерево синтаксиса Markdown.

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | Создано дерево MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Создаёт дерево MarkdownSyntaxTree |

## Свойства

| Имя | Описание |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Получить первый дочерний элемент. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Получить последний дочерний элемент. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Получить следующий соседний элемент. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Получить родительский узел. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Получить предыдущий соседний элемент. |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) Получить SyntaxFactory. |

## Методы

| Имя | Описание |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Определяет интерфейс для посещения узлов синтаксического дерева. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Добавить дочерний узел. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Получить коллекцию дочерних узлов. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Определяет интерфейс для создания итератора узлов. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Определяет интерфейс для создания итератора узлов. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Определяет интерфейс для создания итератора узлов. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Определяет интерфейс для создания обходчика дерева. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Определяет интерфейс для создания обходчика дерева. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Определяет интерфейс для создания обходчика дерева. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Получить начальные вспомогательные элементы. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Получить синтаксическое дерево. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Получить конечные вспомогательные элементы. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Вставить перед узлом. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Удалить дочерний элемент. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Заменить дочерний узел. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Сохраняет синтаксическое дерево в указанный поток. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | Сохраняет синтаксическое дерево в указанный путь. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Сохраняет синтаксическое дерево в указанный объект записи. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Переопределить метод ToString. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Записать в MarkdownTextWriter. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Записать узлы в текстовый писатель. |

### См. также

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
