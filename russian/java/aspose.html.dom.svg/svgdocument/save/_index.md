---
title: "SVGDocument.Save"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGDocument. Сохраняет документ в локальный файл, указанный в url. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name _files"
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(String path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

### См. также

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

### См. также

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

Сохраняет документ в локальный файл, указанный `path`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

### См. также

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Сохраняет документ в локальный файл, указанный `url`. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
