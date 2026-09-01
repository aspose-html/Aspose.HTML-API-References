---
title: "HtmlRenderer.Render"
second_title: "Java용 Aspose.HTML API 참조"
description: "HtmlRenderer 메서드. 여러 HTMLDocument를 특정 IDevice에 렌더링하는 메서드를 정의합니다."
type: docs

url: /ko/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

여러 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s를 특정 [`IDevice`](../../idevice/)에 렌더링하는 메서드를 정의합니다.

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| timeout | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan이거나, 무한히 대기하기 위해 -1 밀리초를 나타내는 TimeSpan입니다. |
| 소스 | HTMLDocument[] | 렌더링할 HTML 문서들입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

취소 토큰을 사용하여 작업 취소를 요청하면서 여러 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s를 특정 [`IDevice`](../../idevice/)에 렌더링하는 메서드를 정의합니다.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| cancellationToken | CancellationToken | 작업이 완료될 때까지 대기하는 동안 관찰할 CancellationToken. |
| 소스 | HTMLDocument[] | 렌더링할 HTML 문서들입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
