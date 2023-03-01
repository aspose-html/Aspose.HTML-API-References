---
title: EpubRenderer.Render
second_title: .NET API 참조용 Aspose.HTML
description: EpubRenderer 방법. 여러 EPub을 렌더링하는 방법을 정의합니다.Stream 구체적으로IDevice . 리소스 로드 활성 타이머 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.
type: docs
weight: 20
url: /ko/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

여러 EPub을 렌더링하는 방법을 정의합니다.Stream 구체적으로[`IDevice`](../../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 출력 장치. |
| timeout | TimeSpan | ㅏTimeSpan 대기 시간(밀리초) 또는TimeSpan 무기한 대기하는 -1밀리초를 나타냅니다. |
| documents | Stream[] | 렌더링할 문서입니다. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../epubrenderer/)
* 집회 [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

EPub 문서를 지정된 형식으로 렌더링합니다.[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 장치. |
| document | Stream | 문서. |
| configuration | Configuration | 구성. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../epubrenderer/)
* 집회 [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

EPub 문서를 지정된 형식으로 렌더링합니다.[`IDevice`](../../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 장치. |
| document | Stream | 문서. |
| configuration | Configuration | 구성. |
| timeout | TimeSpan | ㅏTimeSpan 대기 시간(밀리초) 또는TimeSpan 무기한 대기하는 -1밀리초를 나타냅니다. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../epubrenderer/)
* 집회 [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

여러 EPub 문서를 지정된 문서로 렌더링합니다.[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 장치. |
| documents | IList`1 | 그만큼IList 렌더링할 문서 수. |
| configuration | Configuration | 구성. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../epubrenderer/)
* 집회 [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

여러 EPub 문서를 지정된 문서로 렌더링합니다.[`IDevice`](../../idevice/) . 리소스 로드, 활성 타이머, 애니메이션 작업 또는 지정된 시간 초과에 대한 네트워크 작업이 없으면 렌더링이 수행됩니다.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| device | IDevice | 장치. |
| documents | IList`1 | 그만큼IList 렌더링할 문서 수. |
| configuration | Configuration | 구성. |
| timeout | TimeSpan | ㅏTimeSpan 대기 시간(밀리초) 또는TimeSpan 무기한 대기하는 -1밀리초를 나타냅니다. |

### 또한보십시오

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 네임스페이스 [Aspose.Html.Rendering](../../epubrenderer/)
* 집회 [Aspose.HTML](../../../)


