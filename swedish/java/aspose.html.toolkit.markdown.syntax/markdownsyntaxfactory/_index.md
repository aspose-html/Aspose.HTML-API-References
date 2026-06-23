---
title: "MarkdownSyntaxFactory klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory-klass. Fabrik som används för att skapa olika MarkdownSyntaxNode-efterkommande."
type: docs

url: /sv/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

Fabrik som används för att skapa olika [`MarkdownSyntaxNode`](../markdownsyntaxnode/) efterkommande.

```java
public class MarkdownSyntaxFactory
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | Skapar AtxHeadingSyntaxNode med textinnehåll. |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/). |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | Skapar AtxHeadingSyntaxNode med textinnehåll och rubriknivå. |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Skapar [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | Skapar [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | Skapar [`BlockProxy`](../blockproxy/). |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | Skapar [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/). |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | Skapar [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | Skapar [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | Skapar [`CodeSpanSyntaxNode`](../codespansyntaxnode/) med det angivna antalet bakåtsnedstreck. |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | Skapa EmphasisSyntax. |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`EmphasisSyntaxNode`](../emphasissyntaxnode/). |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | Skapa EmphasisClosing. |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | Skapa MarkdownSyntaxToken. |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | Skapar [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | Skapar [`TextSyntaxNode`](../textsyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | Skapar [`TextSyntaxNode`](../textsyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | Skapar [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Skapar [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | Skapar [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/). |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | Skapa HardBreakingTag. |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | Skapar [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | Skapar [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/). |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Skapar [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/). |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Skapar [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | Skapar [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | Skapar [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | Skapar [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | Skapar [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Skapar [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | Skapar InlineLink. |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Skapar [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/). |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | Skapar [`InlineProxy`](../inlineproxy/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | Skapar [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | Skapar LinkDestinationSyntaxNode-objekt från en sträng. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | Skapar länketikett från en sträng. |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | Skapar [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | Skapar [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | Skapar LinkTitleSyntaxNode-objekt från en sträng. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | Skapar [`ListItemSyntaxNode`](../listitemsyntaxnode/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | Skapar [`ListItemMarker`](../listitemmarker/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`ListItemMarker`](../listitemmarker/). |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | Skapar NewLineTrivia. |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | Skapar [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/). |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | Skapar en ny instans av klassen [`ListItemSyntaxNode`](../listitemsyntaxnode/) med markerare för ordnad listpost. |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | Skapar [`ParagraphSyntaxNode`](../paragraphsyntaxnode/). |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Skapar [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/). |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Skapar [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/). |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | Skapar [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/). |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | Skapar [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/). |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | Skapar [`TableSyntaxNode`](../tablesyntaxnode/). |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | Skapar [`TableCellSyntaxNode`](../tablecellsyntaxnode/). |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | Skapar [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/). |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | Skapar [`TableRowSyntaxNode`](../tablerowsyntaxnode/). |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | Skapar [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/). |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Skapar [`TaskListItemMarker`](../tasklistitemmarker/). |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | Skapa TextSyntax från SourceText. |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | Skapar TextSyntax |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | Skapa TextSyntax från SourceText och TextSpan. |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | Skapar [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | Skapar [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | Skapar [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Skapar blanksteg. |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | Skapar [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/). |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | Skapar en ny instans av klassen [`ListItemSyntaxNode`](../listitemsyntaxnode/) med markör för oordnad listpost. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | Skapa WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | Skapa WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | Skapa WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | Skapar [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |

### Se även

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
