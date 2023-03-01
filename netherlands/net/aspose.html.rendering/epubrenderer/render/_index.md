---
title: EpubRenderer.Render
second_title: Aspose.HTML voor .NET API-referentie
description: EpubRenderer methode. Definieert methode voor het renderen van meerdere EPubStream s in specifiekIDevice . De weergave wordt uitgevoerd zodra er geen netwerkbewerkingen zijn voor het laden van bronnen actieve timers animatietaken of opgegeven timeout is verstreken.
type: docs
weight: 20
url: /nl/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Definieert methode voor het renderen van meerdere EPubStream s in specifiek[`IDevice`](../../idevice/) . De weergave wordt uitgevoerd zodra er geen netwerkbewerkingen zijn voor het laden van bronnen, actieve timers, animatietaken of opgegeven time-out is verstreken.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| device | IDevice | Het uitvoerapparaat. |
| timeout | TimeSpan | ATimeSpan dat staat voor het aantal milliseconden dat moet worden gewacht, of aTimeSpan dat staat voor -1 milliseconde om voor onbepaalde tijd te wachten. |
| documents | Stream[] | De te renderen documenten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* naamruimte [Aspose.Html.Rendering](../../epubrenderer/)
* montage [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rendert EPub-document in opgegeven[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| device | IDevice | Het apparaat. |
| document | Stream | Het document. |
| configuration | Configuration | De configuratie. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* naamruimte [Aspose.Html.Rendering](../../epubrenderer/)
* montage [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rendert EPub-document in opgegeven[`IDevice`](../../idevice/) . De weergave wordt uitgevoerd zodra er geen netwerkbewerkingen zijn voor het laden van bronnen, actieve timers, animatietaken of opgegeven time-out is verstreken.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| device | IDevice | Het apparaat. |
| document | Stream | Het document. |
| configuration | Configuration | De configuratie. |
| timeout | TimeSpan | ATimeSpan dat staat voor het aantal milliseconden dat moet worden gewacht, of aTimeSpan dat staat voor -1 milliseconde om voor onbepaalde tijd te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* naamruimte [Aspose.Html.Rendering](../../epubrenderer/)
* montage [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rendert meerdere EPub-documenten in gespecificeerd[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| device | IDevice | Het apparaat. |
| documents | IList`1 | DeIList van documenten om weer te geven. |
| configuration | Configuration | De configuratie. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* naamruimte [Aspose.Html.Rendering](../../epubrenderer/)
* montage [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rendert meerdere EPub-documenten in gespecificeerd[`IDevice`](../../idevice/) . De weergave wordt uitgevoerd zodra er geen netwerkbewerkingen zijn voor het laden van bronnen, actieve timers, animatietaken of opgegeven time-out is verstreken.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| device | IDevice | Het apparaat. |
| documents | IList`1 | DeIList van documenten om weer te geven. |
| configuration | Configuration | De configuratie. |
| timeout | TimeSpan | ATimeSpan dat staat voor het aantal milliseconden dat moet worden gewacht, of aTimeSpan dat staat voor -1 milliseconde om voor onbepaalde tijd te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* naamruimte [Aspose.Html.Rendering](../../epubrenderer/)
* montage [Aspose.HTML](../../../)


