---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Aspose.HTML för Java API-referens"
description: "ICanvasRenderingContext2D metod. Returnerar ett ImageData-objekt som representerar den underliggande pixeldata för det område på canvas som anges av rektangeln som startar vid sx sy och har en sw bredd och sh höjd. Denna metod påverkas inte av canvas transformationsmatris."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

Returnerar ett ImageData-objekt som representerar den underliggande pixeldata för det område på canvas som anges av rektangeln som börjar vid (sx, sy) och har en bredd sw och en höjd sh. Denna metod påverkas inte av canvasens transformationsmatris.

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | Double | x-koordinaten för rektangelns övre vänstra hörn från vilket ImageData kommer att extraheras. |
| sy | Double | y-koordinaten för rektangelns övre vänstra hörn från vilket ImageData kommer att extraheras. |
| sw | Double | Bredden på rektangeln från vilken ImageData kommer att extraheras. |
| sh | Double | Höjden på rektangeln från vilken ImageData kommer att extraheras. |

### Returvärde

Ett ImageData-objekt som innehåller bilddata för den angivna rektangeln på canvas.

### Se även

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
