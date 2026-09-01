---
title: "Document.Navigate"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. Carga el documento en la URL Uniform Resource Locator especificada en la instancia actual, reemplazando el contenido anterior."
type: docs

url: /es/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Carga el documento en el Uniform Resource Locator (URL) especificado en la instancia actual, reemplazando el contenido anterior.

```java
public void Navigate(String address)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dirección | Cadena | La dirección del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Ver también

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Carga el documento en el Uniform Resource Locator (URL) especificado en la instancia actual, reemplazando el contenido anterior.

```java
public void Navigate(Url url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior.

```java
public void Navigate(String content, String baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido del documento. |
| baseUri | Cadena | El URI base para resolver recursos relativos. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es `null`. |

### Ver también

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior.

```java
public void Navigate(String content, Url baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido del documento. |
| baseUri | Url | El URI base para resolver recursos relativos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es `null`. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en el flujo.

```java
public void Navigate(Stream content, String baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Stream | El contenido del documento. |
| baseUri | Cadena | El URI base para resolver recursos relativos. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es `null`. |

### Ver también

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Carga el documento a partir del contenido especificado y usando baseUri para resolver recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en el flujo.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Stream | El contenido del documento. |
| baseUri | Url | El URI base para resolver recursos relativos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es `null`. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Carga el documento según el objeto de solicitud especificado, reemplazando el contenido anterior.

```java
public void Navigate(RequestMessage request)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| solicitud | RequestMessage | El objeto request que se utiliza para cargar el contenido del documento. |

### Ver también

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
