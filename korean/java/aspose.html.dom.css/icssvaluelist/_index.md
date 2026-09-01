---
title: "ICSSValueList 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.ICSSValueList 인터페이스. CSSValueList 인터페이스는 CSSValue 인터페이스를 상속하며 CSS 값들의 순서가 있는 컬렉션에 대한 추상화를 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList 인터페이스는 [`CSSValue`](../cssvalue/) 인터페이스를 상속하고 CSS 값들의 순서가 있는 컬렉션에 대한 추상화를 제공합니다.

일부 속성은 구문에서 빈 리스트를 허용합니다. 이 경우 해당 속성은 none 식별자를 사용합니다. 따라서 빈 리스트는 속성 값이 none임을 의미합니다.

CSSValueList의 항목은 0부터 시작하는 정수 인덱스를 통해 접근할 수 있습니다.

```java
public interface ICSSValueList
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) 이 메서드는 순서 인덱스로 CSSValue를 검색하는 데 사용됩니다. 이 컬렉션의 순서는 CSS 스타일 속성의 값 순서를 나타냅니다. 인덱스가 리스트의 값 개수보다 크거나 같으면 null을 반환합니다. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) CSSValueList 인터페이스의 읽기 전용 length 속성은 리스트에 포함된 CSSValue의 개수를 나타냅니다. 인덱스의 유효 범위는 0부터 length-1까지 포함합니다. |

## 비고

이 인터페이스는 타입이 지정된 CSS Object Model을 만들려는 시도의 일부였습니다. 해당 시도는 포기되었으며 대부분의 브라우저가 이를 구현하지 않습니다.

목적을 달성하려면 다음을 사용할 수 있습니다:

타입이 지정되지 않은 [CSS Object Model](https://drafts.csswg.org/cssom/), 널리 지원되는 것 또는 최신 [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), 지원이 적고 실험적인 것으로 간주되는 것을 사용할 수 있습니다.

### 또 보기

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
