---
title: "com.aspose.html.rendering"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering 패키지는 문서/파일을 IDevice 구현으로 렌더링하는 데 책임이 있는 수많은 렌더러 객체와 적절한 저수준 옵션 클래스들로 구성됩니다."
type: docs

url: /ko/java/com.aspose.html.rendering/
---
**com.aspose.html.rendering** 패키지는 문서/파일을 IDevice 구현으로 렌더링하는 역할을 하는 수많은 렌더러 객체와 적절한 저수준 옵션 클래스로 구성됩니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [CssOptions](./cssoptions/) | CSS 렌더링 옵션을 나타냅니다. |
| [Device](./device/) | 다양한 형식 및 환경에서 그래픽을 그리는 데 사용되는 렌더링 장치를 구현하기 위한 기본 클래스를 나타냅니다. |
| [Device&lt;TGraphicContext,TRenderingOptions&gt;](./device-2/) | 특정 렌더링 장치 구현을 위한 기본 클래스를 나타냅니다. |
| [EpubRenderer](./epubrenderer/) | EPub 문서 렌더러를 나타냅니다. |
| [GraphicContext](./graphiccontext/) | 현재 그래픽 제어 매개변수를 보유합니다. 이러한 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다. |
| [HtmlRenderer](./htmlrenderer/) | HTML 문서 렌더러를 나타냅니다. |
| [MhtmlRenderer](./mhtmlrenderer/) | MHTML 문서 렌더러를 나타냅니다. |
| [PageSetup](./pagesetup/) | 출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 나타냅니다. |
| [Renderer](./renderer/) | 모든 렌더러의 기본 클래스를 나타내며 IDisposable 인터페이스를 구현합니다. |
| [Renderer&lt;TSource&gt;](./renderer-1/) | 모든 렌더러를 위한 추상 클래스를 나타냅니다. |
| [RenderingOptions](./renderingoptions/) | 렌더링 옵션을 나타냅니다. |
| [SvgRenderer](./svgrenderer/) | SVG 문서 렌더러를 나타냅니다. |
| [TextInfo](./textinfo/) | 렌더링된 텍스트에 대한 정보를 포함합니다. |
## Structures

| 구조 | 설명 |
| --- | --- |
| [GlyphInfo](./glyphinfo/) | 글리프 관련 정보를 포함합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IDevice](./idevice/) | 경로, 텍스트 및 이미지와 같은 그래픽 요소의 사용자 정의 렌더링을 지원하는 메서드와 속성을 정의합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [AtPagePriority](./atpagepriority/) | 페이지 크기 선언 적용 가능한 순서를 지정합니다. |
| [FillRule](./fillrule/) | SVG 및 HTML 렌더링에 사용되는 채우기 규칙을 지정합니다. |
| [MediaType](./mediatype/) | 렌더링 중에 사용되는 가능한 미디어 유형을 지정합니다. |
| [PageLayoutOptions](./pagelayoutoptions/) | 다른 PageSetup 옵션과 함께 페이지의 크기와 레이아웃을 결정하는 플래그를 지정합니다. 이러한 플래그는 설명에 따라 함께 결합될 수 있습니다. |
| [StrokeLineCap](./strokelinecap/) | SVG 및 HTML 렌더링에 사용되는 라인 캡을 지정합니다. |
| [StrokeLineJoin](./strokelinejoin/) | SVG 및 HTML 렌더링에 사용되는 라인 조인 스타일을 지정합니다. |
