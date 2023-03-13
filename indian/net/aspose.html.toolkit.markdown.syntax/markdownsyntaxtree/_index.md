---
title: Class MarkdownSyntaxTree
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree कक्ष. मर्कडउन संटेक्स ट्र क प्रतनधत्व करत है
type: docs
weight: 5220
url: /hi/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

मार्कडाउन सिंटेक्स ट्री का प्रतिनिधित्व करता है।

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | मार्कडाउन सिंटैक्स ट्री बनाया गया। |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | पहला बच्चा प्राप्त करें। |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | अंतिम बच्चा प्राप्त करें। |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | अपने अगले भाई को प्राप्त करें। |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | मूल नोड प्राप्त करें। |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | पिछला भाई प्राप्त करें. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | सिंटैक्स फैक्ट्री प्राप्त करें। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | सिंटैक्स ट्री के विज़िटिंग नोड्स के लिए इंटरफ़ेस को परिभाषित करता है। |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | चाइल्ड नोड जोड़ें. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | चाइल्ड नोड संग्रह प्राप्त करें। |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | नोड पुनरावर्तक के निर्माण के लिए इंटरफ़ेस को परिभाषित करता है। |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | नोड पुनरावर्तक के निर्माण के लिए इंटरफ़ेस को परिभाषित करता है। |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | नोड पुनरावर्तक के निर्माण के लिए इंटरफ़ेस को परिभाषित करता है। |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | प्रमुख ट्रिविया प्राप्त करें. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | सिंटैक्स ट्री प्राप्त करें। |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | ट्रेलिंग ट्रिविया प्राप्त करें। |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | नोड से पहले डालें. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | बच्चे को हटा दें। |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | चाइल्ड नोड बदलें. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | सिंटैक्स ट्री को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | सिंटैक्स ट्री को निर्दिष्ट पथ पर सहेजता है। |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | सिंटैक्स ट्री को निर्दिष्ट लेखक के लिए सहेजता है। |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString विधि को ओवरराइड करें। |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter को लिखें. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | टेक्स्ट राइटर को नोड लिखें। |

### यह सभी देखें

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* नाम स्थान [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* सभा [Aspose.HTML](../../)


