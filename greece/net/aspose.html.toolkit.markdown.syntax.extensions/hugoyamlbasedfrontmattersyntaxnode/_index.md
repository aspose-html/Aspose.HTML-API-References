---
title: Class HugoYamlBasedFrontMatterSyntaxNode
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoYamlBasedFrontMatterSyntaxNode τάξη. Ορίζει το HugoYamlBasedFrontMatterSyntaxNode
type: docs
weight: 4940
url: /el/net/aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/
---
## HugoYamlBasedFrontMatterSyntaxNode class

Ορίζει το HugoYamlBasedFrontMatterSyntaxNode

```csharp
public class HugoYamlBasedFrontMatterSyntaxNode : HugoFrontMatterSyntaxNode, 
    IEnumerable<KeyValuePair<string, ChildFrontMatterSyntaxNode>>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Πάρε το πρώτο παιδί. |
| override [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/frontmatterrootnode/) { get; } | Λήψη και ρύθμιση του RootNode. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Πάρε το τελευταίο παιδί. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Πάρε το επόμενο αδερφάκι. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Λήψη του γονικού κόμβου. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Πάρε το προηγούμενο αδερφάκι. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Καθορίζει τη διεπαφή για την αποδοχή επισκέπτη. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Προσθήκη θυγατρικού κόμβου. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Λήψη της συλλογής θυγατρικών κόμβων. |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/)(params string[]) | Καθορίζει τη διεπαφή για την εύρεση BaseSyntaxNode |
| override [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/find/#find_1)(params string[]) | Καθορίζει τη διεπαφή για την εύρεση T με συμβολοσειρά Path |
| [GetEnumerator](../../aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/getenumerator/)() | Λήψη Enumerator. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Αποκτήστε τα κορυφαία trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Λάβετε το δέντρο σύνταξης. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Λάβετε τα Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Εισαγωγή πριν από τον κόμβο. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Αφαιρέστε το παιδί. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Αντικαταστήστε τον θυγατρικό κόμβο. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Παράκαμψη μεθόδου ToString. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Γράψτε στο MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Εγγραφή κόμβων στο πρόγραμμα εγγραφής κειμένου. |

### Δείτε επίσης

* class [HugoFrontMatterSyntaxNode](../hugofrontmattersyntaxnode/)
* class [ChildFrontMatterSyntaxNode](../childfrontmattersyntaxnode/)
* χώρος ονομάτων [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* συνέλευση [Aspose.HTML](../../)


