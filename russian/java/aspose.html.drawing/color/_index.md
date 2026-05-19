---
title: "Класс Color"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.drawing.Color. Класс Color позволяет задавать цвета в виде значений Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) или по имени цвета. Также доступен альфа‑канал для указания прозрачности."
type: docs

url: /ru/java/com.aspose.html.drawing/color/
---
## Color class

Класс Color позволяет задавать цвета в виде значений Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) или по имени цвета. Также доступен альфа‑канал для указания прозрачности.

```java
public class Color
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Color](color/#constructor)() | Инициализирует новый экземпляр класса `Color`. По умолчанию цвет — чёрный. |
| [Color](color/#constructor_1)(byte, byte, byte) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_5)(float, float, float) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑1. |
| [Color](color/#constructor_3)(int, int, int) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_6)(float, float, float, float) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑1. |
| [Color](color/#constructor_4)(int, int, int, int) | Инициализирует новый экземпляр класса `Color`. Все компоненты цвета должны находиться в диапазоне 0‑255. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Представляет альфа‑компонент цвета. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Представляет синий компонент цвета. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Представляет зелёный компонент цвета. |
| [getRed](../../com.aspose.html.drawing/color/red/) Представляет красный компонент цвета |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Возвращает новый объект Color с указанными значениями cyan, magenta, yellow, key (black). |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Возвращает новый объект Color с указанными значениями cyan, magenta, yellow, key (black) и альфа. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Возвращает новый объект Color с указанным значением gray. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Возвращает новый объект Color с указанными значениями hue, saturation, saturation. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Возвращает новый объект Color с указанными значениями hue, saturation, saturation и альфа. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Возвращает новый объект Color с указанными значениями hue, saturation, value. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Возвращает новый объект Color с указанными значениями hue, saturation, value и альфа. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Возвращает новый объект Color с указанными значениями hue, whiteness, blackness. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Возвращает новый объект Color с указанными значениями hue, whiteness, blackness. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Возвращает новый объект Color с указанным значением ARGB. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Возвращает новый объект Color с указанными значениями lightness, A, B. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Возвращает новый Color с запрошенными значениями светлоты, A, B, альфа. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Возвращает новый Color с запрошенными значениями яркости, хромы, оттенка. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Возвращает новый Color с запрошенными значениями яркости, хромы, оттенка, альфа. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Возвращает новый Color с запрошенными значениями светлоты, A, B для модели OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Возвращает новый Color с запрошенными значениями светлоты, A, B, альфа для модели OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Возвращает новый Color с запрошенными значениями яркости, хромы, оттенка для модели OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Возвращает новый Color с запрошенными значениями яркости, хромы, оттенка, альфа для модели OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Возвращает новый Color с запрошенными значениями ged, green, blue, альфа. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Возвращает новый Color с запрошенными значениями ged, green, blue, альфа. Все компоненты цвета должны быть в диапазоне 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Возвращает новый Color с запрошенными значениями ged, green, blue, альфа. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Разбирает String, содержащий CSS‑цвет, и возвращает новый Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Возвращает новый объект Color с указанным значением ARGB. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Создаёт копию Color с суммой её яркости и значением дельты. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Возвращает компоненты цвета в формате указанной цветовой модели. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Определяет, равен ли указанный `Color` этому экземпляру. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Возвращает новый цвет, находящийся на противоположной стороне цветового круга от оригинала. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Возвращает хеш‑код. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Возвращает Hue цвета. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Возвращает яркость цвета. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Возвращает насыщенность цвета. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Кодирует компоненты ARGB Color в int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Возвращает название цвета, если оно совпадает с цветом из списка именованных CSS‑цветов, или пустую String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Возвращает Natural colors (NCol) указанный цвет, используя буквенное обозначение цвета с числом, определяющим расстояние (в процентах) от цвета. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Возвращает шестнадцатеричный цвет, указанный как: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Возвращает String, содержащую RGBA‑цвет, указанный как: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Возвращает шестнадцатеричный цвет, указанный в формате: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Возвращает строку, содержащую RGB‑цвет, указанный как: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Возвращает строку, состоящую из значений компонентов RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Кодирует компоненты ARGB цвета в беззнаковый int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Создаёт копию цвета с указанным альфа‑компонентом. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Создаёт копию цвета с указанным оттенком (Hue). |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Создаёт копию цвета с указанной яркостью. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Создаёт копию цвета с указанной насыщенностью. |

### См. также

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
