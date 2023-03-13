---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Справочник по Aspose.HTML для .NET API
description: SVGAngle метод. Сохраняет то же базовое сохраненное значение но сбрасывает сохраненный идентификатор устройства на заданный тип устройства. Атрибуты объекта unitType valueInSpecifiedUnits и valueAsString могут быть изменены в результате применения этого метода.
type: docs
weight: 50
url: /ru/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Сохраняет то же базовое сохраненное значение, но сбрасывает сохраненный идентификатор устройства на заданный тип устройства. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате применения этого метода.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы измерения для переключения (например, SVG_ANGLETYPE_DEG). |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Возникает, если unitType имеет значение SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы измерения (одной из других констант SVG_ANGLETYPE_*, определенных в этом интерфейсе). |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Возникает, когда угол соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### Смотрите также

* class [SVGAngle](../)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* сборка [Aspose.HTML](../../../)


