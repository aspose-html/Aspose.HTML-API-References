---
title: "Converter.ConvertMarkdown"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Converter. Converte la sorgente MD markdown presentata dallo stream di input in html. Il risultato è HTMLDocument che può essere salvato tramite il percorso del file di output."
type: docs

url: /it/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Converti la sorgente MD (markdown) presentata dallo stream di input in html. Il risultato è [`HTMLDocument`](../../../com.aspose.html/htmldocument/) che può essere salvato tramite il percorso del file di output.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di dati di input per la conversione MD (Markdown). |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Apri file sorgente come stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Avvia il processo di conversione
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Salva risultato della conversione
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Converti la sorgente MD (markdown) presentata dallo stream di input in html. Il risultato è [`HTMLDocument`](../../../com.aspose.html/htmldocument/) che può essere salvato tramite il percorso del file di output.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di dati di input per la conversione MD (Markdown). |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Apri file sorgente come stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Salva risultato della conversione
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Converti la sorgente MD (markdown) presentata tramite stream di input in html. Il risultato è un file html creato dal percorso del file di output.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di dati di input per la conversione MD (Markdown). |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Apri file sorgente come stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Avvia il processo di conversione
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Converti la sorgente MD (markdown) presentata tramite stream di input in html. Il risultato è un file html creato dal percorso del file di output.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di dati di input per la conversione MD (Markdown). |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Apri file sorgente come stream
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Converti la sorgente MD (markdown) presentata da un percorso di file completo in html. Il risultato è [`HTMLDocument`](../../../com.aspose.html/htmldocument/) che può essere salvato tramite il percorso del file di output.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MD (Markdown). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Avvia il processo di conversione
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Salva risultato della conversione come file locale
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Converti la sorgente MD (markdown) presentata da un percorso di file completo in html. Il risultato è [`HTMLDocument`](../../../com.aspose.html/htmldocument/) che può essere salvato tramite il percorso del file di output.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MD (Markdown). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Avvia il processo di conversione con la configurazione predefinita
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Salva risultato della conversione come file locale
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Converti la sorgente MD (markdown) presentata tramite percorso completo del file in html. Il risultato è un file html creato dal percorso del file di output.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso al file Markdown sorgente. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Avvia il processo di conversione
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Vedi anche

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Converti la sorgente MD (markdown) presentata tramite percorso completo del file in html. Il risultato è un file html creato dal percorso del file di output.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso al file Markdown sorgente. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Convertitore Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Passaggi di conversione

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fonte di conversione. Rileva un file MD locale esistente o crea uno stream di dati di input come fonte di conversione. Risultato della conversione. Puoi ottenere direttamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definire il percorso del file di output del risultato in base alla firma del metodo. Usa il metodo ConvertMarkdown() della classe Converter per salvare MD come risultato html. Puoi anche aggiungere [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Convertitore MD online

Potresti anche essere interessato a un gratuito [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) che converte MD in HTML con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi! Inoltre puoi consultare altri convertitori MD online: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) e trovare i corrispondenti [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Percorso del file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
