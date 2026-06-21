---
title: "HTMLDocument"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Costruttore HTMLDocument. Il costruttore HTMLDocument crea un nuovo oggetto HTML Document che è una pagina web caricata nel browser e funge da punto di ingresso al contenuto della pagina."
type: docs

url: /it/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Il costruttore HTMLDocument crea un nuovo oggetto HTML Document che è una pagina web caricata nel browser e funge da punto di ingresso al contenuto della pagina.

```java
public HTMLDocument()
```

## Osservazioni

Nota: Il documento viene creato con un valore predefinito per la proprietà base-url pari a 'about:blank'.

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

Una volta creato l'oggetto documento, può essere successivamente riempito con elementi HTML. Il seguente frammento di codice mostra l'uso del costruttore predefinito HTMLDocument() per creare un documento HTML vuoto e salvarlo in un file.

```java
import (var document = new HTMLDocument())
{
	// Lavora con il documento qui
	...	
	
	// Salva il documento in un file
	document.Save("document.html");
}
```

### Vedi anche

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Il costruttore HTMLDocument crea un nuovo oggetto HTML Document che è una pagina web caricata nel browser e funge da punto di ingresso al contenuto della pagina.

```java
public HTMLDocument(Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

## Osservazioni

Nota: Il documento viene creato con un valore predefinito per la proprietà base-url pari a 'about:blank'.

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

Il seguente esempio dimostra come utilizzare l'oggetto di configurazione per disabilitare gli script:

```java
// Prepara il codice HTML e salvalo in un file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Crea un'istanza di Configuration
import (var configuration = new Configuration())
{
	// Contrassegna 'scripts' come risorsa non attendibile
	configuration.Security |= Sandbox.Scripts;

	// Inizializza un documento HTML con la configurazione specificata
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Converti HTML in PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Vedi anche

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Carica il documento HTML da un URL.

Nota: Nel caso in cui si fornisca un URL errato che non può essere raggiunto al momento, la libreria genera il [`DOMException`](../../../com.aspose.html.dom/domexception/) con il codice specializzato ‘NetworkError’ per informare che la risorsa selezionata non può essere trovata.

```java
public HTMLDocument(Url url)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | L'URL del documento HTML da aprire. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

Carica un documento dalla pagina web 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Scrivi il contenuto del documento nello stream di output
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Vedi anche

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Carica il documento HTML da un URL con le impostazioni di configurazione dell'ambiente specificate.

Nota: Nel caso in cui si fornisca un URL errato che non può essere raggiunto al momento, la libreria genera il [DOMException](T:com.aspose.html.dom.DOMException) con il codice specializzato ‘NetworkError’ per informare che la risorsa selezionata non può essere trovata.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | L'URL del documento HTML da aprire. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Prepara il codice HTML e salvalo in un file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Crea un'istanza di Configuration
import (var configuration = new Configuration())
{
	// Contrassegna 'scripts' come risorsa non attendibile
	configuration.Security |= Sandbox.Scripts;

	// Inizializza un documento HTML con la configurazione specificata
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Converti HTML in PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Vedi anche

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Carica il documento HTML da un indirizzo.

Nota: Nel caso in cui si fornisca un URL errato che non può essere raggiunto al momento, la libreria genera il [`DOMException`](../../../com.aspose.html.dom/domexception/) con il codice specializzato ‘NetworkError’ per informare che la risorsa selezionata non può essere trovata.

```java
public HTMLDocument(String address)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indirizzo | String | L'indirizzo del documento HTML da aprire. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

Inizializza un documento HTML da un indirizzo.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Vedi anche

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Carica il documento HTML da un indirizzo con le impostazioni di configurazione dell'ambiente specificate.

Nota: Nel caso in cui si fornisca un URL errato che non può essere raggiunto al momento, la libreria genera il [`DOMException`](../../../com.aspose.html.dom/domexception/) con il codice specializzato ‘NetworkError’ per informare che la risorsa selezionata non può essere trovata.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indirizzo | String | L'indirizzo del documento HTML da aprire. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Crea un'istanza di Configuration
import (var configuration = new Configuration())
{
	// Contrassegna 'scripts' come risorsa non attendibile
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Vedi anche

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Crea un documento HTML da un contenuto String con base-uri specificata.

```java
public HTMLDocument(String content, String baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto String da utilizzare per caricare il documento. |
| baseUri | String | L'URI di base del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Prepara il codice HTML
var html_code = "<p>Hello World!</p>";

// Inizializza un documento dalla variabile String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Vedi anche

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Crea un documento HTML da un contenuto String con base-uri e impostazioni di configurazione dell'ambiente specificate.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto String da utilizzare per caricare il documento. |
| baseUri | String | L'URI di base del documento. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Prepara il codice HTML
var html_code = "<p>Hello World!</p>";

// Inizializza un documento dalla variabile String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Vedi anche

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Crea un documento HTML da un contenuto String con base-uri specificata.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto String da utilizzare per caricare il documento. |
| baseUri | Url | L'URI di base del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Prepara il codice HTML
var html_code = "<p>Hello World!</p>";

// Inizializza un documento dalla variabile String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Vedi anche

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Crea un documento HTML da un contenuto String con base-uri e impostazioni di configurazione dell'ambiente specificate.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto String da utilizzare per caricare il documento. |
| baseUri | Url | L'URI di base del documento. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Prepara il codice HTML
var html_code = "<p>Hello World!</p>";

// Inizializza un documento dalla variabile String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Vedi anche

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri specificata, utilizzata per risolvere il percorso delle risorse relative.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | Stream | Il contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) da utilizzare per caricare il documento. |
| baseUri | String | L'URI di base del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Crea un oggetto memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Scrivi il codice HTML nell'oggetto di memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// È importante impostare la posizione all'inizio poiché HTMLDocument inizia la lettura esattamente dalla posizione corrente all'interno del flusso
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inizializza un documento dalla variabile String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Salva il documento su disco
		document.Save("load-from-stream.html");
	}
}
```

### Vedi anche

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri e impostazioni di configurazione dell'ambiente specificate.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | Stream | Il contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) da utilizzare per caricare il documento. |
| baseUri | String | L'URI di base del documento. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Crea un oggetto memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Scrivi il codice HTML nell'oggetto di memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// È importante impostare la posizione all'inizio poiché HTMLDocument inizia la lettura esattamente dalla posizione corrente all'interno del flusso
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inizializza un documento dalla variabile String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Salva il documento su disco
		document.Save("load-from-stream.html");
	}
}
```

### Vedi anche

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri specificata, utilizzata per risolvere il percorso delle risorse relative.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | Stream | Il contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) da utilizzare per caricare il documento. |
| baseUri | Url | L'URI di base del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Crea un oggetto memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Scrivi il codice HTML nell'oggetto di memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// È importante impostare la posizione all'inizio poiché HTMLDocument inizia la lettura esattamente dalla posizione corrente all'interno del flusso
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inizializza un documento dalla variabile String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Salva il documento su disco
		document.Save("load-from-stream.html");
	}
}
```

### Vedi anche

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri e impostazioni di configurazione dell'ambiente specificate.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| content | Stream | Il contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) da utilizzare per caricare il documento. |
| baseUri | Url | L'URI di base del documento. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Genera un'eccezione se il parametro base-uri è null. |

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
// Crea un oggetto memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Scrivi il codice HTML nell'oggetto di memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// È importante impostare la posizione all'inizio poiché HTMLDocument inizia la lettura esattamente dalla posizione corrente all'interno del flusso
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inizializza un documento dalla variabile String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Salva il documento su disco
		document.Save("load-from-stream.html");
	}
}
```

### Vedi anche

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Crea un documento HTML dall'oggetto [`RequestMessage`](../../../com.aspose.html.net/requestmessage/).

```java
public HTMLDocument(RequestMessage request)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| request | RequestMessage | Il messaggio di richiesta che contiene un [`body`](../../../com.aspose.html.net/requestmessage/content/) con il contenuto del documento. |

## Osservazioni

Per definizione, un message handler è una classe che riceve una richiesta Web e restituisce una risposta Web. In altre parole, un message handler viene utilizzato per elaborare una richiesta di servizio Web durante l'input e/o per elaborare la risposta durante l'output.

Per favore, visita il nostro [sito della documentazione](https://docs.aspose.com/html/net/message-handlers/) per vedere altri scenari su come utilizzare questo costruttore.

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Vedi anche

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Crea un documento HTML dall'oggetto [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| request | RequestMessage | Il messaggio di richiesta che contiene un [body](P:com.aspose.html.net.RequestMessage.Content) con il contenuto del documento. |
| configurazione | Configurazione | La configurazione dell'ambiente, come la politica degli script, il foglio di stile personalizzato dell'utente, ecc. |

## Osservazioni

Per definizione, un message handler è una classe che riceve una richiesta Web e restituisce una risposta Web. In altre parole, un message handler viene utilizzato per elaborare una richiesta di servizio Web durante l'input e/o per elaborare la risposta durante l'output.

Per favore, visita il nostro [sito della documentazione](https://docs.aspose.com/html/net/message-handlers/) per vedere altri scenari su come utilizzare questo costruttore.

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Vedi anche

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
