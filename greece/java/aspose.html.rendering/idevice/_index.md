---
title: "Διεπαφή IDevice"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.IDevice διεπαφή. Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των γραφικών στοιχείων όπως διαδρομές, κείμενο και εικόνες"
type: docs

url: /el/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν την προσαρμοσμένη απόδοση των γραφικών στοιχείων όπως μονοπάτια, κείμενο και εικόνες.

```java
public interface IDevice : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Λαμβάνει το γραφικό πλαίσιο. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Λαμβάνει τις επιλογές απόδοσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Ξεκινά την απόδοση του εγγράφου. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του στοιχείου. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Ξεκινά την απόδοση της νέας σελίδας. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Τροποποιεί το τρέχον μονοπάτι αποκοπής διασταυρώνοντάς το με το τρέχον μονοπάτι, χρησιμοποιώντας το FillRule για να καθορίσει την περιοχή προς γέμισμα. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το \"ClosePath\" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός ακόμη τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο τερματισμού που επιτυγχάνεται από τη μέθοδο \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στο τρέχον μονοπάτι. Η καμπύλη εκτείνεται από το τρέχον σημείο στο σημείο pt3, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι το pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Τελειώνει την απόδοση του εγγράφου. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Τελειώνει την απόδοση του στοιχείου. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από το τρέχον μονοπάτι. Εάν το μονοπάτι αποτελείται από αρκετές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρούμενα μαζί. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Γεμίζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Αποστέλλει όλα τα δεδομένα στην έξοδο ροής. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Προσθέτει ένα ευθύγραμμο τμήμα από το τρέχον σημείο προς το σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής μονοπατιού στο τρέχον μονοπάτι ήταν επίσης "MoveTo", το νέο "MoveTo" το αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" στο μονοπάτι. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το γραφικό πλαίσιο στην προηγούμενη τιμή του, αφαιρώντας το από τη στοίβα. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Τοποθετεί ένα αντίγραφο ολόκληρου του γραφικού πλαισίου στη στοίβα. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος του τρέχοντος μονοπατιού. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπύλο τμήμα στο μονοπάτι, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υποδιαδρομή του μονοπατιού αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Σχεδιάζει και γεμίζει το τρέχον μονοπάτι. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

### Δείτε επίσης

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
