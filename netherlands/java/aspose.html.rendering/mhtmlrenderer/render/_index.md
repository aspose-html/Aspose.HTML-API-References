---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML voor Java API-referentie"
description: "MhtmlRenderer-methode. Rendert meerdere MHTML-documenten naar een gespecificeerd IDevice. Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of de opgegeven time-out is verstreken"
type: docs

url: /nl/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Rendert meerdere MHTML-documenten naar een gespecificeerd [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of de opgegeven time-out is verstreken.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het apparaat. |
| time-out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |
| documenten | Stream[] | De documenten om weer te geven. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definieert een methode voor het renderen van meerdere MHTML-documenten naar een specifieke [`IDevice`](../../idevice/), met behulp van een annulerings‑token om annulering van de bewerking aan te vragen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| cancellationToken | CancellationToken | Een CancellationToken om te observeren terwijl men wacht tot de taak voltooid is. |
| sources | Stream[] | De MHTML-documenten om weer te geven. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rendert MHTML-document naar het opgegeven [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het apparaat. |
| document | Stream | Het document. |
| configuratie | Configuratie | De configuratie. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rendert MHTML-document naar het opgegeven [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of wanneer de opgegeven time‑out is verstreken.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het apparaat. |
| document | Stream | Het document. |
| configuratie | Configuratie | De configuratie. |
| time-out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rendert meerdere MHTML-documenten naar het opgegeven [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het apparaat. |
| documenten | IList`1 | De IList met documenten om weer te geven. |
| configuratie | Configuratie | De configuratie. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rendert meerdere MHTML-documenten naar een gespecificeerd [`IDevice`](../../idevice/). Het renderen wordt uitgevoerd zodra er geen netwerkbewerkingen meer zijn voor het laden van bronnen, actieve timers, animatietaken of de opgegeven time-out is verstreken.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het apparaat. |
| documenten | IList`1 | De IList met documenten om weer te geven. |
| configuratie | Configuratie | De configuratie. |
| time-out | TimeSpan | Een TimeSpan die het aantal milliseconden aangeeft om te wachten, of een TimeSpan die -1 milliseconde aangeeft om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
