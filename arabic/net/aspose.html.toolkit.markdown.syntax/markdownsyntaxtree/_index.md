---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree فصل. تمثل شجرة بناء جملة Markdown .
type: docs
weight: 5220
url: /ar/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

تمثل شجرة بناء جملة Markdown .

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | إنشاء MarkdownSyntaxTree . |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | ينشئ MarkdownSyntaxTree |

## الخصائص

| اسم | وصف |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | احصل على الطفل الأول . |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | احصل على آخر طفل . |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | احصل على الأخ التالي . |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | احصل على العقدة الأصلية . |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | احصل على الشقيق السابق . |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | احصل على SyntaxFactory. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | يحدد الواجهة لزيارة عقد شجرة بناء الجملة. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | إلحاق عقدة فرعية . |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | احصل على مجموعة العقد الفرعية. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | يحدد الواجهة لإنشاء مكرر العقدة. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | يحدد الواجهة لإنشاء مكرر العقدة. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | يحدد الواجهة لإنشاء مكرر العقدة. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | يحدد الواجهة لإنشاء جهاز المشي على الشجرة. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | يحدد الواجهة لإنشاء جهاز المشي على الشجرة. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | يحدد الواجهة لإنشاء جهاز المشي على الشجرة. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | احصل على المعلومات الرائدة . |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | احصل على شجرة البنية . |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | احصل على المعلومات التافهة الزائدة . |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | أدخل قبل العقدة . |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | قم بإزالة الطفل . |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | استبدال العقدة الفرعية . |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | يحفظ شجرة البنية في الدفق المحدد. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | يحفظ شجرة بناء الجملة في المسار المحدد. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | يحفظ شجرة بناء الجملة للكاتب المحدد. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | تجاوز طريقة ToString . |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | الكتابة إلى MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | كتابة العقد لكاتب النص. |

### أنظر أيضا

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* مساحة الاسم [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* المجسم [Aspose.HTML](../../)


