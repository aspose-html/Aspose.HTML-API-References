---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Converter. Unisce la sorgente del modello presentata da HTMLDocument con i dati del modello XML JSON. Il risultato è un file html generato dal percorso del file di output."
type: docs

url: /it/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Unisci la sorgente del modello presentata da [`HTMLDocument`](../../../com.aspose.html/htmldocument/) con i dati del modello (XML, JSON). Il risultato è un file html generato dal percorso del file di output.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| template | HTMLDocument | Unione dello scheletro sorgente presentato da [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Documento HTML del modulo come sorgente di conversione
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Avvia il processo di conversione
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Libera le risorse
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Unisci la sorgente HTML del modello presentata da [`URL`](../../../com.aspose.html/url/) con i dati del modello (XML, JSON). Il risultato è un file HTML generato nel percorso del file di output.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Unione dello skeleton della sorgente HTML presentata da [`URL`](../../../com.aspose.html/url/). |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL della sorgente skeleton html del modulo
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Unisci la sorgente HTML del modello presentata da [`URL`](../../../com.aspose.html/url/) con i dati del modello (XML, JSON). Il risultato è un file HTML generato nel percorso del file di output.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Unione dello skeleton della sorgente HTML presentata da [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL della sorgente skeleton html del modulo
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Unisci la sorgente HTML del modello presentata da un percorso di file completo con i dati del modello (XML, JSON). Il risultato è un file html generato dal percorso del file di output.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Unione dello skeleton della sorgente HTML presentata da percorso file completo. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Unisci la sorgente HTML del modello presentata da un percorso di file completo con i dati del modello (XML, JSON). Il risultato è un file html generato dal percorso del file di output.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Unione dello skeleton della sorgente HTML presentata da percorso file completo. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Unisci la sorgente HTML del modello presentata come contenuto inline con i dati del modello (XML, JSON). Il risultato è un file html generato dal percorso del file di output.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Unione dello skeleton della sorgente HTML presentata da contenuto String inline. |
| baseUrl | String | URI di base del modello HTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Contenuto sorgente inline del modulo come modello
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Output del modulo come risultato dell'unione
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();
	  
      // Avvia il processo di conversione
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Vedi anche

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Unisci la sorgente HTML del modello presentata come contenuto inline con i dati del modello (XML, JSON). Il risultato è un file html generato dal percorso del file di output.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Unione dello skeleton della sorgente HTML presentata da contenuto String inline. |
| baseUrl | String | URI di base del modello HTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |
| outputPath | String | Percorso completo del file html come risultato di output della conversione. |

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Contenuto sorgente inline del modulo come modello
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // Percorso del file dati del modello XML (JSON) del modulo
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Definisci l'istanza dell'oggetto TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Output del modulo come risultato dell'unione
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Definisci l'istanza dell'oggetto configuration
   var configuration = new Configuration();

   // Definisci l'oggetto TemplateLoadOptions predefinito
   var options = new TemplateLoadOptions();

   // Avvia il processo di conversione con la configurazione predefinita
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Di seguito è il file dati da unire con la sorgente come modello

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Vedi anche

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Unisci la sorgente del modello presentata da [`HTMLDocument`](../../../com.aspose.html/htmldocument/) con i dati del modello (XML, JSON). Il risultato è un nuovo `HTMLDocument` creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| template | HTMLDocument | Unione dello scheletro sorgente presentato da [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();
      
      // Documento HTML del modulo come sorgente di conversione
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Avvia il processo di conversione
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Salva il risultato con le risorse collegate
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Unisci la sorgente HTML del modello presentata da [`URL`](../../../com.aspose.html/url/) con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Unione dello skeleton della sorgente HTML presentata da [`URL`](../../../com.aspose.html/url/). |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Crea l'URL per il file sorgente HTML scheletro
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Salva il risultato con le risorse collegate
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Unisci la sorgente HTML del modello presentata da [`URL`](../../../com.aspose.html/url/) con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Unione dello skeleton della sorgente HTML presentata da [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Crea l'URL per il file sorgente HTML scheletro
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Salva il risultato con le risorse collegate
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

Unisci la sorgente HTML del modello presentata da un percorso file completo con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Unione dello skeleton della sorgente HTML presentata da percorso file completo. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Salva il risultato con le risorse collegate
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Unisci la sorgente HTML del modello presentata da un percorso file completo con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Unione dello skeleton della sorgente HTML presentata da percorso file completo. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Percorso del file sorgente skeleton HTML del modulo
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Percorso file risultato del modulo
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione con la configurazione predefinita
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Salva il risultato con le risorse collegate
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Unisci la sorgente HTML del modello presentata da contenuto inline con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Unione dello skeleton della sorgente HTML presentata da contenuto String inline. |
| baseUrl | String | URI di base del modello HTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenuto sorgente inline del modulo come modello
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Output del modulo come risultato dell'unione
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione e salva il risultato
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Unisci la sorgente HTML del modello presentata da contenuto inline con i dati del modello (XML, JSON). Il risultato è un nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato che può essere salvato come file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Unione dello skeleton della sorgente HTML presentata da contenuto String inline. |
| baseUrl | String | URI di base del modello HTML. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |
| configuration | Configuration | La configurazione dell'ambiente. Rappresenta l'oggetto di contesto [`configuration`](../../../com.aspose.html/configuration/) che viene utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. |
| dati | TemplateData | Dati del modello per l'unione - sostituzione (XML, JSON). |
| options | TemplateLoadOptions | Istanza dell'oggetto [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) . Viene utilizzata per determinare se i nomi del modello e degli elementi dati corrispondono, indipendentemente dal maiuscolo/minuscolo (opzioni). |

### Valore di ritorno

Nuovo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) creato come risultato della conversione che può essere salvato tramite il percorso del file di output.

## Osservazioni

Unione modello

L'idea dell'unione dei modelli è creare un documento HTML basato su un modello HTML e popolarlo da una fonte di dati. Aspose.HTML fornisce la sintassi delle espressioni inline per lavorare con i modelli e vari tipi di fonti dati, come XML e JSON. Consulta [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dove puoi trovare ulteriori informazioni sull'unione dei modelli e sull'utilizzo del metodo ConvertTemplate().

Passaggi di conversione (unione)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fonte del modello. Definisci la fonte del modello HTML tramite file, [`URL`](../../../com.aspose.html/url/), istanza dell'oggetto [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o anche tramite contenuto inline. Risultato della conversione. Puoi ottenere direttamente l'HTMLDocument risultante o definire il percorso del file di output del risultato a seconda della firma del metodo. Crea un'istanza di [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Usa il metodo ConvertTemplate() della classe Converter per unire il modello con i dati. Puoi aggiungere anche [`configuration`](../../../com.aspose.html/configuration/) come parametro opzionale. Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenuto sorgente inline del modulo come modello
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Percorso del file dati del modello XML (JSON) del modulo
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definisci l'istanza dell'oggetto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Output del modulo come risultato dell'unione
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definisci l'istanza dell'oggetto configuration
      var configuration = new Configuration();

      // Definisci l'oggetto TemplateLoadOptions predefinito
      var options = new TemplateLoadOptions();

      // Avvia il processo di conversione e salva il risultato
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Vedi anche

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
