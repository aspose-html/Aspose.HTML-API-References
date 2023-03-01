---
title: HtmlRenderer.Render
second_title: .NET API 참조용 Aspose.HTML
description: HtmlRenderer 방법. 다중 렌더링 방법을 정의합니다.Document 구체적으로IDevice . 리소스 로드 활성 타이머 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.
type: docs
weight: 20
url: /ko/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

다중 렌더링 방법을 정의합니다.[`Document`](../../../aspose.html.dom/document/) 구체적으로[`IDevice`](../../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 출력 장치. |
| timeout | TimeSpan | ㅏTimeSpan 대기 시간(밀리초) 또는TimeSpan 무기한 대기하는 -1밀리초를 나타냅니다. |
| documents | Document[] | 렌더링할 문서입니다. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../htmlrenderer/)
* 집회 [Aspose.HTML](../../../)


