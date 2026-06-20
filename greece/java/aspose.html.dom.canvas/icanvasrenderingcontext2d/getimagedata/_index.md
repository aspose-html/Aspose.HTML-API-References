---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICanvasRenderingContext2D. Επιστρέφει ένα αντικείμενο ImageData που αντιπροσωπεύει τα υποκείμενα δεδομένα pixel για την περιοχή του καμβά που ορίζεται από το ορθογώνιο που ξεκινά στο sx sy και έχει πλάτος sw και ύψος sh. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά."
type: docs

url: /el/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

Επιστρέφει ένα αντικείμενο ImageData που αντιπροσωπεύει τα υποκείμενα δεδομένα εικονοστοιχείων για την περιοχή του καμβά που ορίζεται από το ορθογώνιο που ξεκινά στο (sx, sy) και έχει πλάτος sw και ύψος sh. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά.

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | Διπλό | Η συντεταγμένη x του άνω αριστερού γωνιακού σημείου του ορθογωνίου από το οποίο θα εξαχθεί το ImageData. |
| sy | Διπλό | Η συντεταγμένη y του άνω αριστερού γωνιακού σημείου του ορθογωνίου από το οποίο θα εξαχθεί το ImageData. |
| sw | Διπλό | Το πλάτος του ορθογωνίου από το οποίο θα εξαχθεί το ImageData. |
| sh | Διπλό | Το ύψος του ορθογωνίου από το οποίο θα εξαχθεί το ImageData. |

### Τιμή Επιστροφής

Ένα αντικείμενο ImageData που περιέχει τα δεδομένα εικόνας για το δοσμένο ορθογώνιο του καμβά.

### Δείτε επίσης

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
