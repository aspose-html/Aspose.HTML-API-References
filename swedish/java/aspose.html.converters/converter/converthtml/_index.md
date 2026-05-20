---
title: "Converter.ConvertHTML"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter-metod. Konvertera HTML-källa som presenteras av HTMLDocument. Resultatet är en docx-fil som skapas av utskriftsfilens sökväg"
type: docs

url: /sv/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Konvertera HTML-källa som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en docx-fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instans som konverteringskälla. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Instansiera standardkonfigurationsobjekt
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Ange utdatafilens sökväg
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Ange standard‑DocSaveOptions‑objekt
        var options = new DocSaveOptions();
         
		// Initiera konverteringsprocessen med standardkonfigurationsobjektet
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Konvertera HTML-källa som presenteras via URL. Resultatet är en docx‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa URL baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär för resultatfilens sökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ange standard‑DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Konvertera HTML-källa som presenteras via URL. Resultatet är en docx‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Skapa URL baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär för resultatfilens sökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ange standard‑DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfigurationsobjektet
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Konvertera HTML-källa som presenteras via fullständig filsökväg till DOCX. Resultatet är en docx‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär för källfilens sökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär för resultatfilens sökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ange standard‑DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Konvertera HTML-källa som presenteras via fullständig filsökväg till DOCX. Resultatet är en docx‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formulär för källfilens sökväg
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Ange standard‑DocSaveOptions‑objekt
   var options = new DocSaveOptions();

   // Initiera konverteringsprocessen med standardkonfiguration
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Konvertera HTML-källa som presenteras via inline-innehåll. Resultatet är docx-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Ange standard‑DocSaveOptions‑objekt
   	var options = new DocSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Konvertera HTML-källa som presenteras via inline-innehåll. Resultatet är docx-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx-filsökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Ange standard‑DocSaveOptions‑objekt
   	var options = new DocSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Definiera inbäddat HTML-innehåll
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Instansiera standardkonfigurationsobjekt
      	var configuration = new Configuration();

      	// Skapa HTML-dokument på ett av flera sätt
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Definiera sökväg för resultatfil utan filändelse
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Använd en av ICreateStreamProvider-implementeringarna
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Ange standard‑DocSaveOptions‑objekt
			var options = new DocSaveOptions();

        	// Initiera konverteringsprocessen
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Formulera käll-URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Definiera sökväg för resultatfil utan filändelse
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd känd ICreateStreamProvider-implementering
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Ange standard‑DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Formulera käll-URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Definiera sökväg för resultatfil utan filändelse
   var resultPath = Path.Combine(OutputFolder, "result");

   // Använd känd ICreateStreamProvider-implementering
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Ange standard‑DocSaveOptions‑objekt
   var options = new DocSaveOptions();

   // Initiera konverteringsprocessen med standardkonfiguration
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Konvertera HTML-källan som presenteras av fullständig filsökväg till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulera käll-HTML-filsökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Definiera sökväg för resultatfil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd standard ICreateStreamProvider-implementering
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Ange standard‑DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Konvertera HTML-källan som presenteras av fullständig filsökväg till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formulera käll-HTML-filsökväg
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Definiera sökväg för resultatfil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Använd standard ICreateStreamProvider-implementering
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Ange standard‑DocSaveOptions‑objekt
   var options = new DocSaveOptions();

   // Initiera konverteringsprocessen med standardkonfigurationsobjektet
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Konvertera HTML-källan som presenteras av inbäddat innehåll till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Formulera inbäddat HTML-innehåll
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Definiera sökväg för resultatfil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd känd lokalt filorienterad ICreateStreamProvider-implementering
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instansiera standard DocSaveOptions-objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Konvertera HTML-källan som presenteras av inbäddat innehåll till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objektanvändning gör att du kan finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar HTML till DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

DOCX-konvertering

En DOCX‑fil är ett Microsoft Word‑dokument som vanligtvis innehåller text men kan innehålla ett brett spektrum av data, inklusive tabeller, raster‑ och vektorgrafik, video, ljud och diagram. DOCX‑filen är mycket redigerbar, lätt att använda och hanterbar i storlek. Detta format är populärt på grund av de många alternativ det erbjuder användare för att skriva alla typer av dokument. Detta filformat är ett av de mest använda och finns tillgängligt i många program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementering som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/html-to-docx) som konverterar HTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Formulera inbäddat HTML-innehåll
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Definiera sökväg för resultatfil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Använd känd lokalt filorienterad ICreateStreamProvider-implementering
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instansiera standard DocSaveOptions-objekt
   var options = new DocSaveOptions();

   // Initiera konverteringsprocessen med standardkonfiguration
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en PDF-fil som bildas av utdatafilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Formulär för källfilens sökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Instansiera standardkonfigurationsobjekt
      var configuration = new Configuration();

      // Skapa HTML‑dokument på ett av flera sätt
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Formulär för resultatfilens sökväg
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Definiera standard‑PdfSaveOptions‑objekt
        var options = new PdfSaveOptions();

		// Instansiera konverteringsprocessen
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Konvertera HTML-källa som presenteras via URL. Resultatet är pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Formulera filbaserad käll‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär för resultatfilens sökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Konvertera HTML-källa som presenteras via URL. Resultatet är pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Formulera filbaserad käll‑URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definiera standard‑PdfSaveOptions‑objekt
   var options = new PdfSaveOptions();

   // Initiera konverteringsprocessen med standardkonfigurationsobjektet
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Konvertera HTML-källa som presenteras via fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formulär för källfilens sökväg
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definiera standard‑PdfSaveOptions‑objekt
   var options = new PdfSaveOptions();

   // Initiera konverteringsprocessen
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Konvertera HTML-källa som presenteras via fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Formulär för källfilens sökväg
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formulär för resultatfilens sökväg
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Definiera standard‑PdfSaveOptions‑objekt
  var options = new PdfSaveOptions();

  // Initiera konverteringsprocessen med standardkonfiguration
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Konvertera HTML-källa som presenteras via inline-innehåll till PDF. Resultatet är pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definiera standard‑PdfSaveOptions‑objekt
   	var options = new PdfSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Konvertera HTML-källa som presenteras via inline-innehåll till PDF. Resultatet är pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definiera standard‑PdfSaveOptions‑objekt
  	var options = new PdfSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Konvertera HTML‑källa som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/) till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Definiera inbäddat HTML-innehåll
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Instansiera standardkonfigurationsobjekt
   	var configuration = new Configuration();

   	// Skapa HTML-dokument på ett av flera sätt
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Definiera sökväg för resultatfil utan filändelse
		var resultPath = Path.Combine(OutputFolder, "result");

		// Använd en av ICreateStreamProvider-implementeringarna
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Definiera standard‑PdfSaveOptions‑objekt
		var options = new PdfSaveOptions();

		// Initiera konverteringsprocessen
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Skapa URL baserat på indatafilens sökväg
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result");

   // Använd en av ICreateStreamProvider-implementeringarna
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definiera standard‑PdfSaveOptions‑objekt
   var options = new PdfSaveOptions();

   // Initiera konverteringsprocessen
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Skapa URL baserat på indatafilens sökväg
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Använd en av ICreateStreamProvider-implementeringarna
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definiera standard‑PdfSaveOptions‑objekt
   var options = new PdfSaveOptions();

   // Initiera konverteringsprocessen med standardkonfiguration
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Konvertera HTML‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Skapa källfilens sökväg
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formulär för resultatfilens sökväg
   var resultPath = Path.Combine(OutputFolder, "result");

   // Använd en av ICreateStreamProvider-implementeringarna
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definiera standard‑PdfSaveOptions‑objekt
   var options = new PdfSaveOptions();

   // Initiera konverteringsprocessen
   Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Konvertera HTML‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Skapa källfilens sökväg
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formulär för resultatfilens sökväg
  var resultPath = Path.Combine(OutputFolder, "result");

  // Använd en av ICreateStreamProvider-implementeringarna
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Definiera standard‑PdfSaveOptions‑objekt
  var options = new PdfSaveOptions();

  // Initiera konverteringsprocessen med standardkonfiguration
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Konvertera HTML‑källa som presenteras av inbäddat innehåll till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Använd en av ICreateStreamProvider-implementeringarna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definiera standard‑PdfSaveOptions‑objekt
  	var options = new PdfSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Konvertera HTML‑källa som presenteras av inbäddat innehåll till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

PDF‑konvertering

Portable Document Format (PDF) är en dokumenttyp som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. En PDF‑fil är en samling byte som kan grupperas i token enligt syntaxregler som definieras av PDF‑specifikationerna. En eller flera token kombineras för att bilda högre‑nivå syntaktiska enheter, främst objekt, vilka är de grundläggande datavärdena som ett PDF‑dokument byggs upp från.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Andra populära formatkonverteringar

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) som konverterar HTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Använd en av ICreateStreamProvider-implementeringarna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definiera standard‑PdfSaveOptions‑objekt
 	var options = new PdfSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Konvertera HTML‑källa som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en mhtml‑fil (.mht) som bildas av utdatafilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera HTML‑dokument
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Skapa HTML-dokument på ett av flera sätt
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Definiera standard MHTMLSaveOptions-objekt
 		var options = new MHTMLSaveOptions();

		// Formulär för resultatfilens sökväg
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Initiera konverteringsprocessen
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Konvertera HTML-källa som presenteras via URL. Resultatet är en mhtml‑fil (.mht) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definiera standard MHTMLSaveOptions-objekt
	var options = new MHTMLSaveOptions();

	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Konvertera HTML-källa som presenteras via URL. Resultatet är en mhtml‑fil (.mht) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definiera standard MHTMLSaveOptions-objekt
	var options = new MHTMLSaveOptions();

	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Konvertera HTML-källa som presenteras via fullständig filsökväg till MHTML. Resultatet är en mhtml‑fil (.mht) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definiera standard MHTMLSaveOptions-objekt
	var options = new MHTMLSaveOptions();

	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Konvertera HTML-källa som presenteras via fullständig filsökväg till MHTML. Resultatet är en mhtml‑fil (.mht) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definiera standard MHTMLSaveOptions-objekt
	var options = new MHTMLSaveOptions();

	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Konvertera HTML-källa som presenteras via inline-innehåll till MHTML. Resultatet är mhtml (.mht)-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal HTML‑fil eller fjärr‑URL som konverteringskälla. Du kan även definiera inbäddat HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Ange filväg för resultatets utdata eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objekt med anpassade eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som ett MHTML‑resultat med tre eller fler parametrar beroende på användarscenariot. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
  	var options = new MHTMLSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Konvertera HTML-källa som presenteras via inline-innehåll till MHTML. Resultatet är mhtml (.mht)-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/)‑objektets användning gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Fullständig mhtml‑filväg (.mht) som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

MHTML‑konvertering

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett MHTML-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) som konverterar HTML till MHTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
 	var options = new MHTMLSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en markdown (.md)-fil som skapas av utdatafilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formulär för källfilens sökväg
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Formulär för resultatfilens sökväg
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Definiera instans av sparalternativ-objekt
			var options = new MarkdownSaveOptions();

			// Initiera konverteringsprocessen
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Konvertera HTML-källa som presenteras via URL. Resultatet är en markdown‑fil (.md) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Formulär för resultatfilens sökväg
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definiera instans av sparalternativ-objekt
	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Konvertera HTML-källa som presenteras via URL. Resultatet är en markdown‑fil (.md) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Formulär för resultatfilens sökväg
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definiera instans av sparalternativ-objekt
	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Konvertera HTML-källa som presenteras via fullständig filsökväg till Markdown. Resultatet är en markdown‑fil (.md) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Formulär för resultatfilens sökväg
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definiera instans av sparalternativ-objekt
	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Konvertera HTML-källa som presenteras via fullständig filsökväg till Markdown. Resultatet är en markdown‑fil (.md) som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Formulär för resultatfilens sökväg
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definiera instans av sparalternativ-objekt
	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Konvertera HTML-källa som presenteras via inline-innehåll till Markdown. Resultatet är mhtml (.mht)-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
  	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Konvertera HTML-källa som presenteras via inline-innehåll till Markdown. Resultatet är mhtml (.mht)-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Fullständig md-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Markdown-konvertering

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Andra populära formatkonverteringar

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett Markdown-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till Markdown](https://products.aspose.app/html/en/conversion/html-to-md) som konverterar HTML till MD med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
 	var options = new MarkdownSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en xps-fil som skapas av utdatafilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formulär för källfilens sökväg
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Formulär för resultatfilens sökväg
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Skapa HTML-dokument på ett av flera sätt
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Definiera instans av sparalternativ-objekt
        	var options = new XpsSaveOptions();

        	// Initiera konverteringsprocessen
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Konvertera HTML-källa som presenteras via URL. Resultatet är xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulär för resultatfilens sökväg
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Konvertera HTML-källa som presenteras via URL. Resultatet är xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulär för resultatfilens sökväg
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Konvertera HTML-källa som presenteras via fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulär för resultatfilens sökväg
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Konvertera HTML-källa som presenteras via fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulär för resultatfilens sökväg
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Konvertera HTML-källa som presenteras via inline-innehåll till XPS. Resultatet är xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
  	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Konvertera HTML-källa som presenteras via inline-innehåll till XPS. Resultatet är xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| outputPath | String | Fullständig xps-filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definiera standard sparalternativ-objekt
 	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Skapa HTML-dokument på ett av flera sätt
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Definiera instans av sparalternativ-objekt
    	var options = new XpsSaveOptions();

		// Använd en av de kända ICreateStreamProvider-implementationerna
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Initiera konverteringsprocessen
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML‑källdokument‑URL – ger en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Använd en av ICreateStreamProvider-implementeringarna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-källans URL - ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Använd en av ICreateStreamProvider-implementeringarna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Konvertera HTML-källan som presenteras av fullständig filsökväg till XPS. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Använd en av ICreateStreamProvider-implementeringarna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Konvertera HTML-källan som presenteras av fullständig filsökväg till XPS. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Använd en av ICreateStreamProvider-implementeringarna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definiera instans av sparalternativ-objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Konvertera HTML-källkod som presenteras som inline-innehåll till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps) konverterare som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Använd en av ICreateStreamProvider-implementeringarna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definiera standard sparalternativ-objekt
  	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Konvertera HTML-källkod som presenteras som inline-innehåll till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation. |

## Anmärkningar

Hur man konverterar HTML till XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

XPS-konvertering

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konvertera HTML till XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inbäddat html-innehåll som konverteringskälla eller skapa ett HTML-dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata-buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objekt med anpassade eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som parameter. Använd ConvertHTML()-metoden i Converter-klassen för att spara HTML som ett XPS-resultat med tre eller fler parametrar beroende på användarscenario. Online HTML-omvandlare

Aspose.HTML erbjuder en gratis online [HTML till XPS-omvandlare](https://products.aspose.app/html/en/conversion/html-to-xps) som konverterar HTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Försök att använda andra populära formatkonverteringar

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Använd en av ICreateStreamProvider-implementeringarna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definiera standard sparalternativ-objekt
 	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Konvertera HTML-källkod som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är en bildfil som bildas av utdatafilens sökväg.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "source.html");

// Formulär för resultatfilens sökväg
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Konvertera HTML-källa som presenteras via URL. Resultatet är en bildfil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-källans URL - ger en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Konvertera HTML-källa som presenteras via URL. Resultatet är en bildfil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-källans URL - ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Konvertera HTML-källa som presenteras via fullständig filsökväg till bild. Resultatet är en bildfil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | ImageSaveOptions | För att lära dig mer om klassen [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) , läs artikeln [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definiera instans av sparalternativ‑objektet. PNG är bildformatet som standard.
	var options = new ImageSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Konvertera HTML-källa som presenteras via fullständig filsökväg till bild. Resultatet är en bildfil som skapas via sökvägen för utdatafilen.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | För att lära dig mer om klassen [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) , läs artikeln [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definiera instans av sparalternativ‑objektet. PNG är bildformatet som standard.
	var options = new ImageSaveOptions();

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Konvertera HTML-källa som presenteras via inline-innehåll till bild. Resultatet är bildfil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | ImageSaveOptions | Nya bildalternativ som format, upplösning med mera. Se klassen [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definiera standard sparalternativ-objekt
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Konvertera HTML-källa som presenteras via inline-innehåll till bild. Resultatet är bildfil som bildas av utdatans filsökväg.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Nya bildalternativ som format, upplösning med mera. Se klassen [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definiera standard sparalternativ-objekt
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Konvertera HTML-källan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | HTMLDocument | Konverteringskälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)objektets användning gör att du kan finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result");

	// Skapa HTML-dokument på ett av flera sätt
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Definiera instans av sparalternativ-objekt
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Använd en av ICreateStreamProvider-implementeringarna
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Initiera konverteringsprocessen
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-källans URL - ger en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formulär för resultatfilens sökväg
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av ICreateStreamProvider-implementeringarna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Konvertera HTML-källan som presenteras av URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-källans URL - ger en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet som kommer att användas för att få en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Skapa URL baserat på indatafilens sökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av ICreateStreamProvider-implementeringarna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Konvertera HTML-källkod som presenteras av fullständig filsökväg till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html fullständig filsökväg. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet som kommer att användas för att få en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formulär för resultatfilens sökväg
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av de kända ICreateStreamProvider-implementationerna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Konvertera HTML-källkod som presenteras av fullständig filsökväg till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet som kommer att användas för att få en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär för källfilens sökväg
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Formulär för resultatfilens sökväg
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definiera instans av sparalternativ-objekt
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av de kända ICreateStreamProvider-implementationerna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Konvertera HTML-källkod som presenteras som inline‑innehåll till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation. |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definiera standard sparalternativ-objekt
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av de kända ICreateStreamProvider-implementationerna
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Konvertera HTML-källkod som presenteras som inline‑innehåll till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Sträng som inbäddat HTML-innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration `](../../../com.aspose.html/configuration/)kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) som kommer att användas för att få en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar HTML till bild

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Huvudpoängen med Aspose.HTML är konverteringsfunktionen. Att konvertera mellan format krävs av olika skäl: för att arbeta i ett bekant, bekvämt format eller för att utnyttja olika format för specifika uppgifter. Paketen com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av HTML-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), och [MD](https://docs.fileformat.com/word-processing/md/).

Denna artikel ger information om listan över stödjade HTML-konverteringar och hur man utför dem med hjälp av [`Converter`](../)-klassen som samlar alla låg-nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I HTML Converter-guiden hittar du följande artiklar:

Bildkonverteringar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Andra populära formatkonverteringar

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konvertera HTML till bild

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Upptäck en befintlig lokal HTML-fil eller fjärr-URL som konverteringskälla. Du kan även definiera inline‑HTML‑innehåll som konverteringskälla eller skapa ett HTML‑dokument (HTMLDocument) på vilket sätt som helst. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) objekt med erforderligt [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Som standard är Format‑egenskapen PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertHTML()-metoden i Converter‑klassen för att spara HTML som en bild med tre eller fler parametrar beroende på användarscenario. Online‑HTML‑konverterare

Aspose.HTML erbjuder en gratis online [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) som konverterar HTML till bilder med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulera inbäddat HTML-innehåll		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formulär för resultatfilens sökväg
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definiera standard sparalternativ-objekt
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Använd en av de kända ICreateStreamProvider-implementationerna
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initiera konverteringsprocessen med standardkonfiguration
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | HTMLDocument | Konverteringskälla. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Dokumentets URL. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Dokumentets URL. |
| konfiguration | Konfiguration | Miljökonfigurationen. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Html-filens källsökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| konfiguration | Konfiguration | Miljökonfigurationen. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Inbäddat sträng‑HTML‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Konvertera html-dokument till text. Resultatet är en TXT‑fil.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Inbäddat sträng‑HTML‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| konfiguration | Konfiguration | Miljökonfigurationen. |
| alternativ | TextSaveOptions | Konverteringsalternativ. |
| outputPath | String | Utskriftsfilens sökväg. |

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
