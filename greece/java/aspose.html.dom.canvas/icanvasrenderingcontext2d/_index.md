---
title: "ICanvasRenderingContext2D Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D διεπαφή. Η διεπαφή ICanvasRenderingContext2D χρησιμοποιείται για τη σχεδίαση ορθογωνίων, κειμένου, εικόνων και άλλων αντικειμένων στο στοιχείο canvas. Παρέχει το 2D περιβάλλον απόδοσης για την επιφάνεια σχεδίασης ενός στοιχείου canvas"
type: docs

url: /el/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Η διεπαφή ICanvasRenderingContext2D χρησιμοποιείται για τη σχεδίαση ορθογωνίων, κειμένου, εικόνων και άλλων αντικειμένων στο στοιχείο καμβά. Παρέχει το 2D πλαίσιο απόδοσης για την επιφάνεια σχεδίασης ενός στοιχείου καμβά.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Μία αναφορά μόνο για ανάγνωση στο HTMLCanvasElement. Μπορεί να είναι null εάν δεν είναι συσχετισμένο με στοιχείο canvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Ξεκινά ένα νέο μονοπάτι αδειάζοντας τη λίστα των υπο-μονοπατιών. Καλέστε αυτή τη μέθοδο όταν θέλετε να δημιουργήσετε ένα νέο μονοπάτι. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Αφαιρεί όλες τις περιοχές κρούσης από το canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Ορίζει όλα τα pixel στο ορθογώνιο που ορίζεται από το σημείο εκκίνησης (x, y) και το μέγεθος (πλάτος, ύψος) σε διαφανές μαύρο, διαγράφοντας οποιοδήποτε προηγούμενο περιεχόμενο. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας τη διατομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από το μονοπάτι, χρησιμοποιώντας τον κανόνα μη μηδενικού αριθμού περιδρόμου. Τα ανοιχτά υπο-μονοπάτια πρέπει να κλείνουν έμμεσα κατά τον υπολογισμό της περιοχής αποκοπής, χωρίς να επηρεάζουν τα πραγματικά υπο-μονοπάτια. Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας τη διατομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από το μονοπάτι, χρησιμοποιώντας τον κανόνα μη μηδενικού αριθμού περιδρόμου. Τα ανοιχτά υπο-μονοπάτια πρέπει να κλείνουν έμμεσα κατά τον υπολογισμό της περιοχής αποκοπής, χωρίς να επηρεάζουν τα πραγματικά υπο-μονοπάτια. Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας τη διατομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από το μονοπάτι, χρησιμοποιώντας τον κανόνα μη μηδενικού αριθμού περιδρόμου. Τα ανοιχτά υπο-μονοπάτια πρέπει να κλείνουν έμμεσα κατά τον υπολογισμό της περιοχής αποκοπής, χωρίς να επηρεάζουν τα πραγματικά υπο-μονοπάτια. Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Δημιουργεί ένα νέο, κενό αντικείμενο ImageData με τις καθορισμένες διαστάσεις. Όλα τα pixel στο νέο αντικείμενο είναι διαφανές μαύρο. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Δημιουργεί ένα νέο, κενό αντικείμενο ImageData με τις καθορισμένες διαστάσεις. Όλα τα pixel στο νέο αντικείμενο είναι διαφανές μαύρο. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Δημιουργεί μια γραμμική διαβάθμιση κατά μήκος της γραμμής που ορίζεται από τις συντεταγμένες που παρέχονται από τις παραμέτρους. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Δημιουργεί ένα μοτίβο χρησιμοποιώντας την καθορισμένη εικόνα (CanvasImageSource). Επαναλαμβάνει την πηγή στις κατευθύνσεις που ορίζονται από το όρισμα επανάληψης. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Δημιουργεί ένα μοτίβο χρησιμοποιώντας την καθορισμένη εικόνα (CanvasImageSource). Επαναλαμβάνει την πηγή στις κατευθύνσεις που ορίζονται από το όρισμα επανάληψης. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Δημιουργεί μια ακτινική διαβάθμιση που καθορίζεται από τις συντεταγμένες των δύο κύκλων που αντιπροσωπεύονται από τις παραμέτρους. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Εάν ένα δεδομένο στοιχείο είναι εστιασμένο, αυτή η μέθοδος σχεδιάζει ένα δακτύλιο εστίασης γύρω από την τρέχουσα διαδρομή. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Γεμίζει τα υποδιαδρομές με το τρέχον στυλ γεμίσματος και τον προεπιλεγμένο αλγόριθμο CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Γεμίζει τα υποδιαδρομές με το τρέχον στυλ γεμίσματος. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Γεμίζει τα υποδιαδρομές με το τρέχον στυλ γεμίσματος και τον προεπιλεγμένο αλγόριθμο CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Γεμίζει τα υποδιαδρομές με το τρέχον στυλ γεμίσματος. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Σχεδιάζει ένα γεμισμένο ορθογώνιο στη θέση (x, y) του οποίου το μέγεθος καθορίζεται από το πλάτος και το ύψος. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Σχεδιάζει (γεμίζει) ένα δεδομένο κείμενο στη δεδομένη θέση (x,y). |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Σχεδιάζει (γεμίζει) ένα δεδομένο κείμενο στη δεδομένη θέση (x,y). |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Επιστρέφει ένα αντικείμενο ImageData που αντιπροσωπεύει τα υποκείμενα δεδομένα εικονοστοιχείων για την περιοχή του καμβά που ορίζεται από το ορθογώνιο που ξεκινά στο (sx, sy) και έχει πλάτος sw και ύψος sh. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Αναφέρει εάν το καθορισμένο σημείο βρίσκεται ή όχι στην περιοχή που περιέχεται από το περίγραμμα μιας διαδρομής. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Αναφέρει εάν το καθορισμένο σημείο βρίσκεται ή όχι στην περιοχή που περιέχεται από το περίγραμμα μιας διαδρομής. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Επιστρέφει ένα αντικείμενο TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Ζωγραφίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα «βρώμικο» ορθογώνιο, μόνο τα εικονοστοιχεία από αυτό το ορθογώνιο ζωγραφίζονται. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Ζωγραφίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα «βρώμικο» ορθογώνιο, μόνο τα εικονοστοιχεία από αυτό το ορθογώνιο ζωγραφίζονται. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Αφαιρεί την περιοχή κλικ με το καθορισμένο αναγνωριστικό από τον καμβά. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Επαναφέρει τον τρέχοντα μετασχηματισμό με τον μοναδιαίο πίνακα. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Επαναφέρει την κατάσταση του στυλ σχεδίασης στο τελευταίο στοιχείο της "state stack" που αποθηκεύτηκε από τη save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Προσθέτει μια περιστροφή στον πίνακα μετασχηματισμού. Το όρισμα γωνίας αντιπροσωπεύει γωνία περιστροφής δεξιόστροφα και εκφράζεται σε ακτίνια. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Αποθηκεύει την τρέχουσα κατάσταση του στυλ σχεδίασης χρησιμοποιώντας μια στοίβα ώστε να μπορείτε να αναιρέσετε οποιαδήποτε αλλαγή κάνετε σε αυτήν με τη restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Προσθέτει μια κλιμακωτική μετατροπή στις μονάδες του καμβά κατά x οριζόντια και κατά y κάθετα. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Επαναφέρει τον τρέχοντα μετασχηματισμό στον μοναδιαίο πίνακα και, στη συνέχεια, καλεί τη μέθοδο transform() με τα ίδια ορίσματα. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Σχεδιάζει τα υποδιαδρομές με το τρέχον στυλ περιγράμματος. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Σχεδιάζει τα υποδιαδρομές με το τρέχον στυλ περιγράμματος. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Ζωγραφίζει ένα ορθογώνιο που έχει σημείο εκκίνησης στο (x, y) και έχει πλάτος w και ύψος h στον καμβά, χρησιμοποιώντας το τρέχον στυλ περιγράμματος. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Σχεδιάζει (περιγράφει) ένα δεδομένο κείμενο στη δεδομένη θέση (x, y). |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Σχεδιάζει (περιγράφει) ένα δεδομένο κείμενο στη δεδομένη θέση (x, y). |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Πολλαπλασιάζει τον τρέχοντα πίνακα μετασχηματισμού με τον πίνακα που περιγράφεται από τα ορίσματά του. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Προσθέτει μια μετάφραση μετασχηματισμού μετακινώντας τον καμβά και το αρχικό του σημείο x οριζόντια και y κάθετα στο πλέγμα. |

### Δείτε επίσης

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
