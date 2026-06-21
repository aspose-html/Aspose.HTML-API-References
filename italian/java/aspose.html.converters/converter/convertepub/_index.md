---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Converter. Converti la sorgente EPUB presentata tramite stream di input dati. Il risultato è un file generato dal percorso del file di output."
type: docs

url: /it/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Converti la sorgente EPUB presentata tramite stream di dati in input. Il risultato è un file generato dal percorso del file di output.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| options | ImageSaveOptions | Nuove opzioni immagine create come formato, risoluzione, ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) e la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Apri il file esistente per la lettura come stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definisci il percorso del file di output
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definisci l'istanza delle opzioni predefinite
var options = new ImageSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Converti la sorgente EPUB presentata da percorso file completo. Il risultato è un file immagine generato dal percorso file di output. Il formato immagine è specificato dall'oggetto ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB come parametro di input. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definisci l'istanza predefinita dell'oggetto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Avvia il processo di conversione
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Converti la sorgente EPUB definita da URL. Il risultato è un file immagine generato dal percorso file di output. Il formato immagine è specificato dall'oggetto ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions ti consente di regolare il processo di rendering. Puoi specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definisci l'istanza delle opzioni predefinite
var options = new ImageSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Converti la sorgente EPUB presentata da stream di input dati. Il risultato è un file immagine generato dal percorso file di output. Il formato immagine è specificato dall'oggetto ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Apri il file esistente per la lettura come stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definisci il percorso del file di output
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definisci l'istanza delle opzioni predefinite
var options = new ImageSaveOptions();

// Avvia il processo di conversione con l'oggetto di configurazione predefinito
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Converti la sorgente EPUB presentata da percorso file completo. Il risultato è un file immagine generato dal percorso file di output. Il formato immagine è specificato dall'oggetto ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB come parametro di input. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions ti consente di regolare il processo di rendering. Puoi specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definisci l'istanza predefinita dell'oggetto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Avvia il processo di conversione con l'oggetto di configurazione predefinito
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Converti la sorgente EPUB definita da URL. Il risultato è un file immagine generato dal percorso file di output. Il formato immagine è specificato dall'oggetto ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions ti consente di regolare il processo di rendering. Puoi specificare la [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), i [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), il [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), ecc. Vedi la classe [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Definisci l'Url in base al file EPUB esistente nel percorso specificato. Definisci il percorso del file di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare anche l'oggetto ImageSaveOptions e Configuration alla conversione in immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Definisci il percorso del file di output
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Definisci l'istanza delle opzioni predefinite
var options = new ImageSaveOptions(); 

// Avvia il processo di conversione con l'oggetto di configurazione predefinito
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Converti la sorgente epub fornita dallo [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) di input in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions ti consente di regolare il processo di rendering. Puoi specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crea l'istanza delle opzioni predefinite  
var options = new ImageSaveOptions();    

// Avvia il processo di conversione  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Converti la sorgente EPUB fornita dal percorso del file in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | ImageSaveOptions | Nuove opzioni immagine create come formato, risoluzione, ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) e la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere uno stream di output. Maggiori informazioni sui provider sono disponibili nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Crea un nuovo oggetto ImageSaveOptions con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

EPUB in JPG in due righe di codice

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Apri un file EPUB esistente per la lettura.
import var stream = File.OpenRead(DataDir + "input.epub");

// Invoca il metodo ConvertEPUB per convertire il codice EPUB in immagine JPG
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Converti la sorgente epub presentata tramite URL in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions ti consente di regolare il processo di rendering. Puoi specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere uno stream di output. Maggiori informazioni sui provider sono disponibili nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Crea un nuovo oggetto ImageSaveOptions con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crea l'istanza delle opzioni predefinite  
var options = new ImageSaveOptions();

// Avvia il processo di conversione  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Converti la sorgente epub fornita dallo [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) di input in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| fornitore | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Crea un nuovo oggetto ImageSaveOptions con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Crea l'istanza delle opzioni predefinite  
var options = new ImageSaveOptions();    


// Avvia il processo di conversione con la configurazione predefinita.
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Converti la sorgente epub presentata tramite percorso file in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Sorgente EPUB definita da percorso file. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere un flusso di output. Vedi l'esempio di implementazione di ICreateStreamProvider nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Crea un nuovo oggetto ImageSaveOptions con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Definisci l'istanza predefinita dell'oggetto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Avvia il processo di conversione con l'oggetto di configurazione predefinito
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Converti la sorgente epub presentata tramite URL in immagine. Il risultato è un file immagine generato dall'implementazione dell'interfaccia [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto ImageSaveOptions consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere un flusso di output. Vedi l'esempio di implementazione di ICreateStreamProvider nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in Immagine

EPUB è un formato di file e-book che fornisce uno standard per le pubblicazioni digitali. È stato creato dall'International Digital Publishing Forum (IDPF) e ora è supportato da molti e-reader e applicazioni software.

Convertire i file EPUB nel formato PNG può essere utile se devi includere i file in una presentazione PowerPoint o inviarli via email. Per favore convertili nel formato immagine e usali come desideri! Puoi utilizzare parametri di conversione aggiuntivi per ottenere il risultato desiderato.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe Converter che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida al Convertitore EPUB trovi i seguenti articoli:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Converti EPUB in Immagine

Per convertire il formato file EPUB in immagine, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Nell'esempio, utilizziamo il metodo OpenRead() della classe System.IO.FileStream per aprire e leggere un file EPUB dal file system nel percorso specificato. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Crea un nuovo oggetto ImageSaveOptions con il formato immagine richiesto. Per impostazione predefinita, la proprietà Format è PNG. Usa il metodo ConvertEPUB() della classe Converter per salvare l'EPUB come immagine. È necessario passare l'inputStream EPUB, ImageSaveOptions e lo stream di output al metodo ConvertEPUB() per la conversione da EPUB a immagine. Convertitori EPUB online

Aspose.HTML offre un convertitore online gratuito [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) che converte gli EPUB in immagini PNG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i file e ottenere i risultati in pochi secondi!

Potresti anche essere interessato alla conversione di formati immagine specifici

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crea l'istanza delle opzioni predefinite  
var options = new ImageSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Converti la sorgente epub presentata dallo stream di input in xps. Il risultato è un file xps definito da percorso completo.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Flusso di input come sorgente di conversione. Vedi la specifica dello Stream nella [fonte ufficiale](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Utilizza un'implementazione conosciuta o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo usare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i parametri preferiti, come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare i dati di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Convertitore EPUB in XPS online

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Apri un file EPUB esistente per la lettura
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Prepara un percorso per salvare il file convertito
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Crea un'istanza di XpsSaveOptions. Imposta la dimensione della pagina e cambia il colore di sfondo in LightGray
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
   
  // Chiama il metodo ConvertEPUB per convertire EPUB in XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Converti la sorgente epub presentata da percorso file EPUB di input in xps. Il risultato è un file xps definito da percorso completo.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Utilizza un'implementazione conosciuta o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo usare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i parametri preferiti, come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare i dati di origine dell'EPUB, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Convertitore EPUB in XPS online

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Converti la sorgente epub presentata da URL in un file xps definito da percorso completo. Vedi [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione.

Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Converti la sorgente epub presentata da [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) di input in xps. Il risultato è un file xps definito da percorso completo.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Apri un file EPUB esistente per la lettura
import var stream = File.OpenRead(DataDir + "input.epub");

// Prepara un percorso per il salvataggio del file convertito
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Inizializza XpsSaveOptions
var options = new XpsSaveOptions();
   
// Chiama il metodo ConvertEPUB per convertire EPUB in XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Converti la sorgente epub presentata da percorso file EPUB di input in xps. Il risultato è un file xps definito da percorso completo.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Converti la sorgente epub presentata da URL in un file xps definito da percorso completo. Vedi [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. |
| outputPath | String | Percorso completo del file .xps come risultato della conversione. |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Converti la sorgente epub fornita tramite l'input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) in xps. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere un flusso di output. Vedi l'esempio di implementazione di ICreateStreamProvider nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Crea un'istanza di MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Apri un file EPUB esistente per la lettura
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Prepara un percorso per salvare il file convertito
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Converti EPUB in XPS utilizzando la classe MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Ottieni l'accesso allo stream di memoria che contiene i dati del risultato
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Scrivi i dati del risultato nel file di output
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Converti la sorgente epub fornita tramite il percorso del file EPUB di input in xps. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia, che verrà utilizzata per ottenere un flusso di output. Vedi un esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Utilizza un'implementazione conosciuta o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo usare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i parametri preferiti, come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare i dati di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Convertitore EPUB in XPS online

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Converti la sorgente epub fornita tramite URL in un file xps definito da un percorso completo. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. Vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione della [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. Vedi un esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Converti la sorgente epub fornita tramite l'input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) in xps. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere un flusso di output. Vedi un esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Converti la sorgente epub fornita tramite il percorso del file EPUB di input in xps. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere un flusso di output. Vedi un esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Converti la sorgente epub fornita tramite URL in un file xps definito da un percorso completo. Il risultato è un dato di output xps definito da un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`dimensione della pagina`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margini`](../../../com.aspose.html.drawing/page/margin/), il [`tipo di media CSS`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere un flusso di output. Vedi un esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in XPS

Un file XPS rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. È stato sviluppato come sostituto del formato di file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter XPS, trovi il seguente articolo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Converti EPUB in XPS

Per convertire il formato di file EPUB in XPS, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. Usa un'implementazione conosciuta o personalizzata dell'interfaccia `ICreateStreamProvider` come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso del file di output. Crea un nuovo oggetto XpsSaveOptions con i numeri dei parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe XpsSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file xps. È necessario passare la data di origine dell'EPUB, XpsSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. È possibile utilizzare la configurazione che rappresenta il contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore online da EPUB a XPS

Aspose.HTML offre un convertitore online gratuito [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Crea l'istanza delle opzioni predefinite  
var options = new XpsSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Converti il file sorgente EPUB indicato con percorso completo in DOCX. Il risultato è un file docx definito dal percorso completo.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Fonte di conversione fornita tramite l'input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();   

// Avvia il processo di conversione
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Converti la sorgente EPUB presentata da percorso file completo in DOCX. Il risultato è un file docx generato dal percorso file di output.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB come parametro di input. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i[` margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definisci l'istanza delle opzioni predefinite
var options = new DocSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Converti la sorgente EPUB presentata da URL. Il risultato è un file docx generato dal percorso file di output.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'uso di [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definisci l'istanza delle opzioni predefinite
var options = new DocSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Converti la sorgente EPUB presentata da stream di input dati. Il risultato è un file docx generato dal percorso file di output.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();   

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Converti la sorgente EPUB presentata da percorso file completo in DOCX. Il risultato è un file docx generato dal percorso file di output.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definisci l'istanza delle opzioni predefinite
var options = new DocSaveOptions();

// Avvia il processo di conversione con configurazione predefinita
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Converti la sorgente EPUB presentata da URL. Il risultato è un file docx generato dal percorso file di output.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso di [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Percorso completo del file .docx come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Percorso del file risultato della conversione del modulo
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();

// Avvia il processo di conversione con la configurazione predefinita.
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Converti la sorgente EPUB come stream di input in DOCX. Il risultato è un file docx generato dall'implementazione di ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();   

// Avvia il processo di conversione
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Converti la sorgente EPUB presentata con percorso file completo in DOCX. Il risultato è dato dai dati di output generati dall'implementazione di [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions ();   

// Avvia il processo di conversione  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Converti la sorgente EPUB presentata da URL. Il risultato è un dato di output generato dall'implementazione dell'interfaccia ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'uso di [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, le risoluzioni, il CSS, ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto DocSaveOptions con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario passare la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Crea l'URL della sorgente dal percorso file di input.
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions ();   

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Converti la sorgente EPUB presentata da stream di input dati. Il risultato è un dato di output generato dall'implementazione dell'interfaccia ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso di [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario fornire la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();   

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Converti la sorgente EPUB presentata con percorso file completo in DOCX. Il risultato è costituito dai dati di output generati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario fornire la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions ();   

// Avvia il processo di conversione  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Converti la sorgente EPUB presentata tramite URL. Il risultato è costituito dai dati di output generati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso di [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) che verrà utilizzata per ottenere uno stream di output. Vedi esempio avanzato nella [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in DOCX

DOCX è un formato ben noto per i documenti Microsoft Word. Questo formato è popolare perché supporta un'ampia gamma di funzionalità di formattazione e offre agli utenti una varietà di opzioni per scrivere qualsiasi tipo di documento. I file DOCX possono essere aperti con Word 2007 e versioni successive, ma non con le versioni precedenti di MS Word, che supportano le estensioni di file DOC. La conversione da EPUB a DOCX è spesso necessaria per sfruttare il formato DOCX per attività specifiche dell'utente.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando la classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter DOCX, trovi il seguente articolo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in DOCX

Per convertire il formato file EPUB in DOCX, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file di origine come primo parametro del metodo ConvertEPUB. Usa un'implementazione nota o personalizzata dell'interfaccia ICreateStreamProvider come buffer di dati di output. Possiamo utilizzare un'alternativa più semplice come percorso di output del risultato. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con diversi parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe DocSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file docx. È necessario fornire la data di origine dell'EPUB come percorso file o stream di input, così come Url, istanza di DocSaveOptions e buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) utilizzato per impostare le impostazioni ambientali dell'applicazione. Convertitore EPUB in DOCX online

Aspose.HTML offre un convertitore online gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) che converte i file EPUB in DOCX con alta qualità, in modo facile e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crea l'istanza delle opzioni predefinite  
var options = new DocSaveOptions();   

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Converti la sorgente EPUB presentata tramite stream di dati in input. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Percorso del file sorgente EPUB come parametro di input. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Percorso file risultato del modulo  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions();   

// Avvia il processo di conversione  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Converti la sorgente EPUB presentata da percorso file completo in PDF. Il risultato è un file pdf generato dal percorso file di output.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definisci l'istanza delle opzioni predefinite
var options = new PdfSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Converti la sorgente EPUB presentata da URL. Il risultato è un file pdf generato dal percorso file di output.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'utilizzo di [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), i [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definisci l'istanza delle opzioni predefinite
var options = new com.aspose.html.saving.PdfSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Converti la sorgente EPUB presentata tramite stream di dati in input. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Percorso file risultato del modulo  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions();   

// Avvia il processo di conversione con la configurazione predefinita
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Converti la sorgente EPUB presentata tramite stream di dati in input. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definisci l'istanza delle opzioni predefinite
var options = new PdfSaveOptions();

// Avvia il processo di conversione con configurazione predefinita
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Converti la sorgente EPUB presentata da URL. Il risultato è un file pdf generato dal percorso file di output.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo di [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), i [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file .pdf come risultato della conversione in output. |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Crea il percorso del file di output risultante
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definisci l'istanza delle opzioni predefinite
var options = new PdfSaveOptions();

// Avvia il processo di conversione con configurazione predefinita
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Converti la sorgente EPUB presentata tramite stream di input dati. Il risultato è il dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions ();   

// Avvia il processo di conversione  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Converti la sorgente EPUB presentata tramite percorso completo del file in PDF. Il risultato è il dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions();   

// Avvia il processo di conversione  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Converti la sorgente EPUB presentata tramite URL. Il risultato è costituito dai dati di output generati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'utilizzo di [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), i [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definisci l'istanza delle opzioni predefinite
var options = new PdfSaveOptions();

// Avvia il processo di conversione
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Converti la sorgente EPUB presentata tramite stream di input dati. Il risultato è il dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di input come origine della conversione. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

La caratteristica principale di Aspose.HTML è la funzionalità di conversione. EPUB è un formato aperto basato su XML per libri digitali e pubblicazioni, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto [`com.aspose.html.converters`](../) implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni [EPUB](https://docs.fileformat.com/ebook/epub/) in formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Apri il file esistente per la lettura come stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions ();   

// Avvia il processo di conversione con l'oggetto di configurazione predefinito  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Converti la sorgente EPUB presentata da percorso file completo in PDF. Il risultato è un dato di output generato dall'implementazione dell'interfaccia ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente EPUB. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | Opzioni di conversione. L'uso dell'oggetto [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) consente di regolare il processo di rendering; è possibile specificare la dimensione della pagina, i margini, il CSS, ecc. Vedi la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Percorso file sorgente del modulo
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crea l'istanza delle opzioni predefinite  
var options = new PdfSaveOptions();   

// Avvia il processo di conversione con l'oggetto di configurazione predefinito 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Converti la sorgente EPUB presentata tramite URL. Il risultato è costituito dai dati di output generati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL sorgente EPUB - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo di [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering; è possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), i [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. Vedi la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'interfaccia [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), che verrà utilizzata per ottenere uno stream di output. Vedi un esempio avanzato nella [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Osservazioni

Come convertire EPUB in PDF

EPUB è un formato di file e‑book che fornisce uno standard per la pubblicazione digitale. È stato creato dall'International Digital Publishing Forum ([IDPF](http://idpf.org/)), e ora è supportato da molti lettori e applicazioni software. La conversione da EPUB a PDF è spesso necessaria per sfruttare il formato PDF. Il formato PDF ha piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi modulo, media ricchi, metadati, ecc. I file PDF possono essere aperti con Adobe Acrobat Reader/Writer e la maggior parte dei browser moderni come Chrome, Safari, Firefox. Sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è inoltre possibile configurare le impostazioni di sicurezza per il PDF.

Il principale punto di forza di Aspose.HTML è la funzionalità di conversione. EPUB è un formato basato su XML aperto per libri e pubblicazioni digitali, che può essere visualizzato e letto su smartphone, tablet e computer. Il pacchetto com.aspose.html.converters implementa un facile accesso ai metodi di conversione. Fornisce un'ampia gamma di conversioni di [EPUB](https://docs.fileformat.com/ebook/epub/) verso formati popolari, come [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), e [GIF](https://docs.fileformat.com/image/gif/).

Questa sezione fornisce informazioni sull'elenco degli scenari di conversione EPUB supportati e su come eseguirli utilizzando una classe [`Converter`](../) che raggruppa tutte le operazioni di conversione a basso livello in un'unica classe per renderle comode e facili da usare. Nella guida specifica per l'EPUB Converter PDF, trovi il seguente articolo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Converti EPUB in PDF

Per convertire il formato di file EPUB in PDF, dovresti seguire alcuni passaggi:

Apri un file EPUB esistente. Per esempio, possiamo definire il percorso del file sorgente come primo parametro del metodo ConvertEPUB. In alternativa, possiamo utilizzare uno stream di input o un'istanza di oggetto Url. Usa un'implementazione dell'interfaccia ICreateStreamProvider, nota o personalizzata, come buffer di dati di output. Possiamo anche utilizzare un'alternativa più semplice, come il percorso del file di output risultante. Crea un nuovo oggetto PdfSaveOptions con una serie di parametri preferiti come dimensione della pagina, margini, CSS, ecc. È possibile utilizzare l'istanza predefinita della classe PdfSaveOptions. Usa il metodo ConvertEPUB() della classe statica Converter per salvare l'EPUB come file PDF. È necessario fornire la data sorgente dell'EPUB come percorso del file o stream di input, così come Url, l'istanza PdfSaveOptions e il buffer di dati di output in qualsiasi forma per avviare il processo di conversione. Puoi utilizzare la configurazione che rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) usato per impostare le impostazioni dell'ambiente per l'applicazione. Convertitore EPUB in PDF online

Aspose.HTML offre un convertitore gratuito online [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) che converte i file EPUB in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Crea Url basato sul percorso del file di input
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Fai riferimento all'implementazione dell'interfaccia ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definisci l'istanza delle opzioni predefinite
var options = new PdfSaveOptions();

// Avvia il processo di conversione con l'oggetto di configurazione predefinito
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
