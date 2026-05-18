---
title: "PageLayoutOptions Enum"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.PageLayoutOptions enum. Spécifie les drapeaux qui, avec d'autres options PageSetup, déterminent les tailles et les mises en page des pages. Ces drapeaux peuvent être combinés selon leurs descriptions."
type: docs

url: /fr/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Spécifie les indicateurs qui, avec d'autres options PageSetup, déterminent les tailles et la disposition des pages. Ces indicateurs peuvent être combinés selon leurs descriptions.

```java
[Flags]
public enum PageLayoutOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Valeur par défaut indiquant que les PageLayoutOptions n'affecteront pas les tailles et les mises en page des pages. |
| FitToContentWidth | `1` | Ce drapeau indique que la largeur des pages est déterminée à partir de la taille du contenu elle‑même, et non de la largeur de page spécifiée. La largeur du contenu est calculée individuellement pour chaque page. |
| UseWidestPage | `2` | Lorsqu'il est combiné avec FitToContentWidth, il indique que la largeur de chaque page sera identique et égale à la plus grande taille de contenu parmi toutes les pages. |
| FitToWidestContentWidth | `3` | Ce drapeau indique que la largeur de la page est déterminée à partir de la taille du contenu elle‑même, et non de la largeur de page spécifiée. La largeur de chaque page sera identique et égale à la plus grande taille de contenu parmi toutes les pages. |
| FitToContentHeight | `10` | Ce drapeau indique que la hauteur de la page est déterminée à partir de la taille du contenu elle‑même, et non de la hauteur de page spécifiée. Tout le contenu du document sera placé sur une seule page si ce drapeau est spécifié. |
| ScaleToPageWidth | `100` | Ce drapeau indique que le contenu du document sera mis à l’échelle pour s’adapter à la page où la différence entre la largeur de page disponible et le contenu qui se chevauche est la plus grande. Il entre en conflit avec le drapeau FitToContentWidth et, si les deux drapeaux sont spécifiés, seul ScaleToPageWidth sera appliqué. |
| ScaleToPageHeight | `1000` | Ce drapeau indique que le contenu du document sera mis à l’échelle pour s’adapter à la hauteur de la première page. Il entre en conflit avec le drapeau FitToContentHeight et, si les deux drapeaux sont spécifiés, seul ScaleToPageHeight sera appliqué. Tout le contenu du document sera placé uniquement sur une seule page. |

### Voir aussi

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
