---
title: Class SVGPathSeg
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg クラス. SVGPathSeg インターフェイスはパス データ仕様内の単一のコマンドに対応する基本インターフェイスです
type: docs
weight: 1690
url: /ja/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg インターフェイスは、パス データ仕様内の単一のコマンドに対応する基本インターフェイスです。

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | このインターフェイスで定義された定数の 1 つによって指定されたパス セグメントのタイプ。 |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | パス セグメントのタイプ。対応する 1 文字のコマンド名で指定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | 「absolute arcto」(A) パス データ コマンドに対応します。 |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | 「relative arcto」(a) パス データ コマンドに対応します。 |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | 「closepath」(z) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 「絶対 3 次ベジェ曲線」 (C) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 「相対 3 次ベジエ曲線」 (c) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 「絶対平滑 3 次曲線」(S) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 「相対スムーズ キュービック カーブ」(s) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 「絶対二次ベジェ曲線」(Q) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 「相対二次ベジェ曲線」(q) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 「絶対平滑二次曲線」(T) パス データ コマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | 「相対平滑二次曲線」(t) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | 「absolute lineto」(L) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | 「絶対水平ライン」(H) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | 「相対水平線」 (h) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | 「relative lineto」(l) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | 「絶対垂直線」(V) パス データ コマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | 「相対垂直線」 (v) パス データ コマンドに対応します。 |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | 「absolute moveto」(M) パス データ コマンドに対応します。 |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | 「相対移動」(m) パス データ コマンドに対応します。 |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | ユニット タイプが事前定義されたタイプの 1 つではありません。この型の新しい値を定義しようとしたり、既存の値をこの型に切り替えようとしたりすることは無効です. |

### 関連項目

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* 名前空間 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* 組み立て [Aspose.HTML](../../)


