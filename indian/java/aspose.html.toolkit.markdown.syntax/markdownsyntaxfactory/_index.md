---
title: "MarkdownSyntaxFactory क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory क्लास। विभिन्न MarkdownSyntaxNode वंशज बनाने के लिए उपयोग किया जाने वाला फ़ैक्टरी"
type: docs

url: /hi/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

विभिन्न [`MarkdownSyntaxNode`](../markdownsyntaxnode/) वंशज बनाने के लिए उपयोग किया जाने वाला फ़ैक्टरी।

```java
public class MarkdownSyntaxFactory
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | टेक्स्ट सामग्री के साथ AtxHeadingSyntaxNode बनाता है। |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/). |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | टेक्स्ट सामग्री और हेडिंग स्तर के साथ AtxHeadingSyntaxNode बनाता है। |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | बनाता है [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | बनाता है [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | बनाता है [`BlockProxy`](../blockproxy/). |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | बनाता है [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/). |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | बनाता है [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | बनाता है [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | निर्दिष्ट बैकटिक संख्या के साथ [`CodeSpanSyntaxNode`](../codespansyntaxnode/) बनाता है। |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | EmphasisSyntax बनाएं। |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`EmphasisSyntaxNode`](../emphasissyntaxnode/). |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | EmphasisClosing बनाएं। |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | MarkdownSyntaxToken बनाएं। |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | बनाता है [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | बनाता है [`TextSyntaxNode`](../textsyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | बनाता है [`TextSyntaxNode`](../textsyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | बनाता है [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | बनाता है [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | बनाता है [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/). |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | HardBreakingTag बनाएं। |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | बनाता है [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | बनाता है [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/). |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | बनाता है [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/). |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | बनाता है [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | बनाता है [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | बनाता है [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | बनाता है [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | बनाता है [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | बनाता है [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | बनाता है InlineLink. |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | बनाता है [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/). |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | बनाता है [`InlineProxy`](../inlineproxy/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | बनाता है [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | एक स्ट्रिंग से LinkDestinationSyntaxNode ऑब्जेक्ट बनाता है. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | एक स्ट्रिंग से लिंक लेबल बनाता है. |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | बनाता है [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | बनाता है [`LinkTitleSyntaxNode`](../linktitlessyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | एक स्ट्रिंग से LinkTitleSyntaxNode ऑब्जेक्ट बनाता है. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`LinkTitleSyntaxNode`](../linktitlessyntaxnode/). |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | बनाता है [`ListItemSyntaxNode`](../listitemsyntaxnode/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | बनाता है [`ListItemMarker`](../listitemmarker/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`ListItemMarker`](../listitemmarker/). |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | बनाता है NewLineTrivia. |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | बनाता है [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/). |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | एक नया उदाहरण बनाता है [`ListItemSyntaxNode`](../listitemsyntaxnode/) वर्ग का क्रमबद्ध सूची आइटम मार्कर के साथ. |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | बनाता है [`ParagraphSyntaxNode`](../paragraphsyntaxnode/). |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | बनाता है [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/). |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | बनाता है [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/). |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | बनाता है [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/). |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | बनाता है [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/). |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | बनाता है [`TableSyntaxNode`](../tablesyntaxnode/). |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | बनाता है [`TableCellSyntaxNode`](../tablecellsyntaxnode/). |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | बनाता है [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/). |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | बनाता है [`TableRowSyntaxNode`](../tablerowsyntaxnode/)। |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | बनाता है [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/)। |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | बनाता है [`TaskListItemMarker`](../tasklistitemmarker/)। |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | SourceText से TextSyntax बनाइए। |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | TextSyntax बनाता है |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | SourceText और TextSpan से TextSyntax बनाइए। |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | बनाता है [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/)। |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | बनाता है [`MarkdownSyntaxToken`](../markdownsyntaxtoken/)। |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | बनाता है [`MarkdownSyntaxToken`](../markdownsyntaxtoken/)। |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Whitespace बनाता है। |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | बनाता है [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/)। |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | unordered list item marker के साथ [`ListItemSyntaxNode`](../listitemsyntaxnode/) क्लास का नया उदाहरण बनाता है। |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | WhitespaceSyntax बनाइए। |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | WhitespaceSyntax बनाइए। |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | WhitespaceSyntax बनाइए। |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | बनाता है [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |

### संबंधित देखें

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
