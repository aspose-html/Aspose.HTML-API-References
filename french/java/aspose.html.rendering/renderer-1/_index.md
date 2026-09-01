---
title: "RendererTSource Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.Renderer1TSource classe. Représente une classe abstraite pour tous les rendus"
type: docs

url: /fr/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Représente une classe abstraite pour tous les moteurs de rendu.

```java
public abstract class Renderer<TSource> : Renderer
```

| Paramètre | Description |
| --- | --- |
| TDocument | Le type du document. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Définit la méthode de rendu du !:TDocument vers le [`IDevice`](../idevice/) spécifié. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Définit la méthode de rendu du !:TDocument vers le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Définit la méthode de rendu du !:TDocument vers le [`IDevice`](../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé. |

### Voir aussi

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
