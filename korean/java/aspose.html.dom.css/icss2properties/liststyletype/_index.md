---
title: "ICSS2Properties.ListStyleType"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties property. 이 속성은 list-style-image가 none 값을 갖거나 URI가 가리키는 이미지를 표시할 수 없을 때 목록 항목 마커의 모양을 지정합니다. 값 none은 마커가 없음을 의미하고, 그 외에는 마커 글리프, 번호 매기기 시스템, 알파벳 시스템의 세 가지 유형이 있습니다. 참고: 번호 매긴 목록은 목록을 더 쉽게 탐색할 수 있게 하여 문서 접근성을 향상시킵니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/liststyletype/
---
## ICSS2Properties.ListStyleType property

이 속성은 ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) 가 'none' 값을 갖거나 URI가 가리키는 이미지를 표시할 수 없을 때 목록 항목 마커의 모양을 지정합니다. 'none' 값은 마커가 없음을 의미하고, 그 외에는 마커가 세 가지 유형, 즉 글리프, 번호 매기기 시스템, 알파벳 시스템으로 구분됩니다. 참고: 번호 매긴 목록은 목록을 더 쉽게 탐색할 수 있게 하여 문서 접근성을 향상시킵니다.

글리프는 disc, circle, square 로 지정됩니다. 정확한 렌더링은 사용자 에이전트에 따라 달라집니다.

번호 매기기 시스템은 다음과 같이 지정됩니다:

decimal - 10진수 숫자, 1부터 시작합니다. decimal-leading-zero - 앞에 0을 채워 넣은 10진수 숫자(예: 01, 02, 03, ..., 98, 99). lower-roman - 소문자 로마 숫자(i, ii, iii, iv, v 등). upper-roman - 대문자 로마 숫자(I, II, III, IV, V 등). hebrew - 전통적인 히브리어 번호 매기기. georgian - 전통적인 조지아어 번호 매기기(an, ban, gan, ..., he, tan, in, in-an, ...). armenian - 전통적인 아르메니아어 번호 매기기. cjk-ideographic - 일반적인 한자 표기 숫자. hiragana - a, i, u, e, o, ka, ki, ... katakana - A, I, U, E, O, KA, KI, ... hiragana-iroha - i, ro, ha, ni, ho, he, to, ... katakana-iroha - I, RO, HA, NI, HO, HE, TO, ...

```java
public String ListStyleType { get; set; }
```

### 반환 값

list-style-type 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
