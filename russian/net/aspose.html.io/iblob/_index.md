---
title: IBlob
second_title: Справочник по Aspose.HTML для .NET API
description: Объект Blob ссылается на последовательность байтов и имеет атрибут размера который является общим количеством байтов в последовательности байтов и атрибут типа который является ASCII закодированная строка в нижнем регистре представляющая тип носителя последовательности байтов.
type: docs
weight: 3780
url: /ru/net/aspose.html.io/iblob/
---
## IBlob interface

Объект Blob ссылается на последовательность байтов и имеет атрибут размера, который является общим количеством байтов в последовательности байтов, и атрибут типа, который является ASCII закодированная строка в нижнем регистре, представляющая тип носителя последовательности байтов.

```csharp
public interface IBlob
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size) { get; } | Возвращает размер последовательности байтов в байтах. При получении соответствующие пользовательские агенты должны возвращать общее количество байтов, которые могут быть прочитаны объектом FileReader или FileReaderSync, или 0, если в большом двоичном объекте нет байтов для чтения. |
| [Type](../../aspose.html.io/iblob/type) { get; } | Строка в кодировке ASCII в нижнем регистре, представляющая тип мультимедиа BLOB-объекта. При получении пользовательские агенты должны возвращать тип Blob в виде строки в кодировке ASCII в нижнем регистре, таким образом, чтобы при преобразовании в последовательность байтов это был анализируемый тип MIME, или пустая строка – 0 байт – если тип не может быть определен. |

## Методы

| Имя | Описание |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice)(ulong, ulong, string) | Возвращает новый объект Blob с байтами в диапазоне от необязательного начального параметра до, но не включая необязательный конечный параметр, и с атрибутом типа это значение необязательного параметра contentType. |

### Смотрите также

* пространство имен [Aspose.Html.IO](../../aspose.html.io)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
