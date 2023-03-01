---
title: Document.Navigate
second_title: Referencia de API de Aspose.HTML para .NET
description: Document método. Carga el documento en el localizador uniforme de recursos URL especificado en la instancia actual reemplazando el contenido anterior.
type: docs
weight: 1010
url: /es/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Carga el documento en el localizador uniforme de recursos (URL) especificado en la instancia actual, reemplazando el contenido anterior.

```csharp
public void Navigate(string address)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| address | String | La dirección del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Ver también

* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Carga el documento en el localizador uniforme de recursos (URL) especificado en la instancia actual, reemplazando el contenido anterior.

```csharp
public void Navigate(Url url)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento. |

### Ver también

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior.

```csharp
public void Navigate(string content, string baseUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| content | String | El contenido del documento. |
| baseUri | String | El URI base para resolver los recursos relativos. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es`nulo`. |

### Ver también

* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| content | String | El contenido del documento. |
| baseUri | Url | El URI base para resolver los recursos relativos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es`nulo`. |

### Ver también

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en la secuencia.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del documento. |
| baseUri | String | El URI base para resolver los recursos relativos. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es`nulo`. |

### Ver también

* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Carga el documento desde el contenido especificado y usa baseUri para resolver los recursos relativos, reemplazando el contenido anterior. La carga del documento comienza desde la posición actual en la secuencia.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del documento. |
| baseUri | Url | El URI base para resolver los recursos relativos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | `baseUri` es`nulo`. |

### Ver también

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Carga el documento basado en el objeto de solicitud especificado, reemplazando el contenido anterior.

```csharp
public void Navigate(RequestMessage request)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| request | RequestMessage | El objeto de solicitud que se utiliza para cargar el contenido del documento. |

### Ver también

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* espacio de nombres [Aspose.Html.Dom](../../document/)
* asamblea [Aspose.HTML](../../../)


