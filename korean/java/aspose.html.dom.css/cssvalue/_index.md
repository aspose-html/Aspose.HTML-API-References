---
title: "CSSValue 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.CSSValue 클래스. 단순하거나 복합적인 값을 나타냅니다. CSSValue 객체는 CSS 속성의 컨텍스트에서만 발생합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

단순값 또는 복합값을 나타냅니다. CSSValue 객체는 CSS 속성의 컨텍스트에서만 발생합니다.

```java
public abstract class CSSValue : DOMObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` 인터페이스의 cssText 속성은 현재 계산된 CSS 속성 값을 나타냅니다. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 값의 유형을 정의하는 코드입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | 이 메서드는 ECMAScript 객체 유형을 가져오는 데 사용됩니다. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | 값은 사용자 정의 값입니다. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | 값은 상속되며 cssText에 "inherit"가 포함됩니다. |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | 값은 원시 값이며 CSSPrimitiveValue 인터페이스의 인스턴스를 CSSValue 인터페이스의 이 인스턴스에 대해 바인딩 전용 캐스팅 메서드를 사용하여 얻을 수 있습니다. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | 값은 CSSValue 목록이며, CSSValue 인터페이스의 이 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 CSSValueList 인터페이스의 인스턴스를 얻을 수 있습니다. |

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
