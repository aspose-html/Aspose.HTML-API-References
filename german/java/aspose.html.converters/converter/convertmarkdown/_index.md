---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter-Methode. Konvertiere die MD-Markdown-Quelle, die über einen Eingabestream bereitgestellt wird, zu HTML. Ergebnis ist ein HTMLDocument, das über den Ausgabepfad gespeichert werden kann."
type: docs

url: /de/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Konvertiere die MD (Markdown)-Quelle, die über einen Eingabestream bereitgestellt wird, zu HTML. Ergebnis ist [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das über den Ausgabepfad gespeichert werden kann.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | MD (Markdown)-Konvertierungs-Eingabedatenstrom. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Quellendatei als Stream öffnen
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Konvertierungsprozess starten
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Konvertierungsergebnis speichern
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Konvertiere die MD (Markdown)-Quelle, die über einen Eingabestream bereitgestellt wird, zu HTML. Ergebnis ist [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das über den Ausgabepfad gespeichert werden kann.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | MD (Markdown)-Konvertierungs-Eingabedatenstrom. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Quellendatei als Stream öffnen
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Konvertierungsprozess mit der Standard‑Konfiguration starten
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Konvertierungsergebnis speichern
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

MD (markdown)-Quelle, die über einen Eingabestream bereitgestellt wird, in html konvertieren. Ergebnis ist eine html-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | MD (Markdown)-Konvertierungs-Eingabedatenstrom. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Quellendatei als Stream öffnen
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Konvertierungsprozess starten
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

MD (markdown)-Quelle, die über einen Eingabestream bereitgestellt wird, in html konvertieren. Ergebnis ist eine html-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | MD (Markdown)-Konvertierungs-Eingabedatenstrom. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Quellendatei als Stream öffnen
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Konvertierungsprozess mit der Standard‑Konfiguration starten
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Konvertiere die MD (Markdown)-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu HTML. Ergebnis ist [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das über den Ausgabepfad gespeichert werden kann.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MD (Markdown)-Quelle. |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Konvertierungsprozess starten
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Konvertierungsergebnis als lokale Datei speichern
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Konvertiere die MD (Markdown)-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu HTML. Ergebnis ist [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das über den Ausgabepfad gespeichert werden kann.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MD (Markdown)-Quelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Konvertierungsergebnis als lokale Datei speichern
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

MD (markdown)-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in html konvertieren. Ergebnis ist eine html-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Pfad zur Quell-Markdown-Datei. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Konvertierungsprozess starten
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Siehe auch

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

MD (markdown)-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in html konvertieren. Ergebnis ist eine html-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Pfad zur Quell-Markdown-Datei. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Markdown-Konverter

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Konvertierungsschritte

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkenne eine vorhandene lokale MD-Datei oder erstelle einen Eingabedatenstrom als Konvertierungsquelle. Konvertierungsergebnis. Du kannst direkt [`HTMLDocument`](../../../com.aspose.html/htmldocument/) erhalten oder den Ausgabepfad des Ergebnisses abhängig von der Methodensignatur festlegen. Verwende die Methode ConvertMarkdown() der Klasse Converter, um MD als ein HTML-Ergebnis zu speichern. Du kannst außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Online MD-Konverter

Vielleicht sind Sie auch an einem kostenlosen Online-[MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) interessiert, der MD zu HTML mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden! Außerdem können Sie weitere Online-MD-Konverter prüfen: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) und passende [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
