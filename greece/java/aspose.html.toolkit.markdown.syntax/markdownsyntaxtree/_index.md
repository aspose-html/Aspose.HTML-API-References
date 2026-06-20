---
title: "MarkdownSyntaxTree Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree κλάση. Αναπαριστά το Δέντρο Σύνταξης Markdown"
type: docs

url: /el/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Αντιπροσωπεύει το Markdown Syntax Tree.

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | Δημιουργήθηκε το MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Δημιουργεί το MarkdownSyntaxTree |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Λάβετε το πρώτο παιδί. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Λάβετε το τελευταίο παιδί. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Λάβετε το επόμενο αδερφό. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Λάβετε τον γονικό κόμβο. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Λάβετε το προηγούμενο αδερφό. |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) Λάβετε το SyntaxFactory. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Ορίζει τη διεπαφή για επισκεπτόμενους κόμβους του δέντρου σύνταξης. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Προσθέστε το παιδικό κόμβο. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Λάβετε τη συλλογή των παιδικών κόμβων. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Ορίζει τη διεπαφή για δημιουργία του επαναλήπτη κόμβων. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Ορίζει τη διεπαφή για δημιουργία του επαναλήπτη κόμβων. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Ορίζει τη διεπαφή για δημιουργία του επαναλήπτη κόμβων. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Ορίζει τη διεπαφή για δημιουργία του περιηγητή δέντρου. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Ορίζει τη διεπαφή για δημιουργία του περιηγητή δέντρου. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Ορίζει τη διεπαφή για δημιουργία του περιηγητή δέντρου. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Λάβετε τα αρχικά trivia. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Λάβετε το δέντρο σύνταξης. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Λάβετε τα τελικά trivia. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Εισαγάγετε πριν από τον κόμβο. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Αφαιρέστε το παιδί. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Αντικαταστήστε τον παιδικό κόμβο. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Αποθηκεύει το δέντρο σύνταξης στο καθορισμένο ρεύμα. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | Αποθηκεύει το δέντρο σύνταξης στην καθορισμένη διαδρομή. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Αποθηκεύει το δέντρο σύνταξης στον καθορισμένο συγγραφέα. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Παρακάμψτε τη μέθοδο ToString. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Γράψτε στο MarkdownTextWriter. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Γράψτε κόμβους στο κειμενογράφο. |

### Δείτε επίσης

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
