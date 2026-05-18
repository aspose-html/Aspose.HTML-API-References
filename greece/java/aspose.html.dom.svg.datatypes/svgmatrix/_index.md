---
title: "Κλάση SVGMatrix"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.svg.datatypes.SVGMatrix. Πολλές από τις γραφικές λειτουργίες των SVG χρησιμοποιούν πίνακες 2x3 της μορφής a c e b d f, οι οποίοι όταν επεκτείνονται σε πίνακα 3x3 για σκοπούς αριθμητικής πινάκων γίνονται a c e b d f 0 0 1"
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Πολλές από τις γραφικές λειτουργίες του SVG χρησιμοποιούν πίνακες 2x3 της μορφής: [a c e] [b d f] οι οποίοι, όταν επεκτείνονται σε πίνακα 3x3 για σκοπούς αριθμητικών πράξεων, γίνονται: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Το στοιχείο A του πίνακα. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Το στοιχείο B του πίνακα. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Το στοιχείο C του πίνακα. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Το στοιχείο D του πίνακα. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Το στοιχείο E του πίνακα. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Το στοιχείο F του πίνακα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Εκτελεί πολλαπλασιασμό πινάκων. Αυτός ο πίνακας πολλαπλασιάζεται μετά από έναν άλλο πίνακα, επιστρέφοντας τον νέο προκύπτοντα πίνακα. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Πολλαπλασιάζει μετά μια περιστροφική μετασχηματισμό στον τρέχοντα πίνακα και επιστρέφει τον προκύπτοντα πίνακα. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Πολλαπλασιάζει μετά μια ομοιόμορφη κλιμάκωση στον τρέχοντα πίνακα και επιστρέφει τον προκύπτοντα πίνακα. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Πολλαπλασιάζει μετά μια μη ομοιόμορφη κλιμάκωση στον τρέχοντα πίνακα και επιστρέφει τον προκύπτοντα πίνακα |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Πολλαπλασιάζει μετά έναν μετασχηματισμό skewX στον τρέχοντα πίνακα και επιστρέφει τον προκύπτον πίνακα. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Πολλαπλασιάζει μετά έναν μετασχηματισμό skewY στον τρέχοντα πίνακα και επιστρέφει τον προκύπτον πίνακα. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Πολλαπλασιάζει μετά έναν μετασχηματισμό μετάφρασης στον τρέχοντα πίνακα και επιστρέφει τον προκύπτον πίνακα. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
