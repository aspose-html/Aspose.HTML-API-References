---
title: Class ImageDevice
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Rendering.Image.ImageDevice τάξη. Αντιπροσωπεύει απόδοση σε μορφές ράστερ jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /el/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Αντιπροσωπεύει απόδοση σε μορφές ράστερ: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice` τάξη. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice` τάξη. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice` τάξη. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice` τάξη με απόδοση επιλογών και πάροχο ροής. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice`τάξη με απόδοση επιλογών και ροή εξόδου. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Αρχικοποιεί μια νέα παρουσία του`ImageDevice` κλάση με απόδοση επιλογών και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Λαμβάνει την παρουσία του Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Ξεκινά η απόδοση του εγγράφου. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του στοιχείου. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Ξεκινά η απόδοση της νέας σελίδας. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής τέμνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον κανόνα FillMode για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο εκκίνησης της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμα κι αν το νέο τμήμα ξεκινά στο τελικό σημείο στο οποίο φτάνει η μέθοδος "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο στο σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου του Bézier. Το νέο τρέχον σημείο είναι pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Τερματίζει την απόδοση του εγγράφου. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Τερματίζει την απόδοση του στοιχείου. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Γεμίζει ολόκληρη την περιοχή που περικλείεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει το εσωτερικό όλων των υπομονοπατιών, το εξεταζόμενο μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Ξεπλύνει όλα τα δεδομένα για έξοδο ροής. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε τμήμα γραμμής σύνδεσης. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης "MoveTo", η νέα "MoveTo" την αντικαθιστά. κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" δεν παραμένει στη διαδρομή. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το περιβάλλον γραφικών στην προηγούμενη τιμή του βγάζοντάς το από τη στοίβα. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του περιβάλλοντος γραφικών στη στοίβα. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Διαγράφει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η διαγραμμισμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα της διαδρομής, με κέντρο το τμήμα με πλευρές παράλληλες προς αυτό. Κάθε ένα από τα υπομονοπάτια της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Περιγράφει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Χαρακτηρίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το`ImageDevice` . Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο εντός του οποίου εκτελούν οι τελεστές γραφικών. |

### Δείτε επίσης

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* χώρος ονομάτων [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* συνέλευση [Aspose.HTML](../../)


