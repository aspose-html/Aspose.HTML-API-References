---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter‑metod. Konvertera MD‑markdown‑källa som presenteras via inmatningsström till HTML. Resultatet är HTMLDocument som kan sparas via utdatafilens sökväg."
type: docs

url: /sv/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Konvertera MD (markdown)‑källa som presenteras via inmatningsström till HTML. Resultatet är [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas via utdatafilens sökväg.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MD (Markdown)‑konverteringsinmatningsdatastream. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Öppna källfil som ström
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiera konverteringsprocessen
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Spara konverteringsresultat
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Konvertera MD (markdown)‑källa som presenteras via inmatningsström till HTML. Resultatet är [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas via utdatafilens sökväg.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MD (Markdown)‑konverteringsinmatningsdatastream. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Öppna källfil som ström
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Spara konverteringsresultat
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Konvertera MD (markdown)‑källa som presenteras via inmatningsström till html. Resultatet är html‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MD (Markdown)‑konverteringsinmatningsdatastream. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Öppna källfil som ström
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiera konverteringsprocessen
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Se även

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Konvertera MD (markdown)‑källa som presenteras via inmatningsström till html. Resultatet är html‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MD (Markdown)‑konverteringsinmatningsdatastream. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Öppna källfil som ström
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Konvertera MD (markdown)‑källa som presenteras via fullständig filsökväg till HTML. Resultatet är [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas via utdatafilens sökväg.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | MD (Markdown)‑källas fullständiga filsökväg. |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiera konverteringsprocessen
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Spara konverteringsresultat som lokal fil
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Konvertera MD (markdown)‑källa som presenteras via fullständig filsökväg till HTML. Resultatet är [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas via utdatafilens sökväg.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | MD (Markdown)‑källas fullständiga filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiera konverteringsprocessen med standardkonfiguration
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Spara konverteringsresultat som lokal fil
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Konvertera MD (markdown)‑källa som presenteras via fullständig filsökväg till html. Resultatet är html‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökväg till käll‑Markdown‑fil. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiera konverteringsprocessen
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Se även

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Konvertera MD (markdown)‑källa som presenteras via fullständig filsökväg till html. Resultatet är html‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sökväg till käll‑Markdown‑fil. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Markdown‑konverterare

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konverteringssteg

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konverteringskälla. Detektera en befintlig lokal MD‑fil eller skapa inmatningsdatastream som konverteringskälla. Konverteringsresultat. Du kan erhålla direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) eller definiera resultatets utdatafilens sökväg beroende på metodsignatur. Använd ConvertMarkdown()-metoden i Converter‑klassen för att spara MD som ett HTML‑resultat. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativt parameter. Online‑MD‑konverterare

Du kan också vara intresserad av en gratis online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) som konverterar MD till HTML med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder! Du kan också kolla på andra online MD‑konverterare: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) och hitta lämpliga [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
