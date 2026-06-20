---
title: "Path2D Class"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.canvas.Path2D class. Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για τη δήλωση διαδρομών που στη συνέχεια χρησιμοποιούνται σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D είναι επίσης παρόντες σε αυτή τη διεπαφή και επιτρέπουν τη δημιουργία διαδρομών που μπορείτε να διατηρήσετε και να επαναλάβετε όπως απαιτείται σε έναν καμβά"
type: docs

url: /el/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για τη δήλωση διαδρομών που στη συνέχεια χρησιμοποιούνται σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D είναι επίσης παρούσες σε αυτή τη διεπαφή και επιτρέπουν τη δημιουργία διαδρομών που μπορείτε να διατηρήσετε και να επαναλάβετε όπως απαιτείται σε έναν καμβά.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Path2D](path2d/#constructor)() | επιστρέφει ένα νέο δημιουργημένο αντικείμενο Path2D |
| [Path2D](path2d/#constructor_1)(Path2D) | επιστρέφει ένα νέο δημιουργημένο αντικείμενο Path2D με μια άλλη διαδρομή ως όρισμα (δημιουργεί ένα αντίγραφο) |
| [Path2D](path2d/#constructor_2)(String) | επιστρέφει ένα νέο δημιουργημένο αντικείμενο Path2D με μια συμβολοσειρά που αποτελείται από δεδομένα διαδρομής SVG. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται ως όρισμα. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται ως όρισμα. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στο μονοπάτι που είναι κεντραρισμένο στη θέση (x, y) με ακτίνα r, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενο στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στο μονοπάτι που είναι κεντραρισμένο στη θέση (x, y) με ακτίνα r, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενο στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στο μονοπάτι με τα δεδομένα σημεία ελέγχου και την ακτίνα, συνδεδεμένο με το προηγούμενο σημείο μέσω μιας ευθείας γραμμής. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στο μονοπάτι. Απαιτεί τρία σημεία. Τα πρώτα δύο σημεία είναι σημεία ελέγχου και το τρίτο είναι το τελικό σημείο. Το αρχικό σημείο είναι το τελευταίο σημείο του τρέχοντος μονοπατιού, το οποίο μπορεί να αλλάξει χρησιμοποιώντας τη moveTo() πριν δημιουργηθεί η καμπύλη Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Κάνει το σημείο του στυλό να επιστρέψει στην αρχή του τρέχοντος υπο-μονοπατιού. Προσπαθεί να σχεδιάσει μια ευθεία γραμμή από το τρέχον σημείο προς την αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η λειτουργία δεν κάνει τίποτα. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Αποδεσμεύει το αντικείμενο. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στο μονοπάτι που είναι κεντραρισμένη στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενη στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στο μονοπάτι που είναι κεντραρισμένη στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από τη startAngle και τελειώνοντας στη endAngle, κινούμενη στην καθορισμένη κατεύθυνση αριστερόστροφα (προεπιλογή δεξιόστροφα). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Συνδέει το τελευταίο σημείο του υπο-μονοπατιού με τις συντεταγμένες x, y μέσω μιας ευθείας γραμμής. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Μετακινεί το αρχικό σημείο ενός νέου υπο-μονοπατιού στις συντεταγμένες (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στο τρέχον μονοπάτι. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Δημιουργεί ένα μονοπάτι για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
