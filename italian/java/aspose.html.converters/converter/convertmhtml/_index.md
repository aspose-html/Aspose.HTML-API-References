---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Converter. Converti la sorgente MHTML presentata dallo stream di input. Il risultato è un file xps generato dal percorso del file di output"
type: docs

url: /it/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Converti la sorgente MHTML presentata tramite [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Stream di dati mhtml (.mht) di input. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Percorso file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Converti la sorgente MHTML presentata tramite percorso file completo in XPS. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Percorso file sorgente del modulo
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Percorso file risultato del modulo
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definisci l'oggetto XpsSaveOptions predefinito
	var options = new XpsSaveOptions();

	// Avvia il processo di conversione
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Percorso file sorgente del modulo
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Percorso file risultato del modulo
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definisci l'oggetto XpsSaveOptions predefinito
	var options = new XpsSaveOptions();

	// Avvia il processo di conversione
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Converti la sorgente MHTML presentata tramite [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) di input. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati sorgente di conversione mhtml (.mht). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Percorso file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Converti la sorgente MHTML presentata tramite percorso file completo in XPS. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Percorso file sorgente del modulo
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Percorso file sorgente del modulo
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati sorgente di conversione mhtml (.mht). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Converti la sorgente MHTML presentata da un percorso file completo in XPS. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Converti la sorgente MHTML presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati sorgente di conversione mhtml (.mht). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Converti la sorgente MHTML presentata da un percorso file completo in XPS. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Converti la sorgente MHTML presentata da URL. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ti consente di regolare il processo di rendering. Per ulteriori informazioni vedi la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) è spesso necessaria per sfruttare il formato XPS in compiti specifici. Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications, creati da Microsoft.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) dove trovi informazioni su come convertire MHTML in XPS usando i metodi ConvertHTML() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in XPS

La classe Converter offre alcune conversioni specifiche da MHTML a XPS. Per convertire MHTML in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Fonte di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche utilizzare uno stream standard o personalizzato come fonte di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) online che converte MHTML in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Converti la sorgente MHTML presentata tramite stream di input. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Converti la sorgente MHTML presentata tramite percorso completo del file in DOCX. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente MHTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file DOCX generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Converti la sorgente MHTML presentata tramite stream di input. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Converti la sorgente MHTML presentata tramite percorso completo del file in DOCX. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Converti la sorgente MHTML presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file docx formato dal percorso del file di output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | Documento sorgente MHTML [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Converti la sorgente MHTML presentata da un percorso file completo in DOCX. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Converti la sorgente MHTML presentata da URL. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | Documento sorgente MHTML [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Converti la sorgente MHTML presentata da un percorso file completo in DOCX. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la configurazione come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Converti la sorgente MHTML presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | Documento sorgente MHTML [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'uso dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a DOCX è spesso necessaria per sfruttare il formato [DOCX](https://docs.fileformat.com/word-processing/docx/) per compiti specifici. DOCX è un formato ben noto per i documenti Microsoft Word. Può contenere un'ampia gamma di dati, inclusi testo, tabelle, grafica raster e vettoriale, video, suoni e diagrammi. Questo formato è popolare perché supporta funzionalità di formattazione complesse e offre agli utenti una varietà di opzioni per redigere qualsiasi tipo di documento.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dove trovi informazioni su come convertire MHTML in DOCX usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in DOCX

La classe Converter offre alcune conversioni specifiche da MHTML a DOCX. Per convertire MHTML in DOCX, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche utilizzare uno stream standard o personalizzato come sorgente di conversione. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la configurazione come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) online che converte MHTML in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Converti la sorgente MHTML presentata tramite stream di input. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Converti la sorgente MHTML presentata tramite percorso file completo in PDF. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Converti la sorgente MHTML presentata tramite stream di input. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Converti la sorgente MHTML presentata tramite percorso file completo in PDF. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente MHTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Converti la sorgente MHTML indicata con il percorso completo del file in PDF. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso del file sorgente MHTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Converti la sorgente MHTML presentata da URL. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Converti la sorgente MHTML indicata con il percorso completo del file in PDF. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Converti la sorgente MHTML presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'uso dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni vedere [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

La conversione da MHTML a PDF è spesso necessaria per sfruttare il formato [PDF](https://docs.fileformat.com/pdf/) per compiti specifici. PDF offre molti vantaggi che altri file non hanno. Ad esempio, molti programmi e app supportano i documenti PDF; i file PDF sono ottimizzati per la stampa e sono ideali per creare copie fisiche dei tuoi documenti; è possibile configurare le impostazioni di sicurezza per i file PDF – disabilitare la stampa, la modifica, l'uso di una firma elettronica, ecc.

Fai riferimento a [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dove trovi informazioni su come convertire MHTML in PDF usando i metodi ConvertMHTML() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in PDF

La classe Converter offre alcune conversioni specifiche di MHTML in PDF. Per convertire MHTML in PDF, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un URL remoto come origine della conversione. Puoi anche utilizzare uno [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online che converte MHTML in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Converti la sorgente MHTML presentata tramite stream di input in immagine. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Converti la sorgente MHTML presentata tramite percorso completo del file. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file immagine generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Converti la sorgente MHTML presentata tramite stream di input in immagine. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Converti la sorgente MHTML presentata tramite percorso completo del file. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Converti la sorgente MHTML presentata tramite URL. Il risultato è un file immagine generato dal percorso file di output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Converti la sorgente MHTML indicata con il percorso completo del file in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Converti la sorgente MHTML presentata da URL. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Converti la sorgente MHTML presentata dallo stream di input. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Flusso di dati di input per la conversione MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Converti la sorgente MHTML indicata con il percorso completo del file in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso completo del file sorgente MHTML. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[` interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere uno stream di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Converti la sorgente MHTML presentata da URL. Il risultato è dati di output formati dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceUrl | Url | URL del documento sorgente MHTML - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore MHTML

I file con estensione [MHTML](https://docs.fileformat.com/web/mhtml/) rappresentano un formato di archivio di pagine web che diverse applicazioni possono creare. Il formato è noto come archivio perché salva il codice HTML della pagina web e le risorse associate in un unico file. Queste risorse includono tutto ciò che è collegato alla pagina web, come immagini, applet, animazioni, file audio e così via. I file MHTML possono essere aperti in varie applicazioni come Internet Explorer e Microsoft Word. Le specifiche effettive del formato sono dettagliate in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Fai riferimento all'articolo, dove trovi informazioni su come convertire MHTML in immagini in diversi formati utilizzando i metodi ConvertMHTML() della classe Converter e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti MHTML in Immagine

La classe Converter offre alcune conversioni specifiche di MHTML in immagini. I formati supportati sono [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) e [TIFF](https://docs.fileformat.com/image/tiff/). Per convertire MHTML in immagine, dovresti seguire uno dei semplici scenari costituito da pochi passaggi:

Origine della conversione. Rileva un file MHTML (.mht) locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come origine della conversione. Puoi anche utilizzare uno stream standard o personalizzato come origine. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Il formato immagine predefinito è PNG. Puoi aggiungere anche configuration come parametro opzionale. Usa il metodo ConvertMHTML() della classe Converter per salvare MHTML come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore MHTML online

Aspose.HTML offre un gratuito [Convertitore MHTML in JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online che converte MHTML in file jpeg con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
