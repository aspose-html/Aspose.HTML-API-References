---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo ICanvasRenderingContext2D. Dipinge i dati dall'oggetto ImageData fornito sul bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione del canvas."
type: docs

url: /it/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Dipinge i dati dall'oggetto ImageData fornito sul bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della canvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imagedata | IImageData | Un oggetto ImageData contenente l'array dei valori dei pixel. |
| dx | Double | Posizione orizzontale (coordinata x) in cui posizionare i dati dell'immagine nella canvas di destinazione. |
| dy | Double | Posizione verticale (coordinata y) in cui posizionare i dati dell'immagine nella canvas di destinazione. |

### Vedi anche

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Dipinge i dati dall'oggetto ImageData fornito sul bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della canvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imagedata | IImageData | Un oggetto ImageData contenente l'array dei valori dei pixel. |
| dx | Double | Posizione orizzontale (coordinata x) in cui posizionare i dati dell'immagine nella canvas di destinazione. |
| dy | Double | Posizione verticale (coordinata y) in cui posizionare i dati dell'immagine nella canvas di destinazione. |
| dirtyX | Double | Posizione orizzontale (coordinata x). La coordinata x dell'angolo superiore sinistro dei tuoi dati immagine. Predefinito 0. |
| dirtyY | Double | Posizione verticale (coordinata y). La coordinata y dell'angolo superiore sinistro dei tuoi dati immagine. Predefinito 0. |
| dirtyWidth | Double | Larghezza del rettangolo da dipingere. Predefinito alla larghezza dei dati immagine. |
| dirtyHeight | Double | Altezza del rettangolo da dipingere. Predefinito all'altezza dei dati immagine. |

### Vedi anche

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
