---
title: "DocDevice Class"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.doc.DocDevice class. Αναπαριστά την απόδοση σε ένα έγγραφο DOCX"
type: docs

url: /el/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Αντιπροσωπεύει την απόδοση σε έγγραφο DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice` με ροή εξόδου. |
| [DocDevice](docdevice/#constructor_5)(String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice` με όνομα αρχείου εξόδου. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice` με επιλογές απόδοσης και πάροχο ροής. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice` με επιλογές απόδοσης και ροή εξόδου. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `DocDevice` με επιλογές απόδοσης και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Ξεκινά την απόδοση του εγγράφου. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του κόμβου html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Ξεκινά την απόδοση της νέας σελίδας. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής διασταυρώνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον κανόνα FillMode για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το \"ClosePath\" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός ακόμη τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο τερματισμού που επιτυγχάνεται από τη μέθοδο \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο μέχρι το σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι το pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Τελειώνει την απόδοση του κόμβου html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από το τρέχον μονοπάτι. Εάν το μονοπάτι αποτελείται από αρκετές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρούμενα μαζί. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Γεμίζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Αποστέλλει όλα τα δεδομένα στην έξοδο ροής. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο προς το σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής μονοπατιού στο τρέχον μονοπάτι ήταν επίσης "MoveTo", το νέο "MoveTo" το αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" στο μονοπάτι. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος του τρέχοντος μονοπατιού. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα στο μονοπάτι, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υποδιαδρομή του μονοπατιού αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Σχεδιάζει και γεμίζει το τρέχον μονοπάτι. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το DocDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών. |

### Δείτε επίσης

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
