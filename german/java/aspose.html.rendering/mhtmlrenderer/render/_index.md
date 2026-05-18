---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML für Java API-Referenz"
description: "MhtmlRenderer‑Methode. Rendert mehrere MHTML‑Dokumente in ein angegebenes IDevice. Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist."
type: docs

url: /de/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Rendert mehrere MHTML‑Dokumente in ein angegebenes [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Gerät. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |
| Dokumente | Stream[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definiert eine Methode zum Rendern mehrerer MHTML-Dokumente in ein bestimmtes [`IDevice`](../../idevice/), wobei ein Cancellation-Token verwendet wird, um den Vorgang abzubrechen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein CancellationToken, das während des Wartens auf den Abschluss der Aufgabe beobachtet werden soll. |
| Quellen | Stream[] | Die zu rendernden MHTML-Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rendert das MHTML-Dokument in das angegebene [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Gerät. |
| Dokument | Stream | Das Dokument. |
| Konfiguration | Konfiguration | Die Konfiguration. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rendert das MHTML-Dokument in das angegebene [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr vorhanden sind oder die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Gerät. |
| Dokument | Stream | Das Dokument. |
| Konfiguration | Konfiguration | Die Konfiguration. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rendert mehrere MHTML-Dokumente in das angegebene [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Gerät. |
| Dokumente | IList`1 | Die IList der zu rendernden Dokumente. |
| Konfiguration | Konfiguration | Die Konfiguration. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rendert mehrere MHTML‑Dokumente in ein angegebenes [`IDevice`](../../idevice/). Das Rendering wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Gerät. |
| Dokumente | IList`1 | Die IList der zu rendernden Dokumente. |
| Konfiguration | Konfiguration | Die Konfiguration. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
