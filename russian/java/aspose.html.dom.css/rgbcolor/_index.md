---
title: "RGBColor класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.RGBColor class. Интерфейс RGBColor используется для представления любого значения цвета RGB. Этот интерфейс отражает значения в базовом свойстве стиля. Поэтому изменения, внесённые в объекты CSSPrimitiveValue, изменяют свойство стиля."
type: docs

url: /ru/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

Интерфейс RGBColor используется для представления любого значения цвета RGB. Этот интерфейс отражает значения в базовом свойстве стиля. Следовательно, изменения, внесённые в объекты CSSPrimitiveValue, изменяют свойство стиля.

Указанный цвет RGB не обрезается (даже если число выходит за диапазон 0‑255 или 0%‑100%). Вычисленный цвет RGB обрезается в зависимости от устройства.

Даже если таблица стилей может содержать только целое число для значения цвета, внутреннее хранение этого целого представлено как число с плавающей точкой, и его можно использовать как float в указанном или вычисленном стиле.

Значение цвета в процентах всегда может быть преобразовано в число и наоборот.

```java
public class RGBColor : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Получает значение альфа‑компоненты этой структуры Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Получает значение синей компоненты этой структуры Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Получает значение зелёной компоненты этой структуры Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Получает значение красной компоненты этой структуры Color. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Преобразует в нативный объект цвета. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
