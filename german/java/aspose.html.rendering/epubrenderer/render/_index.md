---
title: "EpubRenderer.Render"
second_title: "Aspose.HTML für Java API-Referenz"
description: "EpubRenderer-Methode. Definiert eine Methode zum Rendern mehrerer EPub-Streams in ein bestimmtes IDevice. Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben mehr laufen oder die angegebene Zeitüberschreitung abgelaufen ist."
type: docs

url: /de/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Definiert eine Methode zum Rendern mehrerer EPub-Streams in ein bestimmtes [`IDevice`](../../idevice/). Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer oder Animationsaufgaben mehr laufen und die angegebene Zeitüberschreitung abgelaufen ist.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | Ein TimeSpan, das die Anzahl der Millisekunden angibt, die gewartet werden soll, oder ein TimeSpan, das -1 Millisekunde für unbegrenztes Warten darstellt. |
| Dokumente | Stream[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definiert eine Methode zum Rendern mehrerer EPub-Dokumente in ein bestimmtes [`IDevice`](../../idevice/), wobei ein Cancellation-Token verwendet wird, um die Operation abzubrechen.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gerät | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein CancellationToken, das während des Wartens auf den Abschluss der Aufgabe beobachtet werden soll. |
| Quellen | Stream[] | Die zu rendernden EPub-Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rendert EPub-Dokument in das angegebene [`IDevice`](../../idevice/).

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rendert EPub-Dokument in das angegebene [`IDevice`](../../idevice/). Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer oder Animationsaufgaben mehr laufen und die angegebene Zeitüberschreitung abgelaufen ist.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rendert mehrere EPub-Dokumente in das angegebene [`IDevice`](../../idevice/).

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rendert mehrere EPub-Dokumente in das angegebene [`IDevice`](../../idevice/). Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer oder Animationsaufgaben mehr laufen und die angegebene Zeitüberschreitung abgelaufen ist.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
