---
title: Class SVGPathSeg
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Svg.Paths.SVGPathSeg 수업. SVGPathSeg 인터페이스는 경로 데이터 사양 내의 단일 명령에 해당하는 기본 인터페이스입니다.
type: docs
weight: 1690
url: /ko/net/aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg 인터페이스는 경로 데이터 사양 내의 단일 명령에 해당하는 기본 인터페이스입니다.

```csharp
public abstract class SVGPathSeg : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [PathSegType](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) { get; } | 이 인터페이스에 정의된 상수 중 하나에 의해 지정된 경로 세그먼트의 유형입니다. |
| [PathSegTypeAsLetter](../../aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) { get; } | 해당하는 한 문자 명령 이름으로 지정된 경로 세그먼트의 유형입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | "absolute arcto"(A) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_ARC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | "상대 arcto"(a) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CLOSEPATH](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | "closepath"(z) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | "절대 3차 베지어 곡선"(C) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | "상대 3차 베지어 곡선"(c) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | "absolute smooth cubic curveto"(S) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | "상대적으로 부드러운 입방 곡선"(s) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | "절대 2차 베지어 곡선"(Q) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | "상대 2차 베지어 곡선"(q) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | "절대 부드러운 2차 곡선"(T) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | "상대적으로 부드러운 2차 곡선"(t) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | "absolute lineto"(L) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | "절대 수평선"(H) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | "상대 가로선"(h) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | "상대 라인"(l) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | "절대 수직선"(V) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | "상대 수직선"(v) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_MOVETO_ABS](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | "absolute moveto"(M) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_MOVETO_REL](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | "상대 이동"(m) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_UNKNOWN](../../aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | 단위 유형이 미리 정의된 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또한보십시오

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* 네임스페이스 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* 집회 [Aspose.HTML](../../)


