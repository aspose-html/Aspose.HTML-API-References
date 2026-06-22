---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICanvasRenderingContext2D-methode. Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels uit die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas."
type: docs

url: /nl/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imagedata | IImageData | Een ImageData-object dat de array met pixelwaarden bevat. |
| dx | Double | Horizontale positie (x-coördinaat) waarop de beeldgegevens in het bestemmingscanvas worden geplaatst. |
| dy | Double | Verticale positie (y-coördinaat) waarop de beeldgegevens in het bestemmingscanvas worden geplaatst. |

### Zie ook

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Schildert gegevens van het opgegeven ImageData-object op de bitmap. Als een vuile rechthoek wordt opgegeven, worden alleen de pixels van die rechthoek geschilderd. Deze methode wordt niet beïnvloed door de transformatie-matrix van het canvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imagedata | IImageData | Een ImageData-object dat de array met pixelwaarden bevat. |
| dx | Double | Horizontale positie (x-coördinaat) waarop de beeldgegevens in het bestemmingscanvas worden geplaatst. |
| dy | Double | Verticale positie (y-coördinaat) waarop de beeldgegevens in het bestemmingscanvas worden geplaatst. |
| dirtyX | Double | Horizontale positie (x-coördinaat). Het x-coördinaat van de linkerbovenhoek van uw Image data. Standaard 0. |
| dirtyY | Double | Verticale positie (y-coördinaat). Het y-coördinaat van de linkerbovenhoek van uw Image data. Standaard 0. |
| dirtyWidth | Double | Breedte van de te schilderen rechthoek. Standaard de breedte van de image data. |
| dirtyHeight | Double | Hoogte van de te schilderen rechthoek. Standaard de hoogte van de image data. |

### Zie ook

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
