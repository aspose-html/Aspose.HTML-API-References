---
title: SvgRenderer.Render
second_title: Aspose.HTML für .NET-API-Referenz
description: SvgRenderer methode. Definiert Methode zum Rendern mehrererSVGDocument s in spezifischIDevice . Das Rendern wird durchgeführt sobald keine Netzwerkoperationen zum Laden von Ressourcen aktive Timer Animationsaufgaben oder das angegebene Timeout verstrichen sind.
type: docs
weight: 20
url: /de/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Definiert Methode zum Rendern mehrerer[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/) s in spezifisch[`IDevice`](../../idevice/) . Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben oder das angegebene Timeout verstrichen sind.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | ATimeSpan die die Anzahl der zu wartenden Millisekunden darstellt, oder aTimeSpan das entspricht -1 Millisekunde, um auf unbestimmte Zeit zu warten. |
| documents | SVGDocument[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* namensraum [Aspose.Html.Rendering](../../svgrenderer/)
* Montage [Aspose.HTML](../../../)


