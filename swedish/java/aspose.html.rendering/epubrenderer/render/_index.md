---
title: "EpubRenderer.Render"
second_title: "Aspose.HTML för Java API-referens"
description: "EpubRenderer-metoden. Definierar en metod för att rendera flera EPub-strömmar till en specifik IDevice. Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut."
type: docs

url: /sv/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Definierar en metod för att rendera flera EPub-strömmar till en specifik [`IDevice`](../../idevice/). Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |
| dokument | Stream[] | Dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definierar en metod för att rendera flera EPub-dokument till en specifik [`IDevice`](../../idevice/), med hjälp av en avbokningstoken för att begära avbrytning av operationen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| cancellationToken | CancellationToken | En CancellationToken att observera medan du väntar på att uppgiften ska slutföras. |
| källor | Stream[] | EPub-dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Renderar EPub-dokumentet till den angivna [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Enheten. |
| dokument | Stream | Dokumentet. |
| konfiguration | Konfiguration | Konfigurationen. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Renderar EPub-dokumentet till den angivna [`IDevice`](../../idevice/). Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Enheten. |
| dokument | Stream | Dokumentet. |
| konfiguration | Konfiguration | Konfigurationen. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Renderar flera EPub-dokument till den angivna [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Enheten. |
| dokument | IList`1 | IList med dokument som ska renderas. |
| konfiguration | Konfiguration | Konfigurationen. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renderar flera EPub-dokument till den angivna [`IDevice`](../../idevice/). Rendering kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Enheten. |
| dokument | IList`1 | IList med dokument som ska renderas. |
| konfiguration | Konfiguration | Konfigurationen. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
