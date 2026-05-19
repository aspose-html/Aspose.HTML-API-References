---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICanvasRenderingContext2D. Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путём, с использованием правила ненулевого числа оборотов. Открытые подпути должны быть неявно закрыты при вычислении области отсечения без изменения фактических подпутей. Новая область отсечения заменяет текущую область отсечения."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую.

```java
public void Clip()
```

### См. также

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую.

```java
public void Clip(CanvasFillRule fillRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillRule | CanvasFillRule | Алгоритм, определяющий, находится ли точка внутри пути или снаружи пути |

### См. также

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Создаёт новую область отсечения, вычисляя пересечение текущей области отсечения и области, описанной путем, используя правило ненулевого числа оборотов. Открытые под‑пути должны быть неявно закрыты при вычислении области отсечения, без изменения самих под‑путей. Новая область отсечения заменяет текущую.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | Path2D | Путь Path2D для отсечения. |
| fillRule | CanvasFillRule | Алгоритм, определяющий, находится ли точка внутри пути или снаружи. |

### См. также

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
