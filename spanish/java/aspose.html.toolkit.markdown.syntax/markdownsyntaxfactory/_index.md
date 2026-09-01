---
title: "Clase MarkdownSyntaxFactory"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxFactory. Fábrica utilizada para crear varios descendientes de MarkdownSyntaxNode"
type: docs

url: /es/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/
---
## MarkdownSyntaxFactory class

Fábrica utilizada para crear varios descendientes de [`MarkdownSyntaxNode`](../markdownsyntaxnode/).

```java
public class MarkdownSyntaxFactory
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_1)(String) | Crea AtxHeadingSyntaxNode con contenido de texto. |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`AtxHeadingSyntaxNode`](../atxheadingsyntaxnode/). |
| [atxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/atxheading/#atxheading_2)(String, int) | Crea AtxHeadingSyntaxNode con contenido de texto y nivel de encabezado. |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Crea [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [autoLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/autolink/#autolink_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, bool) | Crea [`AutoLinkSyntaxNode`](../autolinksyntaxnode/). |
| [blockProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockproxy/)(MarkdownSyntaxNode) | Crea [`BlockProxy`](../blockproxy/). |
| [blockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/blockquote/)() | Crea [`BlockQuoteSyntaxNode`](../blockquotesyntaxnode/). |
| [characterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/characterreference/)(SourceText, TextSpan, String) | Crea [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan)() | Crea el [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_2)(int) | Crea el [`CodeSpanSyntaxNode`](../codespansyntaxnode/) con el número especificado de acentos graves. |
| [codeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/codespan/#codespan_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`CodeSpanSyntaxNode`](../codespansyntaxnode/). |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis)(Emphasis) | Crea la EmphasisSyntax. |
| [emphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasis/#emphasis_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`EmphasisSyntaxNode`](../emphasissyntaxnode/). |
| [emphasisClosing](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisclosing/)(SourceText, TextSpan) | Crea EmphasisClosing. |
| [emphasisOpening](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emphasisopening/)(SourceText, TextSpan) | Crea el MarkdownSyntaxToken. |
| [emptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/emptyline/)() | Crea [`EmptyLineSyntaxNode`](../emptylinesyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter_1)(char) | Crea [`TextSyntaxNode`](../textsyntaxnode/). |
| [escapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/escapedcharacter/#escapedcharacter)(SourceText, TextSpan) | Crea [`TextSyntaxNode`](../textsyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock)(MarkdownSyntaxToken, TextSyntaxNode) | Crea [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [fencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/fencedcodeblock/#fencedcodeblock_1)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Crea [`FencedCodeBlockSyntaxNode`](../fencedcodeblocksyntaxnode/). |
| [hardBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreak/)(MarkdownSyntaxToken, SourceText, TextSpan) | Crea [`HardBreakSyntaxNode`](../hardbreaksyntaxnode/). |
| [hardBreakingTag](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hardbreakingtag/)(SourceText, TextSpan) | Crea HardBreakingTag. |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment)() | Crea [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hTMLFragment](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/htmlfragment/#htmlfragment_1)(SourceText, TextSpan) | Crea [`HTMLFragmentSyntax`](../htmlfragmentsyntax/). |
| [hugoShortCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcode/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`HugoShortCodeSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoshortcodesyntaxnode/). |
| [hugoShortCodeParameter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoshortcodeparameter/)(TextSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Crea [`ShortCodeParameterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/shortcodeparametersyntaxnode/). |
| [hugoYamlBasedFrontMatter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/hugoyamlbasedfrontmatter/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken) | Crea [`HugoYamlBasedFrontMatterSyntaxNode`](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode)() | Crea [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [indentedCode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/indentedcode/#indentedcode_1)(int) | Crea [`IndentedCodeBlockSyntaxNode`](../indentedcodeblocksyntaxnode/). |
| [inlineContainer](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinecontainer/)() | Crea [`InlineContainerSyntaxNode`](../inlinecontainersyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage_1)(String, String, String) | Crea [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineimage/#inlineimage)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Crea [`InlineImageSyntaxNode`](../inlineimagesyntaxnode/). |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink_1)(String, String, String) | Crea InlineLink. |
| [inlineLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/#inlinelink)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) | Crea [`InlineLinkSyntaxNode`](../inlinelinksyntaxnode/). |
| [inlineProxy](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlineproxy/)(MarkdownSyntaxNode) | Crea [`InlineProxy`](../inlineproxy/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination)() | Crea [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_2)(String) | Crea un objeto LinkDestinationSyntaxNode a partir de una cadena. |
| [linkDestination](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkdestination/#linkdestination_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`LinkDestinationSyntaxNode`](../linkdestinationsyntaxnode/). |
| [linkLabel](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linklabel/)(String) | Crea una etiqueta de enlace a partir de una cadena. |
| [linkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linkreferencedefinition/)(MarkdownSyntaxToken, TextSyntaxNode, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode) | Crea [`LinkReferenceDefinitionSyntaxNode`](../linkreferencedefinitionsyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle)() | Crea [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_2)(String) | Crea un objeto LinkTitleSyntaxNode a partir de una cadena. |
| [linkTitle](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/linktitle/#linktitle_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`LinkTitleSyntaxNode`](../linktitlesyntaxnode/). |
| [listItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitem/)(ListItemMarker) | Crea [`ListItemSyntaxNode`](../listitemsyntaxnode/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker)(MarkdownSyntaxToken) | Crea [`ListItemMarker`](../listitemmarker/). |
| [listItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/listitemmarker/#listitemmarker_1)(MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`ListItemMarker`](../listitemmarker/). |
| [newLineTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/newlinetrivia/)() | Crea NewLineTrivia. |
| [orderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlist/)() | Crea [`OrderedListSyntaxNode`](../orderedlistsyntaxnode/). |
| [orderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/orderedlistitem/)(int) | Crea una nueva instancia de la clase [`ListItemSyntaxNode`](../listitemsyntaxnode/) con marcador de elemento de lista ordenada. |
| [paragraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/paragraph/)() | Crea [`ParagraphSyntaxNode`](../paragraphsyntaxnode/). |
| [referenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referenceimage/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Crea [`ReferenceImageSyntaxNode`](../referenceimagesyntaxnode/). |
| [referenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/referencelink/)(MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken, MarkdownSyntaxToken, InlineContainerSyntaxNode, MarkdownSyntaxToken) | Crea [`ReferenceLinkSyntaxNode`](../referencelinksyntaxnode/). |
| [setextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/setextheading/)(MarkdownSyntaxToken) | Crea [`SetextHeadingSyntaxNode`](../setextheadingsyntaxnode/). |
| [softBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/softbreak/)(SourceText, TextSpan) | Crea [`SoftBreakSyntaxNode`](../softbreaksyntaxnode/). |
| [table](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/table/)() | Crea [`TableSyntaxNode`](../tablesyntaxnode/). |
| [tableCell](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablecell/)() | Crea [`TableCellSyntaxNode`](../tablecellsyntaxnode/). |
| [tableDelimiter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tabledelimiter/)(MarkdownSyntaxToken) | Crea [`TableDelimiterSyntaxNode`](../tabledelimitersyntaxnode/). |
| [tableRow](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tablerow/)() | Crea [`TableRowSyntaxNode`](../tablerowsyntaxnode/). |
| [taskListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitem/)(ListItemMarker, TaskListItemMarker) | Crea [`TaskListItemSyntaxNode`](../tasklistitemsyntaxnode/). |
| [taskListItemMarker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/tasklistitemmarker/)(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken) | Crea [`TaskListItemMarker`](../tasklistitemmarker/). |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text)(SourceText) | Crea el TextSyntax a partir de SourceText. |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_2)(String) | Crea TextSyntax |
| [text](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/text/#text_1)(SourceText, TextSpan) | Crea el TextSyntax a partir de SourceText y TextSpan. |
| [thematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/thematicbreak/)(MarkdownSyntaxToken) | Crea [`ThematicBreakSyntaxNode`](../thematicbreaksyntaxnode/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token)(SourceText) | Crea [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [token](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/token/#token_1)(SourceText, TextSpan) | Crea [`MarkdownSyntaxToken`](../markdownsyntaxtoken/). |
| [trivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/trivia/)(SourceText, TextSpan) | Crea Whitespace. |
| [unorderedList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlist/)() | Crea [`UnorderedListSyntaxNode`](../unorderedlistsyntaxnode/). |
| [unorderedListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/unorderedlistitem/)(String) | Crea una nueva instancia de la clase [`ListItemSyntaxNode`](../listitemsyntaxnode/) con marcador de elemento de lista desordenada. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace)() | Crea el WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_3)(int) | Crea el WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_1)(SourceText) | Crea el WhitespaceSyntax. |
| [whitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/whitespace/#whitespace_2)(SourceText, TextSpan) | Crea [`WhitespaceSyntaxNode`](../whitespacesyntaxnode/). |

### Ver también

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
