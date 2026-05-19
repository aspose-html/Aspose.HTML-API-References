---
title: "MHTMLSaveOptions-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.MHTMLSaveOptions-klasse. Vertegenwoordigt MHTML-opslagopties. Door specifieke eigenschappen toe te wijzen kun je de verwerking van bronnen beheren, zoals maximale verwerkingsdiepte enzovoort. Meer info zie in het documentatie‑artikel."
type: docs

url: /nl/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Stelt MHTML-opslagopties voor. Door specifieke eigenschappen toe te wijzen kun je de verwerking van bronnen beheren, zoals maximale verwerkingsdiepte enzovoort. Meer info zie in de documentatie [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Haalt een [`ResourceHandlingOptions`](../resourcehandlingoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van bronnen. |

## Opmerkingen

Je kunt volledige voorbeelden en gegevensbestanden vinden op [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Bereid HTML-code voor met een link naar een ander bestand en sla deze op in het bestand als 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Bereid HTML-code voor en sla deze op in het bestand als 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Verander de waarde van de diepte van resource‑koppelingen naar 1 om het document te converteren met direct gekoppelde resources
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML naar MHTML converteren
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Zie ook

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
