---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter‑metod. Konvertera EPUB‑källa som presenteras av data‑indataström. Resultatet är en fil som bildas av utdatafilens sökväg."
type: docs

url: /sv/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Konvertera EPUB-källa som presenteras med dataindataström. Resultatet är en fil som bildas av utdatans filsökväg.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| options | ImageSaveOptions | Nya bildalternativ som format, upplösning osv. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen och [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Öppna befintlig fil för läsning som ström
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ange utdatafilens sökväg
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definiera standardalternativinstans
var options = new ImageSaveOptions();

// Initiera konverteringsprocessen
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg. Resultatet är en bildfil som bildas av utdatafilsökvägen. Bildformatet specificeras av ImageSaveOptions‑objektet.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB-källfilens sökväg som inparameter. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definiera standardinstans av ImageSaveOptions‑objektet
var options = new ImageSaveOptions(); 

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Konvertera EPUB‑källa som definieras av URL. Resultatet är en bildfil som bildas av utdatafilsökvägen. Bildformatet specificeras av ImageSaveOptions‑objektet.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definiera standardalternativinstans
var options = new ImageSaveOptions();

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Konvertera EPUB‑källa som presenteras av data‑inmatningsström. Resultatet är en bildfil som bildas av utdatafilsökvägen. Bildformatet specificeras av ImageSaveOptions‑objektet.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Öppna befintlig fil för läsning som ström
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ange utdatafilens sökväg
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definiera standardalternativinstans
var options = new ImageSaveOptions();

// Initiera konverteringsprocessen med standardkonfigurationsobjektet
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg. Resultatet är en bildfil som bildas av utdatafilsökvägen. Bildformatet specificeras av ImageSaveOptions‑objektet.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB-källfilens sökväg som inparameter. |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definiera standardinstans av ImageSaveOptions‑objektet
var options = new ImageSaveOptions(); 

// Initiera konverteringsprocessen med standardkonfigurationsobjektet
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Konvertera EPUB‑källa som definieras av URL. Resultatet är en bildfil som bildas av utdatafilsökvägen. Bildformatet specificeras av ImageSaveOptions‑objektet.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan ange [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), etc. Se [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)‑klassen. |
| outputPath | String | Fullständig bildfilssökväg som resultat av konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Definiera URL baserat på befintlig EPUB-fil på den angivna sökvägen. Definiera resultatets utdatafilssökväg. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste också skicka ImageSaveOptions och Configuration‑objektet till bildkonverteringen. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Ange utdatafilens sökväg
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Definiera standardalternativinstans
var options = new ImageSaveOptions(); 

// Initiera konverteringsprocessen med standardkonfigurationsobjektet
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Konvertera epub‑källan som presenteras av indata‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) till bild. Resultatet är en bildfil som skapas av implementeringen av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen. |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet som utdata‑databuffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Skapa standardalternativinstans  
var options = new ImageSaveOptions();    

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Konvertera EPUB‑källan som presenteras av filsökvägen till bild. Resultatet är en bildfil som skapas av implementeringen av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | ImageSaveOptions | Nya bildalternativ som format, upplösning osv. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen och [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementering av gränssnittet, som kommer att användas för att erhålla en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑databuffert. Skapa ett nytt ImageSaveOptions‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

EPUB till JPG med två kodrader

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Öppna en befintlig EPUB‑fil för läsning.
import var stream = File.OpenRead(DataDir + "input.epub");

// Anropa ConvertEPUB‑metoden för att konvertera EPUB‑koden till en JPG‑bild      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Konvertera epub‑källa som presenteras via URL till en bild. Resultatet är en bildfil som skapas av implementeringen av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Se [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)‑klassen. |
| provider | ICreateStreamProvider | Implementering av gränssnittet, som kommer att användas för att erhålla en utström. Mer information om leverantörer finns i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑databuffert. Skapa ett nytt ImageSaveOptions‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Skapa standardalternativinstans  
var options = new ImageSaveOptions();

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Konvertera epub‑källan som presenteras av indata‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) till bild. Resultatet är en bildfil som skapas av implementeringen av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| leverantör | ICreateStreamProvider | Implementering av gränssnittet, som kommer att användas för att få en utmatningsström. |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑databuffert. Skapa ett nytt ImageSaveOptions‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Skapa standardalternativinstans  
var options = new ImageSaveOptions();    


// Initiera konverteringsprocessen med standardkonfiguration  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Konvertera epub‑källa som presenteras via filsökväg till en bild. Resultatet är en bildfil som skapas av implementeringen av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källa definierad av filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet, som kommer att användas för att få en utmatningsström. Se exempel på ICreateStreamProvider‑implementering i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑databuffert. Skapa ett nytt ImageSaveOptions‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Definiera standardinstans av ImageSaveOptions‑objektet
var options = new ImageSaveOptions(); 

// Initiera konverteringsprocessen med standardkonfigurationsobjektet
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Konvertera epub-källa som presenteras via URL till bild. Resultatet är en bildfil som bildas av implementeringen av [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) gränssnittet.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | ImageSaveOptions‑objektets användning gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet, som kommer att användas för att få en utmatningsström. Se exempel på ICreateStreamProvider‑implementering i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till bild

EPUB är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum (IDPF) och stöds nu av många e‑läsare och programvaror.

Att konvertera EPUB‑filer till PNG‑formatet kan vara användbart om du behöver inkludera filer i en PowerPoint‑presentation eller skicka dem via e‑post. Konvertera dem till bildformatet och använd dem som du vill! Du kan använda ytterligare konverteringsparametrar för att uppnå önskat resultat.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en Converter‑klass som samlar alla lågnivå‑konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑konverteringsguiden hittar du följande artiklar:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konvertera EPUB till bild

För att konvertera EPUB till bildfilformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. I exemplet använder vi OpenRead()-metoden i System.IO.FileStream‑klassen för att öppna och läsa en EPUB‑fil från filsystemet på den angivna sökvägen. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑databuffert. Skapa ett nytt ImageSaveOptions‑objekt med önskat ImageFormat. Som standard är Format‑egenskapen PNG. Använd ConvertEPUB()-metoden i Converter‑klassen för att spara EPUB som en bild. Du måste skicka EPUB‑inputStream, ImageSaveOptions och utströmmen till ConvertEPUB()-metoden för konvertering från EPUB till bild. Online EPUB‑konverterare

Aspose.HTML erbjuder en gratis online [EPUB till PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑konverterare som konverterar EPUB till PNG‑bild med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Du kan också vara intresserad av specifik bildformatkonvertering

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Skapa standardalternativinstans  
var options = new ImageSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Konvertera epub‑källa som presenteras av inmatningsström till xps. Resultatet är en xps‑fil som definieras av fullständig sökväg.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Indataström som konverteringskälla. Se strömspecifikationen i [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Konverteringsalternativ. Användning av [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑buffert. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Öppna en befintlig EPUB‑fil för läsning
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Förbered en sökväg för att spara den konverterade filen 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Skapa en instans av XpsSaveOptions. Ställ in sidstorlek och ändra bakgrundsfärgen till LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Anropa ConvertEPUB‑metoden för att konvertera EPUB till XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Konvertera epub‑källa som presenteras av inmatnings‑EPUB‑filsökväg till xps. Resultatet är en xps‑fil som definieras av fullständig sökväg.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | XpsSaveOptions | Konverteringsalternativ. Användning av [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑buffert. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Konvertera epub‑källa som presenteras av URL till xps‑fil som definieras av fullständig sökväg. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | Konverteringsalternativ. Användning av [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB-fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen.

Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Konvertera epub‑källa som presenteras av inmatnings[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) till xps. Resultatet är en xps‑fil som definieras av fullständig sökväg.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. Användning av [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Öppna en befintlig EPUB‑fil för läsning
import var stream = File.OpenRead(DataDir + "input.epub");

// Förbered en sökväg för att spara den konverterade filen 
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Initiera XpsSaveOptions 
var options = new XpsSaveOptions();
   
// Anropa ConvertEPUB‑metoden för att konvertera EPUB till XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Konvertera epub‑källa som presenteras av inmatnings‑EPUB‑filsökväg till xps. Resultatet är en xps‑fil som definieras av fullständig sökväg.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Konvertera epub‑källa som presenteras av URL till xps‑fil som definieras av fullständig sökväg. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. |
| outputPath | String | Fullständig .xps‑filväg som utdataresultat för konverteringen. |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Konvertera epub‑källan som presenteras via inmatnings‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) till xps. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| options | XpsSaveOptions | Konverteringsalternativ. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet som kommer att användas för att få en utström. Se exempel på ICreateStreamProvider‑implementation i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Skapa en instans av MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Öppna en befintlig EPUB‑fil för läsning
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Förbered en sökväg för att spara den konverterade filen 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Konvertera EPUB till XPS genom att använda MemoryStreamProvider‑klassen
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Få åtkomst till minnesströmmen som innehåller resultatdata
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Spola resultatdata till utfilen
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Konvertera epub‑källan som presenteras via inmatnings‑EPUB‑filens sökväg till xps. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | XpsSaveOptions | Konverteringsalternativ. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. |
| provider | ICreateStreamProvider | Implementering av gränssnittet som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittsimplementation som utdata‑buffert. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Konvertera epub‑källan som presenteras via URL till en xps‑fil definierad av fullständig sökväg. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | Konverteringsalternativ. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Konvertera epub‑källan som presenteras via inmatnings‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) till xps. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnitt, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Konvertera epub‑källan som presenteras via inmatnings‑EPUB‑filens sökväg till xps. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. Användning av [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnitt, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Konvertera epub‑källan som presenteras via URL till en xps‑fil definierad av fullständig sökväg. Resultatet är xps‑utdata definierat av en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Konverteringsalternativ. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnitt, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till XPS

En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Den utvecklades som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som grupperar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare XPS hittar du följande artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konvertera EPUB till XPS

För att konvertera EPUB till XPS‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Som exempel kan vi definiera källfilens sökväg som den första parametern till ConvertEPUB‑metoden. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffer. Vi kan använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt XpsSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av XpsSaveOptions‑klassen. Använd ConvertEPUB()‑metoden i den statiska Converter‑klassen för att spara EPUB som en xps‑fil. Du måste skicka EPUB‑källan, XpsSaveOptions och utdata‑buffer i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till XPS‑konverterare

Aspose.HTML erbjuder en gratis online‑konverterare för [EPUB till XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) som konverterar EPUB till XPS‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Skapa standardalternativinstans  
var options = new XpsSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Konvertera EPUB-källfil som anges med fullständig sökväg till DOCX. Resultatet är en docx-fil som definieras av den fullständiga sökvägen.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Konverteringskälla presenterad via inmatnings‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Skapa standardalternativinstans  
var options = new DocSaveOptions();   

// Initiera konverteringsprocessen
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg till DOCX. Resultatet är en docx‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB-källfilens sökväg som inparameter. |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definiera standardalternativinstans
var options = new DocSaveOptions();

// Starta konverteringsprocessen
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Konvertera EPUB‑källa som presenteras av URL. Resultatet är en docx‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑användning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definiera standardalternativinstans
var options = new DocSaveOptions();

// Starta konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Konvertera EPUB‑källa som presenteras av data‑inmatningsström. Resultatet är en docx‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Skapa standardalternativinstans  
var options = new DocSaveOptions();   

// Initiera konverteringsprocessen med standardkonfiguration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg till DOCX. Resultatet är en docx‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Konverteringsalternativ. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definiera standardalternativinstans
var options = new DocSaveOptions();

// Starta konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Konvertera EPUB‑källa som presenteras av URL. Resultatet är en docx‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑användning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Fullständig .docx‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formulärets konverteringsresultats filväg
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Skapa standardalternativinstans  
var options = new DocSaveOptions();

// Initiera konverteringsprocessen med standardkonfiguration  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Konvertera EPUB-källa som inmatningsström till DOCX. Resultatet är en docx-fil som bildas av en ICreateStreamProvider-implementation.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions();   

// Initiera konverteringsprocessen
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Konvertera EPUB‑källa som anges med fullständig filsökväg till DOCX. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑implementation.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions ();   

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Konvertera EPUB‑källa som presenteras av URL. Resultatet är utdata som bildas av en implementation av ICreateStreamProvider‑gränssnittet.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑användning gör att du kan finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, upplösningar, CSS osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt DocSaveOptions‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Skapa käll‑URL från inmatad filsökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions ();   

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Konvertera EPUB‑källa som presenteras av data‑inmatningsström. Resultatet är utdata som bildas av en implementation av ICreateStreamProvider‑gränssnittet.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑användning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions();   

// Initiera konverteringsprocessen med standardkonfiguration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Konvertera EPUB‑källa som anges med fullständig filsökväg till DOCX. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Konverteringsalternativ. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions ();   

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Konvertera EPUB‑källa som anges med URL. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑användning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att få en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till DOCX

DOCX är ett välkänt format för Microsoft Word‑dokument. Detta format är populärt eftersom det stöder ett brett spektrum av formateringsfunktioner och erbjuder användare en mängd alternativ för att skapa vilken typ av dokument som helst. DOCX‑filer kan öppnas med Word 2007 och senare versioner men inte med de äldre versionerna av MS Word, som stödjer DOC‑filändelser. EPUB‑till‑DOCX‑konvertering krävs ofta för att dra nytta av DOCX‑formatet för specifika användaruppgifter.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

Detta avsnitt ger information om listan över stödda EPUB‑konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)‑klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I EPUB‑Converter‑DOCX‑specifika guiden hittar du följande artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till DOCX

För att konvertera EPUB till DOCX‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med ett antal föredragna parametrar som sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av DocSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en docx‑fil. Du måste skicka EPUB‑källan som filväg eller inmatningsström samt Url, en DocSaveOptions‑instans och utdata‑bufferten i någon form för att initiera konverteringsprocessen. Du kan använda en konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till DOCX‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑konverterare som konverterar EPUB till DOCX‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Skapa standardalternativinstans  
var options = new DocSaveOptions();   

// Initiera konverteringsprocessen med standardkonfiguration 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Konvertera EPUB-källa som presenteras med dataindataström. Resultatet är en pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | EPUB-källfilens sökväg som inparameter. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formresultatfilens sökväg  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions();   

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är en pdf‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definiera standardalternativinstans
var options = new PdfSaveOptions();

// Starta konverteringsprocessen
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Konvertera EPUB‑källa som presenteras av URL. Resultatet är en pdf‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`filbehörigheter`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definiera standardalternativinstans
var options = new com.aspose.html.saving.PdfSaveOptions();

// Starta konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Konvertera EPUB-källa som presenteras med dataindataström. Resultatet är en pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formresultatfilens sökväg  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions();   

// Initiera konverteringsprocessen med standardkonfiguration 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Konvertera EPUB-källa som presenteras med dataindataström. Resultatet är en pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definiera standardalternativinstans
var options = new PdfSaveOptions();

// Starta konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Konvertera EPUB‑källa som presenteras av URL. Resultatet är en pdf‑fil som bildas av utdatafilsökvägen.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`filbehörigheter`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Fullständig .pdf‑sökväg som utdata för konverteringsresultatet. |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Skapa utdatafilens resultatsökväg
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definiera standardalternativinstans
var options = new PdfSaveOptions();

// Starta konverteringsprocessen med standardkonfiguration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Konvertera EPUB‑källa som presenteras via en data‑inmatningsström. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions ();   

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Konvertera EPUB‑källa som presenteras via fullständig filsökväg till PDF. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions();   

// Initiera konverteringsprocessen  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Konvertera EPUB‑källa som anges med URL. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`filbehörigheter`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definiera standardalternativinstans
var options = new PdfSaveOptions();

// Initiera konverteringsprocessen
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Konvertera EPUB‑källa som presenteras via en data‑inmatningsström. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittimplementation.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Indataström som konverteringskälla. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Konverteringsalternativ. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)objektanvändning gör att du kan finjustera renderingsprocessen; du kan ange [`page size`](...), [`margins`](...), [`CSS media-type`](...), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvudfunktionen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. Paketet [`com.aspose.html.converters`](../) ger enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)-konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öppna befintlig fil för läsning som ström  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions ();   

// Initiera konverteringsprocessen med standardkonfigurationsobjektet  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Konvertera EPUB‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är utdata som bildas av en implementation av ICreateStreamProvider‑gränssnittet.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | EPUB‑källfilens sökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Konverteringsalternativ. Användning av [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions)-objektet gör det möjligt att finjustera renderingsprocessen; du kan ange sidstorlek, marginaler, CSS osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulär för källfilens sökväg
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Skapa standardalternativinstans  
var options = new PdfSaveOptions();   

// Initiera konverteringsprocessen med standardkonfigurationsobjektet 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Konvertera EPUB‑källa som anges med URL. Resultatet är utdata som bildas av en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | EPUB-käll-URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration)-kontextobjektet som används för att konfigurera miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen; du kan ange [`sidstorlek`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marginaler`](../../../com.aspose.html.drawing/page/margin/), [`filbehörigheter`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS‑mediatyp`](../../../com.aspose.html.rendering/mediatype/), osv. Se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)‑gränssnittet, som kommer att användas för att erhålla en utström. Se avancerat exempel i [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Anmärkningar

Hur man konverterar EPUB till PDF

EPUB är ett e‑bokformat som tillhandahåller ett standardiserat digitalt publiceringsformat. Det skapades av International Digital Publishing Forum ([IDPF](http://idpf.org/)) och stöds nu av många e‑läsare och mjukvaruapplikationer. EPUB‑till‑PDF‑konvertering krävs ofta för att utnyttja PDF‑formatet. PDF‑filformatet har full förmåga att innehålla information såsom text, bilder, hyperlänkar, formulärfält, rich media, metadata osv. PDF‑filer kan öppnas i Adobe Acrobat Reader/Writer och de flesta moderna webbläsare som Chrome, Safari, Firefox. De är optimerade för utskrift och är idealiska för att skapa fysiska kopior av dina dokument; du kan också konfigurera säkerhetsinställningarna för PDF.

Huvuddragen i Aspose.HTML är konverteringsfunktionen. EPUB är ett öppet XML‑baserat format för digitala böcker och publikationer, som kan visas och läsas på smartphones, surfplattor och datorer. paketet com.aspose.html.converters implementerar enkel åtkomst till konverteringsmetoder. Det erbjuder ett brett utbud av [EPUB](https://docs.fileformat.com/ebook/epub/)‑konverteringar till populära format, såsom [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) och [GIF](https://docs.fileformat.com/image/gif/).

This sektion ger information om listan över stödjade EPUB-konverteringsscenarier och hur man utför dem med hjälp av en [`Converter`](../)-klass som samlar alla låg‑nivå konverteringsoperationer i en enda klass för att göra dem bekväma och enkla att använda. I den specifika guiden för EPUB‑konverterare till PDF hittar du följande artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konvertera EPUB till PDF

För att konvertera EPUB till PDF‑filformat bör du följa några steg:

Öppna en befintlig EPUB‑fil. Till exempel kan vi definiera källfilens sökväg som den första parametern till metoden ConvertEPUB. Som ett alternativ kan vi använda en inmatningsström eller ett Url‑objekt. Använd en känd eller anpassad ICreateStreamProvider‑gränssnittimplementation som utdata‑buffert. Vi kan också använda ett enklare alternativ som resultat‑utdatafilens sökväg. Skapa ett nytt PdfSaveOptions‑objekt med ett antal föredragna parametrar såsom sidstorlek, marginaler, CSS osv. Det är möjligt att använda standardinstansen av PdfSaveOptions‑klassen. Använd ConvertEPUB()-metoden i den statiska Converter‑klassen för att spara EPUB som en pdf‑fil. Du måste ange EPUB‑källan som filsökväg eller inmatningsström samt Url, PdfSaveOptions‑instans och utdata‑buffert i någon form för att initiera konverteringsprocessen. Du kan använda konfiguration som representerar [`configuration`](../../../com.aspose.html/configuration/)‑kontextobjektet som används för att ställa in miljöinställningarna för applikationen. Online EPUB till PDF‑konverterare

Aspose.HTML erbjuder en gratis online‑[EPUB till PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑konverterare som konverterar EPUB till PDF‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Skapa URL baserat på indatafilens sökväg
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Referera till ICreateStreamProvider‑gränssnittsimplementationen  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definiera standardalternativinstans
var options = new PdfSaveOptions();

// Initiera konverteringsprocessen med standardkonfigurationsobjektet
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
