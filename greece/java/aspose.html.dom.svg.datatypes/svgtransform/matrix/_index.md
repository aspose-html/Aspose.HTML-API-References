---
title: "SVGTransform.Matrix"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα SVGTransform. Ο πίνακας που αντιπροσωπεύει αυτή τη μετατροπή. Το αντικείμενο πίνακα είναι ζωντανό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντικατοπτρίζονται αμέσως στο αντικείμενο πίνακα και αντίστροφα. Σε περίπτωση που το αντικείμενο πίνακα αλλάξει άμεσα, δηλαδή χωρίς τη χρήση των μεθόδων του interface SVGTransform, τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX, ο πίνακας περιέχει τις τιμές a, b, c, d, e, f που παρέχονται από τον χρήστη. Για SVG_TRANSFORM_TRANSLATE, τα e και f αντιπροσωπεύουν τα ποσά μετάφρασης (a=1, b=0, c=0 και d=1). Για SVG_TRANSFORM_SCALE, τα a και d αντιπροσωπεύουν τα ποσά κλίμακας (b=0, c=0, e=0 και f=0). Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY, τα a, b, c και d αντιπροσωπεύουν τον πίνακα που θα προκύψει από την δεδομένη παραμόρφωση (e=0 και f=0). Για SVG_TRANSFORM_ROTATE, τα a, b, c, d, e και f μαζί αντιπροσωπεύουν τον πίνακα που θα προκύψει από την δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο (0,0), τα e και f θα είναι μηδέν."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Ο πίνακας που αντιπροσωπεύει αυτή τη μετατροπή. Το αντικείμενο πίνακα είναι ζωντανό, πράγμα που σημαίνει ότι οποιεσδήποτε αλλαγές γίνουν στο αντικείμενο SVGTransform αντικατοπτρίζονται αμέσως στο αντικείμενο πίνακα και αντίστροφα. Σε περίπτωση που το αντικείμενο πίνακα αλλάξει άμεσα (δηλαδή χωρίς τη χρήση των μεθόδων του interface SVGTransform), τότε ο τύπος του SVGTransform αλλάζει σε SVG_TRANSFORM_MATRIX. Για SVG_TRANSFORM_MATRIX, ο πίνακας περιέχει τις τιμές a, b, c, d, e, f που παρέχονται από τον χρήστη. Για SVG_TRANSFORM_TRANSLATE, τα e και f αντιπροσωπεύουν τα ποσά μετάφρασης (a=1, b=0, c=0 και d=1). Για SVG_TRANSFORM_SCALE, τα a και d αντιπροσωπεύουν τα ποσά κλίμακας (b=0, c=0, e=0 και f=0). Για SVG_TRANSFORM_SKEWX και SVG_TRANSFORM_SKEWY, τα a, b, c και d αντιπροσωπεύουν τον πίνακα που θα προκύψει από την δεδομένη παραμόρφωση (e=0 και f=0). Για SVG_TRANSFORM_ROTATE, τα a, b, c, d, e και f μαζί αντιπροσωπεύουν τον πίνακα που θα προκύψει από την δεδομένη περιστροφή. Όταν η περιστροφή είναι γύρω από το κεντρικό σημείο (0, 0), τα e και f θα είναι μηδέν.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

Ο πίνακας που αντιπροσωπεύει αυτή τη μετατροπή.

### Δείτε επίσης

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
