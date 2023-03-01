---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions τάξη. Αντιπροσωπεύει την βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης.
type: docs
weight: 4140
url: /el/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Αντιπροσωπεύει την βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TGraphicContext | Γραφικό περιβάλλον που περιέχει τις τρέχουσες παραμέτρους ελέγχου γραφικών |
| TRenderingOptions | Επιλογές απόδοσης |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Λαμβάνει το γραφικό πλαίσιο |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Λαμβάνει επιλογές απόδοσης. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Ξεκινά η απόδοση του εγγράφου. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του κόμβου. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Ξεκινά η απόδοση της νέας σελίδας. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής τέμνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον κανόνα FillMode για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο εκκίνησης της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμα κι αν το νέο τμήμα ξεκινά στο τελικό σημείο στο οποίο φτάνει η μέθοδος "ClosePath". |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο στο σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου του Bézier. Το νέο τρέχον σημείο είναι pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Εκτελεί εργασίες που καθορίζονται από την εφαρμογή που σχετίζονται με την απελευθέρωση, την απελευθέρωση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Τερματίζει την απόδοση του εγγράφου. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Τερματίζει την απόδοση του κόμβου. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Γεμίζει ολόκληρη την περιοχή που περικλείεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει το εσωτερικό όλων των υπομονοπατιών, το εξεταζόμενο μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Ξεπλύνει όλα τα δεδομένα για έξοδο ροής. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε τμήμα γραμμής σύνδεσης. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης "MoveTo", η νέα "MoveTo" την αντικαθιστά. κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" δεν παραμένει στη διαδρομή. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το περιβάλλον γραφικών στην προηγούμενη τιμή του βγάζοντάς το από τη στοίβα. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του περιβάλλοντος γραφικών στη στοίβα. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Διαγράφει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η διαγραμμισμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα της διαδρομής, με κέντρο το τμήμα με πλευρές παράλληλες προς αυτό. Κάθε ένα από τα υπομονοπάτια της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Περιγράφει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Χαρακτηρίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Αντιπροσωπεύει το αντικείμενο διαμόρφωσης για συσκευές. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Καθορίζει τύπους στρατηγικών για την εγγραφή σελίδων σε ροή/ροές εξόδου. |

### Δείτε επίσης

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* χώρος ονομάτων [Aspose.Html.Rendering](../../aspose.html.rendering/)
* συνέλευση [Aspose.HTML](../../)


