---
title: EpubRenderer.Render
second_title: Aspose.HTML per riferimento API .NET
description: EpubRenderer metodo. Definisce il metodo per il rendering di più EPubStream s in specificoIDevice . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse timer attivi attività di animazione o timeout specificato.
type: docs
weight: 20
url: /it/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Definisce il metodo per il rendering di più EPubStream s in specifico[`IDevice`](../../idevice/) . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o timeout specificato.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo di uscita. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| documents | Stream[] | I documenti da rendere. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../epubrenderer/)
* assemblea [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Visualizza il documento EPub nello specifico[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo. |
| document | Stream | Il documento. |
| configuration | Configuration | La configurazione. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../epubrenderer/)
* assemblea [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Visualizza il documento EPub nello specifico[`IDevice`](../../idevice/) . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o timeout specificato.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo. |
| document | Stream | Il documento. |
| configuration | Configuration | La configurazione. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../epubrenderer/)
* assemblea [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Renderizza più documenti EPub in uno specificato[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo. |
| documents | IList`1 | ILIList di documenti da rendere. |
| configuration | Configuration | La configurazione. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../epubrenderer/)
* assemblea [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renderizza più documenti EPub in uno specificato[`IDevice`](../../idevice/) . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o timeout specificato.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo. |
| documents | IList`1 | ILIList di documenti da rendere. |
| configuration | Configuration | La configurazione. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../epubrenderer/)
* assemblea [Aspose.HTML](../../../)


