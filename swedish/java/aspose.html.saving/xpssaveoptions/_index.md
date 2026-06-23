---
title: "XpsSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.XpsSaveOptions-klass. Specifik alternativdataklass tillhandahåller några egenskaper för att hantera konverteringsresultatet. Till exempel specificerar PageSetup sidans egenskaper. Se dokumentationsartikeln."
type: docs

url: /sv/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Specifik alternativdataklass tillhandahåller några egenskaper för att hantera konverteringsresultatet. Till exempel [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specificerar sidans egenskaper. Se dokumentations[artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Hämtar ett [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) objekt som används för konfiguration av bearbetning av css-egenskaper. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ställer in eller hämtar horisontell upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Ställer in eller hämtar vertikal upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |

## Anmärkningar

Du kan hitta kompletta exempel och datafiler på [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Förbered HTML-kod och spara den till en fil
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initiera ett HTML-dokument från HTML-filen
      using var document = new HTMLDocument(documentPath);
       
      // Ställ in sidstorleken, marginalerna och ändra bakgrundsfärgen till AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Konvertera HTML till XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Se även

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
