---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGLength. Сбрасывает значение как число с соответствующим unitType, тем самым заменяя значения всех атрибутов объекта"
type: docs

url: /ru/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Сбросьте значение как число с ассоциированным unitType, тем самым заменив значения всех атрибутов объекта.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| unitType | UInt16 | Тип единицы для значения. |
| valueInSpecifiedUnits | Single | Новое значение.. |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) вызывается, если unitType имеет значение SVG_LENGTHTYPE_UNKNOWN или не является допустимой константой типа единицы (одна из остальных констант SVG_LENGTHTYPE_* , определённых в этом интерфейсе). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Возникает, когда длина соответствует только для чтения атрибуту или когда сам объект только для чтения. |

### См. также

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
