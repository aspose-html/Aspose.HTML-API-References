---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML per Java Riferimento API"
description: "HTMLDocument metodo. Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente il cui nome sarà costruito come output_file_name  _files."
type: docs

url: /it/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files".

```java
public void Save(Url url)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Locale [`URL`](../../url/) al file di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se l'`url` specificato non è un URL di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Metodo Save(Url)

È necessario specificare un percorso Url completo - 'outputFilePath' per il salvataggio del documento HTML. Il costruttore Url(url) crea un'istanza della classe [`Url`](../../url/) con l'url specificato. Quindi devi passare l'istanza al metodo Save(Url). Il documento sarà salvato nel file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files".

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Salva il contenuto e le risorse del documento usando il [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Il gestore delle risorse [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Vedi anche

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(String path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | String | Percorso del file system locale al file di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se il `path` specificato non è un percorso di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Il metodo Save(String) accetta come parametro un percorso del file system locale per un file di output e salva un documento HTML nel file locale specificato dal percorso. Tutte le risorse utilizzate nel documento saranno salvate in una cartella adiacente.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Vedi anche

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | String | Percorso del file locale al file di output. |
| saveFormat | HTMLSaveFormat | Formato in cui il documento viene salvato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se il `path` specificato non è un percorso di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(String, HTMLSaveFormat) Metodo

Save(String, HTMLSaveFormat) metodo prende come parametri un percorso del file system locale per il file di output e saveFormat. L'[`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) Enumerazione specifica il formato in cui il documento viene salvato, può essere HTML, MHTML e MD. Il metodo salva il documento HTML nel formato specificato nel file locale indicato dal percorso. Tutte le risorse utilizzate nel documento saranno salvate in una cartella adiacente.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Titolo&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Contenitore con ID - identificatore&lt;/div&gt;

&lt;div class="custom-class"&gt;Personalizzato dal contenitore con classe CSS&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Primo paragrafo stilizzato dalla classe pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Secondo paragrafo stilizzato dalla classe pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Terzo paragrafo stilizzato dalla classe pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;Span stilizzato da pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Paragrafo stilizzato dal nome della classe =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Paragrafo stilizzato dal nome della classe =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Paragrafo stilizzato dal nome della classe =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Ciao dall'elemento DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Vedi anche

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | URL locale del file di output. |
| saveFormat | HTMLSaveFormat | Formato in cui il documento viene salvato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se l'`url` specificato non è un URL di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(Url, HTMLSaveFormat) Metodo

È necessario specificare un percorso Url completo - 'outputFilePath' per il salvataggio del documento HTML. Il costruttore Url(url) crea un'istanza della classe [`Url`](../../url/) con l'url specificato. L'enumerazione [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) specifica il formato in cui il documento viene salvato; può essere HTML, MHTML e MD. Quindi dovresti passare i parametri al metodo Save(url, saveFormat). Il documento verrà salvato nel formato specificato nel file locale indicato dall'url.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Vedi anche

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Salva il contenuto e le risorse del documento usando il [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Il gestore delle risorse [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Formato in cui il documento viene salvato. |

### Vedi anche

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | String | Percorso locale del file di output. |
| saveOptions | HTMLSaveOptions | L'oggetto [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) è per la gestione del processo di risorse. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se il `path` specificato non è un percorso di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(String, HTMLSaveOptions) Metodo

Il metodo Save(String, HTMLSaveOptions) accetta come parametri un percorso del file system locale per il file di output, un'istanza della classe [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) e salva un documento HTML con le risorse nel file locale specificato dal percorso. Il costruttore HTMLSaveOptions() crea un'istanza di opzioni di salvataggio che contiene le proprietà [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) utilizzate per la configurazione della gestione delle risorse. Tutte le risorse utilizzate nel documento saranno salvate in una cartella adiacente.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definisci l'istanza della classe di opzioni
	var options = new HTMLSaveOptions();
	// Restrizione della gestione delle pagine
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Locale [`URL`](../../url/) al file di output. |
| saveOptions | HTMLSaveOptions | L'oggetto [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) è per la gestione del processo di risorse. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se l'`url` specificato non è un URL di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(Url, HTMLSaveOptions) Metodo

È necessario specificare un percorso Url completo per il salvataggio del documento HTML. Il costruttore Url(url) crea un'istanza della classe [`Url`](../../url/) con l'url specificato. Il costruttore HTMLSaveOptions() crea un'istanza della classe [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) che contiene le proprietà ResourceHandlingOptions utilizzate per la configurazione della gestione delle risorse. Il metodo Save(url, saveOptions) accetta i parametri e salva il documento HTML con le risorse nel file locale indicato dall'url.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definisci l'istanza della classe di opzioni
	var options = new HTMLSaveOptions();
	// Restrizione della gestione delle pagine
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Salva il contenuto e le risorse del documento usando il [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Il gestore delle risorse [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Opzioni di salvataggio HTML. |

### Vedi anche

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | String | Percorso locale del file di output. |
| saveOptions | MarkdownSaveOptions | L'utilizzo dell'oggetto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [Documentazione Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se il `path` specificato non è un percorso di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(String, MarkdownSaveOptions) Metodo

È necessario specificare un percorso del file system locale per il file di output per il salvataggio del documento. Il costruttore MarkdownSaveOptions() crea un'istanza della classe [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) che dispone di un insieme di proprietà. Ad esempio, è possibile impostare lo stile di formattazione markdown, utilizzare opzioni compatibili predefinite per GitLab Flavored Markdown e configurare la gestione delle risorse. Il metodo Save(path, saveOptions) accetta il percorso del file system locale per il file di output e l'istanza delle opzioni come parametri e salva l'HTML come documento Markdown con risorse nel file locale specificato dal percorso.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definisci l'istanza della classe di opzioni
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | Locale [`URL`](../../url/) al file di output. |
| saveOptions | MarkdownSaveOptions | L'utilizzo dell'oggetto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [documentazione](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se l'`url` specificato non è un URL di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Save(Url, MarkdownSaveOptions) Metodo

È necessario specificare un percorso Url completo per il salvataggio del documento. Il costruttore Url(url) crea un'istanza della classe [`Url`](../../url/) con l'url specificato. Il costruttore MarkdownSaveOptions() crea un'istanza della classe [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) che dispone di un insieme di proprietà. Ad esempio, è possibile impostare lo stile di formattazione Markdown, utilizzare opzioni compatibili predefinite per GitLab Flavored Markdown e configurare la gestione delle risorse. Il metodo Save(url, saveOptions) accetta le istanze di url e delle opzioni di salvataggio come parametri e salva il documento con le risorse nel file locale indicato dall'url.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definisci l'istanza della classe di opzioni
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Salva il contenuto e le risorse del documento usando il [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Il gestore delle risorse [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Opzioni di salvataggio Markdown. |

### Vedi anche

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | String | Percorso locale del file di output. |
| saveOptions | MHTMLSaveOptions | L'utilizzo dell'oggetto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [documentazione](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se il `path` specificato non è un percorso di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Metodo Save(String, MHTMLSaveOptions)

È necessario specificare un percorso del file system locale per il file di output durante il salvataggio del documento. Il costruttore MHTMLSaveOptions() inizializza un'istanza della classe [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) che possiede la proprietà ResourceHandlingOptions utilizzata per la configurazione della gestione delle risorse. Il metodo Save(path, saveOptions) accetta come parametri un percorso locale del file di output e un'istanza delle opzioni di salvataggio e salva l'HTML come documento MHTML nel file locale specificato dal percorso.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definisci l'istanza della classe di opzioni
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | URL locale del file di output. |
| saveOptions | MHTMLSaveOptions | L'utilizzo dell'oggetto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) consente di regolare il processo di rendering. Per ulteriori informazioni, consulta la [documentazione](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato se l'`url` specificato non è un URL di file locale valido. |

## Osservazioni

Salva HTML

La maggior parte delle attività che devi eseguire richiede il salvataggio di un documento. Dopo aver caricato il file esistente o creato un documento HTML da zero, puoi salvare le modifiche utilizzando uno dei metodi HTMLDocument.Save(). I metodi consentono di salvare HTML in un file locale specificato da percorso, URL o archiviazione di output. Consulta la [documentazione](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) per saperne di più sul salvataggio.

Metodo Save(Url, MHTMLSaveOptions)

È necessario specificare un percorso Url completo per il salvataggio del documento. Il costruttore Url(url) crea un'istanza della classe [`Url`](../../url/) con l'url specificato. Il costruttore MHTMLSaveOptions() inizializza un'istanza della classe [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) che possiede la proprietà ResourceHandlingOptions utilizzata per la configurazione della gestione delle risorse. Il metodo Save(url, saveOptions) accetta come parametri l'url e le opzioni e salva l'HTML come documento MHTML nel file locale specificato dall'url.

Codice sorgente

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definisci l'istanza della classe di opzioni
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Vedi anche

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Salva il contenuto e le risorse del documento usando il [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Il gestore delle risorse [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Opzioni di salvataggio MHTML. |

### Vedi anche

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
