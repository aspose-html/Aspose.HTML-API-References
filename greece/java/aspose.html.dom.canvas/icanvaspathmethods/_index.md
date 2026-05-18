---
title: "ICanvasPathMethods Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τη διαχείριση των διαδρομών των αντικειμένων."
type: docs

url: /el/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τη διαχείριση των διαδρομών των αντικειμένων.

```java
public interface ICanvasPathMethods
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή που κεντράρεται στη θέση (x, y) με ακτίνα r, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενο προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στη διαδρομή που κεντράρεται στη θέση (x, y) με ακτίνα r, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενο προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή με τα δεδομένα σημεία ελέγχου και ακτίνα, συνδεδεμένο με το προηγούμενο σημείο με ευθεία γραμμή. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στη διαδρομή. Απαιτεί τρία σημεία. Τα πρώτα δύο σημεία είναι σημεία ελέγχου και το τρίτο είναι το σημείο λήξης. Το σημείο εκκίνησης είναι το τελευταίο σημείο στην τρέχουσα διαδρομή, το οποίο μπορεί να αλλάξει χρησιμοποιώντας τη moveTo() πριν δημιουργηθεί η καμπύλη Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Αναγκάζει το σημείο του στυλό να επιστρέψει στην αρχή της τρέχουσας υποδιαδρομής. Προσπαθεί να σχεδιάσει μια ευθεία γραμμή από το τρέχον σημείο στην αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η λειτουργία δεν κάνει τίποτα. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στη διαδρομή που κεντράρεται στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενη προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στη διαδρομή που κεντράρεται στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενη προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Συνδέει το τελευταίο σημείο στην υποδιαδρομή με τις συντεταγμένες x, y με μια ευθεία γραμμή. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Μετακινεί το σημείο εκκίνησης μιας νέας υποδιαδρομής στις συντεταγμένες (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στην τρέχουσα διαδρομή. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Δημιουργεί μια διαδρομή για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
