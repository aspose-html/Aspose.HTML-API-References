---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods διεπαφή. Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τον χειρισμό μονοπατιών αντικειμένων.
type: docs
weight: 240
url: /el/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Η διεπαφή ICanvasPathMethods χρησιμοποιείται για τον χειρισμό μονοπατιών αντικειμένων.

```csharp
public interface ICanvasPathMethods
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με ακτίνα r που ξεκινά από την startAngle και τελειώνει στο endAngle πηγαίνοντας προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Προσθέτει ένα τόξο στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με ακτίνα r που ξεκινά από την startAngle και τελειώνει στο endAngle πηγαίνοντας προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Προσθέτει ένα τόξο στη διαδρομή με τα δεδομένα σημεία ελέγχου και ακτίνα, συνδεδεμένο με το προηγούμενο σημείο με ευθεία γραμμή. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Προσθέτει μια κυβική καμπύλη Bézier στη διαδρομή. Απαιτεί τρεις βαθμούς. Τα δύο πρώτα σημεία είναι σημεία ελέγχου και το τρίτο είναι το τελικό σημείο. Το σημείο εκκίνησης είναι το τελευταίο σημείο στην τρέχουσα διαδρομή, το οποίο μπορεί να αλλάξει χρησιμοποιώντας το moveTo() πριν από τη δημιουργία της καμπύλης Bézier. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Αναγκάζει το σημείο της πένας να μετακινηθεί πίσω στην αρχή της τρέχουσας υποδιαδρομής. Προσπαθεί να χαράξει μια ευθεία γραμμή από το τρέχον σημείο μέχρι την αρχή. Εάν το σχήμα έχει ήδη κλείσει ή έχει μόνο ένα σημείο, αυτή η συνάρτηση δεν κάνει τίποτα. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Προσθέτει μια έλλειψη στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με την ακτίνα ακτίναςX και ακτίνα Y να ξεκινά από startAngle και να τελειώνει στο endAngle πηγαίνει προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Προσθέτει μια έλλειψη στη διαδρομή που είναι κεντραρισμένη στη θέση (x, y) με την ακτίνα ακτίναςX και ακτίνα Y να ξεκινά από startAngle και να τελειώνει στο endAngle πηγαίνει προς τη δεδομένη κατεύθυνση αριστερόστροφα (από προεπιλογή προς τη φορά των δεικτών του ρολογιού). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Συνδέει το τελευταίο σημείο της υποδιαδρομής με τις συντεταγμένες x, y με ευθεία γραμμή. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Μετακινεί το σημείο εκκίνησης μιας νέας υποδιαδρομής στις συντεταγμένες (x, y). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Προσθέτει μια τετραγωνική καμπύλη Bézier στην τρέχουσα διαδρομή. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Δημιουργεί μια διαδρομή για ένα ορθογώνιο στη θέση (x, y) με μέγεθος που καθορίζεται από το πλάτος και το ύψος. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* συνέλευση [Aspose.HTML](../../)


