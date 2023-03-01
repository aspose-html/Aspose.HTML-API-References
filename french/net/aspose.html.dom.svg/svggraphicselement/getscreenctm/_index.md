---
title: SVGGraphicsElement.GetScreenCTM
second_title: Référence de l'API Aspose.HTML pour .NET
description: SVGGraphicsElement méthode. Renvoie la matrice de transformation à partir des unités utilisateur actuelles cestàdire après application de lattribut transform sil y en a à lavis de lagent utilisateur parent dun pixel. Pour les appareils daffichage cela représente idéalement un pixel décran physique. Pour les autres appareils ou environnements où les tailles de pixels physiques ne sont pas connues un algorithme similaire à la définition CSS2 dun pixel peut être utilisé à la place. Notez que null est renvoyé si cet élément nest pas accroché à larborescence du document. Cette méthode aurait été plus justement nommée getClientCTM mais le nom getScreenCTM est conservé pour des raisons historiques.
type: docs
weight: 90
url: /fr/net/aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Renvoie la matrice de transformation à partir des unités utilisateur actuelles (c'est-à-dire après application de l'attribut 'transform', s'il y en a) à l'avis de l'agent utilisateur parent d'un "pixel". Pour les appareils d'affichage, cela représente idéalement un pixel d'écran physique. Pour les autres appareils ou environnements où les tailles de pixels physiques ne sont pas connues, un algorithme similaire à la définition CSS2 d'un "pixel" peut être utilisé à la place. Notez que null est renvoyé si cet élément n'est pas accroché à l'arborescence du document. Cette méthode aurait été plus justement nommée getClientCTM, mais le nom getScreenCTM est conservé pour des raisons historiques.

```csharp
public SVGMatrix GetScreenCTM()
```

### Return_Value

Un objet SVGMatrix qui définit la matrice de transformation donnée.

### Voir également

* class [SVGMatrix](../../../aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* espace de noms [Aspose.Html.Dom.Svg](../../svggraphicselement/)
* Assemblée [Aspose.HTML](../../../)


