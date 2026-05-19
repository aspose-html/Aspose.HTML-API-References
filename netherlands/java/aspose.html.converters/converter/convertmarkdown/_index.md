---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter-methode. Converteer MD-markdownbron gepresenteerd via invoerstroom naar html. Resultaat is HTMLDocument dat kan worden opgeslagen via het uitvoerbestandspad."
type: docs

url: /nl/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Converteer MD (markdown) bron gepresenteerd via invoerstroom naar html. Resultaat is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) die kan worden opgeslagen via het uitvoerbestandspad.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | MD (Markdown) conversie-invoergegevensstroom. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Open bronbestand als stroom
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Start conversieproces
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Sla conversieresultaat op
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Converteer MD (markdown) bron gepresenteerd via invoerstroom naar html. Resultaat is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) die kan worden opgeslagen via het uitvoerbestandspad.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | MD (Markdown) conversie-invoergegevensstroom. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open bronbestand als stroom
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Start conversieproces met standaard configuratie
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Sla conversieresultaat op
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Converteer MD (markdown)-bron die wordt gepresenteerd via invoerstroom naar html. Resultaat is een html-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | MD (Markdown) conversie-invoergegevensstroom. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open bronbestand als stroom
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Start conversieproces
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Converteer MD (markdown)-bron die wordt gepresenteerd via invoerstroom naar html. Resultaat is een html-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | MD (Markdown) conversie-invoergegevensstroom. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Open bronbestand als stroom
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Converteer MD (markdown) bron gepresenteerd via volledig bestandspad naar html. Resultaat is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) die kan worden opgeslagen via het uitvoerbestandspad.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | MD (Markdown) bron volledig bestandspad. |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Start conversieproces
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Sla conversieresultaat op als lokaal bestand
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Converteer MD (markdown) bron gepresenteerd via volledig bestandspad naar html. Resultaat is [`HTMLDocument`](../../../com.aspose.html/htmldocument/) die kan worden opgeslagen via het uitvoerbestandspad.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | MD (Markdown) bron volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Start conversieproces met standaard configuratie
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Sla conversieresultaat op als lokaal bestand
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Converteer MD (markdown)-bron die wordt gepresenteerd via volledig bestandspad naar html. Resultaat is een html-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Pad naar bron‑Markdown‑bestand. Het wordt gecombineerd met het pad van de huidige map om een absolute URL te vormen. |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Start conversieproces
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Zie ook

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Converteer MD (markdown)-bron die wordt gepresenteerd via volledig bestandspad naar html. Resultaat is een html-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Pad naar bron‑Markdown‑bestand. Het wordt gecombineerd met het pad van de huidige map om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Markdown-converter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Conversiestappen

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Conversiebron. Detecteer een bestaand lokaal MD-bestand of maak een invoergegevensstroom als conversiebron. Conversieresultaat. Je kunt direct [`HTMLDocument`](../../../com.aspose.html/htmldocument/) verkrijgen of het uitvoerbestandspad van het resultaat definiëren, afhankelijk van de methodehandtekening. Gebruik de ConvertMarkdown()‑methode van de Converter‑klasse om MD op te slaan als een html‑resultaat. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Online MD-converter

U bent misschien ook geïnteresseerd in een gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) die MD naar HTML converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en krijg resultaten binnen enkele seconden! U kunt ook andere online MD-converters bekijken: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) en geschikte [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Start conversieproces met standaard configuratie
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
