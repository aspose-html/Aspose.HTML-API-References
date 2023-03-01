---
title: ICanvasRenderingContext2D.PutImageData
second_title: Aspose.HTML för .NET API Referens
description: ICanvasRenderingContext2D metod. Målar data från det givna ImageDataobjektet på bitmappen. Om en smutsig rektangel tillhandahålls målas endast pixlarna från den rektangeln. Denna metod påverkas inte av arbetsytans transformationsmatris.
type: docs
weight: 290
url: /sv/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Målar data från det givna ImageData-objektet på bitmappen. Om en smutsig rektangel tillhandahålls, målas endast pixlarna från den rektangeln. Denna metod påverkas inte av arbetsytans transformationsmatris.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagedata | IImageData | Ett ImageData-objekt som innehåller arrayen av pixelvärden. |
| dx | Double | Horisontell position (x-koordinat) där bilddata ska placeras på målytan. |
| dy | Double | Vertikal position (y-koordinat) där bilddata ska placeras på målytan. |

### Se även

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namnutrymme [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* hopsättning [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Målar data från det givna ImageData-objektet på bitmappen. Om en smutsig rektangel tillhandahålls, målas endast pixlarna från den rektangeln. Denna metod påverkas inte av arbetsytans transformationsmatris.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imagedata | IImageData | Ett ImageData-objekt som innehåller arrayen av pixelvärden. |
| dx | Double | Horisontell position (x-koordinat) där bilddata ska placeras på målytan. |
| dy | Double | Vertikal position (y-koordinat) där bilddata ska placeras på målytan. |
| dirtyX | Double | Horisontell position (x-koordinat). X-koordinaten i det övre vänstra hörnet av din bilddata. Standard är 0. |
| dirtyY | Double | Vertikal position (y-koordinat). Y-koordinaten i det övre vänstra hörnet av din bilddata. Standard är 0. |
| dirtyWidth | Double | Bredden på rektangeln som ska målas. Förinställer bredden på bilddata. |
| dirtyHeight | Double | Höjd på rektangeln som ska målas. Förinställer höjden på bilddata. |

### Se även

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namnutrymme [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* hopsättning [Aspose.HTML](../../../)


