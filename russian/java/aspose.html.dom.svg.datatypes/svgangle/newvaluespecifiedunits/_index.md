---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGAngle. Сбрасывает значение как число с соответствующим unitType, тем самым заменяя значения всех атрибутов объекта."
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Сбросьте значение как число с ассоциированным unitType, тем самым заменив значения всех атрибутов объекта.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newUnitType | UInt16 | Тип единицы измерения для значения (например, SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Значение угла. |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) возникает, если unitType имеет значение SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы (одна из остальных констант SVG_ANGLETYPE_* , определённых в этом интерфейсе). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Возникает, когда угол соответствует атрибуту только для чтения или когда сам объект только для чтения. |

### См. также

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
