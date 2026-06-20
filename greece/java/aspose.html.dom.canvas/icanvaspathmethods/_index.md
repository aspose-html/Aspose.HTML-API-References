---
title: "ICanvasPathMethods Interface"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τη διαχείριση των μονοπατιών των αντικειμένων."
type: docs

url: /el/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τη διαχείριση διαδρομών αντικειμένων.

```java
public interface ICanvasPathMethods
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στο μονοπάτι που είναι κεντραρισμένο στη θέση (x, y) με ακτίνα r, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενο στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στο μονοπάτι που είναι κεντραρισμένο στη θέση (x, y) με ακτίνα r, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενο στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στο μονοπάτι με τα δεδομένα σημεία ελέγχου και την ακτίνα, συνδεδεμένο με το προηγούμενο σημείο μέσω μιας ευθείας γραμμής. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στο μονοπάτι. Απαιτεί τρία σημεία. Τα πρώτα δύο σημεία είναι σημεία ελέγχου και το τρίτο είναι το τελικό σημείο. Το αρχικό σημείο είναι το τελευταίο σημείο του τρέχοντος μονοπατιού, το οποίο μπορεί να αλλάξει χρησιμοποιώντας τη moveTo() πριν δημιουργηθεί η καμπύλη Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Κάνει το σημείο του στυλό να επιστρέψει στην αρχή του τρέχοντος υπο-μονοπατιού. Προσπαθεί να σχεδιάσει μια ευθεία γραμμή από το τρέχον σημείο προς την αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η λειτουργία δεν κάνει τίποτα. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στο μονοπάτι που είναι κεντραρισμένη στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενη στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στο μονοπάτι που είναι κεντραρισμένη στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενη στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Συνδέει το τελευταίο σημείο του υπο-μονοπατιού με τις συντεταγμένες x, y μέσω μιας ευθείας γραμμής. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Μετακινεί το αρχικό σημείο ενός νέου υπο-μονοπατιού στις συντεταγμένες (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στο τρέχον μονοπάτι. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Δημιουργεί ένα μονοπάτι για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
