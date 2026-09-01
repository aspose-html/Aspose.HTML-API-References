---
title: "SVGAngle Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle класс. Интерфейс SVGAngle соответствует базовому типу данных angle"
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Интерфейс SVGAngle соответствует базовому типу данных angle.

```java
public class SVGAngle : SVGValueType
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Тип значения, указанный одним из констант SVG_ANGLETYPE_* , определённых в этом интерфейсе. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Методы

| Имя | Описание |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Сохраните то же самое базовое сохранённое значение, но сбросьте сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате этого метода. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Сбросьте значение как число с ассоциированным unitType, тем самым заменив значения всех атрибутов объекта. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Тип единицы измерения был явно установлен в градусы. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Тип единицы измерения — радианы. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Тип единицы измерения — радианы. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Тип единицы измерения не является одним из предопределённых типов. Недопустимо пытаться определить новое значение этого типа или переключить существующее значение на этот тип. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Тип единицы измерения не был указан (т.е. было задано безразмерное значение). Для углов безразмерное значение рассматривается так же, как если бы были указаны градусы. |

### См. также

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
