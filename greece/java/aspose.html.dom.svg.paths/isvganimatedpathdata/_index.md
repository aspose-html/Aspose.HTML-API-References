---
title: "ISVGAnimatedPathData Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData διεπαφή. Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν χαρακτηριστικό d το οποίο περιέχει δεδομένα διαδρομής SVG και υποστηρίζει τη δυνατότητα κίνησης αυτού του χαρακτηριστικού."
type: docs

url: /el/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Η διεπαφή SVGAnimatedPathData υποστηρίζει στοιχεία που έχουν χαρακτηριστικό ‘d’ που περιέχει δεδομένα SVG διαδρομής και υποστηρίζει τη δυνατότητα κίνησης αυτού του χαρακτηριστικού.

```java
public interface ISVGAnimatedPathData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Παρέχει πρόσβαση στα τρέχοντα κινούμενα περιεχόμενα του χαρακτηριστικού ‘d’ σε μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Εάν το συγκεκριμένο χαρακτηριστικό ή ιδιότητα κινείται, περιέχει την τρέχουσα κινημένη τιμή του χαρακτηριστικού ή της ιδιότητας, και τόσο το αντικείμενο όσο και τα περιεχόμενά του είναι μόνο για ανάγνωση. Εάν το χαρακτηριστικό ή η ιδιότητα δεν κινείται αυτή τη στιγμή, περιέχει την ίδια τιμή με το pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Παρέχει πρόσβαση στα βασικά (δηλαδή στατικά) περιεχόμενα του χαρακτηριστικού ‘d’ σε μορφή που ταιριάζει ακριβώς με τη σύνταξη του SVG. Έτσι, εάν το χαρακτηριστικό ‘d’ έχει μια «απόλυτη μετακίνηση (M)» και μια «απόλυτη καμπύλη (A)» εντολή, τότε το pathSegList θα έχει δύο καταχωρήσεις: ένα SVG_PATHSEG_MOVETO_ABS και ένα SVG_PATHSEG_ARC_ABS. |

### Δείτε επίσης

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
