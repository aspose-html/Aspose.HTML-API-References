---
title: "ISVGAnimatedPathData Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData διεπαφή. Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν ένα χαρακτηριστικό d το οποίο περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα animation αυτού του χαρακτηριστικού."
type: docs

url: /el/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν ένα χαρακτηριστικό ‘d’ που περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα animation αυτού του χαρακτηριστικού.

```java
public interface ISVGAnimatedPathData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Παρέχει πρόσβαση στα τρέχοντα κινούμενα περιεχόμενα του χαρακτηριστικού ‘d’ σε μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Εάν το συγκεκριμένο χαρακτηριστικό ή ιδιότητα βρίσκεται σε κίνηση, περιέχει την τρέχουσα κινούμενη τιμή του χαρακτηριστικού ή της ιδιότητας, και τόσο το αντικείμενο όσο και τα περιεχόμενά του είναι μόνο για ανάγνωση. Εάν το συγκεκριμένο χαρακτηριστικό ή ιδιότητα δεν βρίσκεται αυτή τη στιγμή σε κίνηση, περιέχει την ίδια τιμή με το pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Παρέχει πρόσβαση στα βασικά (δηλαδή στατικά) περιεχόμενα του χαρακτηριστικού ‘d’ σε μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Έτσι, εάν το χαρακτηριστικό ‘d’ έχει μια «απόλυτη μετακίνηση (M)» και μια «απόλυτη arcto (A)» εντολή, τότε το pathSegList θα έχει δύο καταχωρήσεις: ένα SVG_PATHSEG_MOVETO_ABS και ένα SVG_PATHSEG_ARC_ABS. |

### Δείτε επίσης

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
