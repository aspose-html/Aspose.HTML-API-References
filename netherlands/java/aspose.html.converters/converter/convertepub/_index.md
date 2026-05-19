---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter‑methode. Converteer EPUB‑bron die wordt gepresenteerd via een gegevens‑invoerstroom. Het resultaat is een bestand gevormd door het uitvoer‑bestandspad."
type: docs

url: /nl/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Converteer EPUB-bron opgegeven via gegevens‑invoerstroom. Het resultaat is een bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| options | ImageSaveOptions | Nieuwe gevormde afbeeldingsopties zoals formaat, resolutie enzovoort. Zie de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑klasse en de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Open bestaand bestand voor lezen als stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definieer uitvoer‑bestandspad
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieer standaardopties‑instantie
var options = new ImageSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Converteer EPUB-bron gepresenteerd via volledig bestandspad. Resultaat is afbeeldingsbestand gevormd door uitvoerbestandspad. Afbeeldingsformaat wordt gespecificeerd door ImageSaveOptions-object.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad als invoerparameter. |
| options | ImageSaveOptions | Gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definieer standaard ImageSaveOptions‑objectinstantie
var options = new ImageSaveOptions(); 

// Start conversieproces
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Converteer EPUB-bron gedefinieerd door URL. Resultaat is afbeeldingsbestand gevormd door uitvoerbestandspad. Afbeeldingsformaat wordt gespecificeerd door ImageSaveOptions-object.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) specificeren, enz. Zie de [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)klasse. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieer standaardopties‑instantie
var options = new ImageSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Converteer EPUB-bron gepresenteerd via gegevensinvoerstroom. Resultaat is afbeeldingsbestand gevormd door uitvoerbestandspad. Afbeeldingsformaat wordt gespecificeerd door ImageSaveOptions-object.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Open bestaand bestand voor lezen als stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definieer uitvoer‑bestandspad
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieer standaardopties‑instantie
var options = new ImageSaveOptions();

// Start conversieproces met standaard configuratie‑object
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Converteer EPUB-bron gepresenteerd via volledig bestandspad. Resultaat is afbeeldingsbestand gevormd door uitvoerbestandspad. Afbeeldingsformaat wordt gespecificeerd door ImageSaveOptions-object.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad als invoerparameter. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) specificeren, enz. Zie de [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)klasse. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definieer standaard ImageSaveOptions‑objectinstantie
var options = new ImageSaveOptions(); 

// Start conversieproces met standaard configuratie‑object
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Converteer EPUB-bron gedefinieerd door URL. Resultaat is afbeeldingsbestand gevormd door uitvoerbestandspad. Afbeeldingsformaat wordt gespecificeerd door ImageSaveOptions-object.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype) specificeren, enz. Zie de [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)klasse. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Definieer de Url op basis van het bestaande EPUB‑bestand op het opgegeven pad. Definieer het uitvoer‑bestandspad. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet ook ImageSaveOptions en het Configuration‑object doorgeven aan de afbeeldingconversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Definieer uitvoer‑bestandspad
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Definieer standaardopties‑instantie
var options = new ImageSaveOptions(); 

// Start conversieproces met standaard configuratie‑object
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Converteer de epub‑bron die wordt gepresenteerd via de invoer‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) naar een afbeelding. Het resultaat is een afbeeldingsbestand dat wordt gevormd door de implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) specificeren, enz. Zie de [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)klasse. |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoer‑stream te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Maak standaardopties‑instantie aan  
var options = new ImageSaveOptions();    

// Start het conversieproces  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Converteer de EPUB‑bron die wordt gepresenteerd via een bestandspad naar een afbeelding. Het resultaat is een afbeeldingsbestand dat wordt gevormd door de implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Nieuwe gevormde afbeeldingsopties zoals formaat, resolutie enzovoort. Zie de [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑klasse en de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de interface, die wordt gebruikt om een uitvoer‑stream te verkrijgen. Meer info over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw ImageSaveOptions‑object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

EPUB naar JPG met twee regels code

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Open een bestaand EPUB‑bestand voor lezen.
import var stream = File.OpenRead(DataDir + "input.epub");

// Roep de ConvertEPUB-methode aan om de EPUB-code te converteren naar een JPG-afbeelding
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Converteer de EPUB-bron die via een URL wordt gepresenteerd naar een afbeelding. Het resultaat is een afbeeldingsbestand dat wordt gevormd door de implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) specificeren, enz. Zie de [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)klasse. |
| provider | ICreateStreamProvider | Implementatie van de interface, die wordt gebruikt om een uitvoer‑stream te verkrijgen. Meer info over providers vindt u in de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw ImageSaveOptions‑object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Maak standaardopties‑instantie aan  
var options = new ImageSaveOptions();

// Start het conversieproces  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Converteer de epub‑bron die wordt gepresenteerd via de invoer‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) naar een afbeelding. Het resultaat is een afbeeldingsbestand dat wordt gevormd door de implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface, die wordt gebruikt om een outputstream te verkrijgen. |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw ImageSaveOptions‑object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Maak standaardopties‑instantie aan  
var options = new ImageSaveOptions();    


// Start het conversieproces met de standaardconfiguratie.
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Converteer de EPUB-bron die via een bestandspad wordt gepresenteerd naar een afbeelding. Het resultaat is een afbeeldingsbestand dat wordt gevormd door de implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB-bron gedefinieerd door een bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface, die wordt gebruikt om een outputstream te verkrijgen. Zie het voorbeeld van ICreateStreamProvider-implementatie in de [Aspose-documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw ImageSaveOptions‑object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Definieer standaard ImageSaveOptions‑objectinstantie
var options = new ImageSaveOptions(); 

// Start conversieproces met standaard configuratie‑object
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Converteer epub-bron gepresenteerd via URL naar afbeelding. Resultaat is een afbeeldingsbestand gevormd door implementatie van de [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) interface.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het ImageSaveOptions‑object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de interface, die wordt gebruikt om een outputstream te verkrijgen. Zie het voorbeeld van ICreateStreamProvider-implementatie in de [Aspose-documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar afbeelding te converteren

EPUB is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt. Het werd gecreëerd door het International Digital Publishing Forum (IDPF) en wordt nu ondersteund door vele e‑readers en softwaretoepassingen.

Het converteren van EPUB‑bestanden naar het PNG‑formaat kan nuttig zijn als u bestanden wilt opnemen in een PowerPoint‑presentatie of per e‑mail wilt verzenden. Converteer ze alstublieft naar het afbeeldingsformaat en gebruik ze zoals u wilt! U kunt extra conversieparameters gebruiken om het gewenste resultaat te verkrijgen.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB‑conversiescenario’s en hoe u ze kunt uitvoeren met behulp van een Converter‑klasse die alle laag‑niveau conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter‑gids vindt u de volgende artikelen:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converteer EPUB naar afbeelding

Om EPUB naar een afbeeldingsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. In het voorbeeld gebruiken we de OpenRead()-methode van de System.IO.FileStream‑klasse om een EPUB‑bestand te openen en te lezen vanuit het bestandssysteem op het opgegeven pad. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoergegevensbuffer. Maak een nieuw ImageSaveOptions‑object aan met het vereiste ImageFormat. Standaard is de eigenschap Format PNG. Gebruik de ConvertEPUB()-methode van de Converter‑klasse om EPUB als een afbeelding op te slaan. U moet de EPUB‑inputStream, ImageSaveOptions en de uitvoer‑stream doorgeven aan de ConvertEPUB()-methode voor EPUB‑naar‑Afbeelding‑conversie. Online EPUB‑converters

Aspose.HTML biedt een gratis online [EPUB naar PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter die EPUB naar een PNG‑afbeelding converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

U bent misschien ook geïnteresseerd in specifieke afbeeldingsformaatconversie

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Maak standaardopties‑instantie aan  
var options = new ImageSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Converteer epub-bron gepresenteerd via invoerstroom naar xps. Resultaat is xps-bestand gedefinieerd door volledig pad.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Invoerstroom als conversie‑bron. Zie de Stream-specificatie in de [officiële bron](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen; je kunt de paginagrootte, marges, CSS, enz. specificeren. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bron‑bestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als output‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als resultaat‑output‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een xps‑bestand. Je moet de EPUB‑brondatum, XpsSaveOptions en de output‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Open een bestaand EPUB‑bestand voor lezen
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Bereid een pad voor om het geconverteerde bestand op te slaan
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Maak een instantie van XpsSaveOptions. Stel de paginagrootte in en wijzig de achtergrondkleur naar LightGray
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
   
  // Roep de ConvertEPUB‑methode aan om EPUB naar XPS te converteren
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Converteer epub-bron gepresenteerd via invoer-EPUB-bestandspad naar xps. Resultaat is xps-bestand gedefinieerd door volledig pad.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen; je kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), de [`marges`](../../../com.aspose.html.drawing/page/margin/), het [`CSS‑mediatype`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bron‑bestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als output‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als resultaat‑output‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een xps‑bestand. Je moet de EPUB‑brondatum, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), en de output‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Converteer epub-bron gepresenteerd via URL naar xps-bestand gedefinieerd door volledig pad. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen; je kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), de [`marges`](../../../com.aspose.html.drawing/page/margin/), het [`CSS‑mediatype`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten.

Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Converteer epub-bron gepresenteerd via invoer-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) naar xps. Resultaat is xps-bestand gedefinieerd door volledig pad.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen; je kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), de [`marges`](../../../com.aspose.html.drawing/page/margin/), het [`CSS‑mediatype`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Open een bestaand EPUB‑bestand voor lezen
import var stream = File.OpenRead(DataDir + "input.epub");

// Bereid een pad voor om het geconverteerde bestand op te slaan 
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Initialiseer XpsSaveOptions 
var options = new XpsSaveOptions();
   
// Roep de ConvertEPUB‑methode aan om EPUB naar XPS te converteren
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Converteer epub-bron gepresenteerd via invoer-EPUB-bestandspad naar xps. Resultaat is xps-bestand gedefinieerd door volledig pad.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object stelt u in staat om het renderingsproces af te stemmen; u kunt de paginagrootte, marges, CSS, enzovoort opgeven. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Converteer epub-bron gepresenteerd via URL naar xps-bestand gedefinieerd door volledig pad. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object stelt u in staat om het renderingsproces af te stemmen; u kunt de paginagrootte, marges, CSS, enzovoort opgeven. |
| outputPath | String | Volledig .xps‑bestandspad als uitvoer van de conversieresultaat. |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start het conversieproces met de standaardconfiguratie 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Converteer de epub‑bron die wordt gepresenteerd via de invoer‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) naar xps. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑object stelt u in staat om het renderingsproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort opgeven. |
| provider | ICreateStreamProvider | Implementatie van de interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie het ICreateStreamProvider‑implementatievoorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Maak een instantie van MemoryStreamProvider aan
 using var streamProvider = new MemoryStreamProvider();

 // Open een bestaand EPUB‑bestand voor lezen
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Bereid een pad voor om het geconverteerde bestand op te slaan
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Converteer EPUB naar XPS met behulp van de MemoryStreamProvider‑klasse
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Krijg toegang tot de geheugenstroom die de resultaatgegevens bevat
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Schrijf de resultaatgegevens naar het uitvoerbestand
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Converteer de epub‑bron die wordt gepresenteerd via het invoer‑EPUB‑bestandspad naar xps. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)object stelt u in staat om het renderingsproces af te stemmen; u kunt de paginagrootte, marges, CSS, enzovoort opgeven. |
| provider | ICreateStreamProvider | Implementatie van de interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bron‑bestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als output‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als resultaat‑output‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een xps‑bestand. Je moet de EPUB‑brondatum, XpsSaveOptions en de output‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Converteer de epub‑bron die wordt gepresenteerd via een URL naar een xps‑bestand gedefinieerd door het volledige pad. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑object stelt u in staat om het renderingsproces af te stemmen; u kunt de paginagrootte, marges, CSS, enzovoort opgeven. Zie de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Converteer de epub‑bron die wordt gepresenteerd via de invoer‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) naar xps. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑object stelt u in staat om het renderingsproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort opgeven. |
| provider | ICreateStreamProvider | Implementatie van [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Converteer de epub‑bron die wordt gepresenteerd via het invoer‑EPUB‑bestandspad naar xps. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen; je kunt de paginagrootte, marges, CSS, enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Converteer de epub‑bron die wordt gepresenteerd via een URL naar een xps‑bestand gedefinieerd door het volledige pad. Het resultaat is xps‑uitvoergegevens gedefinieerd door een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Conversie‑opties. Het gebruik van het [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)‑object stelt u in staat om het renderingsproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort opgeven. Zie de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie een geavanceerd voorbeeld in de [Aspose‑documentatie](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar XPS te converteren

Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF‑bestandsformaat en lijkt op het PDF‑formaat, maar gebruikt XML voor lay-out, weergave en afdrukinformatie van een document.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie geeft informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe je ze uitvoert met behulp van de [`Converter`](../) klasse die alle low‑level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter XPS‑specifieke gids vind je het volgende artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converteer EPUB naar XPS

Om EPUB naar het XPS‑bestandsformaat te converteren, moet je een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen een eenvoudigere alternatieve optie gebruiken als uitvoer‑bestandspad. Maak een nieuw XpsSaveOptions‑object aan met een aantal voorkeursparameters zoals paginagrootte, marges, CSS enzovoort. Het is mogelijk om de standaardinstantie van de XpsSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om het EPUB‑bestand op te slaan als een xps‑bestand. U moet de EPUB‑brondatum, XpsSaveOptions en de uitvoer‑databuffer in welke vorm dan ook doorgeven om het conversieproces te starten. U kunt de configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑XPS‑converter

Aspose.HTML biedt een gratis online [EPUB naar XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) converter die EPUB naar een XPS‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Maak standaardopties‑instantie aan  
var options = new XpsSaveOptions();

// Start conversieproces met standaard configuratie
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Converteer EPUB-bronbestand opgegeven via volledig pad naar DOCX. Het resultaat is een docx‑bestand gedefinieerd door het volledige pad.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | Conversie‑bron gepresenteerd via de invoer‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();   

// Start conversieproces
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Converteer EPUB-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is docx-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad als invoerparameter. |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieer standaardopties‑instantie
var options = new DocSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Converteer EPUB-bron gepresenteerd via URL. Resultaat is docx-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieer standaardopties‑instantie
var options = new DocSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Converteer EPUB-bron gepresenteerd via gegevensinvoerstroom. Resultaat is docx-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();   

// Start het conversieproces met de standaardconfiguratie 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Converteer EPUB-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is docx-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Conversie-opties. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de paginagrootte, marges, CSS, enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieer standaardopties‑instantie
var options = new DocSaveOptions();

// Start conversieproces met standaardconfiguratie
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Converteer EPUB-bron gepresenteerd via URL. Resultaat is docx-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Volledig .docx-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Bestandspad van het formulierconversieresultaat
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();

// Start het conversieproces met de standaardconfiguratie.
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Converteer EPUB-bron als invoerstroom naar DOCX. Het resultaat is een docx‑bestand gevormd door een ICreateStreamProvider‑implementatie.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();   

// Start conversieproces
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Converteer EPUB‑bron opgegeven via volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑implementatie.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions ();   

// Start het conversieproces  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Converteer EPUB-bron gepresenteerd via URL. Resultaat is uitvoergegevens gevormd door ICreateStreamProvider interface-implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de paginagrootte, marges, resoluties, CSS, enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw DocSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Maak bron‑URL van invoer‑bestandspad.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions ();   

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Converteer EPUB-bron gepresenteerd via gegevensinvoerstroom. Resultaat is uitvoergegevens gevormd door ICreateStreamProvider interface-implementatie.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();   

// Start het conversieproces met de standaardconfiguratie 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Converteer EPUB‑bron opgegeven via volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Conversie-opties. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions ();   

// Start het conversieproces  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Converteer EPUB‑bron opgegeven via URL. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. zien. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die wordt gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar DOCX te converteren

DOCX is een bekend formaat voor Microsoft Word-documenten. Dit formaat is populair omdat het een breed scala aan opmaakfuncties ondersteunt en gebruikers verschillende mogelijkheden biedt om elk type document te maken. DOCX‑bestanden kunnen worden geopend met Word 2007 en latere versies, maar niet met de oudere versies van MS Word, die DOC‑bestandsextensies ondersteunen. Conversie van EPUB naar DOCX is vaak nodig om gebruik te maken van het DOCX‑formaat voor specifieke gebruikerstaken.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Dit gedeelte biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑bewerkingen in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB‑Converter DOCX‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converteer EPUB naar DOCX

Om het EPUB‑naar‑DOCX‑bestandformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Bijvoorbeeld kunnen we het bronbestandspad definiëren als de eerste parameter van de ConvertEPUB‑methode. Gebruik een bekende of aangepaste implementatie van de ICreateStreamProvider‑interface als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatieve uitvoer‑bestandspad gebruiken. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enz. Het is mogelijk om de standaardinstantie van de DocSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een docx‑bestand. U moet de EPUB‑bron doorgeven als bestandspad of invoerstroom, evenals de Url, de DocSaveOptions‑instantie en de uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt een configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/)‑contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB‑naar‑DOCX‑converter

Aspose.HTML biedt een gratis online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑converter die EPUB naar DOCX‑bestanden converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Maak standaardopties‑instantie aan  
var options = new DocSaveOptions();   

// Start het conversieproces met de standaardconfiguratie 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Converteer EPUB-bron opgegeven via gegevens‑invoerstroom. Het resultaat is een pdf‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | EPUB‑bronbestandspad als invoerparameter. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formulier resultaat bestandspad  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions();   

// Start het conversieproces  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Converteer EPUB-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is pdf-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieer standaardopties‑instantie
var options = new PdfSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Converteer EPUB-bron gepresenteerd via URL. Resultaat is pdf-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marges`](../../../com.aspose.html.drawing/page/margin/), [`bestandsrechten`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieer standaardopties‑instantie
var options = new com.aspose.html.saving.PdfSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Converteer EPUB-bron opgegeven via gegevens‑invoerstroom. Het resultaat is een pdf‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formulier resultaat bestandspad  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions();   

// Start het conversieproces met de standaardconfiguratie 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Converteer EPUB-bron opgegeven via gegevens‑invoerstroom. Het resultaat is een pdf‑bestand gevormd door het uitvoer‑bestandspad.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieer standaardopties‑instantie
var options = new PdfSaveOptions();

// Start conversieproces met standaardconfiguratie
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Converteer EPUB-bron gepresenteerd via URL. Resultaat is pdf-bestand gevormd door uitvoerbestandspad.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marges`](../../../com.aspose.html.drawing/page/margin/), [`bestandsrechten`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Volledig .pdf-bestandspad als uitvoer van het conversieresultaat. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Stel uitvoer‑resultaatbestandspad samen
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieer standaardopties‑instantie
var options = new PdfSaveOptions();

// Start conversieproces met standaardconfiguratie
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Converteer EPUB‑bron gepresenteerd via gegevens‑invoerstroom. Resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions ();   

// Start het conversieproces  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Converteer EPUB‑bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die zal worden gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions();   

// Start het conversieproces  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Converteer EPUB‑bron opgegeven via URL. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marges`](../../../com.aspose.html.drawing/page/margin/), [`bestandsrechten`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, die zal worden gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definieer standaardopties‑instantie
var options = new PdfSaveOptions();

// Start conversieproces
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Converteer EPUB‑bron gepresenteerd via gegevens‑invoerstroom. Resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface‑implementatie.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Invoerstroom als conversiebron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Conversie-opties. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, die zal worden gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open XML‑gebaseerd formaat voor digitale boeken en publicaties, dat kan worden bekeken en gelezen op smartphones, tablets en computers. Het [`com.aspose.html.converters`](../) pakket implementeert gemakkelijke toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Open bestaand bestand voor lezen als stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions ();   

// Start het conversieproces met het standaard configuratie‑object  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Converteer EPUB-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is uitvoergegevens gevormd door ICreateStreamProvider interface-implementatie.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | EPUB‑bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | Conversie‑opties. Het [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) objectgebruik stelt u in staat het renderproces af te stemmen; u kunt de paginagrootte, marges, CSS, enzovoort specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, die zal worden gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulier bronbestandspad
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Maak standaardopties‑instantie aan  
var options = new PdfSaveOptions();   

// Start het conversieproces met het standaard configuratie‑object 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Converteer EPUB‑bron opgegeven via URL. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑interface‑implementatie.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑bron‑URL – biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [configuratie](https://apireference.aspose.com/html/net/aspose.html/configuration) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gebruik stelt u in staat het renderproces af te stemmen; u kunt de [`paginagrootte`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`marges`](../../../com.aspose.html.drawing/page/margin/), [`bestandsrechten`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enzovoort specificeren. Zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) interface, die zal worden gebruikt om een uitvoerstroom te verkrijgen. Zie geavanceerd voorbeeld in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Opmerkingen

Hoe EPUB naar PDF te converteren

EPUB is een e‑book‑bestandformaat dat een standaard digitaal publicatieformaat biedt. Het is gemaakt door de International Digital Publishing Forum ([IDPF](http://idpf.org/)), en wordt nu ondersteund door vele e‑readers en softwaretoepassingen. Conversie van EPUB naar PDF is vaak nodig om gebruik te maken van het PDF‑formaat. Het PDF‑bestandformaat heeft de volledige mogelijkheid om informatie zoals tekst, afbeeldingen, hyperlinks, formulier‑velden, rich media, metadata, enz. te bevatten. PDF‑bestanden kunnen worden geopend in Adobe Acrobat Reader/Writer en de meeste moderne browsers zoals Chrome, Safari, Firefox. Ze zijn geoptimaliseerd voor afdrukken en zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt ook de beveiligingsinstellingen voor PDF configureren.

Het belangrijkste kenmerk van Aspose.HTML is de conversiefunctie. EPUB is een open op XML gebaseerd formaat voor digitale boeken en publicaties, die kan worden bekeken en gelezen op smartphones, tablets en computers. Het pakket com.aspose.html.converters biedt eenvoudige toegang tot conversiemethoden. Het biedt een breed scala aan [EPUB](https://docs.fileformat.com/ebook/epub/) conversies naar populaire formaten, zoals [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) en [GIF](https://docs.fileformat.com/image/gif/).

Deze sectie biedt informatie over de lijst met ondersteunde EPUB-conversiescenario's en hoe u ze kunt uitvoeren met behulp van een [`Converter`](../) klasse die alle low-level conversie‑operaties in één klasse groepeert om ze comfortabel en eenvoudig te gebruiken. In de EPUB Converter PDF‑specifieke gids vindt u het volgende artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB naar PDF converteren

Om EPUB naar PDF bestandsformaat te converteren, moet u een paar stappen volgen:

Open een bestaand EPUB‑bestand. Als voorbeeld kunnen we het bronbestandspad definiëren als eerste parameter van de ConvertEPUB‑methode. Als alternatief kunnen we een invoerstroom of Url‑object gebruiken. Gebruik een bekende of aangepaste ICreateStreamProvider‑interface‑implementatie als uitvoer‑databuffer. We kunnen ook een eenvoudigere alternatief gebruiken als resultaat‑uitvoer‑bestandspad. Maak een nieuw PdfSaveOptions‑object aan met een aantal gewenste parameters zoals paginagrootte, marges, CSS, enzovoort. Het is mogelijk om de standaardinstantie van de PdfSaveOptions‑klasse te gebruiken. Gebruik de ConvertEPUB()‑methode van de statische Converter‑klasse om EPUB op te slaan als een pdf‑bestand. U moet de EPUB‑bron‑datum doorgeven als bestandspad of invoerstroom, evenals Url, PdfSaveOptions‑instantie en uitvoer‑databuffer in welke vorm dan ook om het conversieproces te starten. U kunt configuratie gebruiken die het [`configuration`](../../../com.aspose.html/configuration/) contextobject vertegenwoordigt dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. Online EPUB naar PDF converter

Aspose.HTML biedt een gratis online [EPUB naar PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter die EPUB naar PDF‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Maak Url op basis van invoer‑bestandspad
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verwijs naar de ICreateStreamProvider‑interface‑implementatie  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definieer standaardopties‑instantie
var options = new PdfSaveOptions();

// Start conversieproces met standaard configuratie‑object
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
