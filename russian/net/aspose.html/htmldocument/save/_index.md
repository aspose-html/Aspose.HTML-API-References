---
title: Save
second_title: Справочник по Aspose.HTML для .NET API
description: Сохраняет документ в локальный файл указанный url . Все ресурсы используемые в этом документе будут сохранены в в соседнюю папку имя которой будет построено какoutput_file_name  _files.
type: docs
weight: 130
url: /ru/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Сохраняет документ в локальный файл, указанный` url` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный URL не является допустимым URL локального файла . |

### Смотрите также

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

Сохраняет документ в локальный файл, указанный` path` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный путь не является допустимым локальным путем к файлу . |

### Смотрите также

* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

Сохраняет документ в локальный файл, указанный` path` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный путь не является допустимым локальным путем к файлу . |

### Смотрите также

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Сохраняет документ в локальный файл, указанный` url` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный URL не является допустимым URL локального файла . |

### Смотрите также

* class [Url](../../url)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

Сохраняет документ в локальный файл, указанный` path` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveOptions | HTMLSaveOptions | Параметры сохранения HTML. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный путь не является допустимым локальным путем к файлу . |

### Смотрите также

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Сохраняет документ в локальный файл, указанный` url` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveOptions | HTMLSaveOptions | Параметры сохранения HTML. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный URL не является допустимым URL локального файла . |

### Смотрите также

* class [Url](../../url)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | HTMLSaveOptions | Параметры сохранения HTML. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

Сохраняет документ в локальный файл, указанный` path` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveOptions | MarkdownSaveOptions | Параметры сохранения Markdown. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный путь не является допустимым локальным путем к файлу . |

### Смотрите также

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Сохраняет документ в локальный файл, указанный` url` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveOptions | MarkdownSaveOptions | Параметры сохранения Markdown. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный URL не является допустимым URL локального файла . |

### Смотрите также

* class [Url](../../url)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | MarkdownSaveOptions | Параметры сохранения Markdown. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

Сохраняет документ в локальный файл, указанный` path` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveOptions | MHTMLSaveOptions | Параметры сохранения MHTML. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный путь не является допустимым локальным путем к файлу . |

### Смотрите также

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Сохраняет документ в локальный файл, указанный` url` . Все ресурсы, используемые в этом документе, будут сохранены в в соседнюю папку, имя которой будет построено как:output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveOptions | MHTMLSaveOptions | Параметры сохранения MHTML. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указанный URL не является допустимым URL локального файла . |

### Смотрите также

* class [Url](../../url)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | MHTMLSaveOptions | Параметры сохранения MHTML. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* пространство имен [Aspose.Html](../../htmldocument)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
