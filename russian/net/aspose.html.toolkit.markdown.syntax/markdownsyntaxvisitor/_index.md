---
title: Class MarkdownSyntaxVisitor
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor сорт. Базовый класс для посетителя синтаксиса уценки.
type: docs
weight: 5230
url: /ru/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

Базовый класс для посетителя синтаксиса уценки.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | Определяет интерфейс для посещения node. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | Определяет интерфейс для посещения синтаксического дерева. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | Определяет интерфейс для посещения AtxHeadingSyntax. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | Определяет интерфейс для блока посещения. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | Определяет интерфейс для посещения BlockQuoteSyntax. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | Определяет интерфейс для посещения CharacterReferenceSyntax. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | Определяет интерфейс для посещения CodeSpanSyntax. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | Определяет интерфейс для посещения EmphasisSyntax. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | Определяет интерфейс для строки текста посещения. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | Определяет интерфейс для escape-символа посещения. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | Определяет интерфейс для посещения FencedCodeBlockSyntax. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | Определяет интерфейс для посещения HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | Определяет интерфейс для посещения InlineImageSyntax. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | Определяет интерфейс для посещения IndentedCodeBlockSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | Определяет интерфейс для посещения HardBreakSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | Определяет интерфейс для посещения SoftBreakSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | Определяет интерфейс для посещения AutoLinkSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | Определяет интерфейс для посещения InlineLinkSyntax. |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | Определяет интерфейс для посещения LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | Определяет интерфейс для посещения OrderedListSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | Определяет интерфейс для посещения UnorderedListSyntax. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | Определяет интерфейс для посещения ListItemSyntax. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | Определяет интерфейс для посещения NodeList. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | Определяет интерфейс для посещения параграфа. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | Определяет интерфейс для посещения ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | Определяет интерфейс для посещения ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | Определяет интерфейс для посещения SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | Определяет интерфейс для посещения node. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | Определяет интерфейс для посещения MarkdownSyntaxTree. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | Определяет интерфейс для посещения TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | Определяет интерфейс для синтаксиса текста посещения. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | Определяет интерфейс для посещения ThematicBreakSyntax. |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Определяет интерфейс для посещения. Синтаксис пробелов. |

### Смотрите также

* пространство имен [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* сборка [Aspose.HTML](../../)


