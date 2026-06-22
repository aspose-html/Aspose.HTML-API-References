---
title: "ImageSaveOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.ImageSaveOptions klasse. Specifieke opties‑gegevensklasse. Deze biedt eigenschappen om de resolutie, gladstrijken, kwaliteit, formaat van het afbeeldingsresultaat evenals paginainstellingen enzovoort te beheren. Meer informatie kunt u vinden in het documentatie‑artikel."
type: docs

url: /nl/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Specifieke optiedataklasse. Het biedt eigenschappen om de resolutie van het afbeeldingsresultaat, de gladheidskwaliteit, het formaat en paginainstellingen enzovoort te beheren. Meer info kun je vinden in de documentatie [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initialiseert een nieuw exemplaar van de `ImageSaveOptions` klasse; Png wordt gebruikt als standaard afbeeldingsformaat. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Afbeeldingsformaat [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) gebaseerd op initialisatie |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Haalt een [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS‑eigenschappen. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Stelt de horizontale resolutie in of haalt deze op voor uitvoer- en interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de uitvoer‑pagina‑set. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Haalt een [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) object op dat wordt gebruikt voor de configuratie van tekstweergave. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Stelt de verticale resolutie in of haalt deze op voor uitvoer- en interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

## Opmerkingen

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Bereid een pad voor naar een bron‑HTML‑bestand
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Bereid een pad voor voor het opslaan van het geconverteerde bestand 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialiseer een HTML‑document vanuit het bestand
      using var document = new HTMLDocument(documentPath);

      // Initialiseer ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Converteer HTML naar PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Zie ook

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
