---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML för Java API-referens"
description: "ICanvasRenderingContext2D-metod. Målar data från det angivna ImageData-objektet på bitmapen. Om en smutsig rektangel anges målas endast pixlarna från den rektangeln. Denna metod påverkas inte av canvasens transformationsmatris."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Målar data från det angivna ImageData-objektet på bitmapen. Om en smutsig rektangel anges målas endast pixlarna från den rektangeln. Denna metod påverkas inte av canvasens transformationsmatris.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagedata | IImageData | Ett ImageData-objekt som innehåller arrayen av pixelvärden. |
| dx | Double | Horisontell position (x-koordinat) där bilddata ska placeras i målcanvasen. |
| dy | Double | Vertikal position (y-koordinat) där bilddata ska placeras i målcanvasen. |

### Se även

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Målar data från det angivna ImageData-objektet på bitmapen. Om en smutsig rektangel anges målas endast pixlarna från den rektangeln. Denna metod påverkas inte av canvasens transformationsmatris.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagedata | IImageData | Ett ImageData-objekt som innehåller arrayen av pixelvärden. |
| dx | Double | Horisontell position (x-koordinat) där bilddata ska placeras i målcanvasen. |
| dy | Double | Vertikal position (y-koordinat) där bilddata ska placeras i målcanvasen. |
| dirtyX | Double | Horisontell position (x-koordinat). X-koordinaten för det övre vänstra hörnet av din Image-data. Standardvärde 0. |
| dirtyY | Double | Vertikal position (y-koordinat). Y-koordinaten för det övre vänstra hörnet av din Image-data. Standardvärde 0. |
| dirtyWidth | Double | Bredden på den rektangel som ska målas. Standardvärde är bredden på bilddata. |
| dirtyHeight | Double | Höjden på den rektangel som ska målas. Standardvärde är höjden på bilddata. |

### Se även

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
