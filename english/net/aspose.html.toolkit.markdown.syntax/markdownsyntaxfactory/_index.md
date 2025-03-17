---
title: MarkdownSyntaxFactory Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxFactory class. Factory used to create various MarkdownSyntaxNode descendants
type: docs
weight: 5440
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
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(*string*) | Creates AtxHeadingSyntaxNode with text content. |
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/). |
| [AtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(*string, int*) | Creates AtxHeadingSyntaxNode with text content and heading level. |
| [AutoLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [AutoLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), bool*) | Creates [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [BlockProxy](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Creates [`BlockProxy`](../blockproxy/). |
| [BlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | Creates [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/). |
| [CharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/), string*) | Creates [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | Creates the [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(*int*) | Creates the [`CodeSpanSyntaxNode`](../codespansyntaxnode/) with the specified number of backticks. |
| [CodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [Emphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(*[Emphasis](../emphasis/)*) | Create the EmphasisSyntax. |
| [Emphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`EmphasisSyntaxNode`](../emphasissyntaxnode/). |
| [EmphasisClosing](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Create EmphasisClosing. |
| [EmphasisOpening](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Create the MarkdownSyntaxToken. |
| [EmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | Creates [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/). |
| [EscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(*char*) | Creates [`TextSyntaxNode`](../textsyntaxnode/). |
| [EscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`TextSyntaxNode`](../textsyntaxnode/). |
| [FencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/)*) | Creates [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [FencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [HardBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/). |
| [HardBreakingTag](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Create HardBreakingTag. |
| [HTMLFragment](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | Creates [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [HTMLFragment](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [HugoShortCode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`HugoShortCodeSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/). |
| [HugoShortCodeParameter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(*[TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ShortCodeParameterSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/). |
| [HugoYamlBasedFrontMatter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`HugoYamlBasedFrontMatterSyntaxNode`](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/). |
| [IndentedCode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | Creates [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [IndentedCode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(*int*) | Creates [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [InlineContainer](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | Creates [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/). |
| [InlineImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(*string, string, string*) | Creates [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [InlineImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [LinkDestinationSyntaxNode](../linkdestinationsyntaxnode/), [LinkTitleSyntaxNode](../linktitlesyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [InlineLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(*string, string, string*) | Creates InlineLink. |
| [InlineLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [LinkDestinationSyntaxNode](../linkdestinationsyntaxnode/), [LinkTitleSyntaxNode](../linktitlesyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/). |
| [InlineProxy](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(*[MarkdownSyntaxNode](../markdownsyntaxnode/)*) | Creates [`InlineProxy`](../inlineproxy/). |
| [LinkDestination](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | Creates [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [LinkDestination](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(*string*) | Creates LinkDestinationSyntaxNode object from a string. |
| [LinkDestination](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [LinkLabel](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(*string*) | Creates link label from a string. |
| [LinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [TextSyntaxNode](../textsyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [LinkDestinationSyntaxNode](../linkdestinationsyntaxnode/), [LinkTitleSyntaxNode](../linktitlesyntaxnode/)*) | Creates [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/). |
| [LinkTitle](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | Creates [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [LinkTitle](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(*string*) | Creates LinkTitleSyntaxNode object from a string. |
| [LinkTitle](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [ListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(*[ListItemMarker](../listitemmarker/)*) | Creates [`ListItemSyntaxNode`](../listitemsyntaxnode/). |
| [ListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ListItemMarker`](../listitemmarker/). |
| [ListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ListItemMarker`](../listitemmarker/). |
| [NewLineTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | Creates NewLineTrivia. |
| [OrderedList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | Creates [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/). |
| [OrderedListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(*int*) | Creates a new instance of the [`ListItemSyntaxNode`](../listitemsyntaxnode/) class with ordered list item marker. |
| [Paragraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | Creates [`ParagraphSyntaxNode`](../paragraphsyntaxnode/). |
| [ReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [InlineContainerSyntaxNode](../inlinecontainersyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/). |
| [ReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [InlineContainerSyntaxNode](../inlinecontainersyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [InlineContainerSyntaxNode](../inlinecontainersyntaxnode/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/). |
| [SetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/). |
| [SoftBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/). |
| [Table](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | Creates [`TableSyntaxNode`](../tablesyntaxnode/). |
| [TableCell](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | Creates [`TableCellSyntaxNode`](../tablecellsyntaxnode/). |
| [TableDelimiter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/). |
| [TableRow](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | Creates [`TableRowSyntaxNode`](../tablerowsyntaxnode/). |
| [TaskListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(*[ListItemMarker](../listitemmarker/), [TaskListItemMarker](../tasklistitemmarker/)*) | Creates [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/). |
| [TaskListItemMarker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/), [MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`TaskListItemMarker`](../tasklistitemmarker/). |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/)*) | Create the TextSyntax from SourceText. |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(*string*) | Creates TextSyntax |
| [Text](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Create the TextSyntax from SourceText and TextSpan. |
| [ThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(*[MarkdownSyntaxToken](../markdownsyntaxtoken/)*) | Creates [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/). |
| [Token](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/)*) | Creates [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [Token](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [Trivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates Whitespace. |
| [UnorderedList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | Creates [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/). |
| [UnorderedListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(*string*) | Creates a new instance of the [`ListItemSyntaxNode`](../listitemsyntaxnode/) class with unordered list item marker. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | Create the WhitespaceSyntax. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(*int*) | Create the WhitespaceSyntax. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/)*) | Create the WhitespaceSyntax. |
| [Whitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(*[SourceText](../../aspose.html.toolkit.markdown.syntax.text/sourcetext/), [TextSpan](../../aspose.html.toolkit.markdown.syntax.text/textspan/)*) | Creates [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |

### See Also

* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
