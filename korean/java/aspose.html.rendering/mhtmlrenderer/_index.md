---
title: "MhtmlRenderer 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.rendering.MhtmlRenderer 클래스. MHTML 문서 렌더러를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

MHTML 문서 렌더러를 나타냅니다.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | 특정 [`IDevice`](../idevice/)에 여러 MHTML 문서를 렌더링하는 메서드를 정의하며, 작업 취소를 요청하기 위해 취소 토큰을 사용합니다. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | 지정된 [`IDevice`](../idevice/)에 여러 MHTML 문서를 렌더링합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | 지정된 [`IDevice`](../idevice/)에 MHTML 문서를 렌더링합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | 지정된 [`IDevice`](../idevice/)에 여러 MHTML 문서를 렌더링합니다. 렌더링은 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | 지정된 [`IDevice`](../idevice/)에 여러 MHTML 문서를 렌더링합니다. 렌더링은 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | 지정된 [`IDevice`](../idevice/)에 MHTML 문서를 렌더링합니다. 렌더링은 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다. |

### 또 보기

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
