---
title: SvgRenderer.Render
second_title: Aspose.HTML per riferimento API .NET
description: SvgRenderer metodo. Definisce il metodo per il rendering multiploSVGDocument s in specificoIDevice . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse timer attivi attività di animazione o timeout specificato.
type: docs
weight: 20
url: /it/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Definisce il metodo per il rendering multiplo[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/) s in specifico[`IDevice`](../../idevice/) . Il rendering verrà eseguito una volta che non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o timeout specificato.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo di uscita. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo per attendere indefinitamente. |
| documents | SVGDocument[] | I documenti da rendere. |

### Guarda anche

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* spazio dei nomi [Aspose.Html.Rendering](../../svgrenderer/)
* assemblea [Aspose.HTML](../../../)


