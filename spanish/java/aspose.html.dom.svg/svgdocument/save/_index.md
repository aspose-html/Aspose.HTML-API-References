---
title: "SVGDocument.Save"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGDocument. Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente cuyo nombre se construirá como output_file_name _files"
type: docs

url: /es/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Guarda el documento en el archivo local especificado por `url`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local al archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

Guarda el documento en el archivo local especificado por `path`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | String | Ruta local al archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

### Ver también

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Guarda el contenido y los recursos del documento usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

Guarda el documento en el archivo local especificado por `path`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | String | Ruta local al archivo de salida. |
| saveFormat | SVGSaveFormat | Formato en el que se guarda el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

### Ver también

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

Guarda el contenido y los recursos del documento usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Formato en el que se guarda el documento. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

Guarda el documento en el archivo local especificado por `path`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | String | Ruta local al archivo de salida. |
| saveOptions | SVGSaveOptions | Opciones de guardado SVG. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

### Ver también

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

Guarda el contenido y los recursos del documento usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | Opciones de guardado SVG. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Guarda el documento en el archivo local especificado por `url`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local al archivo de salida. |
| saveFormat | SVGSaveFormat | Formato en el que se guarda el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Guarda el documento en el archivo local especificado por `url`. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local al archivo de salida. |
| saveOptions | SVGSaveOptions | Opciones de guardado SVG. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
