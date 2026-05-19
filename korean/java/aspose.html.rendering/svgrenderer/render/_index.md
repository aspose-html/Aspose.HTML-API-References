---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML for Java API 참조"
description: "SvgRenderer 메서드. 여러 SVGDocument를 특정 IDevice에 렌더링하기 위한 메서드를 정의합니다. 렌더링은 리소스 로딩을 위한 네트워크 작업, 활성 타이머, 애니메이션 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다."
type: docs

url: /ko/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

여러 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 특정 [`IDevice`](../../idevice/)에 렌더링하기 위한 메서드를 정의합니다. 렌더링은 리소스 로딩을 위한 네트워크 작업, 활성 타이머, 애니메이션 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| 시간 초과 | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan 또는 무한히 대기하기 위해 -1밀리초를 나타내는 TimeSpan입니다. |
| 문서 | SVGDocument[] | 렌더링할 문서들. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

여러 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 특정 [`IDevice`](../../idevice/)에 렌더링하기 위한 메서드를 정의하며, 작업 취소를 요청하기 위해 취소 토큰을 사용합니다.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| cancellationToken | CancellationToken | 작업이 완료될 때까지 대기하는 동안 관찰할 취소 토큰입니다. |
| 소스 | SVGDocument[] | 렌더링할 SVG 문서들입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
