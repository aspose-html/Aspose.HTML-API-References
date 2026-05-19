---
title: "Renderer-1.Render"
second_title: "Aspose.HTML for Java API 참조"
description: "Renderer 메서드. 지정된 IDevice에 TDocument를 렌더링하는 메서드를 정의합니다."
type: docs

url: /ko/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

지정된 [`IDevice`](../../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다.

```java
public void Render(IDevice device, TSource source)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| 문서 | TSource | 문서. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

지정된 [`IDevice`](../../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다. 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과하면 렌더링이 수행됩니다.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| 문서 | TSource | 문서. |
| 시간 초과 | TimeSpan | 대기할 밀리초 수를 나타내는 TimeSpan 또는 무한히 대기하기 위해 -1밀리초를 나타내는 TimeSpan입니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

지정된 [`IDevice`](../../idevice/)에 !:TDocument를 렌더링하는 메서드를 정의합니다. 리소스 로드, 활성 타이머, 애니메이션 작업에 대한 네트워크 작업이 없고 지정된 시간 제한이 경과하면 렌더링이 수행됩니다.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 장치 | IDevice | 출력 장치입니다. |
| 문서 | TSource | 문서. |
| 시간 초과 | Int32 | 대기할 밀리초 수를 나타내는 값이며, 무한히 대기하려면 -1밀리초를 사용합니다. |

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### 또 보기

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
