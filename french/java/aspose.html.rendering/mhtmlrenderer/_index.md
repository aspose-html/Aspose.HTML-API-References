---
title: "MhtmlRenderer Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.MhtmlRenderer classe. Représente un moteur de rendu de document MHTML"
type: docs

url: /fr/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Représente un moteur de rendu de document MHTML.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Définit une méthode de rendu de plusieurs documents MHTML vers un [`IDevice`](../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Rend plusieurs documents MHTML vers le [`IDevice`](../idevice/) spécifié. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | Rend le document MHTML vers le [`IDevice`](../idevice/) spécifié. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Rend plusieurs documents MHTML vers le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié sera écoulé. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Rend plusieurs documents MHTML vers le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié sera écoulé. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Rend le document MHTML vers le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié sera écoulé. |

### Voir aussi

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
