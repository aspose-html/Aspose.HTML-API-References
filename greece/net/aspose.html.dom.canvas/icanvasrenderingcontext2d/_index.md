---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D διεπαφή. Η διεπαφή ICanvasRenderingContext2D χρησιμοποιείται για τη σχεδίαση ορθογωνίων κειμένου εικόνων και άλλων αντικειμένων στο στοιχείο καμβά. Παρέχει το περιβάλλον απόδοσης 2D για την επιφάνεια σχεδίασης ενός στοιχείου καμβά.
type: docs
weight: 260
url: /el/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Η διεπαφή ICanvasRenderingContext2D χρησιμοποιείται για τη σχεδίαση ορθογωνίων, κειμένου, εικόνων και άλλων αντικειμένων στο στοιχείο καμβά. Παρέχει το περιβάλλον απόδοσης 2D για την επιφάνεια σχεδίασης ενός στοιχείου καμβά.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Μια αναδρομική αναφορά μόνο για ανάγνωση στο HTMLCanvasElement. Ενδέχεται να είναι μηδενικό εάν δεν σχετίζεται με στοιχείο καμβά. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Χρώμα ή στυλ για χρήση μέσα σε σχήματα. Προεπιλογή: (μαύρο). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Τιμή άλφα που εφαρμόζεται σε σχήματα και εικόνες πριν από τη σύνθεση τους στον καμβά. Προεπιλογή 1.0 (αδιαφανές). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Με την εφαρμογή globalAlpha, αυτό ορίζει τον τρόπο σχεδίασης των σχημάτων και των εικόνων στο υπάρχον bitmap. Προεπιλογή: (source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Λειτουργία εξομάλυνσης εικόνας. εάν είναι απενεργοποιημένη, οι εικόνες δεν θα εξομαλυνθούν εάν κλιμακωθούν. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Καθορίζει το εφέ θολώματος. Προεπιλογή 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Χρώμα της σκιάς. Προεπιλεγμένο πλήρως διαφανές μαύρο. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Οριζόντια απόσταση η σκιά θα μετατοπιστεί. Προεπιλογή 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Κατακόρυφη απόσταση η σκιά θα μετατοπιστεί. Προεπιλογή 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Χρώμα ή στυλ για χρήση για τις γραμμές γύρω από τα σχήματα. Προεπιλογή: (μαύρο). |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Προσθέτει μια περιοχή επιτυχίας στον καμβά. Αυτό σας επιτρέπει να κάνετε την ανίχνευση επισκέψεων ευκολότερη, σας επιτρέπει να δρομολογείτε συμβάντα σε στοιχεία DOM, και δίνει τη δυνατότητα στους χρήστες να εξερευνήσουν τον καμβά χωρίς να τον δουν. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Ξεκινά μια νέα διαδρομή αδειάζοντας τη λίστα με τις δευτερεύουσες διαδρομές. Καλέστε αυτήν τη μέθοδο όταν θέλετε να δημιουργήσετε μια νέα διαδρομή. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Αφαιρεί όλες τις περιοχές επιτυχίας από τον καμβά. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Ορίζει όλα τα εικονοστοιχεία στο ορθογώνιο που ορίζονται από το σημείο εκκίνησης (x, y) και το μέγεθος (πλάτος, ύψος) σε διαφανές μαύρο, διαγράφοντας οποιοδήποτε περιεχόμενο που σχεδιάστηκε προηγουμένως. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας την τομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από τη διαδρομή, χρησιμοποιώντας τον κανόνα του αριθμού περιέλιξης μη μηδενικού. . Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας την τομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από τη διαδρομή, χρησιμοποιώντας τον κανόνα αριθμών περιέλιξης μη μηδενικού. Οι ανοιχτές δευτερεύουσες διαδρομές πρέπει να είναι έμμεσα κλειστές κατά τον υπολογισμό της περιοχής αποκοπής, χωρίς να επηρεάζονται οι πραγματικές δευτερεύουσες διαδρομές. Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Δημιουργεί μια νέα περιοχή αποκοπής υπολογίζοντας την τομή της τρέχουσας περιοχής αποκοπής και της περιοχής που περιγράφεται από τη διαδρομή, χρησιμοποιώντας τον κανόνα αριθμών περιέλιξης μη μηδενικού. Οι ανοιχτές δευτερεύουσες διαδρομές πρέπει να είναι έμμεσα κλειστές κατά τον υπολογισμό της περιοχής αποκοπής, χωρίς να επηρεάζονται οι πραγματικές δευτερεύουσες διαδρομές. Η νέα περιοχή αποκοπής αντικαθιστά την τρέχουσα περιοχή αποκοπής. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Δημιουργεί ένα νέο, κενό αντικείμενο ImageData με τις καθορισμένες διαστάσεις. Όλα τα εικονοστοιχεία στο νέο αντικείμενο είναι διαφανή μαύρα. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Δημιουργεί ένα νέο, κενό αντικείμενο ImageData με τις καθορισμένες διαστάσεις. Όλα τα εικονοστοιχεία στο νέο αντικείμενο είναι διαφανή μαύρα. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Δημιουργεί μια γραμμική κλίση κατά μήκος της γραμμής που δίνεται από τις συντεταγμένες που αντιπροσωπεύονται από τις παραμέτρους. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Δημιουργεί ένα μοτίβο χρησιμοποιώντας την καθορισμένη εικόνα (ένα CanvasImageSource). Επαναλαμβάνει την πηγή προς τις κατευθύνσεις που καθορίζονται από το όρισμα επανάληψης. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Δημιουργεί ένα μοτίβο χρησιμοποιώντας την καθορισμένη εικόνα (ένα CanvasImageSource). Επαναλαμβάνει την πηγή προς τις κατευθύνσεις που καθορίζονται από το όρισμα επανάληψης. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Δημιουργεί μια ακτινική κλίση που δίνεται από τις συντεταγμένες των δύο κύκλων που αντιπροσωπεύονται από τις παραμέτρους. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Εάν ένα δεδομένο στοιχείο είναι εστιασμένο, αυτή η μέθοδος σχεδιάζει έναν δακτύλιο εστίασης γύρω από την τρέχουσα διαδρομή. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Σχεδιάζει την καθορισμένη εικόνα. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Γεμίζει τις δευτερεύουσες διαδρομές με το τρέχον στυλ πλήρωσης και τον προεπιλεγμένο αλγόριθμο CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Γεμίζει τις δευτερεύουσες διαδρομές με το τρέχον στυλ πλήρωσης. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Γεμίζει τις δευτερεύουσες διαδρομές με το τρέχον στυλ πλήρωσης και τον προεπιλεγμένο αλγόριθμο CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Γεμίζει τις δευτερεύουσες διαδρομές με το τρέχον στυλ πλήρωσης. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Σχεδιάζει ένα γεμάτο ορθογώνιο στη θέση (x, y) του οποίου το μέγεθος καθορίζεται από το πλάτος και το ύψος. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Σχεδιάζει (γεμίζει) ένα δεδομένο κείμενο στη δεδομένη θέση (x,y). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Σχεδιάζει (γεμίζει) ένα δεδομένο κείμενο στη δεδομένη θέση (x,y). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Επιστρέφει ένα αντικείμενο ImageData που αντιπροσωπεύει τα υποκείμενα δεδομένα pixel για την περιοχή του καμβά που συμβολίζεται με το ορθογώνιο που ξεκινά από (sx, sy) και έχει πλάτος sw και ύψος sh. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού καμβά. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Αναφέρει εάν το καθορισμένο σημείο περιέχεται ή όχι στην τρέχουσα διαδρομή. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Αναφέρει εάν το καθορισμένο σημείο βρίσκεται ή όχι εντός της περιοχής που περιέχεται από τη χάραξη μιας διαδρομής. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Αναφέρει εάν το καθορισμένο σημείο βρίσκεται ή όχι εντός της περιοχής που περιέχεται από τη χάραξη μιας διαδρομής. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Επιστρέφει ένα αντικείμενο TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Χρωματίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα βρώμικο ορθογώνιο, μόνο τα pixel από αυτό το ορθογώνιο είναι ζωγραφισμένα. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού καμβά. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Χρωματίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα βρώμικο ορθογώνιο, μόνο τα pixel από αυτό το ορθογώνιο είναι ζωγραφισμένα. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού καμβά. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Αφαιρεί την περιοχή επίσκεψης με το καθορισμένο αναγνωριστικό από τον καμβά. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Επαναφέρει τον τρέχοντα μετασχηματισμό από τον πίνακα ταυτότητας. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Επαναφέρει την κατάσταση του στυλ σχεδίασης στο τελευταίο στοιχείο στη «στοίβα κατάστασης» που αποθηκεύτηκε από το save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Προσθέτει μια περιστροφή στον πίνακα μετασχηματισμού. Το όρισμα γωνίας αντιπροσωπεύει μια γωνία περιστροφής δεξιόστροφα και εκφράζεται σε ακτίνια. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Αποθηκεύει την τρέχουσα κατάσταση του στυλ σχεδίασης χρησιμοποιώντας μια στοίβα, ώστε να μπορείτε να επαναφέρετε οποιαδήποτε αλλαγή κάνετε σε αυτήν χρησιμοποιώντας το restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Προσθέτει έναν μετασχηματισμό κλιμάκωσης στις μονάδες καμβά κατά x οριζόντια και κατά y κατακόρυφα. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Επαναφέρει τον τρέχοντα μετασχηματισμό στον πίνακα ταυτότητας και, στη συνέχεια, καλεί τη μέθοδο transform() με τα ίδια ορίσματα. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Περιγράφει τις δευτερεύουσες διαδρομές με το τρέχον στυλ διαδρομής. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Περιγράφει τις δευτερεύουσες διαδρομές με το τρέχον στυλ διαδρομής. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Ζωγραφίζει ένα ορθογώνιο που έχει σημείο εκκίνησης στο (x, y) και έχει πλάτος aw και ύψος h στον καμβά, χρησιμοποιώντας το τρέχον στυλ περιγράμματος. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Σχεδιάζει (χτυπά) ένα δεδομένο κείμενο στη δεδομένη θέση (x, y). |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Σχεδιάζει (χτυπά) ένα δεδομένο κείμενο στη δεδομένη θέση (x, y). |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Πολλαπλασιάζει τον τρέχοντα πίνακα μετασχηματισμού με τον πίνακα που περιγράφεται από τα ορίσματά του. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Προσθέτει έναν μετασχηματισμό μετάφρασης μετακινώντας τον καμβά και την αρχή του x οριζόντια και y κατακόρυφα στο πλέγμα. |

### Δείτε επίσης

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* χώρος ονομάτων [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* συνέλευση [Aspose.HTML](../../)


