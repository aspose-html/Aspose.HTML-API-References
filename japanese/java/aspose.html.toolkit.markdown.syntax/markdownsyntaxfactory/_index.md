---
title: "MarkdownSyntaxFactory クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory クラス。さまざまな MarkdownSyntaxNode の派生クラスを作成するために使用されるファクトリです。"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

さまざまな [`MarkdownSyntaxNode`](../markdownsyntaxnode/) の派生クラスを作成するために使用されるファクトリです。

```java
public class MarkdownSyntaxFactory
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | テキストコンテンツを持つ AtxHeadingSyntaxNode を作成します。 |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/) を作成します。 |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | テキストコンテンツと見出しレベルを持つ AtxHeadingSyntaxNode を作成します。 |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`AutoLinkSyntaxNode`](../autolinksyntaxnode/) を作成します。 |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | [`AutoLinkSyntaxNode`](../autolinksyntaxnode/) を作成します。 |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | [`BlockProxy`](../blockproxy/) を作成します。 |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/) を作成します。 |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/) を作成します。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | 次の [`CodeSpanSyntaxNode`](../codespansyntaxnode/) を作成します。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | 指定された数のバックティックを使用して、[`CodeSpanSyntaxNode`](../codespansyntaxnode/) を作成します。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`CodeSpanSyntaxNode`](../codespansyntaxnode/) を作成します。 |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | EmphasisSyntax を作成します。 |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`EmphasisSyntaxNode`](../emphasissyntaxnode/) を作成します。 |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | EmphasisClosing を作成します。 |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | MarkdownSyntaxToken を作成します。 |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/) を作成します。 |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | [`TextSyntaxNode`](../textsyntaxnode/) を作成します。 |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | [`TextSyntaxNode`](../textsyntaxnode/) を作成します。 |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/) を作成します。 |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/) を作成します。 |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/) を作成します。 |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | HardBreakingTag を作成します。 |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | [`HTMLFragmentSyntax`](../htmlfragmentsyntax/) を作成します。 |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | [`HTMLFragmentSyntax`](../htmlfragmentsyntax/) を作成します。 |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/) を作成します。 |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/) を作成します。 |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/) を作成します。 |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | 作成します [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)。 |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | 作成します [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)。 |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | 作成します [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/)。 |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | 作成します [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)。 |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | 作成します [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)。 |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | InlineLink を作成します。 |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | 作成します [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/)。 |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | 作成します [`InlineProxy`](../inlineproxy/)。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | 作成します [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | 文字列から LinkDestinationSyntaxNode オブジェクトを作成します。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 作成します [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)。 |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | 文字列からリンクラベルを作成します。 |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | 作成します [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/)。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | 作成します [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | 文字列から LinkTitleSyntaxNode オブジェクトを作成します。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 作成します [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)。 |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | 作成します [`ListItemSyntaxNode`](../listitemsyntaxnode/)。 |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | 作成します [`ListItemMarker`](../listitemmarker/)。 |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 作成します [`ListItemMarker`](../listitemmarker/)。 |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | NewLineTrivia を作成します。 |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | 作成します [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/)。 |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | 順序付きリスト項目マーカーを使用して、[`ListItemSyntaxNode`](../listitemsyntaxnode/) クラスの新しいインスタンスを作成します。 |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | 作成します [`ParagraphSyntaxNode`](../paragraphsyntaxnode/)。 |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | 作成します [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/)。 |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | 作成します [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/)。 |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | 作成します [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/)。 |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | 作成します [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/)。 |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | 作成します [`TableSyntaxNode`](../tablesyntaxnode/)。 |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | 作成します [`TableCellSyntaxNode`](../tablecellsyntaxnode/)。 |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | 作成します [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/)。 |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | [`TableRowSyntaxNode`](../tablerowsyntaxnode/) を作成します。 |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/) を作成します。 |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | [`TaskListItemMarker`](../tasklistitemmarker/) を作成します。 |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | SourceText から TextSyntax を作成します。 |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | TextSyntax を作成します |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | SourceText と TextSpan から TextSyntax を作成します。 |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/) を作成します。 |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | [`MarkdownSyntaxToken`](../markdownsyntaxtoken/) を作成します。 |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | [`MarkdownSyntaxToken`](../markdownsyntaxtoken/) を作成します。 |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Whitespace を作成します。 |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/) を作成します。 |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | [`ListItemSyntaxNode`](../listitemsyntaxnode/) クラスの新しいインスタンスを、順序なしリスト項目マーカーと共に作成します。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | WhitespaceSyntax を作成します。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | WhitespaceSyntax を作成します。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | WhitespaceSyntax を作成します。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/) を作成します。 |

### 関連項目

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
