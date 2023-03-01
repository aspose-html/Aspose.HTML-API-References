---
title: Class PdfDevice.PdfGraphicContext
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Rendering.Pdf.PdfDevicePdfGraphicContext τάξη. Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το PdfDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο εντός του οποίου εκτελούν οι τελεστές γραφικών.
type: docs
weight: 4450
url: /el/net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το PdfDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο εντός του οποίου εκτελούν οι τελεστές γραφικών.

```csharp
public class PdfGraphicContext : GraphicContext
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Ορίζει ή παίρνει διάστιχο χαρακτήρων. |
| override [FillBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/fillbrush/) { get; set; } | Ορίζει ή παίρνει το αντικείμενο πινέλου που χρησιμοποιείται για να γεμίσει το εσωτερικό των μονοπατιών. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο γραμματοσειράς αληθινού τύπου που χρησιμοποιείται για την απόδοση κειμένου. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Ορίζει ή λαμβάνει μέγεθος γραμματοσειράς κειμένου. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Ορίζει ή λαμβάνει στυλ γραμματοσειράς κειμένου. |
| override [LineCap](../../aspose.html.rendering.pdf/pdfgraphiccontext/linecap/) { get; set; } | Ορίζει ή λαμβάνει τον κώδικα που καθορίζει το σχήμα των τελικών σημείων για κάθε ανοιχτή διαδρομή που έχει διαγραμμιστεί. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Ορίζει ή λαμβάνει τη μετατόπιση φάσης του τρέχοντος μοτίβου παύλας γραμμής. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Ορίζει ή λαμβάνει την περιγραφή του μοτίβου της παύλας που θα χρησιμοποιηθεί όταν τα μονοπάτια χαράσσονται. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Τα σύνολα παίρνουν το στυλ των διακεκομμένων γραμμών μιας διαγραμμισμένης διαδρομής. |
| override [LineJoin](../../aspose.html.rendering.pdf/pdfgraphiccontext/linejoin/) { get; set; } | Ορίζει ή λαμβάνει τον κωδικό που καθορίζει το σχήμα των αρμών μεταξύ συνδεδεμένων τμημάτων μιας διαδρομής με διαδρομή. |
| override [LineWidth](../../aspose.html.rendering.pdf/pdfgraphiccontext/linewidth/) { get; set; } | Ορίζει ή λαμβάνει το πάχος των μονοπατιών που πρέπει να περάσουν. |
| override [MiterLimit](../../aspose.html.rendering.pdf/pdfgraphiccontext/miterlimit/) { get; set; } | Ορίζει ή λαμβάνει το μέγιστο μήκος των ενώσεων με λοξόγραμμη γραμμή για διαγραμμένες διαδρομές. Αυτή η παράμετρος περιορίζει το μήκος των "ακίδων" που παράγονται όταν τα τμήματα γραμμής ενώνονται υπό έντονες γωνίες. |
| override [StrokeBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/strokebrush/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο πινέλου που χρησιμοποιείται για διαγραμμισμένες διαδρομές. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Παίρνει ένα[`TextInfo`](../../aspose.html.rendering/textinfo/) αντικείμενο που περιέχει πληροφορίες σχετικά με το κείμενο που αποδίδεται. |
| override [TransformationMatrix](../../aspose.html.rendering.pdf/pdfgraphiccontext/transformationmatrix/) { get; set; } | Ορίζει ή παίρνει τον πίνακα μετασχηματισμού. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Clone](../../aspose.html.rendering.pdf/pdfgraphiccontext/clone/)() | Δημιουργεί μια νέα παρουσία μιας κλάσης με τις ίδιες τιμές ιδιοτήτων με μια υπάρχουσα παρουσία. |
| override [Transform](../../aspose.html.rendering.pdf/pdfgraphiccontext/transform/)(Matrix) | Τροποποιήστε τον τρέχοντα πίνακα μετασχηματισμού πολλαπλασιάζοντας τον καθορισμένο πίνακα. |

### Δείτε επίσης

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* χώρος ονομάτων [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* συνέλευση [Aspose.HTML](../../)


