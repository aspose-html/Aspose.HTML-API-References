---
title: EpubRenderer.Render
second_title: Aspose.HTML für .NET-API-Referenz
description: EpubRenderer methode. Definiert Methode zum Rendern mehrerer EPubsStream s in spezifischIDevice . Das Rendern wird durchgeführt sobald keine Netzwerkoperationen zum Laden von Ressourcen aktive Timer Animationsaufgaben oder das angegebene Timeout verstrichen sind.
type: docs
weight: 20
url: /de/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Definiert Methode zum Rendern mehrerer EPubsStream s in spezifisch[`IDevice`](../../idevice/) . Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben oder das angegebene Timeout verstrichen sind.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | ATimeSpan die die Anzahl der zu wartenden Millisekunden darstellt, oder aTimeSpan das entspricht -1 Millisekunde, um auf unbestimmte Zeit zu warten. |
| documents | Stream[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* namensraum [Aspose.Html.Rendering](../../epubrenderer/)
* Montage [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rendert das EPub-Dokument in das angegebene[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Gerät. |
| document | Stream | Das Dokument. |
| configuration | Configuration | Die Konfiguration. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namensraum [Aspose.Html.Rendering](../../epubrenderer/)
* Montage [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rendert das EPub-Dokument in das angegebene[`IDevice`](../../idevice/) . Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben oder das angegebene Timeout verstrichen sind.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Gerät. |
| document | Stream | Das Dokument. |
| configuration | Configuration | Die Konfiguration. |
| timeout | TimeSpan | ATimeSpan die die Anzahl der zu wartenden Millisekunden darstellt, oder aTimeSpan das entspricht -1 Millisekunde, um auf unbestimmte Zeit zu warten. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namensraum [Aspose.Html.Rendering](../../epubrenderer/)
* Montage [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rendert mehrere EPub-Dokumente in angegeben[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Gerät. |
| documents | IList`1 | DerIList von Dokumenten zu rendern. |
| configuration | Configuration | Die Konfiguration. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namensraum [Aspose.Html.Rendering](../../epubrenderer/)
* Montage [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rendert mehrere EPub-Dokumente in angegeben[`IDevice`](../../idevice/) . Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben oder das angegebene Timeout verstrichen sind.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Gerät. |
| documents | IList`1 | DerIList von Dokumenten zu rendern. |
| configuration | Configuration | Die Konfiguration. |
| timeout | TimeSpan | ATimeSpan die die Anzahl der zu wartenden Millisekunden darstellt, oder aTimeSpan das entspricht -1 Millisekunde, um auf unbestimmte Zeit zu warten. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namensraum [Aspose.Html.Rendering](../../epubrenderer/)
* Montage [Aspose.HTML](../../../)


