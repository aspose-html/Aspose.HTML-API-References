---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICanvasRenderingContext2D. Ζωγραφίζει δεδομένα από το δοσμένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα dirty rectangle, μόνο τα pixel από αυτό το rectangle ζωγραφίζονται. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά."
type: docs

url: /el/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Ζωγραφίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα «βρώμικο» ορθογώνιο, μόνο τα εικονοστοιχεία από αυτό το ορθογώνιο ζωγραφίζονται. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imagedata | IImageData | Ένα αντικείμενο ImageData που περιέχει τον πίνακα των τιμών pixel. |
| dx | Διπλό | Οριζόντια θέση (συντεταγμένη x) στην οποία θα τοποθετηθούν τα δεδομένα εικόνας στον προορισμό καμβά. |
| dy | Διπλό | Κατακόρυφη θέση (συντεταγμένη y) στην οποία θα τοποθετηθούν τα δεδομένα εικόνας στον προορισμό καμβά. |

### Δείτε επίσης

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Ζωγραφίζει δεδομένα από το δεδομένο αντικείμενο ImageData στο bitmap. Εάν παρέχεται ένα «βρώμικο» ορθογώνιο, μόνο τα εικονοστοιχεία από αυτό το ορθογώνιο ζωγραφίζονται. Αυτή η μέθοδος δεν επηρεάζεται από τον πίνακα μετασχηματισμού του καμβά.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imagedata | IImageData | Ένα αντικείμενο ImageData που περιέχει τον πίνακα των τιμών pixel. |
| dx | Διπλό | Οριζόντια θέση (συντεταγμένη x) στην οποία θα τοποθετηθούν τα δεδομένα εικόνας στον προορισμό καμβά. |
| dy | Διπλό | Κατακόρυφη θέση (συντεταγμένη y) στην οποία θα τοποθετηθούν τα δεδομένα εικόνας στον προορισμό καμβά. |
| dirtyX | Διπλό | Οριζόντια θέση (συντεταγμένη x). Η συντεταγμένη x της πάνω αριστερής γωνίας των δεδομένων Image σας. Προεπιλογή 0. |
| dirtyY | Διπλό | Κατακόρυφη θέση (συντεταγμένη y). Η συντεταγμένη y της πάνω αριστερής γωνίας των δεδομένων Image σας. Προεπιλογή 0. |
| dirtyWidth | Διπλό | Πλάτος του ορθογωνίου που θα ζωγραφιστεί. Προεπιλογή το πλάτος των δεδομένων εικόνας. |
| dirtyHeight | Διπλό | Ύψος του ορθογωνίου που θα ζωγραφιστεί. Προεπιλογή το ύψος των δεδομένων εικόνας. |

### Δείτε επίσης

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
