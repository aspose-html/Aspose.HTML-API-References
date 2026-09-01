---
title: "RendererTSource 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.Renderer1TSource 클래스. 모든 렌더러에 대한 추상 클래스를 나타냅니다"
type: docs

url: /ko/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

모든 렌더러를 위한 추상 클래스를 나타냅니다.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | 설명 |
| --- | --- |
| TDocument | 문서의 유형입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | 지정된 [`IDevice`](../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | 지정된 [`IDevice`](../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다. 렌더링은 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | 지정된 [`IDevice`](../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다. 렌더링은 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과했을 때 수행됩니다. |

### 또 보기

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
