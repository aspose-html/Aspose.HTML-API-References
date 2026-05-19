---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGLength. Сохраняет то же базовое сохранённое значение, но сбрасывает идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было 0.5cm и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменён на числовое значение 5, а valueAsString будет изменён на 5mm."
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода. Например, если исходное значение было "0.5cm" и метод был вызван для преобразования в миллиметры, то unitType будет изменён на SVG_LENGTHTYPE_MM, valueInSpecifiedUnits будет изменено на числовое значение 5, а valueAsString будет изменено на "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы, на который нужно переключиться (например, SVG_LENGTHTYPE_MM). |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) вызывается, если unitType имеет значение SVG_LENGTHTYPE_UNKNOWN или не является допустимой константой типа единицы (одна из остальных констант SVG_LENGTHTYPE_* , определённых в этом интерфейсе). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует только для чтения атрибуту или когда сам объект только для чтения. |

### См. также

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
