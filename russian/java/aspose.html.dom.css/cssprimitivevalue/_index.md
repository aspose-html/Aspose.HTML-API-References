---
title: "CSSPrimitiveValue Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.CSSPrimitiveValue класс. Интерфейс CSSPrimitiveValue наследуется от интерфейса CSSValue и представляет текущее вычисленное значение свойства CSS."
type: docs

url: /ru/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Интерфейс CSSPrimitiveValue наследуется от интерфейса CSSValue и представляет текущее вычисленное значение свойства CSS.

Примечание: Этот интерфейс был частью попытки создать типизированную модель объектного CSS. Эта попытка была прекращена, и большинство браузеров её не реализуют.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Свойство cssText интерфейса [`CSSValue`](../cssvalue/) представляет текущее вычисленное значение CSS‑свойства. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Код, определяющий тип значения. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Тип значения, определённый константами, указанными выше. |

## Методы

| Имя | Описание |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Этот метод используется для получения значения Counter. Если данное CSS‑значение не содержит значения счётчика, генерируется DOMException. Изменение соответствующего свойства стиля может быть выполнено с помощью интерфейса Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Этот метод используется для получения значения с плавающей точкой в указанной единице измерения. Если это CSS‑значение не содержит значение с плавающей точкой или не может быть преобразовано в указанную единицу, генерируется DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Этот метод используется для получения целочисленного значения в указанной единице измерения. Если это CSS‑значение не содержит целочисленного значения или не может быть преобразовано в указанную единицу, генерируется DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Этот метод используется для получения значения Rect. Если это CSS‑значение не содержит значение rect, генерируется DOMException. Изменение соответствующего свойства стиля можно выполнить с помощью интерфейса Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Этот метод используется для получения цвета RGB. Если это CSS‑значение не содержит значение цвета RGB, генерируется DOMException. Изменение соответствующего свойства стиля можно выполнить с помощью интерфейса RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Этот метод используется для получения строкового значения. Если CSS‑значение не содержит строкового значения, генерируется DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Метод для установки значения с плавающей точкой в указанной единице измерения. Если свойство, к которому привязано это значение, не может принимать указанную единицу или значение с плавающей точкой, значение останется неизменным, и будет сгенерирован DOMException. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Метод для установки целочисленного значения в указанной единице измерения. Если свойство, к которому привязано это значение, не может принимать указанную единицу или целочисленное значение, значение останется неизменным, и будет сгенерирован DOMException. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Метод для установки строкового значения в указанной единице измерения. Если свойство, к которому привязано это значение, не может принимать указанную единицу или строковое значение, значение останется неизменным, и будет сгенерирован DOMException. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Значение представляет собой функцию атрибута. Значение можно получить с помощью метода getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Значение представляет собой длину (ch). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Значение представляет собой длину (cm). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Значение представляет собой функцию counter или counters. Значение можно получить с помощью метода GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Значение представляет собой угол (deg). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Значение представляет собой число с неизвестным измерением. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Значение представляет собой точек на сантиметр (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Значение представляет собой точек на дюйм (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Значение представляет собой точек на единицу ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Значение представляет собой длину (ems). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Значение представляет собой длину (exs). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Значение представляет собой угол (grad). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Значение представляет собой частоту (Hz). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Значение представляет собой идентификатор. Значение можно получить с помощью метода getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Значение представляет собой длину (in). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Значение представляет собой частоту (kHz). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Значение представляет собой длину (mm). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Значение — время (мс). Значение можно получить, используя метод getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Значение — простое число. Значение можно получить, используя метод getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Значение — длина (pc). Значение можно получить, используя метод getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Значение — процент. Значение можно получить, используя метод getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Значение — длина (pt). Значение можно получить, используя метод getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Значение — длина (px). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Значение — угол (rad). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Значение — функция rect. Значение можно получить, используя метод GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Значение — длина (rem). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Значение — цвет RGB. Значение можно получить, используя метод GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Значение — время (s). Значение можно получить, используя метод getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Значение — STRING. Значение можно получить, используя метод getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Значение не является распознанным значением CSS2. Значение можно получить только, используя атрибут cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Значение — URI. Значение можно получить, используя метод getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Значение — процент от полной высоты области просмотра. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Значение — процент от ширины или высоты области просмотра, в зависимости от того, что больше. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Значение — процент от ширины или высоты области просмотра, в зависимости от того, что меньше. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Значение — процент от полной ширины области просмотра. |

### См. также

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
