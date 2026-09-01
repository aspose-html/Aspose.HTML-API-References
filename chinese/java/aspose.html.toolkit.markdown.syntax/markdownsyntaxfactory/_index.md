---
title: "MarkdownSyntaxFactory 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory 类。用于创建各种 MarkdownSyntaxNode 派生类的工厂"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

用于创建各种 [`MarkdownSyntaxNode`](../markdownsyntaxnode/) 派生类的工厂。

```java
public class MarkdownSyntaxFactory
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | 创建带有文本内容的 AtxHeadingSyntaxNode。 |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/)。 |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | 创建带有文本内容和标题级别的 AtxHeadingSyntaxNode。 |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | 创建 [`AutoLinkSyntaxNode`](../autolinksyntaxnode/)。 |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | 创建 [`AutoLinkSyntaxNode`](../autolinksyntaxnode/)。 |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | 创建 [`BlockProxy`](../blockproxy/)。 |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | 创建 [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/)。 |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | 创建 [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/)。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | 创建 [`CodeSpanSyntaxNode`](../codespansyntaxnode/)。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | 创建具有指定数量反引号的 [`CodeSpanSyntaxNode`](../codespansyntaxnode/)。 |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`CodeSpanSyntaxNode`](../codespansyntaxnode/)。 |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | 创建 EmphasisSyntax。 |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`EmphasisSyntaxNode`](../emphasissyntaxnode/)。 |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | 创建 EmphasisClosing。 |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | 创建 MarkdownSyntaxToken。 |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | 创建 [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/)。 |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | 创建 [`TextSyntaxNode`](../textsyntaxnode/)。 |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | 创建 [`TextSyntaxNode`](../textsyntaxnode/)。 |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | 创建 [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/)。 |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | 创建 [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/)。 |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | 创建 [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/)。 |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | 创建 HardBreakingTag。 |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | 创建 [`HTMLFragmentSyntax`](../htmlfragmentsyntax/)。 |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | 创建 [`HTMLFragmentSyntax`](../htmlfragmentsyntax/)。 |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/)。 |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | 创建 [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/)。 |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | 创建 [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/)。 |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | 创建 [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)。 |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | 创建 [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)。 |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | 创建 [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/)。 |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | 创建 [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)。 |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | 创建 [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)。 |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | 创建 InlineLink。 |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | 创建 [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/)。 |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | 创建 [`InlineProxy`](../inlineproxy/)。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | 创建 [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | 创建来自字符串的 LinkDestinationSyntaxNode 对象。 |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)。 |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | 创建来自字符串的链接标签。 |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | 创建 [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/)。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | 创建 [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | 创建来自字符串的 LinkTitleSyntaxNode 对象。 |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)。 |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | 创建 [`ListItemSyntaxNode`](../listitemsyntaxnode/)。 |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | 创建 [`ListItemMarker`](../listitemmarker/)。 |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`ListItemMarker`](../listitemmarker/)。 |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | 创建 NewLineTrivia。 |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | 创建 [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/)。 |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | 创建一个新的 [`ListItemSyntaxNode`](../listitemsyntaxnode/) 类实例，使用有序列表项标记。 |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | 创建 [`ParagraphSyntaxNode`](../paragraphsyntaxnode/)。 |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | 创建 [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/)。 |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | 创建 [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/)。 |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | 创建 [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/)。 |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | 创建 [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/)。 |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | 创建 [`TableSyntaxNode`](../tablesyntaxnode/)。 |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | 创建 [`TableCellSyntaxNode`](../tablecellsyntaxnode/)。 |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | 创建 [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/)。 |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | 创建 [`TableRowSyntaxNode`](../tablerowsyntaxnode/)。 |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | 创建 [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/)。 |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | 创建 [`TaskListItemMarker`](../tasklistitemmarker/)。 |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | 从 SourceText 创建 TextSyntax。 |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | 创建 TextSyntax |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | 从 SourceText 和 TextSpan 创建 TextSyntax。 |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | 创建 [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/)。 |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | 创建 [`MarkdownSyntaxToken`](../markdownsyntaxtoken/)。 |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | 创建 [`MarkdownSyntaxToken`](../markdownsyntaxtoken/)。 |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | 创建空白。 |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | 创建 [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/)。 |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | 使用无序列表项标记创建 [`ListItemSyntaxNode`](../listitemsyntaxnode/) 类的新实例。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | 创建 WhitespaceSyntax。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | 创建 WhitespaceSyntax。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | 创建 WhitespaceSyntax。 |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | 创建 [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/)。 |

### 另请参见

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
