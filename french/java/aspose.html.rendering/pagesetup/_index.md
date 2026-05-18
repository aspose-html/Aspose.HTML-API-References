---
title: "PageSetup Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.rendering.PageSetup classe. Représente un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages"
type: docs

url: /fr/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

Représente un objet de configuration de page utilisé pour configurer la sortie du jeu de pages.

```java
public class PageSetup
```

## Propriétés

| Nom | Description |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) Obtient la configuration de la page impaire. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) Obtient la configuration de la page paire. |

## Méthodes

| Nom | Description |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Définit la configuration de la page Gauche/Droite. |

### Voir aussi

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
