---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Converter. Converte la sorgente SVG presentata da SVGDocument. Il risultato è un dato di output generato dall'implementazione dell'interfaccia ICreateStreamProvider"
type: docs

url: /it/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Avvia il processo di conversione con la configurazione predefinita
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Converti la sorgente SVG presentata da un percorso file completo in XPS. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Converti la sorgente SVG presentata da un percorso file completo in XPS. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Converti la sorgente SVG presentata da contenuto inline in XPS. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Converti la sorgente SVG presentata da contenuto inline in XPS. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Converti la sorgente SVG presentata tramite percorso file completo in DOCX. Il risultato è un file DOCX generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Converti la sorgente SVG presentata tramite percorso file completo in DOCX. Il risultato è un file DOCX generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Converti la sorgente SVG presentata come contenuto inline. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Converti la sorgente SVG presentata come contenuto inline. Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Percorso completo del file docx come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, sp);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file docx generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Converti la sorgente SVG presentata da un percorso file completo in DOCX. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Converti la sorgente SVG presentata da un percorso file completo in DOCX. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Converti la sorgente SVG presentata da contenuto inline in DOCX. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Vedi anche

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Converti la sorgente SVG presentata da contenuto inline in DOCX. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | DocSaveOptions | L'utilizzo dell'oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) dove trovi informazioni su come convertire SVG in [DOCX](https://docs.fileformat.com/word-processing/docx/) utilizzando i metodi ConvertSVG() della classe Converter e su come applicare i parametri [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in DOCX

La classe Converter offre molteplici conversioni specifiche di SVG in DOCX. Per convertire SVG in DOCX, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato DOCX con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in DOCX](https://products.aspose.app/svg/en/conversion/svg) online che converte SVG in DOCX con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto DocSaveOptions predefinito
      var options = new DocSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) in PDF. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Converti la sorgente SVG presentata tramite percorso file completo in PDF. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Converti la sorgente SVG presentata tramite percorso file completo in PDF. Il risultato è un file PDF generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Converti la sorgente SVG presentata come contenuto inline in PDF. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Converti la sorgente SVG presentata come contenuto inline in PDF. Il risultato è un file pdf generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Percorso completo del file pdf come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) in PDF. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Converti la sorgente SVG presentata da un percorso file completo in PDF. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Converti la sorgente SVG presentata da un percorso file completo in PDF. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Converti la sorgente SVG presentata da contenuto inline in PDF. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Vedi anche

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Converti la sorgente SVG presentata da contenuto inline in PDF. Il risultato è dato di output formato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | PdfSaveOptions | L'utilizzo dell'oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) dove trovi informazioni su come convertire SVG in PDF utilizzando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in PDF

La classe Converter offre molteplici conversioni specifiche di SVG in PDF. Per convertire SVG in PDF, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato PDF con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online che converte SVG in PDF con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto PdfSaveOptions predefinito
      var options = new PdfSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione con la configurazione predefinita
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Converti la sorgente SVG presentata tramite percorso file completo in immagine. Il risultato è un file immagine generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Converti la sorgente SVG presentata tramite percorso file completo in immagine. Il risultato è un file immagine generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Converti la sorgente SVG presentata come contenuto inline in immagine. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Converti la sorgente SVG presentata come contenuto inline in immagine. Il risultato è un file immagine generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| outputPath | String | Percorso completo del file immagine come risultato della conversione di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Converti la sorgente SVG presentata da un percorso file completo in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Converti la sorgente SVG presentata da un percorso file completo in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Converti la sorgente SVG presentata da contenuto inline in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Nota (vedi [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementazione personalizzata dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Vedi anche

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Converti la sorgente SVG presentata da contenuto inline in immagine. Il risultato è un dato di output generato dall'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | ImageSaveOptions | L'utilizzo dell'oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) consente di regolare il processo di rendering. È possibile specificare la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), i [`margins`](../../../com.aspose.html.drawing/page/margin/), il [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), ecc. |
| provider | ICreateStreamProvider | Implementazione dell'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), che verrà utilizzata per ottenere un flusso di output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dove trovi informazioni su come convertire SVG in JPG usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Altri articoli relativi a formati immagine popolari: [conversione SVG in PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversione SVG in BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversione SVG in GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) e [conversione SVG in TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converti SVG in Immagine

La classe Converter offre molte conversioni specifiche per SVG in immagine nei formati più popolari. Per convertire SVG in immagine, dovresti seguire uno dei semplici scenari costituiti da pochi passaggi:

Fonte di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come fonte di conversione. Puoi anche definire un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come fonte di conversione o persino utilizzare contenuto SVG inline fornito da una stringa. Risultato della conversione. Definisci il percorso del file di output o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) conosciuta o personalizzata come buffer di dati di output. Crea un nuovo oggetto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con impostazioni specifiche o predefinite. Nota che il formato immagine predefinito è PNG. Puoi anche aggiungere la [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Usa il metodo ConvertSVG() della classe Converter per salvare SVG come risultato immagine con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) online che converte SVG in JPG con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Altri convertitori di immagini popolari per formati diversi possono essere trovati qui: [Convertitore SVG in PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertitore SVG in BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertitore SVG in GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) e [Convertitore SVG in TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usa una delle implementazioni di ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisci l'oggetto ImageSaveOptions predefinito
      var options = new ImageSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Converti la sorgente SVG presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | SVGDocument | Sorgente di conversione presentata da [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Crea il documento SVG come sorgente di conversione
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Avvia il processo di conversione con la configurazione predefinita
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Converti la sorgente SVG presentata da [`URL`](../../../com.aspose.html/url/). Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Documento sorgente SVG [`URL`](../../../com.aspose.html/url/) - fornisce una rappresentazione oggetto di un identificatore universale (URL). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Converti la sorgente SVG presentata tramite percorso file completo in XPS. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Converti la sorgente SVG presentata tramite percorso file completo in XPS. Il risultato è un file XPS generato dal percorso file di output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Percorso file completo della sorgente SVG. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Converti la sorgente SVG presentata come contenuto inline in XPS. Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Converti la sorgente SVG presentata come contenuto inline in XPS. Il risultato è un file xps generato dal percorso del file di output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Stringa come contenuto SVG inline. |
| baseUri | String | L'URI di base del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| options | XpsSaveOptions | L'utilizzo dell'oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Percorso completo del file xps come risultato della conversione in output. |

## Osservazioni

Convertitore SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Fai riferimento all'[articolo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) dove trovi informazioni su come convertire SVG in XPS usando i metodi ConvertSVG() della classe [`Converter`](../) e su come applicare i parametri [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) e [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Converti SVG in XPS

La classe Converter offre molte conversioni specifiche per SVG in XPS. Per convertire SVG in XPS, dovresti seguire uno dei semplici scenari composti da pochi passaggi:

Sorgente di conversione. Rileva un file SVG locale esistente o un [`Url`](../../../com.aspose.html/url/) remoto come sorgente di conversione. Puoi anche definire [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) come sorgente di conversione o persino utilizzare contenuto SVG inline presentato da una stringa sorgente. Risultato della conversione. Definisci il percorso del file di output del risultato o utilizza un'implementazione dell'interfaccia [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) nota o personalizzata come buffer dei dati di output. Crea un nuovo oggetto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con impostazioni specifiche o predefinite. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Utilizza il metodo ConvertSVG() della classe Converter per salvare SVG come risultato XPS con tre o più parametri a seconda dello scenario dell'utente. Convertitore SVG online

Aspose.HTML offre un gratuito [Convertitore SVG in XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) online che converte SVG in XPS con alta qualità, in modo semplice e veloce. Basta caricare, convertire i tuoi file e ottenere i risultati in pochi secondi!

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formato del contenuto SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisci l'oggetto XpsSaveOptions predefinito
      var options = new XpsSaveOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
