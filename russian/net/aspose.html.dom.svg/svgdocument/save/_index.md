---
title: SVGDocument.Save
second_title: Справочник по Aspose.HTML для .NET API
description: SVGDocument метод. Сохраняет документ в локальный файл указанныйURL Все ресурсы используемые в этом документе будут сохранены в в соседней папке имя которой будет построено как output_file_name  _files.
type: docs
weight: 90
url: /ru/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Сохраняет документ в локальный файл, указанный`URL` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`URL` не является допустимым URL-адресом локального файла. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

Сохраняет документ в локальный файл, указанный`путь` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`путь` не является допустимым локальным путем к файлу. |

### Смотрите также

* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

Сохраняет документ в локальный файл, указанный`путь` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`путь` не является допустимым локальным путем к файлу. |

### Смотрите также

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

Сохраняет документ в локальный файл, указанный`путь` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Локальный путь к выходному файлу. |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`путь` не является допустимым локальным путем к файлу. |

### Смотрите также

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

Сохраняет содержимое и ресурсы документа в выходное хранилище.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStorage | IOutputStorage | Выходное хранилище[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### Смотрите также

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Сохраняет документ в локальный файл, указанный`URL` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveFormat | SVGSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`URL` не является допустимым URL-адресом локального файла. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Сохраняет документ в локальный файл, указанный`URL` Все ресурсы, используемые в этом документе, будут сохранены в в соседней папке, имя которой будет построено как: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL для выходного файла. |
| saveOptions | SVGSaveOptions | Параметры сохранения SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Возникает, если указано`URL` не является допустимым URL-адресом локального файла. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* пространство имен [Aspose.Html.Dom.Svg](../../svgdocument/)
* сборка [Aspose.HTML](../../../)


