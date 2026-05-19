---
title: "MarkdownSyntaxVisitor 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxVisitor 클래스. 마크다운 구문 방문자를 위한 기본 클래스입니다."
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

마크다운 구문 방문자를 위한 기본 클래스입니다.

```java
public abstract class MarkdownSyntaxVisitor
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | 노드를 방문하기 위한 인터페이스를 정의합니다. |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | 구문 트리를 방문하기 위한 인터페이스를 정의합니다. |
| [visitAtxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | AtxHeadingSyntax를 방문하기 위한 인터페이스를 정의합니다. |
| [visitBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | 블록을 방문하기 위한 인터페이스를 정의합니다. |
| [visitBlockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | BlockQuoteSyntax를 방문하기 위한 인터페이스를 정의합니다. |
| [visitCharacterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | CharacterReferenceSyntax를 방문하기 위한 인터페이스를 정의합니다. |
| [visitCodeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | CodeSpanSyntax를 방문하기 위한 인터페이스를 정의합니다. |
| [visitEmphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | EmphasisSyntax를 방문하기 위한 인터페이스를 정의합니다. |
| [visitEmptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | 텍스트 라인을 방문하기 위한 인터페이스를 정의합니다. |
| [visitEscapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | 이스케이프 문자를 방문하기 위한 인터페이스를 정의합니다. |
| [visitFencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | FencedCodeBlockSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitHtml](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | HTMLFragmentSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | InlineImageSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitIndentedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | IndentedCodeBlockSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | HardBreakSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | SoftBreakSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | AutoLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | InlineLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitLinkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | LinkReferenceDefinitionSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | OrderedListSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | UnorderedListSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | ListItemSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitNodeList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | NodeList 방문을 위한 인터페이스를 정의합니다. |
| [visitParagraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | paragraph 방문을 위한 인터페이스를 정의합니다. |
| [visitReferenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | ReferenceImageSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitReferenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | ReferenceLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitSetextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | SetextHeadingSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | 노드를 방문하기 위한 인터페이스를 정의합니다. |
| [visitSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | MarkdownSyntaxTree 방문을 위한 인터페이스를 정의합니다. |
| [visitTable](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | TableSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitText](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | text syntax 방문을 위한 인터페이스를 정의합니다. |
| [visitThematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | ThematicBreakSyntax 방문을 위한 인터페이스를 정의합니다. |
| [visitWhitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Whitespace Syntax 방문을 위한 인터페이스를 정의합니다. |

### 또 보기

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
