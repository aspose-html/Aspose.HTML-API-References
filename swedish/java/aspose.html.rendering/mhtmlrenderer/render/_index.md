---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML för Java API-referens"
description: "MhtmlRenderer-metod. Renderar flera MHTML-dokument till angivet IDevice. Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna tidsgränsen har löpt ut"
type: docs

url: /sv/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Renderar flera MHTML-dokument till angivet [`IDevice`](../../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna tidsgränsen har löpt ut.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Enheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta obegränsat. |
| dokument | Stream[] | Dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definierar en metod för att rendera flera MHTML-dokument till en specifik [`IDevice`](../../idevice/), med en avbokningstoken för att begära avbrytning av operationen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enhet | IDevice | Utmatningsenheten. |
| cancellationToken | CancellationToken | En CancellationToken att observera medan du väntar på att uppgiften ska slutföras. |
| källor | Stream[] | MHTML-dokumenten som ska renderas. |

### Se även

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Renderar MHTML-dokument till angiven [`IDevice`](../../idevice/).

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Renderar MHTML-dokument till angiven [`IDevice`](../../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animeringsuppgifter eller när den angivna tidsgränsen har löpt ut.

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Renderar flera MHTML-dokument till angiven [`IDevice`](../../idevice/).

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renderar flera MHTML-dokument till angivet [`IDevice`](../../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna tidsgränsen har löpt ut.

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
