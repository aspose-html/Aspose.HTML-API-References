---
title: Enum PageLayoutOptions
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Rendering.PageLayoutOptions énumération. Spécifie les drapeaux qui avec dautres options de PageSetup déterminent les tailles et les mises en page des pages. Ces drapeaux peuvent être combinés en fonction de leurs descriptions.
type: docs
weight: 4380
url: /fr/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Spécifie les drapeaux qui, avec d'autres options de PageSetup, déterminent les tailles et les mises en page des pages. Ces drapeaux peuvent être combinés en fonction de leurs descriptions.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Valeur par défaut qui indique que les PageLayoutOptions n'affecteront pas les tailles et les mises en page des pages. |
| FitToContentWidth | `1` | Cet indicateur indique que la largeur des pages est déterminée à partir de la taille du contenu lui-même, et non à partir de la largeur de page spécifiée. La largeur du contenu est calculée individuellement pour chaque page. |
| UseWidestPage | `2` | Lorsqu'il est combiné avecFitToContentWidth indique que la largeur de chaque page sera la même et sera égale à la taille de contenu la plus large parmi toutes les pages. |
| FitToWidestContentWidth | `3` | Cet indicateur indique que la largeur de la page est déterminée à partir de la taille du contenu lui-même, et non à partir de la largeur de page spécifiée. La largeur de chaque page sera la même et sera égale à la taille de contenu la plus large parmi toutes les pages. |
| FitToContentHeight | `10` | Cet indicateur indique que la hauteur de la page est déterminée à partir de la taille du contenu lui-même, et non à partir de la hauteur de page spécifiée. Tout le contenu des documents sera situé sur une seule page si cet indicateur est spécifié. |
| ScaleToPageWidth | `100` | Cet indicateur indique que le contenu du document sera mis à l'échelle pour s'adapter à la page où la différence entre la largeur de page disponible et le contenu qui se chevauche est la plus grande. Il entre en collision avecFitToContentWidth flag et si les deux flags sont spécifiés uniquementScaleToPageWidth prendra effet. |
| ScaleToPageHeight | `1000` | Cet indicateur indique que le contenu du document sera mis à l'échelle pour s'adapter à la hauteur de la première page. Il entre en collision avecFitToContentHeight flag et si les deux flags sont spécifiés uniquementScaleToPageHeight prendra effet. Tout le contenu du document sera placé sur une seule page uniquement. |

### Voir également

* espace de noms [Aspose.Html.Rendering](../../aspose.html.rendering/)
* Assemblée [Aspose.HTML](../../)


