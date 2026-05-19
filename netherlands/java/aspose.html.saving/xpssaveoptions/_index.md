---
title: "XpsSaveOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.XpsSaveOptions class. Specifieke opties gegevensklasse biedt enkele eigenschappen om het conversieresultaat te beheren. Bijvoorbeeld PageSetup specificeert paginakarakteristieken. Zie het documentatie‑artikel"
type: docs

url: /nl/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Specifieke opties gegevensklasse biedt enkele eigenschappen om het conversieresultaat te beheren. Bijvoorbeeld [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specificeert paginakarakteristieken. Zie de documentatie [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Haalt een [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS‑eigenschappen. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Stelt de horizontale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de uitvoer‑pagina‑set. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Stelt de verticale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

## Opmerkingen

Je kunt volledige voorbeelden en gegevensbestanden vinden op [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Bereid HTML‑code voor en sla deze op in een bestand
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialiseer een HTML‑document vanuit het html‑bestand
      using var document = new HTMLDocument(documentPath);
       
      // Stel de paginagrootte, marges in en wijzig de achtergrondkleur naar AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Converteer HTML naar XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Zie ook

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
