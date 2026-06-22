---
title: "IWindow.Atob"
second_title: "Java용 Aspose.HTML API 참조"
description: "IWindow 메서드. 입력 데이터를 base64 인코딩된 이진 데이터를 포함하는 Unicode String 형태로 받아 디코딩하고, 해당 이진 데이터에 대응하는 각각 0x00~0xFF 값을 갖는 U0000~U00FF 범위의 문자로 구성된 문자열을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

입력 데이터를 base64로 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 형태로 받아 디코딩하고, 해당 바이너리 데이터에 대응하는 각 바이트 값을 0x00~0xFF로 나타내는 U+0000부터 U+00FF 범위의 문자들로 구성된 문자열을 반환합니다.

```java
public String Atob(String data)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 데이터 | String | base64 인코딩된 이진 데이터를 포함하는 Unicode String |

### 반환 값

U+0000에서 U+00FF 범위의 문자로 구성된 문자열

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 입력 문자열이 유효한 base64 데이터가 아닌 경우 "InvalidCharacterError" DOMException을 발생시킵니다. |

### 또 보기

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
