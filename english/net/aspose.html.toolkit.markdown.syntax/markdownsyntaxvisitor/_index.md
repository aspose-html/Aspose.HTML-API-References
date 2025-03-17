---
title: MarkdownSyntaxVisitor Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor class. The base class for markdown syntax visitor
type: docs
weight: 5490
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

The base class for markdown syntax visitor.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## Methods

| Name | Description |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Defines the interface for visit node. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(*[MarkdownSyntaxTree](../markdownsyntaxtree/)*) | Defines the interface for visit syntax tree. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(*[AtxHeadingSyntaxNode](../atxheadingsyntaxnode/)*) | Defines the interface for visit AtxHeadingSyntax. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(*[BlockSyntaxNode](../blocksyntaxnode/)*) | Defines the interface for visit block. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(*[BlockQuoteSyntaxNode](../blockquotesyntaxnode/)*) | Defines the interface for visit BlockQuoteSyntax. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(*[CharacterReferenceSyntaxNode](../characterreferencesyntaxnode/)*) | Defines the interface for visit CharacterReferenceSyntax. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(*[CodeSpanSyntaxNode](../codespansyntaxnode/)*) | Defines the interface for visit CodeSpanSyntax. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(*[EmphasisSyntaxNode](../emphasissyntaxnode/)*) | Defines the interface for visit EmphasisSyntax. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(*[EmptyLineSyntaxNode](../emptylinesyntaxnode/)*) | Defines the interface for visit text line. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(*[EscapedCharacterSyntaxNode](../escapedcharactersyntaxnode/)*) | Defines the interface for visit escape character. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(*[FencedCodeBlockSyntaxNode](../fencedcodeblocksyntaxnode/)*) | Defines the interface for visit FencedCodeBlockSyntax. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(*[HTMLFragmentSyntax](../htmlfragmentsyntax/)*) | Defines the interface for visit HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(*[InlineImageSyntaxNode](../inlineimagesyntaxnode/)*) | Defines the interface for visit InlineImageSyntax. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(*[IndentedCodeBlockSyntaxNode](../indentedcodeblocksyntaxnode/)*) | Defines the interface for visit IndentedCodeBlockSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(*[HardBreakSyntaxNode](../hardbreaksyntaxnode/)*) | Defines the interface for visit HardBreakSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(*[SoftBreakSyntaxNode](../softbreaksyntaxnode/)*) | Defines the interface for visit SoftBreakSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(*[AutoLinkSyntaxNode](../autolinksyntaxnode/)*) | Defines the interface for visit AutoLinkSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(*[InlineLinkSyntaxNode](../inlinelinksyntaxnode/)*) | Defines the interface for visit InlineLinkSyntax. |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(*[LinkReferenceDefinitionSyntaxNode](../linkreferencedefinitionsyntaxnode/)*) | Defines the interface for visit LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(*[OrderedListSyntaxNode](../orderedlistsyntaxnode/)*) | Defines the interface for visit OrderedListSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(*[UnorderedListSyntaxNode](../unorderedlistsyntaxnode/)*) | Defines the interface for visit UnorderedListSyntax. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(*[ListItemSyntaxNode](../listitemsyntaxnode/)*) | Defines the interface for visit ListItemSyntax. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(*[NodeList](../nodelist/)*) | Defines the interface for visit NodeList. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(*[ParagraphSyntaxNode](../paragraphsyntaxnode/)*) | Defines the interface for visit paragraph. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(*[ReferenceImageSyntaxNode](../referenceimagesyntaxnode/)*) | Defines the interface for visit ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(*[ReferenceLinkSyntaxNode](../referencelinksyntaxnode/)*) | Defines the interface for visit ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(*[SetextHeadingSyntaxNode](../setextheadingsyntaxnode/)*) | Defines the interface for visit SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Defines the interface for visit node. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(*[MarkdownSyntaxTree](../markdownsyntaxtree/)*) | Defines the interface for visit MarkdownSyntaxTree. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(*[TableSyntaxNode](../tablesyntaxnode/)*) | Defines the interface for visit TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(*[TextSyntaxNode](../textsyntaxnode/)*) | Defines the interface for visit text syntax. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(*[ThematicBreakSyntaxNode](../thematicbreaksyntaxnode/)*) | Defines the interface for visit ThematicBreakSyntax. |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(*[WhitespaceSyntaxNode](../whitespacesyntaxnode/)*) | Defines the interface for visit Whitespace Syntax. |

### See Also

* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
