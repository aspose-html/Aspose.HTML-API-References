---
title: "Classe EpubRenderer"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.EpubRenderer classe. Représente un moteur de rendu de document EPub"
type: docs

url: /fr/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Représente un moteur de rendu de document EPub.

```java
public class EpubRenderer : Renderer<Stream>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Définit une méthode pour rendre plusieurs documents EPub dans un [`IDevice`](../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Rend plusieurs documents EPub dans le [`IDevice`](../idevice/) spécifié. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Rend le document EPub dans le [`IDevice`](../idevice/) spécifié. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Définit une méthode pour rendre plusieurs flux EPub dans un [`IDevice`](../idevice/) spécifique. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour charger les ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Rend plusieurs documents EPub dans le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour charger les ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Rend le document EPub dans le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour charger les ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé. |

### Voir aussi

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
