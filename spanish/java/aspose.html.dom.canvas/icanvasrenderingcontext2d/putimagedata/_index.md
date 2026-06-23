---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método ICanvasRenderingContext2D. Pinta datos del objeto ImageData proporcionado en el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo."
type: docs

url: /es/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Pinta datos del objeto ImageData dado sobre el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagedata | IImageData | Un objeto ImageData que contiene la matriz de valores de píxeles. |
| dx | Double | Posición horizontal (coordenada x) donde colocar los datos de la imagen en el lienzo de destino. |
| dy | Double | Posición vertical (coordenada y) donde colocar los datos de la imagen en el lienzo de destino. |

### Ver también

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Pinta datos del objeto ImageData dado sobre el mapa de bits. Si se proporciona un rectángulo sucio, solo se pintan los píxeles de ese rectángulo. Este método no se ve afectado por la matriz de transformación del lienzo.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagedata | IImageData | Un objeto ImageData que contiene la matriz de valores de píxeles. |
| dx | Double | Posición horizontal (coordenada x) donde colocar los datos de la imagen en el lienzo de destino. |
| dy | Double | Posición vertical (coordenada y) donde colocar los datos de la imagen en el lienzo de destino. |
| dirtyX | Double | Posición horizontal (coordenada x). La coordenada x de la esquina superior izquierda de sus datos de imagen. Predeterminado 0. |
| dirtyY | Double | Posición vertical (coordenada y). La coordenada y de la esquina superior izquierda de sus datos de imagen. Predeterminado 0. |
| dirtyWidth | Double | Ancho del rectángulo a pintar. Predeterminado al ancho de los datos de imagen. |
| dirtyHeight | Double | Altura del rectángulo a pintar. Predeterminado a la altura de los datos de imagen. |

### Ver también

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
