---
title: "com.aspose.html.dom.svg"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.svg 패키지의 모든 클래스는 w3c SVG2 권고안을 기반으로 합니다. 이 패키지를 사용하면 요구 사항에 따라 SVG 파일을 로드, 탐색 또는 렌더링할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg/
---
All classes in **com.aspose.html.dom.svg** 패키지는 w3c SVG2 권고안을 기반으로 합니다. 이 패키지를 사용하면 요구 사항에 따라 SVG 파일을 로드, 탐색 또는 렌더링할 수 있습니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [SVGAElement](./svgaelement/) | SVGAElement 인터페이스는 ‘a’ 요소에 해당합니다. |
| [SVGAnimateElement](./svganimateelement/) | SVGAnimateElement 인터페이스는 ‘animate’ 요소에 해당합니다. SVG DOM을 통한 ‘animate’ 요소의 속성에 대한 객체 지향 접근은 사용할 수 없습니다. |
| [SVGAnimateMotionElement](./svganimatemotionelement/) | SVGAnimateMotionElement 인터페이스는 ‘animateMotion’ 요소에 해당합니다. SVG DOM을 통한 ‘animateMotion’ 요소의 속성에 대한 객체 지향 접근은 사용할 수 없습니다. |
| [SVGAnimateTransformElement](./svganimatetransformelement/) | SVGAnimateTransformElement 인터페이스는 ‘animateTransform’ 요소에 해당합니다. SVG DOM을 통한 ‘animateTransform’ 요소의 속성에 대한 객체 지향 접근은 사용할 수 없습니다. |
| [SVGAnimationElement](./svganimationelement/) | SVGAnimationElement 인터페이스는 모든 애니메이션 요소 인터페이스(SVGAnimateElement, SVGSetElement, SVGAnimateColorElement, SVGAnimateMotionElement 및 SVGAnimateTransformElement)의 기본 인터페이스입니다. |
| [SVGCircleElement](./svgcircleelement/) | SVGCircleElement 인터페이스는 ‘circle’ 요소에 해당합니다. |
| [SVGClipPathElement](./svgclippathelement/) | SVGClipPathElement 인터페이스는 ‘clipPath’ 요소에 해당합니다. |
| [SVGComponentTransferFunctionElement](./svgcomponenttransferfunctionelement/) | 이 인터페이스는 컴포넌트 전송 함수 인터페이스에서 사용되는 기본 인터페이스를 정의합니다. |
| [SVGCursorElement](./svgcursorelement/) | SVGCursorElement 인터페이스는 ‘cursor’ 요소에 해당합니다. |
| [SVGDefsElement](./svgdefselement/) | SVGDefsElement 인터페이스는 ‘defs’ 요소에 해당합니다. |
| [SVGDescElement](./svgdescelement/) | SVGDescElement 인터페이스는 ‘desc’ 요소에 해당합니다. |
| [SVGDocument](./svgdocument/) | `SVGDocument`는 SVG 계층 구조의 루트이며 전체 콘텐츠를 보유합니다. 계층 구조에 대한 접근을 제공할 뿐만 아니라 문서에서 특정 정보 집합에 접근하기 위한 편리한 메서드도 제공합니다. ‘svg’ 요소가 다른 패키지의 문서 구성 요소로 인라인 삽입될 때, 예를 들어 ‘svg’ 요소가 XHTML 문서 [XHTML] 내에 인라인 삽입될 경우, `SVGDocument` 객체는 존재하지 않습니다; 대신 문서 객체 계층 구조의 루트 객체는 HTMLDocument와 같은 다른 유형의 Document 객체가 됩니다. 그러나 XML 문서 계층 구조의 루트 요소가 ‘svg’ 요소인 경우, 예를 들어 독립 실행형 SVG 파일(즉, MIME 타입 "image/svg+xml"인 파일)을 볼 때는 `SVGDocument` 객체가 실제로 존재합니다. 이 경우 `SVGDocument` 객체가 문서 객체 모델 계층 구조의 루트 객체가 됩니다. |
| [SVGElement](./svgelement/) | SVG 언어의 요소에 직접 대응하는 모든 SVG DOM 인터페이스(예: ‘path’ 요소에 대한 SVGPathElement 인터페이스)는 SVGElement 인터페이스를 상속합니다. |
| [SVGElementInstance](./svgelementinstance/) | 각 use-element 섀도우 트리의 루트 객체는 SVGUseElementShadowRoot 인터페이스를 구현합니다. 이 인터페이스는 현재 ShadowRoot 인터페이스와 DocumentOrShadowRoot 믹스인에 정의된 속성과 메서드에 대한 확장을 정의하고 있지 않습니다. 그러나 이 노드를 루트로 하는 트리는 작성자 스크립트 관점에서 완전히 읽기 전용입니다. |
| [SVGEllipseElement](./svgellipseelement/) | SVGEllipseElement 인터페이스는 ‘ellipse’ 요소에 해당합니다. |
| [SVGException](./svgexception/) | 특정 SVG 작업을 수행할 수 없을 때 이 예외가 발생합니다. |
| [SVGFilterElement](./svgfilterelement/) | SVGFilterElement 인터페이스는 ‘filter’ 요소에 해당합니다. |
| [SVGForeignObjectElement](./svgforeignobjectelement/) | SVGForeignObjectElement 인터페이스는 ‘foreignObject’ 요소에 해당합니다. |
| [SVGGElement](./svggelement/) | SVGGElement 인터페이스는 ‘g’ 요소에 해당합니다. |
| [SVGGeometryElement](./svggeometryelement/) | SVGGeometryElement 인터페이스는 등가 경로를 가진 기하학으로 렌더링이 정의되고 채우기 및 스트로크가 가능한 SVG 요소를 나타냅니다. 여기에는 경로와 기본 도형이 포함됩니다. |
| [SVGGradientElement](./svggradientelement/) | SVGGradientElement 인터페이스는 SVGLinearGradientElement와 SVGRadialGradientElement에서 사용되는 기본 인터페이스입니다. |
| [SVGGraphicsElement](./svggraphicselement/) | SVGGraphicsElement 인터페이스는 기본 목적이 그래픽을 그룹에 직접 렌더링하는 SVG 요소를 나타냅니다. |
| [SVGImageElement](./svgimageelement/) | SVGImageElement 인터페이스는 ‘image’ 요소에 해당합니다. |
| [SVGLinearGradientElement](./svglineargradientelement/) | SVGLinearGradientElement 인터페이스는 ‘linearGradient’ 요소에 해당합니다. |
| [SVGLineElement](./svglineelement/) | SVGLineElement 인터페이스는 ‘line’ 요소에 해당합니다. |
| [SVGMarkerElement](./svgmarkerelement/) | SVGMarkerElement 인터페이스는 ‘marker’ 요소에 해당합니다. |
| [SVGMaskElement](./svgmaskelement/) | SVGMaskElement 인터페이스는 ‘mask’ 요소에 해당합니다. |
| [SVGMetadataElement](./svgmetadataelement/) | SVGMetadataElement 인터페이스는 ‘metadata’ 요소에 해당합니다. |
| [SVGMPathElement](./svgmpathelement/) | SVGMPathElement 인터페이스는 ‘mpath’ 요소에 해당합니다. |
| [SVGPathElement](./svgpathelement/) | SVGPathElement 인터페이스는 ‘path’ 요소에 해당합니다. |
| [SVGPatternElement](./svgpatternelement/) | SVGPatternElement 인터페이스는 ‘pattern’ 요소에 해당합니다. |
| [SVGPolygonElement](./svgpolygonelement/) | SVGPolygonElement 인터페이스는 ‘polygon’ 요소에 해당합니다. |
| [SVGPolylineElement](./svgpolylineelement/) | SVGPolylineElement 인터페이스는 ‘polyline’ 요소에 해당합니다. |
| [SVGRadialGradientElement](./svgradialgradientelement/) | SVGRadialGradientElement 인터페이스는 ‘radialGradient’ 요소에 해당합니다. |
| [SVGRectElement](./svgrectelement/) | SVGRectElement 인터페이스는 ‘rect’ 요소에 해당합니다. |
| [SVGScriptElement](./svgscriptelement/) | SVGScriptElement 인터페이스는 ‘script’ 요소에 해당합니다. |
| [SVGSetElement](./svgsetelement/) | SVGSetElement 인터페이스는 ‘set’ 요소에 해당합니다. SVG DOM을 통한 ‘set’ 요소의 속성에 대한 객체 지향 접근은 제공되지 않습니다. |
| [SVGStopElement](./svgstopelement/) | SVGStopElement 인터페이스는 ‘stop’ 요소에 해당합니다. |
| [SVGStyleElement](./svgstyleelement/) | SVGStyleElement 인터페이스는 ‘style’ 요소에 해당합니다. |
| [SVGSVGElement](./svgsvgelement/) | 핵심 인터페이스 정의는 ‘svg’ 요소에 해당하는 SVGSVGElement 인터페이스입니다. 이 인터페이스는 행렬 연산 및 시각 렌더링 장치에서 다시 그리기 시간을 제어하는 기능과 같은 다양한 일반적으로 사용되는 유틸리티 메서드를 포함합니다. |
| [SVGSwitchElement](./svgswitchelement/) | SVGSwitchElement 인터페이스는 ‘switch’ 요소에 해당합니다. |
| [SVGSymbolElement](./svgsymbolelement/) | SVGSymbolElement 인터페이스는 ‘symbol’ 요소에 해당합니다. |
| [SVGTextContentElement](./svgtextcontentelement/) | SVGTextContentElement는 SVGTextElement, SVGTSpanElement, SVGTRefElement, SVGAltGlyphElement 및 SVGTextPathElement와 같은 다양한 텍스트 관련 인터페이스에서 상속됩니다. 이 인터페이스의 메서드 중 문자에 대한 인덱스 또는 문자 수를 참조하는 경우, 이러한 참조는 각각 UTF-16 코드 단위에 대한 인덱스 또는 UTF-16 코드 단위의 수로 해석되어야 합니다. 이는 CharacterData 인터페이스의 메서드가 문자 데이터 내에서 인덱스와 개수로 UTF-16 코드 단위를 사용하는 DOM Level 2 Core와의 일관성을 위해서입니다. 예를 들어, ‘text’ 요소의 텍스트 내용이 U+10000과 같은 단일 비BMP 문자일 경우, 해당 요소에서 getNumberOfChars를 호출하면 해당 문자를 나타내는 두 개의 UTF-16 코드 단위(서러게이트 쌍) 때문에 2가 반환됩니다. |
| [SVGTextElement](./svgtextelement/) | SVGTextElement 인터페이스는 ‘text’ 요소에 해당합니다. |
| [SVGTextPathElement](./svgtextpathelement/) | SVGTextPathElement 인터페이스는 ‘textPath’ 요소에 해당합니다. |
| [SVGTextPositioningElement](./svgtextpositioningelement/) | SVGTextPositioningElement 인터페이스는 텍스트 관련 인터페이스인 SVGTextElement, SVGTSpanElement, SVGTRefElement 및 SVGAltGlyphElement에 의해 상속됩니다. |
| [SVGTitleElement](./svgtitleelement/) | SVGTitleElement 인터페이스는 ‘title’ 요소에 해당합니다. |
| [SVGTSpanElement](./svgtspanelement/) | SVGTSpanElement 인터페이스는 ‘tspan’ 요소에 해당합니다. |
| [SVGUseElement](./svguseelement/) | SVGUseElement 인터페이스는 ‘use’ 요소에 해당합니다. |
| [SVGViewElement](./svgviewelement/) | SVGViewElement 인터페이스는 ‘view’ 요소에 해당합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [ISVGAnimatedPoints](./isvganimatedpoints/) | The SVGAnimatedPoints 인터페이스는 ‘points’ 속성을 가지고 좌표 값 목록을 보유하고 해당 속성을 애니메이션화할 수 있는 요소를 지원합니다. 또한 XML DOM(e.g., getAttribute() 메서드 호출 사용)으로 접근한 원본 요소의 ‘points’ 속성은 points에 대한 모든 변경 사항을 반영합니다. |
| [ISVGFitToViewBox](./isvgfittoviewbox/) | SVGFitToViewBox 인터페이스는 ‘viewBox’ 및 ‘preserveAspectRatio’ XML 속성을 가진 요소에 적용되는 DOM 속성을 정의합니다. |
| [ISVGRenderingIntent](./isvgrenderingintent/) | SVGRenderingIntent 인터페이스는 ‘rendering-intent’ 속성 또는 기술자에 대한 가능한 값들의 열거 목록을 정의합니다. |
| [ISVGTests](./isvgtests/) | SVGTests 인터페이스는 ‘requiredFeatures’, ‘requiredExtensions’, ‘systemLanguage’ 속성을 가진 모든 요소에 적용되는 인터페이스를 정의합니다. |
| [ISVGUnitTypes](./isvgunittypes/) | SVGUnitTypes 인터페이스는 일반적으로 사용되는 상수 집합을 정의하며, SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement 및 SVGFilterElement에서 사용되는 기본 인터페이스입니다. |
| [ISVGURIReference](./isvgurireference/) | SVGURIReference 인터페이스는 ‘xlink:href’와 같이 URI 참조를 정의하는 XLink 속성 집합을 가진 모든 요소에 적용되는 인터페이스를 정의합니다. |
| [ISVGZoomAndPan](./isvgzoomandpan/) | SVGZoomAndPan 인터페이스는 zoomAndPan 속성과 관련 상수를 정의합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [SVGRenderingIntent](./svgrenderingintent/) | SVGRenderingIntent 열거형은 ‘rendering-intent’ 속성 또는 기술자에 대한 가능한 값들의 열거 목록을 정의합니다. |
| [SVGUnitTypes](./svgunittypes/) | SVGUnitTypes 열거형은 일반적으로 사용되는 상수 집합을 정의하며, SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement 및 SVGFilterElement에서 사용되는 기본 인터페이스입니다. |
| [SVGZoomAndPan](./svgzoomandpan/) | SVGZoomAndPan 열거형은 zoomAndPan 속성과 관련 상수를 정의합니다. |
