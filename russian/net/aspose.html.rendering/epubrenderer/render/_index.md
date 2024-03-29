---
title: EpubRenderer.Render
second_title: Справочник по Aspose.HTML для .NET API
description: EpubRenderer метод. Определяет метод для рендеринга нескольких EPubStream в конкретныеIDevice . Рендеринг будет выполнен после того как не будет никаких сетевых операций для загрузки ресурсов активных таймеров задач анимации или истечет указанное время ожидания.
type: docs
weight: 20
url: /ru/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Определяет метод для рендеринга нескольких EPubStream в конкретные[`IDevice`](../../idevice/) . Рендеринг будет выполнен после того, как не будет никаких сетевых операций для загрузки ресурсов, активных таймеров, задач анимации или истечет указанное время ожидания.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Выходное устройство. |
| timeout | TimeSpan | АTimeSpan который представляет количество миллисекунд ожидания, илиTimeSpan что представляет собой -1 миллисекунду ожидания на неопределенный срок. |
| documents | Stream[] | Документы для оформления. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../epubrenderer/)
* сборка [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Визуализирует документ EPub в указанный[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство. |
| document | Stream | Документ. |
| configuration | Configuration | Конфигурация. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../epubrenderer/)
* сборка [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Визуализирует документ EPub в указанный[`IDevice`](../../idevice/) . Рендеринг будет выполнен после того, как не будет никаких сетевых операций для загрузки ресурсов, активных таймеров, задач анимации или истечет указанное время ожидания.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство. |
| document | Stream | Документ. |
| configuration | Configuration | Конфигурация. |
| timeout | TimeSpan | АTimeSpan который представляет количество миллисекунд ожидания, илиTimeSpan что представляет собой -1 миллисекунду ожидания на неопределенный срок. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../epubrenderer/)
* сборка [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Преобразует несколько документов EPub в указанные[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство. |
| documents | IList`1 | IList документов для оформления. |
| configuration | Configuration | Конфигурация. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../epubrenderer/)
* сборка [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Преобразует несколько документов EPub в указанные[`IDevice`](../../idevice/) . Рендеринг будет выполнен после того, как не будет никаких сетевых операций для загрузки ресурсов, активных таймеров, задач анимации или истечет указанное время ожидания.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | IDevice | Устройство. |
| documents | IList`1 | IList документов для оформления. |
| configuration | Configuration | Конфигурация. |
| timeout | TimeSpan | АTimeSpan который представляет количество миллисекунд ожидания, илиTimeSpan что представляет собой -1 миллисекунду ожидания на неопределенный срок. |

### Смотрите также

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* пространство имен [Aspose.Html.Rendering](../../epubrenderer/)
* сборка [Aspose.HTML](../../../)


