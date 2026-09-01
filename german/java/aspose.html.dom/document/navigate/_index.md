---
title: "Document.Navigate"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Lädt das Dokument unter der angegebenen Uniform Resource Locator‑URL in die aktuelle Instanz und ersetzt den vorherigen Inhalt."
type: docs

url: /de/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Lädt das Dokument an der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```java
public void Navigate(String address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Adresse | String | Die Dokumentadresse. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |

### Siehe auch

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Lädt das Dokument an der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```java
public void Navigate(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die Dokument-URL. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | String | Die Basis-URI zum Auflösen relativer Ressourcen. Sie wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | Url | Die Basis-URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | String | Die Basis-URI zum Auflösen relativer Ressourcen. Sie wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | Url | Die Basis-URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt.

```java
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anfrage | RequestMessage | Das Anforderungsobjekt, das zum Laden des Dokumentinhalts verwendet wird. |

### Siehe auch

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
