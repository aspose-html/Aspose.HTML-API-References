---
title: ICanvasRenderingContext2D.Clip
second_title: Aspose.HTML for .NET API 参考
description: ICanvasRenderingContext2D 方法. 通过计算当前裁剪区域和路径所描述的区域的交集使用非零绕数规则来创建一个新的裁剪区域 Open subpaths must be implicitly closed when computing the clipping region without affect the actual subpaths . 新的剪辑区域替换当前剪辑区域
type: docs
weight: 150
url: /zh/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

通过计算当前裁剪区域和路径所描述的区域的交集，使用非零绕数规则来创建一个新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths . 新的剪辑区域替换当前剪辑区域。

```csharp
public void Clip()
```

### 也可以看看

* interface [ICanvasRenderingContext2D](../)
* 命名空间 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 部件 [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

通过使用非零缠绕数规则计算当前裁剪区域与路径描述的区域的交集来创建新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths. new clipping region replaces the current clipping region. 计算裁剪区域时必须隐式关闭，而不影响实际子路径。

```csharp
public void Clip(CanvasFillRule fillRule)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fillRule | CanvasFillRule | 确定一个点是在路径内还是路径外的算法 |

### 也可以看看

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* 命名空间 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 部件 [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

通过使用非零缠绕数规则计算当前裁剪区域与路径描述的区域的交集来创建新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths. new clipping region replaces the current clipping region. 计算裁剪区域时必须隐式关闭，而不影响实际子路径。

```csharp
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | Path2D | 要剪辑的 Path2D 路径。 |
| fillRule | CanvasFillRule | 确定点是在路径内部还是路径外部的算法。 |

### 也可以看看

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* 命名空间 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 部件 [Aspose.HTML](../../../)


