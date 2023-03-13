---
title: Class Path2D
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Canvas.Path2D τάξη. Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για τη δήλωση διαδρομών που στη συνέχεια χρησιμοποιούνται αργότερα σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D υπάρχουν και σε αυτήν τη διεπαφή και σας επιτρέπουν να δημιουργήσετε διαδρομές που μπορείτε να διατηρήσετε και να αναπαράγετε ξανά όπως απαιτείται σε έναν καμβά.
type: docs
weight: 290
url: /el/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Η διεπαφή Path2D του Canvas 2D API χρησιμοποιείται για τη δήλωση διαδρομών που στη συνέχεια χρησιμοποιούνται αργότερα σε αντικείμενα CanvasRenderingContext2D. Οι μέθοδοι διαδρομής της διεπαφής CanvasRenderingContext2D υπάρχουν και σε αυτήν τη διεπαφή και σας επιτρέπουν να δημιουργήσετε διαδρομές που μπορείτε να διατηρήσετε και να αναπαράγετε ξανά όπως απαιτείται σε έναν καμβά.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Path2D](path2d/#constructor)() | Το επιστρέφει ένα πρόσφατα εγκατεστημένο αντικείμενο Path2D |
| [Path2D](path2d/#constructor_1)(Path2D) | Το επιστρέφει ένα νέο αντικείμενο Path2D με μια άλλη διαδρομή ως όρισμα (δημιουργεί ένα αντίγραφο) |
| [Path2D](path2d/#constructor_2)(string) | Το επιστρέφει ένα νέο αντικείμενο Path2D με μια συμβολοσειρά που αποτελείται από δεδομένα διαδρομής SVG. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται από το όρισμα. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Προσθέτει στη διαδρομή τη διαδρομή που δίνεται από το όρισμα. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με ακτίνα r που ξεκινά από την startAngle και τελειώνει στο endAngle πηγαίνοντας προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με ακτίνα r που ξεκινά από την startAngle και τελειώνει στο endAngle πηγαίνοντας προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή με τα δεδομένα σημεία ελέγχου και ακτίνα, συνδεδεμένο με το προηγούμενο σημείο με ευθεία γραμμή. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στη διαδρομή. Απαιτεί τρεις βαθμούς. Τα δύο πρώτα σημεία είναι σημεία ελέγχου και το τρίτο είναι το τελικό σημείο. Το σημείο εκκίνησης είναι το τελευταίο σημείο στην τρέχουσα διαδρομή, το οποίο μπορεί να αλλάξει χρησιμοποιώντας το moveTo() πριν από τη δημιουργία της καμπύλης Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Αναγκάζει το σημείο της πένας να μετακινηθεί πίσω στην αρχή της τρέχουσας υποδιαδρομής. Προσπαθεί να χαράξει μια ευθεία γραμμή από το τρέχον σημείο μέχρι την αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η συνάρτηση δεν κάνει τίποτα. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Απορρίπτει αντικείμενο. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με την ακτίνα ακτίναςX και ακτίνα Y να ξεκινά από startAngle και να τελειώνει στο endAngle πηγαίνει προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με την ακτίνα ακτίναςX και ακτίνα Y να ξεκινά από startAngle και να τελειώνει στο endAngle πηγαίνει προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Συνδέει το τελευταίο σημείο της υποδιαδρομής με τις συντεταγμένες x, y με ευθεία γραμμή. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Μετακινεί το σημείο εκκίνησης μιας νέας υποδιαδρομής στις συντεταγμένες (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στην τρέχουσα διαδρομή. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Δημιουργεί μια διαδρομή για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* χώρος ονομάτων [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* συνέλευση [Aspose.HTML](../../)


