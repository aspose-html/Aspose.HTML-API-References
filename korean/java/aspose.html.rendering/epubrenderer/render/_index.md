---
title: "EpubRenderer.Render"
second_title: "Aspose.HTML for Java API 참조"
description: "EpubRenderer 메서드. 여러 EPub 스트림을 특정 IDevice에 렌더링하기 위한 메서드를 정의합니다. 렌더링은 리소스를 로드하는 네트워크 작업, 활성 타이머, 애니메이션 작업이 없거나 지정된 시간 제한이 경과했을 때 수행됩니다."
type: docs

url: /ko/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

여러 EPub 스트림을 특정 [`IDevice`](../../idevice/)에 렌더링하기 위한 메서드를 정의합니다. 렌더링은 리소스를 로드하는 네트워크 작업, 활성 타이머, 애니메이션 작업이 없거나 지정된 시간 제한이 경과했을 때 수행됩니다.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| 시간 초과 | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan 또는 무한히 대기하기 위해 -1밀리초를 나타내는 TimeSpan입니다. |
| 문서 | Stream[] | 렌더링할 문서들. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

취소 토큰을 사용하여 작업 취소를 요청하면서, 여러 EPub 문서를 특정 [`IDevice`](../../idevice/)에 렌더링하기 위한 메서드를 정의합니다.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| cancellationToken | CancellationToken | 작업이 완료될 때까지 대기하는 동안 관찰할 CancellationToken. |
| 소스 | Stream[] | 렌더링할 EPub 문서들. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

지정된 [`IDevice`](../../idevice/)에 EPub 문서를 렌더링합니다.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 디바이스. |
| 문서 | 스트림 | 문서. |
| 구성 | 구성 | 구성. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

지정된 [`IDevice`](../../idevice/)에 EPub 문서를 렌더링합니다. 렌더링은 리소스를 로드하는 네트워크 작업, 활성 타이머, 애니메이션 작업이 없거나 지정된 시간 제한이 경과했을 때 수행됩니다.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 디바이스. |
| 문서 | 스트림 | 문서. |
| 구성 | 구성 | 구성. |
| 시간 초과 | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan 또는 무한히 대기하기 위해 -1밀리초를 나타내는 TimeSpan입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

지정된 [`IDevice`](../../idevice/)에 여러 EPub 문서를 렌더링합니다.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 디바이스. |
| 문서 | IList`1 | 렌더링할 문서들의 IList. |
| 구성 | 구성 | 구성. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

지정된 [`IDevice`](../../idevice/)에 여러 EPub 문서를 렌더링합니다. 렌더링은 리소스를 로드하는 네트워크 작업, 활성 타이머, 애니메이션 작업이 없거나 지정된 시간 제한이 경과했을 때 수행됩니다.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 디바이스. |
| 문서 | IList`1 | 렌더링할 문서들의 IList. |
| 구성 | 구성 | 구성. |
| 시간 초과 | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan 또는 무한히 대기하기 위해 -1밀리초를 나타내는 TimeSpan입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
