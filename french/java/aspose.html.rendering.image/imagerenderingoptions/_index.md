---
title: "Classe ImageRenderingOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.rendering.image.ImageRenderingOptions. Représente les options de rendu pour ImageDevice. Ces options sont utilisées pour spécifier le format d'image de sortie, la compression, la résolution, etc."
type: docs

url: /fr/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Représente les options de rendu pour [`ImageDevice`](../imagedevice/). Ces options sont utilisées pour spécifier le format d'image de sortie, la compression, la résolution, etc.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initialise une nouvelle instance de la classe `ImageRenderingOptions` ; le format PNG sera utilisé comme format d'image par défaut. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Initialise une nouvelle instance de la classe `ImageRenderingOptions` avec le format d'image spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtient un objet [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) qui est utilisé pour la configuration du traitement des propriétés CSS. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Définit ou obtient la résolution horizontale pour les images de sortie et internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtient un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Obtient un objet [`TextOptions`](../textoptions/) qui est utilisé pour la configuration du rendu du texte. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Définit ou obtient la résolution verticale pour les images de sortie et internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |

### Voir aussi

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
