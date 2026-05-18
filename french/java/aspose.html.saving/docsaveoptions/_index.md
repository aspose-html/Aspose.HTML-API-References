---
title: "Classe DocSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.saving.DocSaveOptions. Classe de données d'options spécifiques. En assignant des propriétés, vous pouvez gérer les caractéristiques de rendu telles que la résolution, la taille de page, la couleur d'arrière-plan ainsi que les options spécifiques au document comme l'incorporation de polices. Plus d'informations dans l'article de documentation."
type: docs

url: /fr/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Classe de données d'options spécifiques. En assignant des propriétés, vous pouvez gérer les caractéristiques de rendu telles que la résolution, la taille de la page, la couleur d'arrière-plan ainsi que les options spécifiques au document comme l'incorporation des polices. Plus d'informations dans la documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtient un objet [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) qui est utilisé pour la configuration du traitement des propriétés CSS. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Définit ou obtient la résolution horizontale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtient un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Définit ou obtient la résolution verticale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |

## Remarques

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Préparez un chemin vers un fichier HTML source
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Préparez un chemin pour l'enregistrement du fichier converti
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialisez un document HTML à partir du fichier
      using var document = new HTMLDocument(documentPath);

      // Initialisez DocSaveOptions. Configurez la taille de page à 600x400 pixels et les marges
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Convertir HTML en DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Voir aussi

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
