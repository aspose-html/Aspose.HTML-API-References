---
title: "Διεπαφή IDevice"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.rendering.IDevice. Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των γραφικών στοιχείων όπως διαδρομές, κείμενο και εικόνες."
type: docs

url: /el/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των γραφικών στοιχείων όπως διαδρομές, κείμενο και εικόνες.

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
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Τροποποιεί τη τρέχουσα διαδρομή αποκοπής διασταυρώνοντάς την με τη τρέχουσα διαδρομή, χρησιμοποιώντας το FillRule για τον καθορισμό της περιοχής προς γέμισμα. Αυτή η μέθοδος τερματίζει τη τρέχουσα διαδρομή. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός ακόμη τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο λήξης που επιτυγχάνεται από τη μέθοδο "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στη τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο έως το σημείο pt3, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι το pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Τελειώνει την απόδοση του εγγράφου. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Τελειώνει την απόδοση του στοιχείου. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από αρκετές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρούμενα μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Γεμίζει το καθορισμένο κείμενο String στην καθορισμένη θέση. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Αδειάζει όλα τα δεδομένα στη ροή εξόδου. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Προσθέτει ένα ευθύ τμήμα γραμμής από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης \"MoveTo\", το νέο \"MoveTo\" την αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας \"MoveTo\" στη διαδρομή. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το γραφικό πλαίσιο στην προηγούμενη τιμή του, αφαιρώντας το από τη στοίβα. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του γραφικού πλαισίου στη στοίβα. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπυλωτό τμήμα στη διαδρομή, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υποδιαδρομή της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Σχεδιάζει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Σχεδιάζει το καθορισμένο κείμενο String στην καθορισμένη θέση. |

### Δείτε επίσης

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
