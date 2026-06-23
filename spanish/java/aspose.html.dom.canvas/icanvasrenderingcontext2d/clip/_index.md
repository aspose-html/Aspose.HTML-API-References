---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de ICanvasRenderingContext2D. Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta usando la regla del número de vueltas no cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual."
type: docs

url: /es/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual.

```java
public void Clip()
```

### Ver también

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual.

```java
public void Clip(CanvasFillRule fillRule)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillRule | CanvasFillRule | El algoritmo mediante el cual determinar si un punto está dentro de una ruta o fuera de ella |

### Ver también

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Las subrutas abiertas deben cerrarse implícitamente al calcular la región de recorte, sin afectar a las subrutas reales. La nueva región de recorte reemplaza a la región de recorte actual.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Path2D | Una ruta Path2D para recortar. |
| fillRule | CanvasFillRule | El algoritmo mediante el cual se determina si un punto está dentro o fuera de una ruta. |

### Ver también

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
