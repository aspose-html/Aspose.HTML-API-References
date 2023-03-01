---
title: Class RendererTDocument
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Renderer1TDocument 수업. 모든 렌더러에 대한 추상 클래스를 나타냅니다.
type: docs
weight: 4490
url: /ko/net/aspose.html.rendering/renderer-1/
---
## Renderer&lt;TDocument&gt; class

모든 렌더러에 대한 추상 클래스를 나타냅니다.

```csharp
public abstract class Renderer<TDocument> : Renderer
```

| 모수 | 설명 |
| --- | --- |
| TDocument | 문서의 유형입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | 관리되지 않는 리소스와 선택적으로 관리되는 리소스를 해제합니다. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TDocument) | 렌더링 방법 정의!:TDocument 지정된[`IDevice`](../idevice/) . |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_5)(IDevice, params TDocument[]) | 다중 렌더링 방법을 정의합니다.!:TDocument 구체적으로[`IDevice`](../idevice/) . |
| [Render](../../aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TDocument[]) | 다중 렌더링 방법을 정의합니다.!:TDocument 구체적으로[`IDevice`](../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TDocument, int) | 렌더링 방법 정의!:TDocument 지정된[`IDevice`](../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TDocument, TimeSpan) | 렌더링 방법 정의!:TDocument 지정된[`IDevice`](../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다. |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_1)(IDevice, TimeSpan, params TDocument[]) | 다중 렌더링 방법을 정의합니다.!:TDocument 구체적으로[`IDevice`](../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다. |

### 또한보십시오

* class [Renderer](../renderer/)
* 네임스페이스 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 집회 [Aspose.HTML](../../)


