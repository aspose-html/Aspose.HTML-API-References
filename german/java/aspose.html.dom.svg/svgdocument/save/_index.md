---
title: "SVGDocument.Save"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGDocument-Methode. Speichert das Dokument in einer lokalen Datei, die durch url angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name als output_file_name_files konstruiert wird."
type: docs

url: /de/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Speichert das Dokument in die lokale Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

Speichert das Dokument in die lokale Datei, die durch `path` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

Speichert das Dokument in die lokale Datei, die durch `path` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

Speichert das Dokument in die lokale Datei, die durch `path` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

### Siehe auch

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Speichert das Dokument in die lokale Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Speichert das Dokument in die lokale Datei, die durch `url` angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
