---
title: HtmlRenderer.Render
second_title: Aspose.HTML für .NET-API-Referenz
description: HtmlRenderer methode. Definiert Methode zum Rendern mehrererDocument s in spezifischIDevice . Das Rendern wird durchgeführt sobald keine Netzwerkoperationen zum Laden von Ressourcen aktive Timer Animationsaufgaben oder das angegebene Timeout verstrichen sind.
type: docs
weight: 20
url: /de/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Definiert Methode zum Rendern mehrerer[`Document`](../../../aspose.html.dom/document/) s in spezifisch[`IDevice`](../../idevice/) . Das Rendern wird durchgeführt, sobald keine Netzwerkoperationen zum Laden von Ressourcen, aktive Timer, Animationsaufgaben oder das angegebene Timeout verstrichen sind.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | ATimeSpan die die Anzahl der zu wartenden Millisekunden darstellt, oder aTimeSpan das entspricht -1 Millisekunde, um auf unbestimmte Zeit zu warten. |
| documents | Document[] | Die zu rendernden Dokumente. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* namensraum [Aspose.Html.Rendering](../../htmlrenderer/)
* Montage [Aspose.HTML](../../../)


