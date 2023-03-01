---
title: Interface IDevice
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Rendering.IDevice διεπαφή. Καθορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των στοιχείων γραφικών όπως διαδρομές κείμενο και εικόνες.
type: docs
weight: 4280
url: /el/net/aspose.html.rendering/idevice/
---
## IDevice interface

Καθορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των στοιχείων γραφικών όπως διαδρομές, κείμενο και εικόνες.

```csharp
public interface IDevice : IDisposable
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Λαμβάνει το γραφικό πλαίσιο. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Λαμβάνει επιλογές απόδοσης. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Ξεκινά η απόδοση του εγγράφου. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του στοιχείου. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Ξεκινά η απόδοση της νέας σελίδας. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής τέμνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον κανόνα FillMode για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο εκκίνησης της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμα κι αν το νέο τμήμα ξεκινά στο τελικό σημείο στο οποίο φτάνει η μέθοδος "ClosePath". |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο μέχρι το σημείο pt3, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου του Bézier. Το νέο τρέχον σημείο είναι pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Τερματίζει την απόδοση του εγγράφου. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Τερματίζει την απόδοση του στοιχείου. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Γεμίζει ολόκληρη την περιοχή που περικλείεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει το εσωτερικό όλων των υπομονοπατιών, το εξεταζόμενο μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Ξεπλύνει όλα τα δεδομένα για έξοδο ροής. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε τμήμα γραμμής σύνδεσης. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης "MoveTo", η νέα "MoveTo" την αντικαθιστά. κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" δεν παραμένει στη διαδρομή. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το περιβάλλον γραφικών στην προηγούμενη τιμή του βγάζοντάς το από τη στοίβα. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του περιβάλλοντος γραφικών στη στοίβα. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Διαγράφει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η διαγραμμισμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα της διαδρομής, με κέντρο το τμήμα με πλευρές παράλληλες προς αυτό. Κάθε ένα από τα υπομονοπάτια της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Περιγράφει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Χαρακτηρίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Rendering](../../aspose.html.rendering/)
* συνέλευση [Aspose.HTML](../../)


