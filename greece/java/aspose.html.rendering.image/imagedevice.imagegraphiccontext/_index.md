---
title: "ImageDevice.ImageGraphicContext Class"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.image.ImageDeviceImageGraphicContext class. Διατηρεί τρέχουσες παραμέτρους ελέγχου γραφικών για το ImageDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών."
type: docs

url: /el/java/com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Διατηρεί τρέχουσες παραμέτρους ελέγχου γραφικών για το [`ImageDevice`](../imagedevice/). Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών.

```java
public class ImageGraphicContext : GraphicContext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [imageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

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
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Ορίζει ή λαμβάνει τον πίνακα μετασχηματισμού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης GraphicContext με τις ίδιες τιμές ιδιοτήτων όπως ένα υπάρχον στιγμιότυπο. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Τροποποιεί τον τρέχοντα πίνακα μετασχηματισμού πολλαπλασιάζοντας τον καθορισμένο πίνακα. |

### Δείτε επίσης

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
