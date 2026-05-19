---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. 공간 오디오는 청각 프레젠테이션을 위한 중요한 스타일 속성입니다. 실제 생활에서 사람들은 방 안의 같은 지점에 모두 서 있지 않듯이 여러 목소리를 구분할 수 있는 자연스러운 방법을 제공합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

공간 오디오는 청각 프레젠테이션을 위한 중요한 스타일 속성입니다. 실제 생활에서 (사람들이 방 안의 같은 지점에 모두 서 있지 않듯이) 여러 목소리를 구분할 수 있는 자연스러운 방법을 제공합니다.

```java
public String Azimuth { get; set; }
```

### 반환 값

azimuth 속성

### Property Value

값은 다음과 같은 의미를 가집니다:

각도 - 위치는 '-360deg'에서 '360deg' 범위의 각도로 설명됩니다. '0deg' 값은 사운드 스테이지 중앙에서 바로 앞을 의미합니다. '90deg'는 오른쪽, '180deg'는 뒤쪽, 그리고 '270deg'(또는 동등하고 편리하게 '-90deg')는 왼쪽을 의미합니다.

left-side - '270deg'와 동일합니다. 'behind'와 함께 사용할 경우, '270deg'입니다.

far-left - '300deg'와 동일합니다. 'behind'와 함께 사용할 경우, '240deg'입니다.

left - '320deg'와 동일합니다. 'behind'와 함께 사용할 경우, '220deg'입니다.

center-left - '340deg'와 동일합니다. 'behind'와 함께 사용할 경우, '200deg'입니다.

center - '0deg'와 동일합니다. 'behind'와 함께 사용할 경우, '180deg'입니다.

center-right - '20deg'와 동일합니다. 'behind'와 함께 사용할 경우, '160deg'입니다.

right - '40deg'와 동일합니다. 'behind'와 함께 사용할 경우, '140deg'입니다.

far-right - '60deg'와 동일합니다. 'behind'와 함께 사용할 경우, '120deg'입니다.

right-side - '90deg'와 동일합니다. 'behind'와 함께 사용할 경우, '90deg'입니다.

leftwards - 현재 각도에 상대적으로 사운드를 왼쪽으로 이동시킵니다. 보다 정확히는 20도를 빼는 것입니다. 연산은 360도 모듈로 수행됩니다. 참고로 'leftwards'는 "turned counter-clockwise,"라고 더 정확히 설명할 수 있는데, 이는 항상 20도를 빼기 때문에, 상속된 azimuth가 이미 청취자 뒤에 있더라도(이 경우 사운드가 실제로 오른쪽으로 이동하는 것처럼 보입니다).

rightwards - 현재 각도에 상대적으로 사운드를 오른쪽으로 이동시킵니다. 보다 정확히는 20도를 더합니다. 연산에 대해서는 'leftwards'를 참고하십시오.

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
