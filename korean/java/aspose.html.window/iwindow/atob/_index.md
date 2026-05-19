---
title: "IWindow.Atob"
second_title: "Aspose.HTML for Java API 참조"
description: "IWindow 메서드. base64 인코딩된 바이너리 데이터를 포함하는 유니코드 문자열 형태의 입력 데이터를 받아 이를 디코드하고, 해당 바이너리 데이터에 대응하는 0x00에서 0xFF 값을 갖는 바이너리 바이트를 각각 나타내는 U0000에서 U00FF 범위의 문자들로 구성된 문자열을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

입력 데이터를 base64로 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 형태로 받아 디코딩하고, 각 문자가 U+0000부터 U+00FF까지의 범위에 해당하며 각각 0x00부터 0xFF까지의 바이너리 바이트 값을 나타내는 문자열을 반환합니다.

```java
public String Atob(String data)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | String | base64 인코딩된 바이너리 데이터를 포함하는 유니코드 문자열 |

### 반환 값

U+0000에서 U+00FF 범위의 문자들로 구성된 문자열

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 입력 문자열이 유효한 base64 데이터가 아닌 경우 "InvalidCharacterError" DOMException을 발생시킵니다. |

### 또 보기

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
