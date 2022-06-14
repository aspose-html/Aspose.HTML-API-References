---
title: SVGLength
second_title: Справочник по Aspose.HTML для .NET API
description: Интерфейс SVGLength соответствует базовому типу данных length. Объект SVGLength может быть назначен только для чтения что означает что попытки изменить объект приведут к возникновению исключения как описано ниже.
type: docs
weight: 1310
url: /ru/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Интерфейс SVGLength соответствует базовому типу данных length. Объект SVGLength может быть назначен только для чтения, что означает, что попытки изменить объект приведут к возникновению исключения, как описано ниже.

```csharp
public class SVGLength : SVGValueType
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype) { get; } | Тип значения, указанный одной из констант SVG_LENGTHTYPE_*, определенных в этом интерфейсе. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value) { get; set; } | Значение в виде числа с плавающей запятой в пользовательских единицах. Установка этого атрибута приведет к автоматическому обновлению valueInSpecifiedUnits и valueAsString, чтобы отразить этот параметр. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring) { get; set; } | Значение в виде строкового значения в единицах, выраженных unitType. Установка этого атрибута приведет к автоматическому обновлению value, valueInSpecifiedUnits и unitType, чтобы отразить этот параметр. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits) { get; set; } | Значение в виде значения с плавающей запятой в единицах, выраженных unitType. Установка этого атрибута приведет к автоматическому обновлению value и valueAsString, чтобы отразить этот параметр. |

## Методы

| Имя | Описание |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits)(ushort) | Сохраняет то же базовое сохраненное значение, но сбрасывает сохраненный идентификатор устройства на заданный тип устройства. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате применения этого метода. Например, если исходное значение было «0,5 см», а метод был вызван для преобразования в миллиметры, то unitType будет изменен на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменен на числовое значение 5, а valueAsString будет изменен на «5 мм». |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | Освобождает неуправляемые и (необязательно) управляемые ресурсы. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits)(ushort, float) | Сбросить значение как число с соответствующим unitType, тем самым заменив значения для всех атрибутов объекта. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm) | Значение было указано с использованием единиц см, определенных в CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems) | Значение было указано с использованием единиц измерения em, определенных в CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs) | Значение было указано с использованием единиц ex, определенных в CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in) | Значение было указано с использованием единиц измерения, определенных в CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm) | Значение было указано с использованием единиц мм, определенных в CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number) | Тип единицы измерения не указан (т. е. указано безразмерное значение), что указывает на значение в пользовательских единицах. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc) | Значение было указано с использованием единиц пк, определенных в CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage) | Было указано процентное значение. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt) | Значение было указано с использованием единиц измерения pt, определенных в CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px) | Значение было указано с использованием единиц измерения пикселей, определенных в CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown) | Тип юнита не является одним из предопределенных типов юнита. Недопустимо пытаться определить новое значение этого типа или пытаться переключить существующее значение на этот тип. |

### Смотрите также

* class [SVGValueType](../svgvaluetype)
* пространство имен [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
