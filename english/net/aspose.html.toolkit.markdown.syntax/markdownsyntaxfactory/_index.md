---
title: MarkdownSyntaxFactory Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxFactory class. Factory used to create various MarkdownSyntaxNode descendants
type: docs
weight: 5190
url: /net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

Factory used to create various [`MarkdownSyntaxNode`](../markdownsyntaxnode/) descendants.

```csharp
public class MarkdownSyntaxFactory
```

## Methods

| Name | Description |
| --- | --- |
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(string) | Creates AtxHeadingSyntaxNode with text content. |
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/). |
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(string, int) | Creates AtxHeadingSyntaxNode with text content and heading level. |
| [AutoLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | Creates [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [BlockProxy](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | Creates [`BlockProxy`](../blockproxy/). |
| [BlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | Creates [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/). |
| [CharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, string) | Creates [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | Creates the [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | Creates the [`CodeSpanSyntaxNode`](../codespansyntaxnode/) with the specified number of backticks. |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [Emphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | Create the EmphasisSyntax. |
| [Emphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`EmphasisSyntaxNode`](../emphasissyntaxnode/). |
| [EmphasisClosing](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | Create EmphasisClosing. |
| [EmphasisOpening](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | Create the MarkdownSyntaxToken. |
| [EmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | Creates [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/). |
| [EscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | Creates [`TextSyntaxNode`](../textsyntaxnode/). |
| [EscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | Creates [`TextSyntaxNode`](../textsyntaxnode/). |
| [FencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Creates [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [HardBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | Creates [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/). |
| [HardBreakingTag](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | Create HardBreakingTag. |
| [HTMLFragment](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | Creates [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [HTMLFragment](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | Creates [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [HugoShortCode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`HugoShortCodeSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/). |
| [HugoShortCodeParameter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Creates [`ShortCodeParameterSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/). |
| [HugoYamlBasedFrontMatter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Creates [`HugoYamlBasedFrontMatterSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/). |
| [IndentedCode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/)(int) | Creates [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [InlineContainer](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | Creates [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/). |
| [InlineImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(string, string, string) | Creates [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [InlineImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Creates [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [InlineLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(string, string, string) | Creates InlineLink. |
| [InlineLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Creates [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/). |
| [InlineProxy](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | Creates [`InlineProxy`](../inlineproxy/). |
| [LinkDestination](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(string) | Creates LinkDestinationSyntaxNode object from a string. |
| [LinkDestination](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [LinkLabel](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(string) | Creates link label from a string. |
| [LinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | Creates [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/). |
| [LinkTitle](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(string) | Creates LinkTitleSyntaxNode object from a string. |
| [LinkTitle](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [ListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | Creates [`ListItemSyntaxNode`](../listitemsyntaxnode/). |
| [ListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | Creates [`ListItemMarker`](../listitemmarker/). |
| [ListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`ListItemMarker`](../listitemmarker/). |
| [NewLineTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | Creates NewLineTrivia. |
| [OrderedList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | Creates [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/). |
| [OrderedListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | Creates a new instance of the [`ListItemSyntaxNode`](../listitemsyntaxnode/) class with ordered list item marker. |
| [Paragraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | Creates [`ParagraphSyntaxNode`](../paragraphsyntaxnode/). |
| [ReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Creates [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/). |
| [ReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Creates [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/). |
| [SetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | Creates [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/). |
| [SoftBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | Creates [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/). |
| [Table](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | Creates [`TableSyntaxNode`](../tablesyntaxnode/). |
| [TableCell](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | Creates [`TableCellSyntaxNode`](../tablecellsyntaxnode/). |
| [TableDelimiter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | Creates [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/). |
| [TableRow](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | Creates [`TableRowSyntaxNode`](../tablerowsyntaxnode/). |
| [TaskListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | Creates [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/). |
| [TaskListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Creates [`TaskListItemMarker`](../tasklistitemmarker/). |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | Create the TextSyntax from SourceText. |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(string) | Creates TextSyntax |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | Create the TextSyntax from SourceText and TextSpan. |
| [ThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | Creates [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/). |
| [Token](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | Creates [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [Token](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | Creates [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [Trivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Creates Whitespace. |
| [UnorderedList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | Creates [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/). |
| [UnorderedListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(string) | Creates a new instance of the [`ListItemSyntaxNode`](../listitemsyntaxnode/) class with unordered list item marker. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(int) | Create the WhitespaceSyntax. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)(SourceText) | Create the WhitespaceSyntax. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText, TextSpan) | Creates [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |

### See Also

* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
