---
title: "Classe SvgRenderer"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.rendering.SvgRenderer. Représente le moteur de rendu de documents SVG."
type: docs

url: /fr/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

Représente un moteur de rendu de document SVG.

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | Définit une méthode pour le rendu de plusieurs [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s dans un [`IDevice`](../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | Définit une méthode pour le rendu de plusieurs [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s dans un [`IDevice`](../idevice/) spécifique. Le rendu sera effectué une fois qu'aucune opération réseau de chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié ne sera écoulé. |

### Voir aussi

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
