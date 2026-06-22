---
title: "ICSS2Properties.PauseAfter"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이러한 속성은 요소의 내용을 말하기 전이나 후에 적용되는 일시 정지를 지정합니다. 값은 다음과 같은 의미를 가집니다"
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/pauseafter/
---
## ICSS2Properties.PauseAfter property

이러한 속성은 요소의 내용을 말하기 전(또는 후)에 적용되는 일시 정지를 지정합니다. 값은 다음과 같은 의미를 가집니다:

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - 일시 정지를 절대 시간 단위(초와 밀리초)로 표현합니다.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate) 속성 값의 역값을 나타냅니다. 예를 들어, speech-rate가 분당 120단어(즉, 한 단어에 0.5초 또는 500ms)라면, 100%의 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 는 500ms의 일시 정지를 의미하고, 20%의 ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) 는 100ms를 의미합니다.

```java
public String PauseAfter { get; set; }
```

### 반환 값

pause-after 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
