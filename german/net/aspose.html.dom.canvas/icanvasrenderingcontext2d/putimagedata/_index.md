---
title: ICanvasRenderingContext2D.PutImageData
second_title: Aspose.HTML für .NET-API-Referenz
description: ICanvasRenderingContext2D methode. Zeichnet Daten aus dem gegebenen ImageDataObjekt auf die Bitmap. Wenn ein schmutziges Rechteck bereitgestellt wird werden nur die Pixel dieses Rechtecks gezeichnet. Diese Methode wird nicht von der CanvasTransformationsmatrix beeinflusst.
type: docs
weight: 290
url: /de/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Zeichnet Daten aus dem gegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck bereitgestellt wird, werden nur die Pixel dieses Rechtecks gezeichnet. Diese Methode wird nicht von der Canvas-Transformationsmatrix beeinflusst.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagedata | IImageData | Ein ImageData-Objekt, das das Array von Pixelwerten enthält. |
| dx | Double | Horizontale Position (x-Koordinate), an der die Bilddaten im Zielbereich platziert werden sollen. |
| dy | Double | Vertikale Position (y-Koordinate), an der die Bilddaten im Zielbereich platziert werden sollen. |

### Siehe auch

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namensraum [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* Montage [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Zeichnet Daten aus dem gegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck bereitgestellt wird, werden nur die Pixel dieses Rechtecks gezeichnet. Diese Methode wird nicht von der Canvas-Transformationsmatrix beeinflusst.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imagedata | IImageData | Ein ImageData-Objekt, das das Array von Pixelwerten enthält. |
| dx | Double | Horizontale Position (x-Koordinate), an der die Bilddaten im Zielbereich platziert werden sollen. |
| dy | Double | Vertikale Position (y-Koordinate), an der die Bilddaten im Zielbereich platziert werden sollen. |
| dirtyX | Double | Horizontale Position (x-Koordinate). Die x-Koordinate der oberen linken Ecke Ihrer Bilddaten. Standardmäßig 0. |
| dirtyY | Double | Vertikale Position (y-Koordinate). Die y-Koordinate der oberen linken Ecke Ihrer Bilddaten. Standardmäßig 0. |
| dirtyWidth | Double | Breite des zu malenden Rechtecks. Standardmäßig die Breite der Bilddaten. |
| dirtyHeight | Double | Höhe des zu malenden Rechtecks. Standardmäßig auf die Höhe der Bilddaten. |

### Siehe auch

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namensraum [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* Montage [Aspose.HTML](../../../)


