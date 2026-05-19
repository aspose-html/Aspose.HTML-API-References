---
title: "Document.Navigate"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Carica il documento all'URL Uniform Resource Locator specificato nell'istanza corrente, sostituendo il contenuto precedente."
type: docs

url: /it/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente.

```java
public void Navigate(String address)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indirizzo | String | L'indirizzo del documento. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |

### Vedi anche

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente.

```java
public void Navigate(Url url)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | Url | L'URL del documento. |

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente.

```java
public void Navigate(String content, String baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto del documento. |
| baseUri | String | L'URI di base per risolvere le risorse relative. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | `baseUri` è `null`. |

### Vedi anche

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente.

```java
public void Navigate(String content, Url baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | String | Il contenuto del documento. |
| baseUri | Url | L'URI di base per risolvere le risorse relative. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | `baseUri` è `null`. |

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream.

```java
public void Navigate(Stream content, String baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | Stream | Il contenuto del documento. |
| baseUri | String | L'URI di base per risolvere le risorse relative. Verrà combinato con il percorso della directory corrente per formare un URL assoluto. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | `baseUri` è `null`. |

### Vedi anche

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contenuto | Stream | Il contenuto del documento. |
| baseUri | Url | L'URI di base per risolvere le risorse relative. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | `baseUri` è `null`. |

### Vedi anche

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Carica il documento in base all'oggetto request specificato, sostituendo il contenuto precedente.

```java
public void Navigate(RequestMessage request)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| richiesta | RequestMessage | L'oggetto request utilizzato per caricare il contenuto del documento. |

### Vedi anche

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
