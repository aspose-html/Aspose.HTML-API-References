---
title: "HTMLDocument"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLDocument-konstruktor. HTMLDocument-konstruktorn skapar ett nytt HTML Document-objekt som är en webbsida laddad i webbläsaren och fungerar som en ingångspunkt till sidans innehåll."
type: docs

url: /sv/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

HTMLDocument‑konstruktorn skapar ett nytt HTML‑dokumentobjekt som är en webbsida laddad i webbläsaren och fungerar som en ingångspunkt till sidans innehåll.

```java
public HTMLDocument()
```

## Anmärkningar

Obs: Dokumentet skapas med ett standardvärde för egenskapen base-url som är lika med 'about:blank'.

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

När dokumentobjektet har skapats kan det fyllas senare med HTML-element. Följande kodsnutt visar hur standardkonstruktorn HTMLDocument() används för att skapa ett tomt HTML-dokument och spara det till en fil.

```java
import (var document = new HTMLDocument())
{
	// Arbeta med dokumentet här
	...	
	
	// Spara dokumentet till en fil
	document.Save("document.html");
}
```

### Se även

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

HTMLDocument‑konstruktorn skapar ett nytt HTML‑dokumentobjekt som är en webbsida laddad i webbläsaren och fungerar som en ingångspunkt till sidans innehåll.

```java
public HTMLDocument(Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

## Anmärkningar

Obs: Dokumentet skapas med ett standardvärde för egenskapen base-url som är lika med 'about:blank'.

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

Följande exempel demonstrerar hur man använder konfigurationsobjektet för att inaktivera skript:

```java
// Förbered HTML-kod och spara den till en fil.
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Skapa en instans av Configuration
import (var configuration = new Configuration())
{
	// Markera 'scripts' som en opålitlig resurs
	configuration.Security |= Sandbox.Scripts;

	// Initiera ett HTML-dokument med angiven konfiguration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Konvertera HTML till PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Se även

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Läser in HTML‑dokumentet från en URL.

Obs: Om du anger en felaktig URL som inte kan nås för tillfället kastar biblioteket [`DOMException`](../../../com.aspose.html.dom/domexception/) med den specialiserade koden ‘NetworkError’ för att informera dig om att den valda resursen inte kan hittas.

```java
public HTMLDocument(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-dokumentets URL att öppna. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

Läs in ett dokument från webbsidan 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Skriv dokumentets innehåll till utdata‑strömmen
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Se även

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Läser in HTML‑dokumentet från en URL med angivna miljökonfigurationsinställningar.

Obs: Om du anger en felaktig URL som inte kan nås för tillfället kastar biblioteket [DOMException](T:com.aspose.html.dom.DOMException) med den specialiserade koden ‘NetworkError’ för att informera dig om att den valda resursen inte kan hittas.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | HTML-dokumentets URL att öppna. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Förbered HTML-kod och spara den till en fil.
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Skapa en instans av Configuration
import (var configuration = new Configuration())
{
	// Markera 'scripts' som en opålitlig resurs
	configuration.Security |= Sandbox.Scripts;

	// Initiera ett HTML-dokument med angiven konfiguration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Konvertera HTML till PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Se även

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Läser in HTML‑dokumentet från en adress.

Obs: Om du anger en felaktig URL som inte kan nås för tillfället kastar biblioteket [`DOMException`](../../../com.aspose.html.dom/domexception/) med den specialiserade koden ‘NetworkError’ för att informera dig om att den valda resursen inte kan hittas.

```java
public HTMLDocument(String address)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | String | HTML-dokumentets adress att öppna. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

Initiera ett HTML-dokument från en adress.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Se även

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Läser in HTML‑dokumentet från en adress med angivna miljökonfigurationsinställningar.

Obs: Om du anger en felaktig URL som inte kan nås för tillfället kastar biblioteket [`DOMException`](../../../com.aspose.html.dom/domexception/) med den specialiserade koden ‘NetworkError’ för att informera dig om att den valda resursen inte kan hittas.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | String | HTML-dokumentets adress att öppna. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Skapa en instans av Configuration
import (var configuration = new Configuration())
{
	// Markera 'scripts' som en opålitlig resurs
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Se även

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri.

```java
public HTMLDocument(String content, String baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | String‑innehållet att ladda dokumentet med. |
| baseUri | String | Dokumentets bas-URI. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Förbered HTML-kod
var html_code = "<p>Hello World!</p>";

// Initiera ett dokument från String-variabeln
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Se även

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri och miljökonfigurationsinställningar.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | String‑innehållet att ladda dokumentet med. |
| baseUri | String | Dokumentets bas-URI. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Förbered HTML-kod
var html_code = "<p>Hello World!</p>";

// Initiera ett dokument från String-variabeln
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Se även

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | String‑innehållet att ladda dokumentet med. |
| baseUri | Url | Dokumentets bas-URI. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Förbered HTML-kod
var html_code = "<p>Hello World!</p>";

// Initiera ett dokument från String-variabeln
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Se även

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri och miljökonfigurationsinställningar.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | String‑innehållet att ladda dokumentet med. |
| baseUri | Url | Dokumentets bas-URI. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Förbered HTML-kod
var html_code = "<p>Hello World!</p>";

// Initiera ett dokument från String-variabeln
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Se även

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri som används för att lösa relativa resurssökvägar.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Det [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehållet att ladda dokumentet med. |
| baseUri | String | Dokumentets bas-URI. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Skapa ett minnesström‑objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Skriv HTML‑koden till minnesobjektet
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Det är viktigt att sätta positionen till början eftersom HTMLDocument börjar läsa exakt från den aktuella positionen i strömmen
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initiera ett dokument från String-variabeln
	using (var document = new HTMLDocument(mem, "."))
	{
		// Spara dokumentet till en disk
		document.Save("load-from-stream.html");
	}
}
```

### Se även

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri och miljökonfigurationsinställningar.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Det [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehållet att ladda dokumentet med. |
| baseUri | String | Dokumentets bas-URI. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Skapa ett minnesström‑objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Skriv HTML‑koden till minnesobjektet
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Det är viktigt att sätta positionen till början eftersom HTMLDocument börjar läsa exakt från den aktuella positionen i strömmen
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initiera ett dokument från String-variabeln
	using (var document = new HTMLDocument(mem, "."))
	{
		// Spara dokumentet till en disk
		document.Save("load-from-stream.html");
	}
}
```

### Se även

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri som används för att lösa relativa resurssökvägar.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Det [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehållet att ladda dokumentet med. |
| baseUri | Url | Dokumentets bas-URI. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Skapa ett minnesström‑objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Skriv HTML‑koden till minnesobjektet
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Det är viktigt att sätta positionen till början eftersom HTMLDocument börjar läsa exakt från den aktuella positionen i strömmen
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initiera ett dokument från String-variabeln
	using (var document = new HTMLDocument(mem, "."))
	{
		// Spara dokumentet till en disk
		document.Save("load-from-stream.html");
	}
}
```

### Se även

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri och miljökonfigurationsinställningar.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Det [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehållet att ladda dokumentet med. |
| baseUri | Url | Dokumentets bas-URI. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastar ett undantag om base-uri‑parametern är null. |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
// Skapa ett minnesström‑objekt
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Skriv HTML‑koden till minnesobjektet
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Det är viktigt att sätta positionen till början eftersom HTMLDocument börjar läsa exakt från den aktuella positionen i strömmen
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initiera ett dokument från String-variabeln
	using (var document = new HTMLDocument(mem, "."))
	{
		// Spara dokumentet till en disk
		document.Save("load-from-stream.html");
	}
}
```

### Se även

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Skapar ett HTML-dokument från [`RequestMessage`](../../../com.aspose.html.net/requestmessage/)‑objektet.

```java
public HTMLDocument(RequestMessage request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| request | RequestMessage | Begäranmeddelandet som innehåller en [`body`](../../../com.aspose.html.net/requestmessage/content/) med dokumentinnehåll. |

## Anmärkningar

Enligt definitionen är en meddelandehanterare en klass som tar emot en Web‑begäran och returnerar ett Web‑svar. Med andra ord används en meddelandehanterare för att bearbeta en Web‑tjänstbegäran under inmatning och/eller för att bearbeta svaret under utmatning.

Vänligen besök vår [docs site](https://docs.aspose.com/html/net/message-handlers/) för att se fler scenarier om hur man använder denna konstruktor.

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Skapar ett HTML‑dokument från [RequestMessage](T:com.aspose.html.net.RequestMessage)‑objektet.

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| request | RequestMessage | Begäranmeddelandet som innehåller en [body](P:com.aspose.html.net.RequestMessage.Content) med dokumentinnehåll. |
| konfiguration | Konfiguration | Miljökonfigurationen såsom skriptpolicy, anpassad användar‑stilmall osv. |

## Anmärkningar

Enligt definitionen är en meddelandehanterare en klass som tar emot en Web‑begäran och returnerar ett Web‑svar. Med andra ord används en meddelandehanterare för att bearbeta en Web‑tjänstbegäran under inmatning och/eller för att bearbeta svaret under utmatning.

Vänligen besök vår [docs site](https://docs.aspose.com/html/net/message-handlers/) för att se fler scenarier om hur man använder denna konstruktor.

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
