---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo MhtmlRenderer. Renderizza più documenti MHTML nel IDevice specificato. Il rendering verrà eseguito una volta che non vi sono operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato è trascorso."
type: docs

url: /it/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Renderizza più documenti MHTML nel [`IDevice`](../../idevice/) specificato. Il rendering verrà eseguito una volta che non vi sono operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato è trascorso.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| documenti | Stream[] | I documenti da rendere. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Definisce un metodo per il rendering di più documenti MHTML in un specifico [`IDevice`](../../idevice/), utilizzando un token di cancellazione per richiedere l'annullamento dell'operazione.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo di output. |
| cancellationToken | CancellationToken | Un CancellationToken da osservare mentre si attende il completamento dell'operazione. |
| fonti | Stream[] | I documenti MHTML da rendere. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Esegue il rendering del documento MHTML nel [`IDevice`](../../idevice/) specificato.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo. |
| documento | Stream | Il documento. |
| configurazione | Configurazione | La configurazione. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Esegue il rendering del documento MHTML nel [`IDevice`](../../idevice/) specificato. Il rendering verrà eseguito una volta che non vi siano operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o sia trascorso il timeout specificato.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo. |
| documento | Stream | Il documento. |
| configurazione | Configurazione | La configurazione. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Esegue il rendering di più documenti MHTML nel [`IDevice`](../../idevice/) specificato.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo. |
| documenti | IList`1 | L'IList dei documenti da rendere. |
| configurazione | Configurazione | La configurazione. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renderizza più documenti MHTML nel [`IDevice`](../../idevice/) specificato. Il rendering verrà eseguito una volta che non vi sono operazioni di rete per il caricamento delle risorse, timer attivi, attività di animazione o il timeout specificato è trascorso.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dispositivo | IDevice | Il dispositivo. |
| documenti | IList`1 | L'IList dei documenti da rendere. |
| configurazione | Configurazione | La configurazione. |
| timeout | TimeSpan | Un TimeSpan che rappresenta il numero di millisecondi da attendere, oppure un TimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |

### Vedi anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
