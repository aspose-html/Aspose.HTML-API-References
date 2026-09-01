---
title: "DocDevice.DocGraphicContext Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.doc.DocDeviceDocGraphicContext κλάση. Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το DocDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι λειτουργίες γραφικών"
type: docs

url: /el/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το DocDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι λειτουργίες γραφικών.

```java
public class DocGraphicContext : GraphicContext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Ορίζει ή λαμβάνει το διάστημα χαρακτήρων. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο πινέλου που χρησιμοποιείται για τη γέμιση των εσωτερικών περιοχών των διαδρομών. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο γραμματοσειράς TrueType που χρησιμοποιείται για την απόδοση κειμένου. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Ορίζει ή λαμβάνει το μέγεθος γραμματοσειράς κειμένου. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Ορίζει ή λαμβάνει το στυλ γραμματοσειράς κειμένου. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Ορίζει ή λαμβάνει τον κώδικα που καθορίζει το σχήμα των άκρων για οποιαδήποτε ανοικτή διαδρομή που έχει σχεδιαστεί. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Ορίζει ή λαμβάνει τη φάση μετατόπισης του τρέχοντος μοτίβου παύλας γραμμής. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Ορίζει ή λαμβάνει την περιγραφή του μοτίβου παύλας που θα χρησιμοποιηθεί όταν σχεδιάζονται διαδρομές. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Ορίζει ή λαμβάνει τον κώδικα που καθορίζει το σχήμα των ενώσεων μεταξύ συνδεδεμένων τμημάτων μιας σχεδιασμένης διαδρομής. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Ορίζει ή λαμβάνει το πάχος των διαδρομών που θα σχεδιαστούν. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Ορίζει ή λαμβάνει το μέγιστο μήκος των γωνιακών ενώσεων γραμμών για σχεδιασμένες διαδρομές. Αυτή η παράμετρος περιορίζει το μήκος των \"ακίδων\" που παράγονται όταν τμήματα γραμμής ενώνονται σε οξυγώνιες γωνίες. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο πινέλου που χρησιμοποιείται για σχεδιασμένες διαδρομές. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Λαμβάνει ένα αντικείμενο [`TextInfo`](../../com.aspose.html.rendering/textinfo/) το οποίο περιέχει πληροφορίες σχετικά με το αποδοθέν κείμενο. |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | Ορίζει ή λαμβάνει τον πίνακα μετασχηματισμού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | Δημιουργεί ένα νέο αντικείμενο μιας κλάσης [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) με τις ίδιες τιμές ιδιοτήτων όπως ένα υπάρχον αντικείμενο. |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | Τροποποιεί τον τρέχοντα πίνακα μετασχηματισμού πολλαπλασιάζοντας τον καθορισμένο πίνακα. |

### Δείτε επίσης

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
