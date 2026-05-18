---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICanvasRenderingContext2D-Methode. Malt Daten aus dem angegebenen ImageData-Objekt auf das Bitmap. Wenn ein dirty rectangle bereitgestellt wird, werden nur die Pixel aus diesem Rechteck gemalt. Diese Methode wird nicht von der canvas transformation matrix beeinflusst."
type: docs

url: /de/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Malt Daten aus dem angegebenen ImageData-Objekt auf die Bitmap. Wenn ein Dirty-Rectangle angegeben wird, werden nur die Pixel dieses Rechtecks gemalt. Diese Methode wird nicht von der Transformationsmatrix der Leinwand beeinflusst.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagedata | IImageData | Ein ImageData-Objekt, das das Array der Pixelwerte enthält. |
| dx | Double | Horizontale Position (x-Koordinate), an der die Bilddaten im Ziel-Canvas platziert werden. |
| dy | Double | Vertikale Position (y-Koordinate), an der die Bilddaten im Ziel-Canvas platziert werden. |

### Siehe auch

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Malt Daten aus dem angegebenen ImageData-Objekt auf die Bitmap. Wenn ein Dirty-Rectangle angegeben wird, werden nur die Pixel dieses Rechtecks gemalt. Diese Methode wird nicht von der Transformationsmatrix der Leinwand beeinflusst.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagedata | IImageData | Ein ImageData-Objekt, das das Array der Pixelwerte enthält. |
| dx | Double | Horizontale Position (x-Koordinate), an der die Bilddaten im Ziel-Canvas platziert werden. |
| dy | Double | Vertikale Position (y-Koordinate), an der die Bilddaten im Ziel-Canvas platziert werden. |
| dirtyX | Double | Horizontale Position (x-Koordinate). Die x-Koordinate der oberen linken Ecke Ihrer Image data. Standardwert 0. |
| dirtyY | Double | Vertikale Position (y-Koordinate). Die y-Koordinate der oberen linken Ecke Ihrer Image data. Standardwert 0. |
| dirtyWidth | Double | Breite des zu malenden Rechtecks. Standardwert ist die Breite der Bilddaten. |
| dirtyHeight | Double | Höhe des zu malenden Rechtecks. Standardwert ist die Höhe der Bilddaten. |

### Siehe auch

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
