---
title: "Document.Navigate"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Laddar dokumentet från den angivna Uniform Resource Locator‑URL:en i den aktuella instansen och ersätter det tidigare innehållet."
type: docs

url: /sv/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Läser in dokumentet på den angivna Uniform Resource Locator (URL) i den aktuella instansen och ersätter det tidigare innehållet.

```java
public void Navigate(String address)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | String | Dokumentadressen. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |

### Se även

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Läser in dokumentet på den angivna Uniform Resource Locator (URL) i den aktuella instansen och ersätter det tidigare innehållet.

```java
public void Navigate(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Dokumentets URL. |

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet.

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet.

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Dokumentets innehåll. |
| baseUri | Url | Bas‑URI för att lösa relativa resurser. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Dokumentets innehåll. |
| baseUri | Url | Bas‑URI för att lösa relativa resurser. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet.

```java
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| begäran | RequestMessage | Begäran‑objektet som används för att ladda dokumentinnehåll. |

### Se även

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
