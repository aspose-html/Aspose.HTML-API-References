---
title: "Класс HugoFrontMatterSyntaxNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.toolkit.markdown.syntax.extensions.HugoFrontMatterSyntaxNode. Определяет базовый класс HugoFrontMatterSyntaxNode"
type: docs

url: /ru/java/com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Определяет базовый класс HugoFrontMatterSyntaxNode.

```java
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Получить первого дочернего узла. |
| abstract [getFrontMatterRootNode](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) Получать и задавать RootNode |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Получить последнего дочернего узла. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Получить следующего соседнего узла. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Получить родительский узел. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Получить предыдущего соседнего узла. |

## Методы

| Имя | Описание |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Определяет интерфейс для принятия посетителя. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Добавить дочерний узел. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Получить коллекцию дочерних узлов. |
| [find](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params String[]) | Определяет интерфейс для поиска BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params String[]) | Определяет интерфейс для поиска T |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Получить начальные вспомогательные элементы. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Получить синтаксическое дерево. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Получить завершающие вспомогательные элементы. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Вставить перед узлом. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Удалить дочерний элемент. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Заменить дочерний узел. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Переопределить метод ToString. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Записать в MarkdownTextWriter. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Записать узлы в текстовый writer. |

### См. также

* class [BlockSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax.extensions](../../com.aspose.html.toolkit.markdown.syntax.extensions/)
* package [Aspose.HTML](../../)
