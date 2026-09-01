---
title: "ICSS2Properties.Azimuth"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties property. 공간 오디오는 청각 프레젠테이션을 위한 중요한 스타일 속성입니다. 실제 생활에서 사람들은 방 안의 같은 위치에 모두 서 있지 않듯이 여러 목소리를 구분하는 자연스러운 방법을 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

공간 오디오는 청각 프레젠테이션을 위한 중요한 스타일 속성입니다. 실제 생활에서 (사람들이 방 안의 같은 위치에 모두 서 있지 않듯이) 여러 목소리를 구분하는 자연스러운 방법을 제공합니다.

```java
public String Azimuth { get; set; }
```

### 반환 값

azimuth 속성

### Property Value

값은 다음과 같은 의미를 가집니다:

angle - 위치는 '-360deg'에서 '360deg' 범위의 각도로 설명됩니다. '0deg' 값은 사운드 스테이지 중앙에서 바로 앞을 의미합니다. '90deg'는 오른쪽, '180deg'는 뒤쪽, 그리고 '270deg'(또는 동등하고 편리하게는 '-90deg')는 왼쪽을 의미합니다.

left-side - '270deg'와 동일합니다. 'behind'와 함께 사용할 때는 '270deg'입니다.

far-left - '300deg'와 동일합니다. 'behind'와 함께 사용할 때는 '240deg'입니다.

left - '320deg'와 동일합니다. 'behind'와 함께 사용할 때는 '220deg'입니다.

center-left - '340deg'와 동일합니다. 'behind'와 함께 사용할 때는 '200deg'입니다.

center - '0deg'와 동일합니다. 'behind'와 함께 사용할 때는 '180deg'입니다.

center-right - '20deg'와 동일합니다. 'behind'와 함께 사용할 때는 '160deg'입니다.

right - '40deg'와 동일합니다. 'behind'와 함께 사용할 때는 '140deg'입니다.

far-right - '60deg'와 동일합니다. 'behind'와 함께 사용할 때는 '120deg'입니다.

right-side - '90deg'와 동일합니다. 'behind'와 함께 사용할 때는 '90deg'입니다.

leftwards - 현재 각도에 대해 소리를 왼쪽으로 이동시킵니다. 보다 정확히는 20도를 빼는 것입니다. 연산은 360도 모듈로 수행됩니다. 참고로 'leftwards'는 실제로는 "반시계 방향 회전"이라고 설명하는 것이 더 정확합니다. 왜냐하면 항상 20도를 빼기 때문에, 상속된 azimuth가 이미 청취자 뒤에 있더라도(이 경우 소리가 실제로 오른쪽으로 움직이는 것처럼 보입니다) 그렇기 때문입니다.

rightwards - 현재 각도에 대해 소리를 오른쪽으로 이동시�니다. 보다 정확히는 20도를 더합니다. 연산에 대해서는 'leftwards'를 참고하십시오.

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
