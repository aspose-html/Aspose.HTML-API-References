---
title: "Converter.ConvertHTML"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter-methode. Converteer HTML-bron gepresenteerd door HTMLDocument. Resultaat is een docx-bestand gevormd door het uitvoerpad"
type: docs

url: /nl/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instance als conversiebron. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Instantieer standaard configuratie‑object
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Definieer uitvoer‑bestandspad
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Definieer standaard DocSaveOptions‑object
        var options = new DocSaveOptions();
         
		// Start conversieproces met standaard configuratie‑object
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een docx‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een docx‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie‑object
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is een docx‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is een docx‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formulier bronbestandspad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Definieer standaard DocSaveOptions‑object
   var options = new DocSaveOptions();

   // Start conversieproces met standaard configuratie
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Converteer HTML-bron gepresenteerd via inline-inhoud. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Definieer standaard DocSaveOptions‑object
   	var options = new DocSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Converteer HTML-bron gepresenteerd via inline-inhoud. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Definieer standaard DocSaveOptions‑object
   	var options = new DocSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Definieer inline html-inhoud
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Instantieer standaard configuratie‑object
      	var configuration = new Configuration();

      	// Maak een HTML-document op een van de meerdere manieren
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Definieer het pad van het resultaatbestand zonder extensie
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Gebruik een van de ICreateStreamProvider-implementaties
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Definieer standaard DocSaveOptions‑object
			var options = new DocSaveOptions();

        	// Start conversieproces
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Formuleer bron-URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Definieer het pad van het resultaatbestand zonder extensie
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een bekende ICreateStreamProvider-implementatie
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Formuleer bron-URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Definieer het pad van het resultaatbestand zonder extensie
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gebruik een bekende ICreateStreamProvider-implementatie
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieer standaard DocSaveOptions‑object
   var options = new DocSaveOptions();

   // Start conversieproces met standaard configuratie
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Converteer HTML-bron gepresenteerd door een volledig bestandspad naar DOCX. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formuleer bron-html-bestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Definieer het pad van het resultaatbestand
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik de standaard ICreateStreamProvider-implementatie
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Converteer HTML-bron gepresenteerd door een volledig bestandspad naar DOCX. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formuleer bron-html-bestandspad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Definieer het pad van het resultaatbestand
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gebruik de standaard ICreateStreamProvider-implementatie
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieer standaard DocSaveOptions‑object
   var options = new DocSaveOptions();

   // Start conversieproces met standaard configuratie‑object
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Converteer HTML-bron gepresenteerd door inline-inhoud naar DOCX. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Formuleer html inline-inhoud
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Definieer het pad van het resultaatbestand
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een bekende lokaal-bestandgerichte ICreateStreamProvider-implementatie
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instantieer het standaard DocSaveOptions-object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Converteer HTML-bron gepresenteerd door inline-inhoud naar DOCX. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik van het object stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe HTML naar DOCX te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

DOCX-conversie

Een DOCX‑bestand is een Microsoft Word‑document dat doorgaans de tekst bevat, maar een breed scala aan gegevens kan bevatten, waaronder tabellen, raster‑ en vector‑grafische afbeeldingen, video, geluiden en diagrammen. Het DOCX‑bestand is zeer bewerkbaar, gemakkelijk te gebruiken en beheersbaar in grootte. Dit formaat is populair vanwege de verscheidenheid aan opties die het gebruikers biedt om elk type documenten te maken. Dit bestandsformaat is een van de meest gebruikte en is beschikbaar via talrijke programma's.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Converteer HTML naar DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Conversie‑bron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversie‑bron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversie‑bron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversie‑resultaat. Definieer het uitvoer‑bestandspad van het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met aangepaste of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter‑klasse om HTML op te slaan als een DOCX‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑conversies

Aspose.HTML biedt een gratis online [HTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) die HTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Formuleer html inline-inhoud
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Definieer het pad van het resultaatbestand
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gebruik een bekende lokaal-bestandgerichte ICreateStreamProvider-implementatie
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instantieer het standaard DocSaveOptions-object
   var options = new DocSaveOptions();

   // Start conversieproces met standaard configuratie
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is een pdf-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Instantieer standaard configuratie‑object
      var configuration = new Configuration();

      // Maak een HTML‑document op een van de verschillende manieren
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Formulier resultaat‑bestandspad
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Definieer standaard PdfSaveOptions‑object
        var options = new PdfSaveOptions();

		// Instantieer het conversieproces
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Converteer HTML-bron gepresenteerd via URL. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Vorm bestand‑gebaseerde bron‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Converteer HTML-bron gepresenteerd via URL. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Vorm bestand‑gebaseerde bron‑URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definieer standaard PdfSaveOptions‑object
   var options = new PdfSaveOptions();

   // Start conversieproces met standaard configuratie‑object
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formulier bronbestandspad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definieer standaard PdfSaveOptions‑object
   var options = new PdfSaveOptions();

   // Start conversieproces
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Formulier bronbestandspad
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formulier resultaat‑bestandspad
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Definieer standaard PdfSaveOptions‑object
  var options = new PdfSaveOptions();

  // Start conversieproces met standaard configuratie
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Converteer HTML-bron gepresenteerd via inline-inhoud naar PDF. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definieer standaard PdfSaveOptions‑object
   	var options = new PdfSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Converteer HTML-bron gepresenteerd via inline-inhoud naar PDF. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definieer standaard PdfSaveOptions‑object
  	var options = new PdfSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Converteer HTML‑bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/) naar PDF. Resultaat is uitvoergegevens gevormd door [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Definieer inline html-inhoud
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Instantieer standaard configuratie‑object
   	var configuration = new Configuration();

   	// Maak een HTML-document op een van de meerdere manieren
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Definieer het pad van het resultaatbestand zonder extensie
		var resultPath = Path.Combine(OutputFolder, "result");

		// Gebruik een van de ICreateStreamProvider-implementaties
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Definieer standaard PdfSaveOptions‑object
		var options = new PdfSaveOptions();

		// Start conversieproces
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Maak Url op basis van invoer‑bestandspad
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gebruik een van de ICreateStreamProvider-implementaties
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieer standaard PdfSaveOptions‑object
   var options = new PdfSaveOptions();

   // Start conversieproces
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Maak Url op basis van invoer‑bestandspad
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Gebruik een van de ICreateStreamProvider-implementaties
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieer standaard PdfSaveOptions‑object
   var options = new PdfSaveOptions();

   // Start conversieproces met standaard configuratie
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Converteer HTML‑bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is uitvoergegevens gevormd door [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Maak bronbestandspad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulier resultaat‑bestandspad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gebruik een van de ICreateStreamProvider-implementaties
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieer standaard PdfSaveOptions‑object
   var options = new PdfSaveOptions();

   // Start conversieproces
   Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Converteer HTML‑bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is uitvoergegevens gevormd door [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Maak bronbestandspad
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formulier resultaat‑bestandspad
  var resultPath = Path.Combine(OutputFolder, "result");

  // Gebruik een van de ICreateStreamProvider-implementaties
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Definieer standaard PdfSaveOptions‑object
  var options = new PdfSaveOptions();

  // Start conversieproces met standaard configuratie
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Converteer HTML‑bron gepresenteerd via inline‑inhoud naar PDF. Resultaat is uitvoergegevens gevormd door [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gebruik een van de ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieer standaard PdfSaveOptions‑object
  	var options = new PdfSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Converteer HTML‑bron gepresenteerd via inline‑inhoud naar PDF. Resultaat is uitvoergegevens gevormd door [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar PDF te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

PDF-conversie

Portable Document Format (PDF) is een type document dat door Adobe in de jaren 1990 is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Een PDF‑bestand is een reeks bytes die volgens de syntaxisregels gedefinieerd in de PDF-specificaties in tokens kan worden gegroepeerd. Een of meer tokens worden gecombineerd tot hoger‑niveau syntactische entiteiten, voornamelijk objecten, die de basale gegevenswaarden vormen waaruit een PDF‑document wordt opgebouwd.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andere populaire formaatconversies

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar PDF converteren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) die HTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gebruik een van de ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieer standaard PdfSaveOptions‑object
 	var options = new PdfSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Converteer HTML‑bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is een mhtml‑bestand (.mht) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Vorm HTML‑document
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Maak een HTML-document op een van de meerdere manieren
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Definieer standaard MHTMLSaveOptions-object
 		var options = new MHTMLSaveOptions();

		// Formulier resultaat‑bestandspad
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Start conversieproces
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een mhtml‑bestand (.mht) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definieer standaard MHTMLSaveOptions-object
	var options = new MHTMLSaveOptions();

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een mhtml‑bestand (.mht) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definieer standaard MHTMLSaveOptions-object
	var options = new MHTMLSaveOptions();

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar MHTML. Resultaat is een mhtml‑bestand (.mht) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definieer standaard MHTMLSaveOptions-object
	var options = new MHTMLSaveOptions();

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Start conversieproces
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar MHTML. Resultaat is een mhtml‑bestand (.mht) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definieer standaard MHTMLSaveOptions-object
	var options = new MHTMLSaveOptions();

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Converteer HTML-bron gepresenteerd via inline-inhoud naar MHTML. Resultaat is mhtml (.mht)-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. Je kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoer‑bestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een MHTML‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
  	var options = new MHTMLSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Converteer HTML-bron gepresenteerd via inline-inhoud naar MHTML. Resultaat is mhtml (.mht)-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Volledig mhtml‑bestandspad (.mht) als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar MHTML te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

MHTML-conversie

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar MHTML converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een MHTML-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) die HTML naar MHTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
 	var options = new MHTMLSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is een markdown (.md)-bestand gevormd door het uitvoerpad.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formulier bronbestandspad
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Formulier resultaat‑bestandspad
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Definieer instantie van save options-object
			var options = new MarkdownSaveOptions();

			// Start conversieproces
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een markdown‑bestand (.md) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Formulier resultaat‑bestandspad
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieer instantie van save options-object
	var options = new MarkdownSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een markdown‑bestand (.md) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Formulier resultaat‑bestandspad
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieer instantie van save options-object
	var options = new MarkdownSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar Markdown. Resultaat is een markdown‑bestand (.md) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Formulier resultaat‑bestandspad
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieer instantie van save options-object
	var options = new MarkdownSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar Markdown. Resultaat is een markdown‑bestand (.md) gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Formulier resultaat‑bestandspad
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieer instantie van save options-object
	var options = new MarkdownSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Converteer HTML-bron gepresenteerd via inline-inhoud naar Markdown. Resultaat is mhtml (.mht)-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
  	var options = new MarkdownSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Converteer HTML-bron gepresenteerd via inline-inhoud naar Markdown. Resultaat is mhtml (.mht)-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | MarkdownSaveOptions | Het gebruik van het [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Volledig md-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar Markdown te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Markdown-conversie

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andere populaire formaatconversies

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar Markdown converteren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een Markdown-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) die HTML naar MD converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
 	var options = new MarkdownSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is een xps-bestand gevormd door het uitvoerpad.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formulier bronbestandspad
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Formulier resultaat‑bestandspad
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Maak een HTML-document op een van de meerdere manieren
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Definieer instantie van save options-object
        	var options = new XpsSaveOptions();

        	// Start conversieproces
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Converteer HTML-bron gepresenteerd via URL. Resultaat is xps-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulier resultaat‑bestandspad
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Converteer HTML-bron gepresenteerd via URL. Resultaat is xps-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulier resultaat‑bestandspad
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulier resultaat‑bestandspad
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulier resultaat‑bestandspad
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Converteer HTML-bron gepresenteerd via inline-inhoud naar XPS. Resultaat is xps-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
  	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Converteer HTML-bron gepresenteerd via inline-inhoud naar XPS. Resultaat is xps-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieer standaard opslaanopties-object
 	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Maak een HTML-document op een van de meerdere manieren
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Definieer instantie van save options-object
    	var options = new XpsSaveOptions();

		// Gebruik één van de bekende ICreateStreamProvider-implementaties
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Start conversieproces
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML‑bron‑document‑URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gebruik een van de ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML-bron-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gebruik een van de ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Converteer HTML-bron gepresenteerd door volledig bestandspad naar XPS. Resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gebruik een van de ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Converteer HTML-bron gepresenteerd door volledig bestandspad naar XPS. Resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gebruik een van de ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieer instantie van save options-object
	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Converteer HTML-bron die via inline-inhoud wordt gepresenteerd naar XPS. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML naar XPS](https://products.aspose.app/html/en/conversion/html-to-xps) converter die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gebruik een van de ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieer standaard opslaanopties-object
  	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Converteer HTML-bron die via inline-inhoud wordt gepresenteerd naar XPS. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie. |

## Opmerkingen

Hoe HTML naar XPS te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

XPS-conversie

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML naar XPS converteren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML-bestand of een externe URL als conversiebron. Je kunt zelfs inline HTML-inhoud definiëren als conversiebron of een HTML-document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad van het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met aangepaste of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()-methode van de Converter-klasse om HTML op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML-converters

Aspose.HTML biedt een gratis online [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) die HTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Probeer andere populaire formaatconversies te gebruiken

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gebruik een van de ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieer standaard opslaanopties-object
 	var options = new XpsSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Converteer HTML-bron die wordt gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Het resultaat is een afbeeldingsbestand dat is gevormd door het uitvoerpad.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "source.html");

// Formulier resultaat‑bestandspad
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Start conversieproces
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een afbeeldingsbestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML-bron-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Converteer HTML-bron gepresenteerd via URL. Resultaat is een afbeeldingsbestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML-bron-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar afbeelding. Resultaat is een afbeeldingsbestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Om meer te weten te komen over de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) klasse, lees alstublieft het artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definieer een instantie van het opslaan‑opties object. PNG is standaard het afbeeldingsformaat.
	var options = new ImageSaveOptions();

	// Start conversieproces
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Converteer HTML-bron gepresenteerd via volledig bestandspad naar afbeelding. Resultaat is een afbeeldingsbestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Om meer te weten te komen over de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) klasse, lees alstublieft het artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definieer een instantie van het opslaan‑opties object. PNG is standaard het afbeeldingsformaat.
	var options = new ImageSaveOptions();

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Converteer HTML-bron gepresenteerd via inline-inhoud naar afbeelding. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Nieuw gevormde afbeeldingopties zoals formaat, resolutie enz. Zie de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) klasse en de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieer standaard opslaanopties-object
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Converteer HTML-bron gepresenteerd via inline-inhoud naar afbeelding. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Nieuw gevormde afbeeldingopties zoals formaat, resolutie enz. Zie de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) klasse en de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieer standaard opslaanopties-object
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Converteer HTML-bron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)object stelt u in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Maak een HTML-document op een van de meerdere manieren
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Definieer instantie van save options-object
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Gebruik een van de ICreateStreamProvider-implementaties
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Start conversieproces
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML-bron-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulier resultaat‑bestandspad
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik een van de ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Converteer HTML-bron gepresenteerd door een URL. Resultaat is uitvoergegevens gevormd door de implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | HTML-bron-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Meer informatie over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Maak Url op basis van invoer‑bestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik een van de ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Converteer HTML-bron die via een volledig bestandspad wordt gepresenteerd naar afbeelding. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Html volledig bestandspad. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Meer informatie over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulier resultaat‑bestandspad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik één van de bekende ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Converteer HTML-bron die via een volledig bestandspad wordt gepresenteerd naar afbeelding. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Meer informatie over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Formulier resultaat‑bestandspad
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieer instantie van save options-object
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik één van de bekende ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Converteer HTML-bron die via inline-inhoud wordt gepresenteerd naar afbeelding. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie. |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieer standaard opslaanopties-object
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik één van de bekende ICreateStreamProvider-implementaties
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Converteer HTML-bron die via inline-inhoud wordt gepresenteerd naar afbeelding. Het resultaat is uitvoergegevens die zijn gevormd door een implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline html-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration `](../../../com.aspose.html/configuration/)contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) die wordt gebruikt om een uitvoerstroom te verkrijgen. Meer informatie over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe HTML naar afbeelding te converteren

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. Converteren tussen formaten is om verschillende redenen nodig: om te werken in een bekend, handig formaat of om voordeel te halen uit verschillende formaten voor specifieke taken. Het com.aspose.html.converters-pakket biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan HTML-conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), en [MD](https://docs.fileformat.com/word-processing/md/).

Dit artikel geeft informatie over de lijst met ondersteunde HTML-conversies en hoe u ze kunt uitvoeren met behulp van de [`Converter`](../) klasse die alle laag-niveau conversie‑operaties groepeert in één klasse om ze comfortabel en eenvoudig te gebruiken. In de HTML Converter‑gids vindt u de volgende artikelen:

Afbeeldingsconversies

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andere populaire formaatconversies

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Converteer HTML naar afbeelding

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal HTML‑bestand of een externe URL als conversiebron. U kunt zelfs inline‑HTML‑inhoud definiëren als conversiebron of een HTML‑document (HTMLDocument) op welke manier dan ook maken. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met de vereiste [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standaard is de eigenschap Format PNG. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertHTML()‑methode van de Converter‑klasse om HTML op te slaan als een afbeelding met drie of meer parameters, afhankelijk van het gebruikersscenario. Online HTML‑converters

Aspose.HTML biedt een gratis online [HTML naar PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) die HTML naar afbeeldingen converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formuleer inline html-inhoud		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieer standaard opslaanopties-object
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gebruik één van de bekende ICreateStreamProvider-implementaties
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Start conversieproces met standaard configuratie
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | HTMLDocument | Conversiebron. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De document-URL. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De document-URL. |
| configuratie | Configuratie | De omgevingsconfiguratie. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | HTML-bestand bronpad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuratie | Configuratie | De omgevingsconfiguratie. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Inline tekenreeks HTML-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Converteer html‑document naar tekst. Resultaat is een TXT‑bestand.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Inline tekenreeks HTML-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuratie | Configuratie | De omgevingsconfiguratie. |
| opties | TextSaveOptions | Conversie‑opties. |
| outputPath | String | Uitvoerbestandspad. |

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
