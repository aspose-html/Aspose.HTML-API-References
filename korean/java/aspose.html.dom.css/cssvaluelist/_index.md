---
title: "CSSValueList 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.CSSValueList 클래스. CSSValueList 인터페이스는 CSS 값들의 순서가 있는 컬렉션에 대한 추상화를 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList 인터페이스는 CSS 값들의 순서가 있는 컬렉션에 대한 추상화를 제공합니다.

참고: 이 인터페이스는 타입이 지정된 CSS 객체 모델을 만들려는 시도의 일부였습니다. 해당 시도는 포기되었으며, 대부분의 브라우저가 이를 구현하지 않습니다.

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | `CSSValueList` 클래스의 새 인스턴스를 초기화합니다. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | `CSSValueList` 클래스의 새 인스턴스를 초기화합니다. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | `CSSValueList` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 인터페이스의 cssText 속성은 현재 계산된 CSS 속성 값을 나타냅니다. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 값의 유형을 정의하는 코드입니다. |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) CSSValueList 인터페이스의 item() 메서드는 순서 인덱스로 CSSValue를 가져오는 데 사용됩니다. |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) CSSValueList 인터페이스의 읽기 전용 length 속성은 리스트에 포함된 CSSValue의 개수를 나타냅니다. 인덱스의 유효 범위는 0부터 length-1까지 포함합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 지정된 객체가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | 이 메서드는 ECMAScript 객체 유형을 가져오는 데 사용됩니다. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

### 또 보기

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
