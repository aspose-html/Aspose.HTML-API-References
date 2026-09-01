---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGAngle. Сохраняет то же базовое сохранённое значение, но сбрасывает сохранённый идентификатор единицы на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате вызова этого метода"
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Сохраните то же самое базовое сохранённое значение, но сбросьте сохранённый идентификатор единицы измерения на указанный unitType. Атрибуты объекта unitType, valueInSpecifiedUnits и valueAsString могут быть изменены в результате этого метода.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы, на который следует переключиться (например, SVG_ANGLETYPE_DEG). |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) вызывается, если unitType равен SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы (одной из остальных констант SVG_ANGLETYPE_* определённых в этом интерфейсе). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) возникает, когда угол соответствует атрибуту только для чтения или когда сам объект только для чтения. |

### См. также

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
