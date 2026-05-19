---
title: "HTMLSaveOptions Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.HTMLSaveOptions class. Vertegenwoordigt HTML-opslagopties. Door specifieke eigenschappen toe te wijzen kun je de bronverwerking beheren, zoals maximale verwerkingsdiepte enzovoort. Meer info zie in het documentatie‑artikel."
type: docs

url: /nl/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Stelt HTML-opslagopties voor. Door specifieke eigenschappen toe te wijzen kun je de verwerking van bronnen beheren, zoals maximale verwerkingsdiepte enzovoort. Meer info zie in de documentatie [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Haalt een [`ResourceHandlingOptions`](../resourcehandlingoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van bronnen. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Het type uitvoerdocument wordt automatisch geselecteerd. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Het document wordt opgeslagen als HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Het document wordt opgeslagen als XHTML. |

## Opmerkingen

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Bereid een uitvoerpad voor een HTML‑document voor.
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Bereid een eenvoudig HTML‑bestand voor met een gekoppeld document.
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Bereid een eenvoudig gekoppeld HTML‑bestand voor.
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Laad "save-with-linked-file.html" in het geheugen.
      using (var document = new HTMLDocument(documentPath))
      {
        // Maak een instantie van opslagopties aan.
        var options = new HTMLSaveOptions();

        // De volgende regel met waarde '0' schakelt alle andere gekoppelde HTML-bestanden uit tijdens het opslaan van deze instantie
        // Als je deze regel verwijdert of de waarde wijzigt naar '1', wordt het bestand 'linked.html' ook opgeslagen in de uitvoermap
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Sla het document op met de opslaanopties
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Zie ook

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
