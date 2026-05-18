---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML for Java API 参考"
description: "ICanvasRenderingContext2D 方法。通过使用非零环绕数规则计算当前裁剪区域与路径描述的区域的交集来创建新的裁剪区域。计算裁剪区域时必须隐式关闭打开的子路径，但不影响实际的子路径。新的裁剪区域取代当前裁剪区域。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。

```java
public void Clip()
```

### 另请参阅

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。

```java
public void Clip(CanvasFillRule fillRule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillRule | CanvasFillRule | 用于确定点是在路径内部还是路径外部的算法 |

### 另请参阅

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | Path2D | 用于裁剪的 Path2D 路径。 |
| fillRule | CanvasFillRule | 用于确定点是在路径内部还是外部的算法。 |

### 另请参阅

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
