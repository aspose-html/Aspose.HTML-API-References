---
title: HtmlRenderer.Render
second_title: Aspose.HTML per riferimento API .NET
description: HtmlRenderer metodo. Definisce il metodo per il rendering multiploDocument s in specificoIDevice . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse timer attivi attività di animazione o timeout specificato.
type: docs
weight: 20
url: /it/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Definisce il metodo per il rendering multiplo[`Document`](../../../aspose.html.dom/document/) s in specifico[`IDevice`](../../idevice/) . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o timeout specificato.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo di uscita. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| documents | Document[] | I documenti da rendere. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../htmlrenderer/)
* assemblea [Aspose.HTML](../../../)


