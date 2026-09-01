---
title: "HTMLDocument"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Konstruktor HTMLDocument. Der Konstruktor HTMLDocument erstellt ein neues HTML Document-Objekt, das eine im Browser geladene Webseite ist und als Einstiegspunkt in den Seiteninhalt dient."
type: docs

url: /de/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Der HTMLDocument‑Konstruktor erstellt ein neues HTML‑Document‑Objekt, das eine im Browser geladene Webseite ist und als Einstiegspunkt in den Seiteninhalt dient.

```java
public HTMLDocument()
```

## Hinweise

Hinweis: Das Dokument wird mit einem Standardwert für die base-url‑Eigenschaft erstellt, der 'about:blank' entspricht.

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

Sobald das Dokumentobjekt erstellt ist, kann es später mit HTML-Elementen gefüllt werden. Das folgende Code‑Snippet zeigt die Verwendung des Standardkonstruktors HTMLDocument(), um ein leeres HTML‑Dokument zu erstellen und es in einer Datei zu speichern.

```java
import (var document = new HTMLDocument())
{
	// Arbeiten Sie hier mit dem Dokument
	...	
	
	// Speichern Sie das Dokument in einer Datei
	document.Save("document.html");
}
```

### Siehe auch

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Der HTMLDocument‑Konstruktor erstellt ein neues HTML‑Document‑Objekt, das eine im Browser geladene Webseite ist und als Einstiegspunkt in den Seiteninhalt dient.

```java
public HTMLDocument(Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

## Hinweise

Hinweis: Das Dokument wird mit einem Standardwert für die base-url‑Eigenschaft erstellt, der 'about:blank' entspricht.

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

Das folgende Beispiel demonstriert, wie das Konfigurationsobjekt verwendet wird, um Skripte zu deaktivieren:

```java
// Bereiten Sie HTML‑Code vor und speichern Sie ihn in einer Datei
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Erstellen Sie eine Instanz von Configuration
import (var configuration = new Configuration())
{
	// Markieren Sie 'scripts' als nicht vertrauenswürdige Ressource
	configuration.Security |= Sandbox.Scripts;

	// Initialisieren Sie ein HTML-Dokument mit der angegebenen Konfiguration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML zu PDF konvertieren
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Siehe auch

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Lädt das HTML‑Dokument von einer URL.

Hinweis: Falls Sie eine falsche URL übergeben, die momentan nicht erreichbar ist, wirft die Bibliothek die [`DOMException`](../../../com.aspose.html.dom/domexception/) mit dem speziellen Code ‘NetworkError’, um Sie darüber zu informieren, dass die ausgewählte Ressource nicht gefunden werden kann.

```java
public HTMLDocument(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die zu öffnende HTML‑Dokument‑URL. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

Laden Sie ein Dokument von der Webseite 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html' :

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Schreiben Sie den Dokumentinhalt in den Ausgabestream
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Siehe auch

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Lädt das HTML‑Dokument von einer URL mit angegebenen Umgebungs‑Konfigurationseinstellungen.

Hinweis: Falls Sie eine falsche URL übergeben, die momentan nicht erreichbar ist, wirft die Bibliothek die [DOMException](T:com.aspose.html.dom.DOMException) mit dem speziellen Code ‘NetworkError’, um Sie darüber zu informieren, dass die ausgewählte Ressource nicht gefunden werden kann.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die zu öffnende HTML‑Dokument‑URL. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Bereiten Sie HTML‑Code vor und speichern Sie ihn in einer Datei
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Erstellen Sie eine Instanz von Configuration
import (var configuration = new Configuration())
{
	// Markieren Sie 'scripts' als nicht vertrauenswürdige Ressource
	configuration.Security |= Sandbox.Scripts;

	// Initialisieren Sie ein HTML-Dokument mit der angegebenen Konfiguration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML zu PDF konvertieren
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Siehe auch

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Lädt das HTML‑Dokument von einer Adresse.

Hinweis: Falls Sie eine falsche URL übergeben, die momentan nicht erreichbar ist, wirft die Bibliothek die [`DOMException`](../../../com.aspose.html.dom/domexception/) mit dem speziellen Code ‘NetworkError’, um Sie darüber zu informieren, dass die ausgewählte Ressource nicht gefunden werden kann.

```java
public HTMLDocument(String address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Adresse | String | Die zu öffnende HTML‑Dokument‑Adresse. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

Initialisieren Sie ein HTML‑Dokument aus einer Adresse.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Siehe auch

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Lädt das HTML‑Dokument von einer Adresse mit angegebenen Umgebungs‑Konfigurationseinstellungen.

Hinweis: Falls Sie eine falsche URL übergeben, die momentan nicht erreichbar ist, wirft die Bibliothek die [`DOMException`](../../../com.aspose.html.dom/domexception/) mit dem speziellen Code ‘NetworkError’, um Sie darüber zu informieren, dass die ausgewählte Ressource nicht gefunden werden kann.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Adresse | String | Die zu öffnende HTML‑Dokument‑Adresse. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Erstellen Sie eine Instanz von Configuration
import (var configuration = new Configuration())
{
	// Markieren Sie 'scripts' als nicht vertrauenswürdige Ressource
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Siehe auch

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Erstellt ein HTML‑Dokument aus einem String‑Inhalt mit angegebener Basis‑URI.

```java
public HTMLDocument(String content, String baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der String‑Inhalt, mit dem das Dokument geladen wird. |
| baseUri | String | Die Basis-URI des Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Bereiten Sie HTML‑Code vor
var html_code = "<p>Hello World!</p>";

// Initialisieren Sie ein Dokument aus der String‑Variablen
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Siehe auch

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Erstellt ein HTML‑Dokument aus einem String‑Inhalt mit angegebener Basis‑URI und Umgebungs‑Konfigurationseinstellungen.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der String‑Inhalt, mit dem das Dokument geladen wird. |
| baseUri | String | Die Basis-URI des Dokuments. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Bereiten Sie HTML‑Code vor
var html_code = "<p>Hello World!</p>";

// Initialisieren Sie ein Dokument aus der String‑Variablen
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Siehe auch

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Erstellt ein HTML‑Dokument aus einem String‑Inhalt mit angegebener Basis‑URI.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der String‑Inhalt, mit dem das Dokument geladen wird. |
| baseUri | Url | Die Basis-URI des Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Bereiten Sie HTML‑Code vor
var html_code = "<p>Hello World!</p>";

// Initialisieren Sie ein Dokument aus der String‑Variablen
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Siehe auch

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Erstellt ein HTML‑Dokument aus einem String‑Inhalt mit angegebener Basis‑URI und Umgebungs‑Konfigurationseinstellungen.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der String‑Inhalt, mit dem das Dokument geladen wird. |
| baseUri | Url | Die Basis-URI des Dokuments. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Bereiten Sie HTML‑Code vor
var html_code = "<p>Hello World!</p>";

// Initialisieren Sie ein Dokument aus der String‑Variablen
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Siehe auch

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Erstellt ein HTML‑Dokument aus einem [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)‑Inhalt mit angegebener Basis‑URI, die zum Auflösen des Pfads relativer Ressourcen verwendet wird.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-Inhalt, mit dem das Dokument geladen wird. |
| baseUri | String | Die Basis-URI des Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Erstellen Sie ein Memory‑Stream‑Objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schreiben Sie den HTML‑Code in das Speicherobjekt
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es ist wichtig, die Position auf den Anfang zu setzen, da HTMLDocument das Lesen exakt von der aktuellen Position im Stream beginnt.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialisieren Sie ein Dokument aus der String‑Variablen
	using (var document = new HTMLDocument(mem, "."))
	{
		// Speichern Sie das Dokument auf einer Festplatte.
		document.Save("load-from-stream.html");
	}
}
```

### Siehe auch

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Erstellt ein HTML‑Dokument aus einem [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)‑Inhalt mit angegebener Basis‑URI und Umgebungs‑Konfigurationseinstellungen.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-Inhalt, mit dem das Dokument geladen wird. |
| baseUri | String | Die Basis-URI des Dokuments. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Erstellen Sie ein Memory‑Stream‑Objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schreiben Sie den HTML‑Code in das Speicherobjekt
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es ist wichtig, die Position auf den Anfang zu setzen, da HTMLDocument das Lesen exakt von der aktuellen Position im Stream beginnt.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialisieren Sie ein Dokument aus der String‑Variablen
	using (var document = new HTMLDocument(mem, "."))
	{
		// Speichern Sie das Dokument auf einer Festplatte.
		document.Save("load-from-stream.html");
	}
}
```

### Siehe auch

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Erstellt ein HTML‑Dokument aus einem [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)‑Inhalt mit angegebener Basis‑URI, die zum Auflösen des Pfads relativer Ressourcen verwendet wird.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-Inhalt, mit dem das Dokument geladen wird. |
| baseUri | Url | Die Basis-URI des Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Erstellen Sie ein Memory‑Stream‑Objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schreiben Sie den HTML‑Code in das Speicherobjekt
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es ist wichtig, die Position auf den Anfang zu setzen, da HTMLDocument das Lesen exakt von der aktuellen Position im Stream beginnt.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialisieren Sie ein Dokument aus der String‑Variablen
	using (var document = new HTMLDocument(mem, "."))
	{
		// Speichern Sie das Dokument auf einer Festplatte.
		document.Save("load-from-stream.html");
	}
}
```

### Siehe auch

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Erstellt ein HTML‑Dokument aus einem [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)‑Inhalt mit angegebener Basis‑URI und Umgebungs‑Konfigurationseinstellungen.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-Inhalt, mit dem das Dokument geladen wird. |
| baseUri | Url | Die Basis-URI des Dokuments. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wirft eine Ausnahme, wenn der base-uri‑Parameter null ist. |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Beispiele

```java
// Erstellen Sie ein Memory‑Stream‑Objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schreiben Sie den HTML‑Code in das Speicherobjekt
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es ist wichtig, die Position auf den Anfang zu setzen, da HTMLDocument das Lesen exakt von der aktuellen Position im Stream beginnt.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialisieren Sie ein Dokument aus der String‑Variablen
	using (var document = new HTMLDocument(mem, "."))
	{
		// Speichern Sie das Dokument auf einer Festplatte.
		document.Save("load-from-stream.html");
	}
}
```

### Siehe auch

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Erstellt ein HTML-Dokument aus dem [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) Objekt.

```java
public HTMLDocument(RequestMessage request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | RequestMessage | Die Anforderungsnachricht, die einen [`body`](../../../com.aspose.html.net/requestmessage/content/) mit Dokumentinhalt enthält. |

## Hinweise

Nach Definition ist ein Message handler eine Klasse, die eine Web-Anfrage empfängt und eine Web-Antwort zurückgibt. Mit anderen Worten wird ein Message handler verwendet, um eine Web-Service-Anfrage während der Eingabe und/oder die Antwort während der Ausgabe zu verarbeiten.

Bitte besuchen Sie unsere [Dokumentationsseite](https://docs.aspose.com/html/net/message-handlers/), um weitere Szenarien zur Verwendung dieses Konstruktors zu sehen.

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Siehe auch

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Erstellt ein HTML‑Dokument aus dem [RequestMessage](T:com.aspose.html.net.RequestMessage) Objekt.

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | RequestMessage | Die Anforderungsnachricht, die einen [body](P:com.aspose.html.net.RequestMessage.Content) mit Dokumentinhalt enthält. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration wie Skript‑Richtlinie, benutzerdefiniertes Benutzer‑Stylesheet usw. |

## Hinweise

Nach Definition ist ein Message handler eine Klasse, die eine Web-Anfrage empfängt und eine Web-Antwort zurückgibt. Mit anderen Worten wird ein Message handler verwendet, um eine Web-Service-Anfrage während der Eingabe und/oder die Antwort während der Ausgabe zu verarbeiten.

Bitte besuchen Sie unsere [Dokumentationsseite](https://docs.aspose.com/html/net/message-handlers/), um weitere Szenarien zur Verwendung dieses Konstruktors zu sehen.

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Siehe auch

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
