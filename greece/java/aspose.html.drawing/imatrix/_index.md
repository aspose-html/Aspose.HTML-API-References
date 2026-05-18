---
title: "Διεπαφή IMatrix"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.drawing.IMatrix. Αντιπροσωπεύει έναν πίνακα που χρησιμοποιείται για μετασχηματισμούς"
type: docs

url: /el/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Αναπαριστά έναν πίνακα που χρησιμοποιείται για μετασχηματισμούς.

```java
public interface IMatrix
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο πίνακας είναι ο μοναδιαίος πίνακας. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο πίνακας είναι αντιστρέψιμος. |
[getM11]
[setM11] Gets or sets the value in the first row and first column of the matrix. |
[getM12]
[setM12] Gets or sets the value in the first row and second column of the matrix. |
[getM21]
[setM21] Gets or sets the value in the second row and first column of the matrix. |
[getM22]
[setM22] Gets or sets the value in the second row and second column of the matrix. |
[getM31]
[setM31] Gets or sets the value in the third row and first column of the matrix. |
[getM32]
[setM32] Gets or sets the value in the third row and second column of the matrix. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Δημιουργεί ένα αντίγραφο αυτού του πίνακα. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Λαμβάνει τα στοιχεία του πίνακα ως έναν πίνακα. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Αντιστρέφει αυτόν τον πίνακα. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Πολλαπλασιάζει αυτόν τον πίνακα με έναν άλλο πίνακα. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Πολλαπλασιάζει αυτόν τον πίνακα με έναν άλλο πίνακα με την καθορισμένη σειρά. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Επαναφέρει τον πίνακα στον μοναδιαίο πίνακα. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Περιστρέφει τον πίνακα κατά την καθορισμένη γωνία. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Περιστρέφει τον πίνακα κατά την καθορισμένη γωνία με την καθορισμένη σειρά. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Περιστρέφει τον πίνακα κατά την καθορισμένη γωνία γύρω από το καθορισμένο σημείο. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Περιστρέφει τον πίνακα κατά την καθορισμένη γωνία γύρω από το καθορισμένο σημείο με την καθορισμένη σειρά. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Κλιμακώνει τον πίνακα με τους καθορισμένους παράγοντες κλίμακας ομοιόμορφα. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Κλιμακώνει τον πίνακα με τους καθορισμένους παράγοντες κλίμακας με την καθορισμένη σειρά. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Εφαρμόζει μια παραμόρφωση κλίσης στον πίνακα. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Μετασχηματίζει το καθορισμένο σημείο χρησιμοποιώντας αυτόν τον πίνακα. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Μετασχηματίζει έναν πίνακα σημείων χρησιμοποιώντας αυτόν τον πίνακα. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Μετασχηματίζει το καθορισμένο ορθογώνιο χρησιμοποιώντας αυτόν τον πίνακα. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Μετατοπίζει τον πίνακα κατά τις καθορισμένες τιμές μετατόπισης. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Μετατοπίζει τον πίνακα κατά τις καθορισμένες τιμές μετατόπισης με την καθορισμένη σειρά. |

### Δείτε επίσης

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
