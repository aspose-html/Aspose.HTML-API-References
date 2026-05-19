---
title: "EpubRenderer.Render"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод EpubRenderer. Определяет метод для рендеринга нескольких EPub потоков в конкретное IDevice. Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут"
type: docs

url: /ru/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Определяет метод для рендеринга нескольких EPub потоков в конкретный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| тайм-аут | TimeSpan | TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |
| документы | Stream[] | Документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Определяет метод для рендеринга нескольких EPub документов в конкретный [`IDevice`](../../idevice/), используя токен отмены для запроса отмены операции.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| cancellationToken | CancellationToken | Токен CancellationToken, наблюдаемый во время ожидания завершения задачи. |
| источники | Stream[] | EPub документы для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Рендерит EPub документ в указанный [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Устройство. |
| документ | Поток | Документ. |
| конфигурация | Конфигурация | Конфигурация. |

### См. также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Рендерит EPub документ в указанный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Устройство. |
| документ | Поток | Документ. |
| конфигурация | Конфигурация | Конфигурация. |
| тайм-аут | TimeSpan | TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Рендерит несколько EPub документов в указанный [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Устройство. |
| документы | IList`1 | IList документов для рендеринга. |
| конфигурация | Конфигурация | Конфигурация. |

### См. также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Рендерит несколько EPub документов в указанный [`IDevice`](../../idevice/). Рендеринг будет выполнен, когда не будет никаких сетевых операций по загрузке ресурсов, активных таймеров, анимационных задач или когда истечёт указанный тайм‑аут.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Устройство. |
| документы | IList`1 | IList документов для рендеринга. |
| конфигурация | Конфигурация | Конфигурация. |
| тайм-аут | TimeSpan | TimeSpan, представляющий количество миллисекунд ожидания, или TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
