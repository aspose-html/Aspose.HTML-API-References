---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasRenderingContext2D のメソッドです。非ゼロ winding number ルールを使用して、現在のクリッピング領域とパスで記述された領域の交差を計算し、新しいクリッピング領域を作成します。オープンしたサブパスは、実際のサブパスに影響を与えずにクリッピング領域を計算する際に暗黙的に閉じられます。新しいクリッピング領域は現在のクリッピング領域と置き換わります。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

非ゼロ winding number ルールを使用して、現在のクリッピング領域とパスで記述された領域の交差を計算し、新しいクリッピング領域を作成します。クリッピング領域を計算する際、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。

```java
public void Clip()
```

### 関連項目

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

非ゼロ winding number ルールを使用して、現在のクリッピング領域とパスで記述された領域の交差を計算し、新しいクリッピング領域を作成します。クリッピング領域を計算する際、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。

```java
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| fillRule | CanvasFillRule | 点がパスの内部にあるか外部にあるかを判定するアルゴリズムです。 |

### 関連項目

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

非ゼロ winding number ルールを使用して、現在のクリッピング領域とパスで記述された領域の交差を計算し、新しいクリッピング領域を作成します。クリッピング領域を計算する際、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| パス | Path2D | クリップするための Path2D パスです。 |
| fillRule | CanvasFillRule | 点がパスの内部にあるか外部にあるかを判定するアルゴリズムです。 |

### 関連項目

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
