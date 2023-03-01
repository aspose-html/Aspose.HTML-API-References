---
title: Class DocDevice
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Rendering.Doc.DocDevice τάξη. Αντιπροσωπεύει απόδοση σε έγγραφο DOCX.
type: docs
weight: 4170
url: /el/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Αντιπροσωπεύει απόδοση σε έγγραφο DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` τάξη. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` τάξη ανά ροή εξόδου. |
| [DocDevice](docdevice/#constructor_5)(string) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` κλάση ανά όνομα αρχείου εξόδου. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` τάξη με απόδοση επιλογών και πάροχο ροής. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` κλάση με απόδοση επιλογών και ροή εξόδου. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Αρχικοποιεί μια νέα παρουσία του`DocDevice` κλάση με απόδοση επιλογών και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Ξεκινά η απόδοση του εγγράφου. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του κόμβου html. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Ξεκινά η απόδοση της νέας σελίδας. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής τέμνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον κανόνα FillMode για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο εκκίνησης της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμα κι αν το νέο τμήμα ξεκινά στο τελικό σημείο στο οποίο φτάνει η μέθοδος "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο στο σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου του Bézier. Το νέο τρέχον σημείο είναι pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Τερματίζει την απόδοση του κόμβου html. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Γεμίζει ολόκληρη την περιοχή που περικλείεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει το εσωτερικό όλων των υπομονοπατιών, το εξεταζόμενο μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Ξεπλύνει όλα τα δεδομένα για έξοδο ροής. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε τμήμα γραμμής σύνδεσης. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης "MoveTo", η νέα "MoveTo" την αντικαθιστά. κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" δεν παραμένει στη διαδρομή. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το περιβάλλον γραφικών στην προηγούμενη τιμή του βγάζοντάς το από τη στοίβα. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του περιβάλλοντος γραφικών στη στοίβα. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Διαγράφει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η διαγραμμισμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα της διαδρομής, με κέντρο το τμήμα με πλευρές παράλληλες προς αυτό. Κάθε ένα από τα υπομονοπάτια της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Περιγράφει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Χαρακτηρίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το DocDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο εντός του οποίου εκτελούν οι τελεστές γραφικών. |

### Δείτε επίσης

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* χώρος ονομάτων [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* συνέλευση [Aspose.HTML](../../)


