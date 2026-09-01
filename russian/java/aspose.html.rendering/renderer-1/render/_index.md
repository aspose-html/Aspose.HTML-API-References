---
title: "Renderer-1.Render"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Renderer. Определяет метод для рендеринга TDocument в указанный IDevice"
type: docs

url: /ru/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TSource source)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| документ | TSource | Документ. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм-аут.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| документ | TSource | Документ. |
| тайм-аут | TimeSpan | Объект TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Определяет метод для рендеринга !:TDocument в указанный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм-аут.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| документ | TSource | Документ. |
| тайм-аут | Int32 | Количество миллисекунд, представляющее время ожидания, или -1 миллисекунда для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### См. также

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

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
