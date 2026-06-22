---
title: "SVGPathSeg 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.paths.SVGPathSeg 클래스. SVGPathSeg 인터페이스는 경로 데이터 사양 내 단일 명령에 해당하는 기본 인터페이스입니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.paths/svgpathseg/
---
## SVGPathSeg class

SVGPathSeg 인터페이스는 경로 데이터 사양 내 단일 명령에 해당하는 기본 인터페이스입니다.

```java
public abstract class SVGPathSeg : SVGValueType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getPathSegType](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtype/) 이 인터페이스에 정의된 상수 중 하나에 의해 지정되는 경로 세그먼트 유형입니다. |
| [getPathSegTypeAsLetter](../../com.aspose.html.dom.svg.paths/svgpathseg/pathsegtypeasletter/) 해당 한 문자 명령 이름에 의해 지정되는 경로 세그먼트 유형입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [PATHSEG_ARC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_abs/) | 절대 arcto (A) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_ARC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_arc_rel/) | 상대 arcto (a) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CLOSEPATH](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_closepath/) | closepath (z) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_abs/) | 절대 큐빅 Bézier 커브투 (C) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_rel/) | 상대 큐빅 Bézier 커브투 (c) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_abs/) | 절대 부드러운 큐빅 커브투 (S) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_CUBIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_cubic_smooth_rel/) | 상대 부드러운 큐빅 커브투 (s) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_abs/) | 절대 2차 Bézier 커브투 (Q) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_rel/) | 상대 2차 Bézier 커브투 (q) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_abs/) | 절대 부드러운 2차 커브투 (T) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_CURVETO_QUADRATIC_SMOOTH_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_curveto_quadratic_smooth_rel/) | 상대적인 "relative smooth quadratic curveto" (t) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_abs/) | 절대 "absolute lineto" (L) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_HORIZONTAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_abs/) | 절대 "absolute horizontal lineto" (H) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_HORIZONTAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_horizontal_rel/) | 상대적인 "relative horizontal lineto" (h) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_rel/) | 상대적인 "relative lineto" (l) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_VERTICAL_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_abs/) | 절대 "absolute vertical lineto" (V) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_LINETO_VERTICAL_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_lineto_vertical_rel/) | 상대적인 "relative vertical lineto" (v) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_MOVETO_ABS](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_abs/) | 절대 "absolute moveto" (M) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_MOVETO_REL](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_moveto_rel/) | 상대적인 "relative moveto" (m) 경로 데이터 명령에 해당합니다. |
| const [PATHSEG_UNKNOWN](../../com.aspose.html.dom.svg.paths/svgpathseg/pathseg_unknown/) | 단위 유형이 미리 정의된 유형 중 하나가 아닙니다. 이 유형의 새 값을 정의하거나 기존 값을 이 유형으로 전환하려는 시도는 유효하지 않습니다. |

### 또 보기

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
