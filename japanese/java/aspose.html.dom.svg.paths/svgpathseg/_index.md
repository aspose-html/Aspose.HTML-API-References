---
title: "SVGPathSeg クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg クラス。SVGPathSeg インターフェイスは、パスデータ仕様内の単一コマンドに対応する基本インターフェイスです"
type: docs

url: /ja/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg インターフェイスは、パスデータ仕様内の単一コマンドに対応する基本インターフェイスです。

```java
public abstract class SVGPathSeg : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) このインターフェイスで定義された定数のいずれかで指定されるパスセグメントのタイプ。 |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) 対応する1文字コマンド名で指定されるパスセグメントのタイプ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | 「絶対 arcto」(A) パスデータコマンドに対応します。 |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | 「相対 arcto」(a) パスデータコマンドに対応します。 |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | 「closepath」(z) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 「絶対 cubic Bézier curveto」(C) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 「相対 cubic Bézier curveto」(c) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 「絶対 smooth cubic curveto」(S) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 「相対 smooth cubic curveto」(s) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 「絶対 quadratic Bézier curveto」(Q) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 「相対 quadratic Bézier curveto」(q) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 「絶対 smooth quadratic curveto」(T) パスデータコマンドに対応します。 |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | "relative smooth quadratic curveto" (t) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | "absolute lineto" (L) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | "absolute horizontal lineto" (H) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | "relative horizontal lineto" (h) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | "relative lineto" (l) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | "absolute vertical lineto" (V) パスデータコマンドに対応します。 |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | "relative vertical lineto" (v) パスデータコマンドに対応します。 |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | "absolute moveto" (M) パスデータコマンドに対応します。 |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | "relative moveto" (m) パスデータコマンドに対応します。 |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | 単位タイプは事前定義されたタイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 関連項目

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
