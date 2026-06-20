---
title: "SvgRenderer.Render"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SvgRenderer. Définit une méthode pour rendre plusieurs SVGDocuments dans un IDevice spécifique. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé."
type: docs

url: /fr/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Définit une méthode pour rendre plusieurs [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s dans un [`IDevice`](../../idevice/) spécifique. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |
| documents | SVGDocument[] | Les documents à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Définit une méthode pour rendre plusieurs [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s dans un [`IDevice`](../../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| cancellationToken | CancellationToken | Un jeton d'annulation à observer pendant l'attente de l'achèvement de la tâche. |
| sources | SVGDocument[] | Les documents SVG à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
