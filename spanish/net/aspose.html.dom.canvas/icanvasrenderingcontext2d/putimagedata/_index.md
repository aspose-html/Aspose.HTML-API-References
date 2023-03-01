---
title: ICanvasRenderingContext2D.PutImageData
second_title: Referencia de API de Aspose.HTML para .NET
description: ICanvasRenderingContext2D método. Pinta los datos del objeto ImageData dado en el mapa de bits. Si se proporciona un rectángulo sucio solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo.
type: docs
weight: 290
url: /es/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Pinta los datos del objeto ImageData dado en el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imagedata | IImageData | Un objeto ImageData que contiene la matriz de valores de píxeles. |
| dx | Double | Posición horizontal (coordenada x) en la que colocar los datos de la imagen en el lienzo de destino. |
| dy | Double | Posición vertical (coordenada y) en la que colocar los datos de la imagen en el lienzo de destino. |

### Ver también

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* asamblea [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Pinta los datos del objeto ImageData dado en el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imagedata | IImageData | Un objeto ImageData que contiene la matriz de valores de píxeles. |
| dx | Double | Posición horizontal (coordenada x) en la que colocar los datos de la imagen en el lienzo de destino. |
| dy | Double | Posición vertical (coordenada y) en la que colocar los datos de la imagen en el lienzo de destino. |
| dirtyX | Double | Posición horizontal (coordenada x). La coordenada x de la esquina superior izquierda de sus datos de imagen. El valor predeterminado es 0. |
| dirtyY | Double | Posición vertical (coordenada y). La coordenada y de la esquina superior izquierda de sus datos de imagen. El valor predeterminado es 0. |
| dirtyWidth | Double | Ancho del rectángulo a pintar. El valor predeterminado es el ancho de los datos de la imagen. |
| dirtyHeight | Double | Altura del rectángulo a pintar. El valor predeterminado es la altura de los datos de la imagen. |

### Ver también

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* asamblea [Aspose.HTML](../../../)


