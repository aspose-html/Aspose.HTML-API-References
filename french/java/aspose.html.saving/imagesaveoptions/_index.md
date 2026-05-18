---
title: "Classe ImageSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.saving.ImageSaveOptions. Classe de données d'options spécifiques. Elle fournit des propriétés pour gérer la résolution, le lissage, la qualité, le format du résultat d'image ainsi que les paramètres de page, etc. Vous pouvez obtenir plus d'informations dans l'article de documentation."
type: docs

url: /fr/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Classe de données d'options spécifiques. Elle fournit des propriétés pour gérer la résolution du résultat image, la qualité de lissage, le format ainsi que les paramètres de page, etc. Vous pouvez obtenir plus d'informations dans la documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initialise une nouvelle instance de la classe `ImageSaveOptions` ; Png sera utilisé comme format d'image par défaut. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Format d'image [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) basé sur l'initialisation |

## Propriétés

| Nom | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtient un objet [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) qui est utilisé pour la configuration du traitement des propriétés CSS. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Définit ou obtient la résolution horizontale pour les images de sortie et internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtient un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Obtient un objet [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) qui est utilisé pour la configuration du rendu du texte. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Définit ou obtient la résolution verticale pour les images de sortie et internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |

## Remarques

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Préparez un chemin vers un fichier HTML source
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Préparez un chemin pour l'enregistrement du fichier converti
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialisez un document HTML à partir du fichier
      using var document = new HTMLDocument(documentPath);

      // Initialisez ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Convertir HTML en PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Voir aussi

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
