---
title: "SvgRenderer 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.rendering.SvgRenderer 클래스. SVG 문서 렌더러를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

SVG 문서 렌더러를 나타냅니다.

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | 특정 [`IDevice`](../idevice/)에 여러 [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)을 렌더링하는 메서드를 정의하고, 작업 취소를 요청하기 위해 취소 토큰을 사용합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | 특정 [`IDevice`](../idevice/)에 여러 [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)을 렌더링하는 메서드를 정의합니다. 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과하면 렌더링이 수행됩니다. |

### 또 보기

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
