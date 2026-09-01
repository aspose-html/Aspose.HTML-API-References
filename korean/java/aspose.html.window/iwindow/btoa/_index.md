---
title: "IWindow.Btoa"
second_title: "Java용 Aspose.HTML API 참조"
description: "IWindow 메서드. 입력 데이터를 Unicode String 형태로 받아, 범위 U0000~U00FF의 문자만 포함하고 각각 0x00~0xFF 값을 갖는 이진 바이트를 나타내며, 이를 base64 표현으로 변환하여 반환합니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

입력 데이터를 U+0000부터 U+00FF 범위의 문자만 포함하는 Unicode 문자열 형태로 받아, 각 문자가 0x00~0xFF 값을 갖는 바이너리 바이트를 나타내며, 이를 base64 표현으로 변환하여 반환합니다.

```java
public String Btoa(String data)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 데이터 | String | 범위 U+0000에서 U+00FF 사이의 문자만 포함하는 Unicode String입니다. |

### 반환 값

base64 문자열입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 입력 문자열에 범위를 벗어난 문자가 포함된 경우 "InvalidCharacterError" DOMException 예외를 발생시킵니다. |

### 또 보기

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
