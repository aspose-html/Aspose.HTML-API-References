---
title: ICanvasRenderingContext2D.Clip
second_title: Aspose.HTML for .NET API リファレンス
description: ICanvasRenderingContext2D 方法. 現在のクリッピング領域とパスによって記述された領域の交点を計算することにより新しいクリッピング領域を作成します クリッピング領域を計算するときは実際のサブパスに影響を与えずに開いているサブパスを暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます.
type: docs
weight: 150
url: /ja/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 クリッピング領域を計算するときは、実際のサブパスに影響を与えずに、開いているサブパスを暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます.

```csharp
public void Clip()
```

### 関連項目

* interface [ICanvasRenderingContext2D](../)
* 名前空間 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 組み立て [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

非ゼロの巻き数規則を使用して、現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 開いているサブパスは、実際のサブパスに影響を与えることなく、クリッピング領域を計算するときに暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます.

```csharp
public void Clip(CanvasFillRule fillRule)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fillRule | CanvasFillRule | ポイントがパスの内側にあるかパスの外側にあるかを判断するアルゴリズム |

### 関連項目

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* 名前空間 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 組み立て [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

非ゼロの巻き数規則を使用して、現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 開いているサブパスは、実際のサブパスに影響を与えることなく、クリッピング領域を計算するときに暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます.

```csharp
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | Path2D | クリップする Path2D パス。 |
| fillRule | CanvasFillRule | ポイントがパスの内側にあるかパスの外側にあるかを判断するためのアルゴリズム。 |

### 関連項目

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* 名前空間 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 組み立て [Aspose.HTML](../../../)


