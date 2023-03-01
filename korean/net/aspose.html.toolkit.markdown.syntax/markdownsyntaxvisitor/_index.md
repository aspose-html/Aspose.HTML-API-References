---
title: Class MarkdownSyntaxVisitor
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor 수업. 마크다운 구문 방문자의 기본 클래스입니다.
type: docs
weight: 5230
url: /ko/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

마크다운 구문 방문자의 기본 클래스입니다.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | 방문 노드에 대한 인터페이스를 정의합니다. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | 방문 구문 트리에 대한 인터페이스를 정의합니다. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | AtxHeadingSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | 방문 블록에 대한 인터페이스를 정의합니다. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | BlockQuoteSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | CharacterReferenceSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | CodeSpanSyntax. 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | 방문 EmphasisSyntax에 대한 인터페이스를 정의합니다. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | 방문 텍스트 라인에 대한 인터페이스를 정의합니다. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | 방문 이스케이프 문자에 대한 인터페이스를 정의합니다. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | FencedCodeBlockSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | HTMLFragmentSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | InlineImageSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | IndentedCodeBlockSyntax. 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | 방문 HardBreakSyntax에 대한 인터페이스를 정의합니다. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | SoftBreakSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | AutoLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | InlineLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | LinkReferenceDefinitionSyntax. 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | OrderedListSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | UnorderedListSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | ListItemSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | NodeList 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | 방문 단락에 대한 인터페이스를 정의합니다. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | ReferenceImageSyntax. 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | ReferenceLinkSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | SetextHeadingSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | 방문 노드에 대한 인터페이스를 정의합니다. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | 방문 MarkdownSyntaxTree에 대한 인터페이스를 정의합니다. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | TableSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | 방문 텍스트 구문에 대한 인터페이스를 정의합니다. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | ThematicBreakSyntax 방문을 위한 인터페이스를 정의합니다. |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | 방문용 인터페이스 정의 공백 구문. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 집회 [Aspose.HTML](../../)


