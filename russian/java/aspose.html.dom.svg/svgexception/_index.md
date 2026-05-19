---
title: "SVGException класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.SVGException класс. Это исключение возникает, когда конкретную операцию SVG выполнить невозможно."
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

Это исключение вызывается, когда конкретную операцию SVG выполнить невозможно.

```java
public class SVGException : PlatformException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGException](svgexception/)(ushort) | Инициализирует новый экземпляр класса `SVGException`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) Код, идентифицирующий причину, по которой запрошенная операция не могла быть выполнена. Значение этого члена будет одной из констант в группе кодов SVGException. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | Возникает, когда недопустимое значение передаётся в операцию или назначается атрибуту. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | Возникает, когда предпринимается попытка обратить матрицу, которая не обратима. |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | Возникает, когда объект неверного типа передаётся в операцию. |

### См. также

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
