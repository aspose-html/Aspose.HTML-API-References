---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Справочник по Aspose.HTML для .NET API
description: SVGLength метод. Сохраняет то же базовое сохраненное значение но сбрасывает сохраненный идентификатор устройства на заданный тип устройства. Атрибуты объекта unitType valueInSpecifiedUnits и valueAsString могут быть изменены в результате применения этого метода. Например если исходное значение было 05 см а метод был вызван для преобразования в миллиметры то unitType будет изменен на SVG_LENGTHTYPE_MM valueInSpecifiedUnits будет изменен на числовое значение 5 а valueAsString будет изменен на 5 мм.
type: docs
weight: 50
url: /ru/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Сохраняет то же базовое сохраненное значение, но сбрасывает сохраненный идентификатор устройства на заданный тип устройства. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате применения этого метода. Например, если исходное значение было «0,5 см», а метод был вызван для преобразования в миллиметры, то unitType будет изменен на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменен на числовое значение 5, а valueAsString будет изменен на «5 мм».

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы измерения для переключения (например, SVG_LENGTHTYPE_MM). |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Возникает, если unitType имеет значение SVG_LENGTHTYPE_UNKNOWN или не является допустимой константой типа единицы измерения (одной из других констант SVG_LENGTHTYPE_*, определенных в этом интерфейсе). |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### Смотрите также

* class [SVGLength](../)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* сборка [Aspose.HTML](../../../)


