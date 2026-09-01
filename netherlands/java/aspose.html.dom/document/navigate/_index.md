---
title: "Document.Navigate"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. Laadt het document op de opgegeven Uniform Resource Locator URL in de huidige instantie, waarbij de vorige inhoud wordt vervangen."
type: docs

url: /nl/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```java
public void Navigate(String address)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| adres | String | Het documentadres. Het wordt gecombineerd met het pad van de huidige map om een absolute URL te vormen. |

### Zie ook

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```java
public void Navigate(Url url)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De document-URL. |

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document begint vanaf de huidige positie in de stream.

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stroom | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document begint vanaf de huidige positie in de stream.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stroom | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen.

```java
public void Navigate(RequestMessage request)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| verzoek | RequestMessage | Het request-object dat wordt gebruikt om documentinhoud te laden. |

### Zie ook

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
