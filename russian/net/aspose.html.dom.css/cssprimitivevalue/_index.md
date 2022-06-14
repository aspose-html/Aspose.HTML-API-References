---
title: CSSPrimitiveValue
second_title: Справочник по Aspose.HTML для .NET API
description: Интерфейс CSSPrimitiveValue представляет одно значение CSS. Этот интерфейс может использоваться для определения значения определенного свойства стиля установленного в данный момент в блоке или для явной установки определенного свойства стиля в блоке. Экземпляр этого интерфейса можно получить из метода getPropertyCSSValue интерфейса CSSStyleDeclaration. Объект CSSPrimitiveValue встречается только в контексте свойства CSS.
type: docs
weight: 440
url: /ru/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Интерфейс CSSPrimitiveValue представляет одно значение CSS. Этот интерфейс может использоваться для определения значения определенного свойства стиля, установленного в данный момент в блоке, или для явной установки определенного свойства стиля в блоке. Экземпляр этого интерфейса можно получить из метода getPropertyCSSValue интерфейса CSSStyleDeclaration. Объект CSSPrimitiveValue встречается только в контексте свойства CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Характеристики

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext) { get; set; } | Строковое представление текущего значения. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype) { get; } | Код, определяющий тип значения. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype) { get; } | Тип значения, определенный указанными выше константами. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals)(object) | Определяет, равен ли указанныйObjectэтому экземпляру. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue)() | Этот метод используется для получения значения счетчика. Если это значение CSS не содержит значения счетчика, возникает исключение DOMException. Модификация соответствующего свойства стиля может быть достигнута с помощью интерфейса счетчика. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue)(ushort) | Этот метод используется для получения значения с плавающей запятой в указанных единицах измерения. Если это значение CSS не содержит значения с плавающей запятой или не может быть преобразовано в указанную единицу измерения, возникает исключение DOMException. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue)(ushort) | Этот метод используется для получения значения int в указанных единицах измерения. Если это значение CSS не содержит значение int или не может быть преобразовано в указанную единицу измерения, возникает исключение DOMException. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype)() | Этот метод используется для получения объекта ECMAScriptType. |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue)() | Этот метод используется для получения значения Rect. Если это значение CSS не содержит прямоугольного значения, возникает исключение DOMException. Модификация соответствующего свойства стиля может быть достигнута с помощью интерфейса Rect. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue)() | Этот метод используется для получения цвета RGB. Если это значение CSS не содержит значение цвета RGB, возникает исключение DOMException. Изменение соответствующего свойства стиля может быть достигнуто с помощью интерфейса RGBColor. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue)() | Этот метод используется для получения строкового значения. Если значение CSS не содержит строкового значения, возникает исключение DOMException. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue)(ushort, float) | Метод для установки значения с плавающей запятой с указанными единицами измерения. Если свойство, присоединенное к этому значению, не может принять указанную единицу измерения или значение с плавающей запятой, значение останется неизменным и будет возбуждено исключение DOMException. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue)(ushort, int) | Метод для установки значения int с указанными единицами измерения. Если свойство, присоединенное к этому значению, не может принять указанную единицу измерения или значение int, значение не изменится, и будет возбуждено исключение DOMException. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue)(ushort, string) | Метод установки строкового значения с указанными единицами измерения. Если свойство, присоединенное к этому значению, не может принять указанную единицу измерения или строковое значение, значение останется неизменным и будет возбуждено исключение DOMException. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr) | Значение является функцией атрибута. Значение можно получить с помощью метода getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch) | Значение представляет собой длину (ch). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm) | Значение представляет собой длину (см). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter) | Значение представляет собой счетчик или функцию счетчиков. Значение можно получить с помощью метода GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg) | Значение представляет собой угол (градус). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension) | Значение представляет собой число с неизвестной размерностью. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm) | Значение — количество точек на сантиметр (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi) | Значение равно количеству точек на дюйм (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx) | Значение представляет собой количество точек на единицу 'px' (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems) | Значение представляет собой длину (ems). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs) | Значение представляет собой длину (exs). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad) | Значение представляет собой угол (град). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz) | Значение представляет собой частоту (Гц). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident) | Значение является идентификатором. Значение можно получить с помощью метода getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in) | Значение представляет собой длину (в дюймах). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz) | Значение представляет собой частоту (кГц). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm) | Значение представляет собой длину (мм). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms) | Значение представляет собой время (мс). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number) | Значение представляет собой простое число. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc) | Значение представляет собой длину (пк). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage) | Значение в процентах. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt) | Значение представляет собой длину (pt). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px) | Значение представляет собой длину (px). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad) | Значение представляет собой угол (рад). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect) | Значение представляет собой прямоугольную функцию. Значение можно получить с помощью метода GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem) | Значение представляет собой длину (бэр). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor) | Значение представляет собой цвет RGB. Значение можно получить с помощью метода GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s) | Значение представляет собой время (с). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string) | Значение представляет собой STRING. Значение можно получить с помощью метода getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown) | Значение не является распознанным значением CSS2. Значение можно получить только с помощью атрибута cssText. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri) | Значение представляет собой URI. Значение можно получить с помощью метода getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh) | Значение представляет собой процент от полной высоты окна просмотра. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax) | Значение представляет собой процент от ширины или высоты области просмотра, в зависимости от того, что больше. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin) | Значение представляет собой процент от ширины или высоты области просмотра, в зависимости от того, что меньше. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw) | Значение представляет собой процент от полной ширины области просмотра. |

### Смотрите также

* class [CSSValue](../cssvalue)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
