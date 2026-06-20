---
title: "DeviceTGraphicContextTRenderingOptions Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions κλάση. Αντιπροσωπεύει τη βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης"
type: docs

url: /el/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Αναπαριστά τη βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TGraphicContext | Γραφικό πλαίσιο που διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών |
| TRenderingOptions | Επιλογές απόδοσης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Λαμβάνει το γραφικό πλαίσιο |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Λαμβάνει τις επιλογές απόδοσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Ξεκινά την απόδοση του εγγράφου. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Ξεκινά την απόδοση του κόμβου. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Ξεκινά την απόδοση της νέας σελίδας. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Τροποποιεί τη τρέχουσα διαδρομή αποκοπής διασταυρώνοντάς την με τη τρέχουσα διαδρομή, χρησιμοποιώντας το FillRule για τον καθορισμό της περιοχής προς γέμισμα. Αυτή η μέθοδος τερματίζει τη τρέχουσα διαδρομή. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός ακόμη τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο λήξης που επιτυγχάνεται από τη μέθοδο "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο μέχρι το σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι το pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Σχεδιάζει την καθορισμένη εικόνα. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Τελειώνει την απόδοση του εγγράφου. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Τελειώνει την απόδοση του κόμβου. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Τερματίζει την απόδοση της τρέχουσας σελίδας. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από αρκετές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρούμενα μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Γεμίζει το καθορισμένο κείμενο String στην καθορισμένη θέση. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Αδειάζει όλα τα δεδομένα στη ροή εξόδου. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Προσθέτει ένα ευθύ τμήμα γραμμής από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Ξεκινά μια νέα υποδιαδρομή μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στην τρέχουσα διαδρομή ήταν επίσης \"MoveTo\", το νέο \"MoveTo\" την αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας \"MoveTo\" στη διαδρομή. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το γραφικό πλαίσιο στην προηγούμενη τιμή του, αφαιρώντας το από τη στοίβα. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Σπρώχνει ένα αντίγραφο ολόκληρου του γραφικού πλαισίου στη στοίβα. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος της τρέχουσας διαδρομής. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπυλωτό τμήμα στη διαδρομή, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υποδιαδρομή της διαδρομής αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Σχεδιάζει και γεμίζει την τρέχουσα διαδρομή. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Σχεδιάζει το καθορισμένο κείμενο String στην καθορισμένη θέση. |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Καθορίζει τύπους στρατηγικών για τη γραφή σελίδων σε ροές εξόδου\streams. |

### Δείτε επίσης

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
