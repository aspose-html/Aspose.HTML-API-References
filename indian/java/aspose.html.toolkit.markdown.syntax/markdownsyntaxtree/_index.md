---
title: "MarkdownSyntaxTree क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree क्लास। Markdown सिंटैक्स ट्री का प्रतिनिधित्व करता है"
type: docs

url: /hi/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Markdown सिंटैक्स ट्री का प्रतिनिधित्व करता है।

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | MarkdownSyntaxTree बनाया गया। |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | MarkdownSyntaxTree बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) पहला चाइल्ड प्राप्त करें। |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) अंतिम चाइल्ड प्राप्त करें। |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) अगला सिब्लिंग प्राप्त करें। |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) पैरेंट नोड प्राप्त करें। |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) पिछला सिब्लिंग प्राप्त करें। |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) SyntaxFactory प्राप्त करें। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | सिंटैक्स ट्री के नोड्स का दौरा करने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | चाइल्ड नोड जोड़ें। |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | चाइल्ड नोड्स संग्रह प्राप्त करें। |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | नोड इटरेटर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | नोड इटरेटर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | नोड इटरेटर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | ट्री वॉकर बनाने के लिए इंटरफ़ेस को परिभाषित करता है। |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | लीडिंग ट्रिविया प्राप्त करें। |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | सिंटैक्स ट्री प्राप्त करें। |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | ट्रेलिंग ट्रिविया प्राप्त करें। |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | नोड से पहले डालें। |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | चाइल्ड को हटाएँ। |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | चाइल्ड नोड को बदलें। |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | निर्दिष्ट स्ट्रीम में सिंटैक्स ट्री को सहेजता है। |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | निर्दिष्ट पथ में सिंटैक्स ट्री को सहेजता है। |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | निर्दिष्ट राइटर में सिंटैक्स ट्री को सहेजता है। |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | ToString मेथड को ओवरराइड करें। |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | MarkdownTextWriter में लिखें। |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | नोड्स को टेक्स्ट राइटर में लिखें। |

### संबंधित देखें

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
