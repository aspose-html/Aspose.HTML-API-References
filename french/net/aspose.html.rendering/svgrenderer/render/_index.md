---
title: SvgRenderer.Render
second_title: Référence de l'API Aspose.HTML pour .NET
description: SvgRenderer méthode. Définit la méthode de rendu de plusieursSVGDocument s en spécifiqueIDevice . Le rendu sera effectué une fois quil ny aura plus dopérations réseau pour charger des ressources des minuteries actives des tâches danimation ou un délai dattente spécifié écoulé.
type: docs
weight: 20
url: /fr/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Définit la méthode de rendu de plusieurs[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/) s en spécifique[`IDevice`](../../idevice/) . Le rendu sera effectué une fois qu'il n'y aura plus d'opérations réseau pour charger des ressources, des minuteries actives, des tâches d'animation ou un délai d'attente spécifié écoulé.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le périphérique de sortie. |
| timeout | TimeSpan | UNTimeSpan qui représente le nombre de millisecondes à attendre, ou unTimeSpan cela représente -1 milliseconde à attendre indéfiniment. |
| documents | SVGDocument[] | Les documents à rendre. |

### Voir également

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../svgrenderer/)
* Assemblée [Aspose.HTML](../../../)


