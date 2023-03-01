---
title: Class Color
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Drawing.Color сорт. Класс Color позволяет задавать цвета как значения RedGreenBlue RGB значения HueSaturationLuminosity HSL значения HueSaturationValue HSV HueWhitenessBlackness HWB  значения значения яркостиAB LAB значения LuminanceChromaHue LCH значения CyanMagentaYellowKey CMYK значения естественных цветов NCOL или с названием цвета . Также доступен альфаканал для обозначения прозрачности.
type: docs
weight: 2640
url: /ru/net/aspose.html.drawing/color/
---
## Color class

Класс Color позволяет задавать цвета как значения Red-Green-Blue (RGB), значения Hue-Saturation-Luminosity (HSL), значения Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB) ) значения, значения яркости-AB (LAB), значения Luminance-Chroma-Hue (LCH), значения Cyan-Magenta-Yellow-Key (CMYK), значения естественных цветов (NCOL), или с названием цвета . Также доступен альфа-канал для обозначения прозрачности.

```csharp
public class Color
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Color](color/#constructor)() | Инициализирует новый экземпляр`Color` class. По умолчанию черный цвет. |
| [Color](color/#constructor_1)(byte, byte, byte) | Инициализирует новый экземпляр`Color`class. Все компоненты цвета должны быть в диапазоне 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Инициализирует новый экземпляр`Color` class. Все компоненты цвета должны быть в диапазоне 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Инициализирует новый экземпляр`Color`class. Все компоненты цвета должны быть в диапазоне 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Инициализирует новый экземпляр`Color`class. Все компоненты цвета должны быть в диапазоне 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Инициализирует новый экземпляр`Color` class. Все компоненты цвета должны быть в диапазоне 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Инициализирует новый экземпляр`Color`class. Все компоненты цвета должны быть в диапазоне 0-255. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Представляет альфа-компонент цвета. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Представляет синий компонент цвета. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Представляет зеленый компонент цвета. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Представляет красный компонент цвета |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями голубого, пурпурного, желтого, ключевого (черного) цвета. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Возвращает новый цвет с запрошенными значениями голубого, пурпурного, желтого, ключевого (черного) и альфа-канала. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Возвращает новый цвет с запрошенным значением серого. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Возвращает новый цвет с запрошенными значениями оттенка, насыщенности, насыщенности. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями оттенка, насыщенности, насыщенности, альфа-канала. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Возвращает новый цвет с запрошенным оттенком, насыщенностью, значением. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Возвращает новый цвет с запрошенным оттенком, насыщенностью, значением, альфа-каналом. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Возвращает новый цвет с запрошенными значениями оттенка, белизны, черноты. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями оттенка, белизны, черноты. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Возвращает новый цвет с запрошенным значением ARGB. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Возвращает новый цвет с запрошенными значениями светлоты, A, B. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями светлоты, A, B, альфа. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Возвращает новый цвет с запрошенными значениями яркости, цветности и оттенка. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями яркости, цветности, оттенка и альфа-канала. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Возвращает новый цвет с запрошенными значениями светлоты, A, B для модели OKLAB. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями светлоты, A, B, альфа для модели OKLAB. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Возвращает новый цвет с запрошенными значениями яркости, цветности и оттенка для модели OKLAB. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями яркости, цветности, оттенка, альфа-канала для модели OKLAB. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Возвращает новый цвет с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Возвращает новый цвет с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-1. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Возвращает новый цвет с запрошенными значениями ged, green, blue. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Возвращает новый цвет с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Возвращает новый цвет с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны быть в диапазоне 0-1. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Возвращает новый цвет с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны быть в диапазоне 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Разбирает строку, содержащую цвет CSS, и возвращает новый цвет. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Возвращает новый цвет с запрошенным значением ARGB. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Создает копию цвета с суммой его яркости и значения дельты. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Возвращает компоненты цвета в формате указанной цветовой модели. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Определяет, является ли указанный`Color` равен этому экземпляру. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Возвращает новый цвет, который находится на противоположной стороне цветового круга от исходного. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Возвращает хэш-код. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Возвращает оттенок цвета. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Возвращает яркость цвета. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Возвращает насыщенность цвета. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Кодирует компоненты Color ARGB в int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Возвращает название цвета, если оно соответствует цвету в списке именованных цветов CSS, или пустую строку. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Возвращает указанный цвет Natural colors (NCol), используя букву цвета с числом, чтобы указать расстояние (в процентах) от цвета. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Возвращает шестнадцатеричный цвет, указанный с помощью: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Возвращает строку, содержащую цвет RGBA, заданный следующим образом: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Возвращает шестнадцатеричный цвет, указанный с помощью: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Возвращает строку, содержащую цвет RGB, заданный следующим образом: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Возвращает строку, состоящую из значений компонента RGBA. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Кодирует компоненты Color ARGB в беззнаковое целое число. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Создает копию цвета с указанным альфа-компонентом. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Создает копию цвета с указанным оттенком. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Создает копию цвета с указанной яркостью. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Создает копию цвета с указанной насыщенностью. |

### Смотрите также

* пространство имен [Aspose.Html.Drawing](../../aspose.html.drawing/)
* сборка [Aspose.HTML](../../)


