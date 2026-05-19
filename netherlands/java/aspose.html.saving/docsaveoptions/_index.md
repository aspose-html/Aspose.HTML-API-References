---
title: "DocSaveOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.DocSaveOptions class. Specifieke opties gegevensklasse. Door eigenschappen toe te wijzen kun je renderkenmerken beheren, zoals resolutie, paginagrootte, achtergrondkleur, evenals documentspecifieke opties zoals lettertype-embedden. Meer info zie in het documentatie‑artikel"
type: docs

url: /nl/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Specifieke opties dataklasse. Door eigenschappen toe te wijzen kun je weergavekenmerken beheren, zoals resolutie, paginagrootte, achtergrondkleur, evenals documentspecifieke opties zoals het insluiten van lettertypen. Meer info zie in de documentatie [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Haalt een [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS‑eigenschappen. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Stelt de horizontale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de uitvoer‑pagina‑set. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Stelt de verticale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

## Opmerkingen

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Bereid een pad voor naar een bron‑HTML‑bestand
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Bereid een pad voor om het geconverteerde bestand op te slaan 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialiseer een HTML‑document vanuit het bestand
      using var document = new HTMLDocument(documentPath);

      // Initialiseer DocSaveOptions. Stel de paginagrootte in op 600x400 pixels en de marges
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // HTML naar DOCX converteren
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Zie ook

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
