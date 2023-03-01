---
title: ICanvasRenderingContext2D.Clip
second_title: Referencia de API de Aspose.HTML para .NET
description: ICanvasRenderingContext2D método. Crea una nueva región de recorte mediante el cálculo de la intersección de la región de recorte actual y el área descrita por la ruta utilizando la regla del número de vueltas distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte sin afectar los subtrayectos reales . La nueva región de recorte reemplaza la región de recorte actual.
type: docs
weight: 150
url: /es/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Crea una nueva región de recorte mediante el cálculo de la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vueltas distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales . La nueva región de recorte reemplaza la región de recorte actual.

```csharp
public void Clip()
```

### Ver también

* interface [ICanvasRenderingContext2D](../)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* asamblea [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vuelta distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales. La nueva región de recorte reemplaza a la región de recorte actual.

```csharp
public void Clip(CanvasFillRule fillRule)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fillRule | CanvasFillRule | El algoritmo por el cual determinar si un punto está dentro o fuera de un camino |

### Ver también

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* asamblea [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Crea una nueva región de recorte calculando la intersección de la región de recorte actual y el área descrita por la ruta, utilizando la regla del número de vuelta distinto de cero. Los subtrayectos abiertos deben cerrarse implícitamente al calcular la región de recorte, sin afectar los subtrayectos reales. La nueva región de recorte reemplaza a la región de recorte actual.

```csharp
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | Path2D | Una ruta Path2D para recortar. |
| fillRule | CanvasFillRule | El algoritmo mediante el cual se determina si un punto está dentro o fuera de una ruta. |

### Ver también

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* espacio de nombres [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* asamblea [Aspose.HTML](../../../)


