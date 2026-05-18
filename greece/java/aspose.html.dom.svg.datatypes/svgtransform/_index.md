---
title: "SVGTransform Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform κλάση. Το SVGTransform είναι η διεπαφή για μία από τις μετασχηματιστικές συνιστώσες μέσα σε μια SVGTransformList, έτσι ένα αντικείμενο SVGTransform αντιστοιχεί σε μία μοναδική συνιστώσα π.χ. κλίμακα ή μήτρα μέσα σε προδιαγραφή ιδιότητας μετασχηματισμού."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

Η SVGTransform είναι η διεπαφή για έναν από τους μετασχηματισμούς στοιχείου μέσα σε μια SVGTransformList· έτσι, ένα αντικείμενο SVGTransform αντιστοιχεί σε ένα μοναδικό στοιχείο (π.χ., 'scale(…)' ή 'matrix(…)') μέσα σε μια προδιαγραφή χαρακτηριστικού ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Ένα βολικό χαρακτηριστικό για SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY. Διατηρεί τη γωνία που είχε καθοριστεί. Για SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE και SVG_TRANSFORM_SCALE, η γωνία θα είναι μηδέν. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) Η μήτρα που αντιπροσωπεύει αυτή τη μετατροπή. Το αντικείμενο μήτρας είναι ενεργό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντανακλώνται αμέσως στο αντικείμενο μήτρας και αντίστροφα. Σε περίπτωση που το αντικείμενο μήτρας αλλάξει άμεσα (δηλαδή, χωρίς χρήση των μεθόδων στη διεπαφή SVGTransform), τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX, η μήτρα περιέχει τις τιμές a, b, c, d, e, f που παρείχε ο χρήστης. Για SVG_TRANSFORM_TRANSLATE, τα e και f αντιπροσωπεύουν τα ποσά μετάφρασης (a=1, b=0, c=0 και d=1). Για SVG_TRANSFORM_SCALE, τα a και d αντιπροσωπεύουν τα ποσά κλίμακας (b=0, c=0, e=0 και f=0). Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY, τα a, b, c και d αντιπροσωπεύουν τη μήτρα που θα προκύψει από την δεδομένη παραμόρφωση (e=0 και f=0). Για SVG_TRANSFORM_ROTATE, τα a, b, c, d, e και f μαζί αντιπροσωπεύουν τη μήτρα που θα προκύψει από την δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο (0,0), τα e και f θα είναι μηδέν. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Ο τύπος της τιμής όπως καθορίζεται από μία από τις σταθερές SVG_TRANSFORM_* που ορίζονται σε αυτή τη διεπαφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_MATRIX, με την παράμετρο matrix που ορίζει τον νέο μετασχηματισμό. Οι τιμές από την παράμετρο matrix αντιγράφονται, η παράμετρος matrix δεν αντικαθιστά το SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_ROTATE, με την παράμετρο angle που καθορίζει τη γωνία περιστροφής και τις παραμέτρους cx και cy που καθορίζουν το προαιρετικό κέντρο περιστροφής. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SCALE, με τις παραμέτρους sx και sy που καθορίζουν τα ποσά κλίμακας. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SKEWX, με την παράμετρο angle που καθορίζει το ποσό της παραμόρφωσης. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_SKEWY, με την παράμετρο angle που καθορίζει το ποσό της παραμόρφωσης. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Ορίζει τον τύπο μετασχηματισμού σε SVG_TRANSFORM_TRANSLATE, με τις παραμέτρους tx και ty που καθορίζουν τα ποσά μετάφρασης. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Μια μετατροπή 'matrix(…)' |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Μια μετατροπή 'rotate(…)' |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Ένας μετασχηματισμός 'scale(…)' |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Ένας μετασχηματισμός 'skewX(…)' |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Ένας μετασχηματισμός 'skewY(…)' |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Ένας μετασχηματισμός 'translate(…)' |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους. Είναι μη έγκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να αλλάξετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
