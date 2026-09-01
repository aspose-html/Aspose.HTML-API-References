---
title: "IWindowTimers 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.window.IWindowTimers 인터페이스. 작성자가 타이머 기반 콜백을 예약할 수 있도록 합니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

작성자가 타이머 기반 콜백을 예약하도록 허용합니다.

```java
public interface IWindowTimers
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [clearInterval](../../com.aspose.html.window/iwindowtimers/clearinterval/)(int) | handle로 식별된 setInterval()로 설정된 타임아웃을 취소합니다. |
| [clearTimeout](../../com.aspose.html.window/iwindowtimers/cleartimeout/)(int) | handle로 식별된 setTimeout()으로 설정된 타임아웃을 취소합니다. |
| [setInterval](../../com.aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | timeout 밀리초마다 핸들러를 실행하도록 타임아웃을 예약합니다. 모든 인수는 핸들러에 그대로 전달됩니다. |
| [setTimeout](../../com.aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | timeout 밀리초 후에 핸들러를 실행하도록 타임아웃을 예약합니다. 모든 인수는 핸들러에 그대로 전달됩니다. |

### 또 보기

* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
