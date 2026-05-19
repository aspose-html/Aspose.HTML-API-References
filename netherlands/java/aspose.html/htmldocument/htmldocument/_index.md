---
title: "HTMLDocument"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLDocument constructor. De HTMLDocument constructor maakt een nieuw HTML Document-object dat een webpagina is die in de browser is geladen en dient als toegangspunt tot de inhoud van de pagina."
type: docs

url: /nl/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

De HTMLDocument‑constructor maakt een nieuw HTML‑Document‑object aan dat een webpagina is die in de browser is geladen en dient als toegangspunt tot de inhoud van de pagina.

```java
public HTMLDocument()
```

## Opmerkingen

Opmerking: Het document wordt aangemaakt met een standaardwaarde voor de base-url eigenschap die gelijk is aan 'about:blank'.

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

Zodra het documentobject is aangemaakt, kan het later worden gevuld met HTML-elementen. Het volgende codefragment toont het gebruik van de standaard HTMLDocument() constructor om een leeg HTML-document te maken en op te slaan in een bestand.

```java
import (var document = new HTMLDocument())
{
	// Werk hier met het document
	...	
	
	// Sla het document op in een bestand
	document.Save("document.html");
}
```

### Zie ook

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

De HTMLDocument‑constructor maakt een nieuw HTML‑Document‑object aan dat een webpagina is die in de browser is geladen en dient als toegangspunt tot de inhoud van de pagina.

```java
public HTMLDocument(Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

## Opmerkingen

Opmerking: Het document wordt aangemaakt met een standaardwaarde voor de base-url eigenschap die gelijk is aan 'about:blank'.

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

Het volgende voorbeeld laat zien hoe je het configuratieobject gebruikt om scripts uit te schakelen:

```java
// Bereid HTML‑code voor en sla deze op in een bestand
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Maak een instantie van Configuration
import (var configuration = new Configuration())
{
	// Markeer 'scripts' als een niet-vertrouwde bron
	configuration.Security |= Sandbox.Scripts;

	// Initialiseer een HTML-document met de opgegeven configuratie
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML naar PDF converteren
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Zie ook

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Laadt het HTML‑document vanaf een URL.

Opmerking: Als je een onjuiste URL opgeeft die op dit moment niet bereikbaar is, gooit de bibliotheek de [`DOMException`](../../../com.aspose.html.dom/domexception/) met de gespecialiseerde code ‘NetworkError’ om je te informeren dat de geselecteerde bron niet gevonden kan worden.

```java
public HTMLDocument(Url url)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De URL van het HTML-document om te openen. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

Laad een document van de webpagina 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Schrijf de documentinhoud naar de uitvoerstroom
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Zie ook

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Laadt het HTML‑document vanaf een URL met opgegeven omgevings‑configuratie‑instellingen.

Opmerking: Als je een onjuiste URL opgeeft die op dit moment niet bereikbaar is, gooit de bibliotheek de [DOMException](T:com.aspose.html.dom.DOMException) met de gespecialiseerde code ‘NetworkError’ om je te informeren dat de geselecteerde bron niet gevonden kan worden.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De URL van het HTML-document om te openen. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Bereid HTML‑code voor en sla deze op in een bestand
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Maak een instantie van Configuration
import (var configuration = new Configuration())
{
	// Markeer 'scripts' als een niet-vertrouwde bron
	configuration.Security |= Sandbox.Scripts;

	// Initialiseer een HTML-document met de opgegeven configuratie
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML naar PDF converteren
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Zie ook

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Laadt het HTML‑document vanaf een adres.

Opmerking: Als je een onjuiste URL opgeeft die op dit moment niet bereikbaar is, gooit de bibliotheek de [`DOMException`](../../../com.aspose.html.dom/domexception/) met de gespecialiseerde code ‘NetworkError’ om je te informeren dat de geselecteerde bron niet gevonden kan worden.

```java
public HTMLDocument(String address)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| adres | String | Het adres van het HTML-document om te openen. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

Initialiseer een HTML-document vanuit een adres.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Zie ook

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Laadt het HTML‑document vanaf een adres met opgegeven omgevings‑configuratie‑instellingen.

Opmerking: Als je een onjuiste URL opgeeft die op dit moment niet bereikbaar is, gooit de bibliotheek de [`DOMException`](../../../com.aspose.html.dom/domexception/) met de gespecialiseerde code ‘NetworkError’ om je te informeren dat de geselecteerde bron niet gevonden kan worden.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| adres | String | Het adres van het HTML-document om te openen. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Maak een instantie van Configuration
import (var configuration = new Configuration())
{
	// Markeer 'scripts' als een niet-vertrouwde bron
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Zie ook

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Maakt een HTML‑document aan vanuit een String‑inhoud met een opgegeven basis‑URI.

```java
public HTMLDocument(String content, String baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De String-inhoud om het document mee te laden. |
| baseUri | String | De basis-URI van het document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Bereid HTML-code voor
var html_code = "<p>Hello World!</p>";

// Initialiseer een document vanuit de String-variabele
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Zie ook

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Maakt een HTML‑document aan vanuit een String‑inhoud met een opgegeven basis‑URI en omgevings‑configuratie‑instellingen.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De String-inhoud om het document mee te laden. |
| baseUri | String | De basis-URI van het document. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Bereid HTML-code voor
var html_code = "<p>Hello World!</p>";

// Initialiseer een document vanuit de String-variabele
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Zie ook

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Maakt een HTML‑document aan vanuit een String‑inhoud met een opgegeven basis‑URI.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De String-inhoud om het document mee te laden. |
| baseUri | Url | De basis-URI van het document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Bereid HTML-code voor
var html_code = "<p>Hello World!</p>";

// Initialiseer een document vanuit de String-variabele
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Zie ook

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Maakt een HTML‑document aan vanuit een String‑inhoud met een opgegeven basis‑URI en omgevings‑configuratie‑instellingen.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De String-inhoud om het document mee te laden. |
| baseUri | Url | De basis-URI van het document. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Bereid HTML-code voor
var html_code = "<p>Hello World!</p>";

// Initialiseer een document vanuit de String-variabele
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Zie ook

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Maakt een HTML‑document aan vanuit een [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud met een opgegeven basis‑URI die wordt gebruikt om het pad van relatieve bronnen op te lossen.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | Stream | De [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud om het document mee te laden. |
| baseUri | String | De basis-URI van het document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Maak een geheugenstroomobject
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schrijf de HTML-code naar het geheugenobject
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Het is belangrijk om de positie op het begin in te stellen, aangezien HTMLDocument het lezen precies vanaf de huidige positie in de stream start.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiseer een document vanuit de String-variabele
	using (var document = new HTMLDocument(mem, "."))
	{
		// Sla het document op een schijf op.
		document.Save("load-from-stream.html");
	}
}
```

### Zie ook

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Maakt een HTML‑document aan vanuit een [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud met een opgegeven basis‑URI en omgevings‑configuratie‑instellingen.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | Stream | De [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud om het document mee te laden. |
| baseUri | String | De basis-URI van het document. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Maak een geheugenstroomobject
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schrijf de HTML-code naar het geheugenobject
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Het is belangrijk om de positie op het begin in te stellen, aangezien HTMLDocument het lezen precies vanaf de huidige positie in de stream start.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiseer een document vanuit de String-variabele
	using (var document = new HTMLDocument(mem, "."))
	{
		// Sla het document op een schijf op.
		document.Save("load-from-stream.html");
	}
}
```

### Zie ook

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Maakt een HTML‑document aan vanuit een [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud met een opgegeven basis‑URI die wordt gebruikt om het pad van relatieve bronnen op te lossen.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | Stream | De [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud om het document mee te laden. |
| baseUri | Url | De basis-URI van het document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Maak een geheugenstroomobject
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schrijf de HTML-code naar het geheugenobject
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Het is belangrijk om de positie op het begin in te stellen, aangezien HTMLDocument het lezen precies vanaf de huidige positie in de stream start.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiseer een document vanuit de String-variabele
	using (var document = new HTMLDocument(mem, "."))
	{
		// Sla het document op een schijf op.
		document.Save("load-from-stream.html");
	}
}
```

### Zie ook

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Maakt een HTML‑document aan vanuit een [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud met een opgegeven basis‑URI en omgevings‑configuratie‑instellingen.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | Stream | De [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) inhoud om het document mee te laden. |
| baseUri | Url | De basis-URI van het document. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Gooit een uitzondering als de base-uri parameter null is. |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Voorbeelden

```java
// Maak een geheugenstroomobject
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Schrijf de HTML-code naar het geheugenobject
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Het is belangrijk om de positie op het begin in te stellen, aangezien HTMLDocument het lezen precies vanaf de huidige positie in de stream start.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiseer een document vanuit de String-variabele
	using (var document = new HTMLDocument(mem, "."))
	{
		// Sla het document op een schijf op.
		document.Save("load-from-stream.html");
	}
}
```

### Zie ook

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Maakt een HTML-document aan vanuit het [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) object.

```java
public HTMLDocument(RequestMessage request)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| request | RequestMessage | Het verzoekbericht dat een [`body`](../../../com.aspose.html.net/requestmessage/content/) bevat met documentinhoud. |

## Opmerkingen

Per definitie is een message handler een klasse die een webverzoek ontvangt en een webrespons retourneert. Met andere woorden, een message handler wordt gebruikt om een webserviceverzoek tijdens invoer te verwerken en/of de respons tijdens uitvoer te verwerken.

Bezoek alstublieft onze [docs site](https://docs.aspose.com/html/net/message-handlers/) om meer scenario's te zien over hoe deze constructor te gebruiken.

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Zie ook

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Maakt een HTML‑document aan vanuit een [RequestMessage](T:com.aspose.html.net.RequestMessage) object.

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| request | RequestMessage | Het verzoekbericht dat een [body](P:com.aspose.html.net.RequestMessage.Content) bevat met documentinhoud. |
| configuratie | Configuratie | De omgevingsconfiguratie, zoals scriptsbeleid, aangepaste gebruikersstylesheet, enz. |

## Opmerkingen

Per definitie is een message handler een klasse die een webverzoek ontvangt en een webrespons retourneert. Met andere woorden, een message handler wordt gebruikt om een webserviceverzoek tijdens invoer te verwerken en/of de respons tijdens uitvoer te verwerken.

Bezoek alstublieft onze [docs site](https://docs.aspose.com/html/net/message-handlers/) om meer scenario's te zien over hoe deze constructor te gebruiken.

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Zie ook

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
