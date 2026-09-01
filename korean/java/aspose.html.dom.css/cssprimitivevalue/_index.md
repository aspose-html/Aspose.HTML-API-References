---
title: "CSSPrimitiveValue 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.CSSPrimitiveValue 클래스. CSSPrimitiveValue 인터페이스는 CSSValue 인터페이스를 상속하며 CSS 속성의 현재 계산된 값을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

CSSPrimitiveValue 인터페이스는 CSSValue 인터페이스에서 파생되며 CSS 속성의 현재 계산된 값을 나타냅니다.

참고: 이 인터페이스는 타입이 지정된 CSS 객체 모델을 만들려는 시도의 일부였습니다. 해당 시도는 포기되었으며, 대부분의 브라우저가 이를 구현하지 않습니다.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 인터페이스의 cssText 속성은 현재 계산된 CSS 속성 값을 나타냅니다. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 값의 유형을 정의하는 코드입니다. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) 위에 지정된 상수에 정의된 값의 유형을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | 이 메서드는 Counter 값을 가져오는 데 사용됩니다. 해당 CSS 값에 카운터 값이 없으면 DOMException이 발생합니다. 해당 스타일 속성의 수정은 Counter 인터페이스를 사용해 수행할 수 있습니다. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | 이 메서드는 지정된 단위의 부동 소수점 값을 가져오는 데 사용됩니다. 이 CSS 값에 부동 소수점 값이 없거나 지정된 단위로 변환할 수 없으면 DOMException이 발생합니다. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | 이 메서드는 지정된 단위의 정수 값을 가져오는 데 사용됩니다. 이 CSS 값에 정수 값이 없거나 지정된 단위로 변환할 수 없으면 DOMException이 발생합니다. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | 이 메서드는 ECMAScript 객체 유형을 가져오는 데 사용됩니다. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | 이 메서드는 Rect 값을 가져오는 데 사용됩니다. 이 CSS 값에 rect 값이 없으면 DOMException이 발생합니다. 해당 스타일 속성의 수정은 Rect 인터페이스를 사용하여 수행할 수 있습니다. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | 이 메서드는 RGB 색상을 가져오는 데 사용됩니다. 이 CSS 값에 RGB 색상 값이 없으면 DOMException이 발생합니다. 해당 스타일 속성의 수정은 RGBColor 인터페이스를 사용하여 수행할 수 있습니다. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | 이 메서드는 문자열 값을 가져오는 데 사용됩니다. CSS 값에 문자열 값이 없으면 DOMException이 발생합니다. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | 지정된 단위로 부동 소수점 값을 설정하는 메서드입니다. 이 값이 연결된 속성이 지정된 단위나 부동 소수점 값을 허용하지 않으면 값은 변경되지 않고 DOMException이 발생합니다. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | 지정된 단위로 정수 값을 설정하는 메서드입니다. 이 값이 연결된 속성이 지정된 단위나 정수 값을 허용하지 않으면 값은 변경되지 않고 DOMException이 발생합니다. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | 지정된 단위로 문자열 값을 설정하는 메서드입니다. 이 값이 연결된 속성이 지정된 단위나 문자열 값을 허용하지 않으면 값은 변경되지 않고 DOMException이 발생합니다. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | 값은 속성 함수입니다. 이 값은 getStringValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | 값은 길이 (ch)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | 값은 길이 (cm)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | 값은 counter 또는 counters 함수입니다. 이 값은 GetCounterValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | 값은 각도 (deg)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | 값은 알 수 없는 차원의 숫자입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | 값은 센티미터당 점(dpcm)입니다. |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | 값은 인치당 점(dpi)입니다. |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | 값은 ‘px’ 단위당 점(dppx)입니다. |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | 값은 길이 (ems)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | 값은 길이 (exs)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | 값은 각도 (grad)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | 값은 주파수 (Hz)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | 값은 식별자입니다. 이 값은 getStringValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | 값은 길이 (in)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | 값은 주파수 (kHz)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | 값은 길이 (mm)입니다. 이 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | 값은 시간(ms)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | 값은 단순한 숫자입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | 값은 길이(pc)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | 값은 백분율입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | 값은 길이(pt)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | 값은 길이(px)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | 값은 각도(rad)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | 값은 rect 함수입니다. 값은 GetRectValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | 값은 길이(rem)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | 값은 RGB 색상입니다. 값은 GetRGBColorValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | 값은 시간(s)입니다. 값은 getFloatValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | 값은 문자열(STRING)입니다. 값은 getStringValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | 값은 인식된 CSS2 값이 아닙니다. 값은 cssText 속성을 사용하여만 얻을 수 있습니다. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | 값은 URI입니다. 값은 getStringValue 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | 값은 전체 뷰포트 높이의 백분율입니다. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | 값은 뷰포트 너비 또는 높이 중 큰 쪽의 백분율입니다. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | 값은 뷰포트 너비 또는 높이 중 작은 쪽의 백분율입니다. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | 값은 전체 뷰포트 너비의 백분율입니다. |

### 또 보기

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
