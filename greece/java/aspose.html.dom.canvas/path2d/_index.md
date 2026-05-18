---
title: "Path2D Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.canvas.Path2D κλάση. Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για να δηλώνει διαδρομές που στη συνέχεια χρησιμοποιούνται σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D είναι επίσης παρόντες σε αυτή τη διεπαφή και επιτρέπουν τη δημιουργία διαδρομών που μπορείτε να διατηρήσετε και να επαναλάβετε όπως απαιτείται σε έναν καμβά"
type: docs

url: /el/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για τη δήλωση διαδρομών που στη συνέχεια χρησιμοποιούνται σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D είναι επίσης παρούσες σε αυτή τη διεπαφή και σας επιτρέπουν να δημιουργείτε διαδρομές που μπορείτε να διατηρήσετε και να επαναλάβετε όπως απαιτείται σε έναν καμβά.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Path2D](path2d/#constructor)() | επιστρέφει ένα νεοδημιουργημένο αντικείμενο Path2D |
| [Path2D](path2d/#constructor_1)(Path2D) | επιστρέφει ένα νεοδημιουργημένο αντικείμενο Path2D με μια άλλη διαδρομή ως όρισμα (δημιουργεί ένα αντίγραφο) |
| [Path2D](path2d/#constructor_2)(String) | επιστρέφει ένα νεοδημιουργημένο αντικείμενο Path2D με μια συμβολοσειρά που αποτελείται από δεδομένα διαδρομής SVG. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται ως όρισμα. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται ως όρισμα. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή που κεντράρεται στη θέση (x, y) με ακτίνα r, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενο προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στη διαδρομή που κεντράρεται στη θέση (x, y) με ακτίνα r, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενο προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή με τα δεδομένα σημεία ελέγχου και ακτίνα, συνδεδεμένο με το προηγούμενο σημείο με ευθεία γραμμή. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στη διαδρομή. Απαιτεί τρία σημεία. Τα πρώτα δύο σημεία είναι σημεία ελέγχου και το τρίτο είναι το σημείο λήξης. Το σημείο εκκίνησης είναι το τελευταίο σημείο στην τρέχουσα διαδρομή, το οποίο μπορεί να αλλάξει χρησιμοποιώντας τη moveTo() πριν δημιουργηθεί η καμπύλη Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Αναγκάζει το σημείο του στυλό να επιστρέψει στην αρχή της τρέχουσας υποδιαδρομής. Προσπαθεί να σχεδιάσει μια ευθεία γραμμή από το τρέχον σημείο στην αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η λειτουργία δεν κάνει τίποτα. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Καταστρέφει το αντικείμενο. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στη διαδρομή που κεντράρεται στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενη προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στη διαδρομή που κεντράρεται στη θέση (x, y) με τις ακτίνες radiusX και radiusY, ξεκινώντας από την startAngle και λήγοντας στην endAngle, κινούμενη προς την καθορισμένη κατεύθυνση αντίστροφα από το ρολόι (προεπιλογή προς το ρολόι). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Συνδέει το τελευταίο σημείο στην υποδιαδρομή με τις συντεταγμένες x, y με μια ευθεία γραμμή. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Μετακινεί το σημείο εκκίνησης μιας νέας υποδιαδρομής στις συντεταγμένες (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στην τρέχουσα διαδρομή. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Δημιουργεί μια διαδρομή για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
