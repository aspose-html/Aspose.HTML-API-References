---
title: "Κλάση XpsDevice.XpsGraphicContext"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.xps.XpsDeviceXpsGraphicContext κλάση. Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το XpsDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών."
type: docs

url: /el/java/com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το XpsDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών.

```java
public class XpsGraphicContext : GraphicContext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [xpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Ορίζει ή διαβάζει το διάστημα χαρακτήρων. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Ορίζει ή διαβάζει το αντικείμενο πινέλου που χρησιμοποιείται για τη γέμιση των εσωτερικών περιοχών των διαδρομών. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Ορίζει ή διαβάζει το αντικείμενο γραμματοσειράς TrueType που χρησιμοποιείται για την απόδοση κειμένου. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Ορίζει ή διαβάζει το μέγεθος γραμματοσειράς κειμένου. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Ορίζει ή διαβάζει το στυλ γραμματοσειράς κειμένου. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Ορίζει ή διαβάζει τον κώδικα που καθορίζει το σχήμα των άκρων για οποιαδήποτε ανοιχτή διαδρομή που έχει σχεδιαστεί. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Ορίζει ή διαβάζει τη φάση μετατόπισης του τρέχοντος μοτίβου παύλας γραμμής. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Ορίζει ή διαβάζει την περιγραφή του μοτίβου παύλας που θα χρησιμοποιηθεί όταν σχεδιάζονται διαδρομές. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Ορίζει ή διαβάζει τον κώδικα που καθορίζει το σχήμα των ενώσεων μεταξύ συνδεδεμένων τμημάτων μιας σχεδιασμένης διαδρομής. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Ορίζει ή διαβάζει το πάχος των διαδρομών που θα σχεδιαστούν. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Ορίζει ή διαβάζει το μέγιστο μήκος των κοπής γραμμών για τις ενώσεις των σχεδιασμένων διαδρομών. Αυτή η παράμετρος περιορίζει το μήκος των «ακίδων» που δημιουργούνται όταν τμήματα γραμμής ενώνονται σε οξές γωνίες. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Ορίζει ή διαβάζει το αντικείμενο πινέλου που χρησιμοποιείται για τις σχεδιασμένες διαδρομές. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Λαμβάνει ένα αντικείμενο [`TextInfo`](../../com.aspose.html.rendering/textinfo/) που περιέχει πληροφορίες σχετικά με το αποδοθέν κείμενο. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Ορίζει ή διαβάζει τον πίνακα μετασχηματισμού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Δημιουργεί ένα νέο αντικείμενο της κλάσης GraphicContext με τις ίδιες τιμές ιδιοτήτων όπως ένα υπάρχον αντικείμενο. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Τροποποιεί τον τρέχοντα πίνακα μετασχηματισμού πολλαπλασιάζοντας με τον καθορισμένο πίνακα. |

### Δείτε επίσης

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
