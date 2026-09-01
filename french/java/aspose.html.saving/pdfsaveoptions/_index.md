---
title: "Classe PdfSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.saving.PdfSaveOptions. Cette classe de données spécifique fournit quelques propriétés pour gérer le résultat de la conversion. Par exemple, PageSetup spécifie les caractéristiques de la page. Consultez l'article de documentation."
type: docs

url: /fr/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Une classe de données spécifique fournit quelques propriétés pour gérer le résultat de la conversion. Par exemple, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) spécifie les caractéristiques de la page. Consultez la documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtient un objet [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) qui est utilisé pour la configuration du traitement des propriétés CSS. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Contient des informations sur le document PDF de sortie. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Définit ou obtient la résolution horizontale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtient un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Définit ou obtient la résolution verticale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |

## Remarques

Vous pouvez trouver des exemples complets et des fichiers de données sur [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Préparez un chemin vers un fichier HTML source
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Préparez un chemin pour l'enregistrement du fichier converti
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initialisez un document HTML à partir du fichier
      using var document = new HTMLDocument(documentPath);

      // Initialisez PdfSaveOptions. Définissez la taille de page à 600x300 pixels, les marges, 
      // les résolutions et changez la couleur d'arrière-plan en AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Convertir HTML en PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Voir aussi

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
