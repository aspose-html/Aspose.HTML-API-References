---
title: "MarkdownSyntaxFactory 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory 클래스. 다양한 MarkdownSyntaxNode 파생 클래스를 생성하는 데 사용되는 팩토리"
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

다양한 [`MarkdownSyntaxNode`](../markdownsyntaxnode/) 파생 클래스를 생성하는 팩토리.

```java
public class MarkdownSyntaxFactory
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | 텍스트 내용을 가진 AtxHeadingSyntaxNode를 생성합니다. |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/)를 생성합니다. |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | 텍스트 내용과 헤딩 레벨을 가진 AtxHeadingSyntaxNode를 생성합니다. |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`AutoLinkSyntaxNode`](../autolinksyntaxnode/)를 생성합니다. |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | [`AutoLinkSyntaxNode`](../autolinksyntaxnode/)를 생성합니다. |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | [`BlockProxy`](../blockproxy/)를 생성합니다. |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/)를 생성합니다. |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/)를 생성합니다. |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | [`CodeSpanSyntaxNode`](../codespansyntaxnode/)를 생성합니다. |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | 지정된 개수의 백틱을 사용하여 [`CodeSpanSyntaxNode`](../codespansyntaxnode/)를 생성합니다. |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`CodeSpanSyntaxNode`](../codespansyntaxnode/)를 생성합니다. |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | EmphasisSyntax를 생성합니다. |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`EmphasisSyntaxNode`](../emphasissyntaxnode/)를 생성합니다. |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | EmphasisClosing을 생성합니다. |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | MarkdownSyntaxToken을 생성합니다. |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/)를 생성합니다. |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | [`TextSyntaxNode`](../textsyntaxnode/)를 생성합니다. |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | [`TextSyntaxNode`](../textsyntaxnode/)를 생성합니다. |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/)를 생성합니다. |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/)를 생성합니다. |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/)를 생성합니다. |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | HardBreakingTag를 생성합니다. |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | [`HTMLFragmentSyntax`](../htmlfragmentsyntax/)를 생성합니다. |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | [`HTMLFragmentSyntax`](../htmlfragmentsyntax/)를 생성합니다. |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/)를 생성합니다. |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/)를 생성합니다. |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/)를 생성합니다. |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)을 생성합니다. |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/)을 생성합니다. |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/)을 생성합니다. |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)을 생성합니다. |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/)을 생성합니다. |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | InlineLink을 생성합니다. |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/)을 생성합니다. |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | [`InlineProxy`](../inlineproxy/)를 생성합니다. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)을 생성합니다. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | String에서 LinkDestinationSyntaxNode 객체를 생성합니다. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/)을 생성합니다. |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | String에서 링크 레이블을 생성합니다. |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/)을 생성합니다. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)을 생성합니다. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | String에서 LinkTitleSyntaxNode 객체를 생성합니다. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/)을 생성합니다. |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | [`ListItemSyntaxNode`](../listitemsyntaxnode/)을 생성합니다. |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | [`ListItemMarker`](../listitemmarker/)을 생성합니다. |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | [`ListItemMarker`](../listitemmarker/)을 생성합니다. |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | NewLineTrivia를 생성합니다. |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/)을 생성합니다. |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | [`ListItemSyntaxNode`](../listitemsyntaxnode/) 클래스를 정렬된 목록 항목 마커와 함께 새 인스턴스로 생성합니다. |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | [`ParagraphSyntaxNode`](../paragraphsyntaxnode/)을 생성합니다. |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/)을 생성합니다. |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/)을 생성합니다. |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/)을 생성합니다. |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/)을 생성합니다. |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | [`TableSyntaxNode`](../tablesyntaxnode/)을 생성합니다. |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | [`TableCellSyntaxNode`](../tablecellsyntaxnode/)을 생성합니다. |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/)을 생성합니다. |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | 생성합니다 [`TableRowSyntaxNode`](../tablerowsyntaxnode/). |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | 생성합니다 [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/). |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | 생성합니다 [`TaskListItemMarker`](../tasklistitemmarker/). |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | SourceText에서 TextSyntax를 생성합니다. |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | TextSyntax를 생성합니다 |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | SourceText와 TextSpan에서 TextSyntax를 생성합니다. |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | 생성합니다 [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | 생성합니다 [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | 생성합니다 [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Whitespace를 생성합니다. |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | 생성합니다 [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/). |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | [`ListItemSyntaxNode`](../listitemsyntaxnode/) 클래스의 새 인스턴스를 unordered list item marker와 함께 생성합니다. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | WhitespaceSyntax를 생성합니다. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | WhitespaceSyntax를 생성합니다. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | WhitespaceSyntax를 생성합니다. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/)를 생성합니다. |

### 또 보기

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
