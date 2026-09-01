---
title: "SVGException 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.svg.SVGException 클래스. 이 예외는 특정 SVG 작업을 수행할 수 없을 때 발생합니다"
type: docs

url: /ko/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

특정 SVG 작업을 수행할 수 없을 때 이 예외가 발생합니다.

```java
public class SVGException : PlatformException
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGException](svgexception/)(ushort) | `SVGException` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) 요청된 작업을 수행할 수 없게 된 이유를 식별하는 코드입니다. 이 멤버의 값은 SVGException 코드 그룹의 상수 중 하나가 됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | 작업에 잘못된 값이 전달되었거나 속성에 할당될 때 발생합니다. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | 역행렬이 존재하지 않을 때 역행을 시도하면 발생합니다. |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | 잘못된 유형의 객체가 작업에 전달될 때 발생합니다. |

### 또 보기

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
