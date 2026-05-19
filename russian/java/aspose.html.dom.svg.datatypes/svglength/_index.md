---
title: "Класс SVGLength"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.datatypes.SVGLength. Интерфейс SVGLength соответствует базовому типу данных length. Объект SVGLength может быть помечен как только для чтения, что означает, что попытки изменить объект приведут к выбросу исключения, как описано ниже."
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Интерфейс SVGLength соответствует базовому типу данных длина. Объект SVGLength может быть помечен как только для чтения, что означает, что попытки изменить объект приведут к выбросу исключения, как описано ниже.

```java
public class SVGLength : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Тип значения, указанный одним из констант SVG_LENGTHTYPE_* определённых в этом интерфейсе. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Методы

| Имя | Описание |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было "0.5cm" и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменено на числовое значение 5, а valueAsString будет изменено на "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Сбросьте значение как число с ассоциированным unitType, тем самым заменив значения всех атрибутов объекта. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Значение было указано с использованием единиц cm, определённых в CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Значение было указано с использованием единиц em, определённых в CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Значение было указано с использованием единиц ex, определённых в CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Значение было указано с использованием единиц in, определённых в CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Значение было указано с использованием единиц mm, определённых в CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Тип единицы не был указан (т.е. было указано безединичное значение), что указывает на значение в пользовательских единицах. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Значение было указано с использованием единиц pc, определённых в CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Было указано процентное значение. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Значение было указано с использованием единиц pt, определённых в CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Значение было указано с использованием единиц px, определённых в CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Тип единицы измерения не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или переключить существующее значение на этот тип. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
