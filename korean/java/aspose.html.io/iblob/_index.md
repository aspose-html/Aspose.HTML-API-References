---
title: "IBlob 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.io.IBlob 인터페이스. Blob 객체는 바이트 시퀀스를 나타내며, size 속성은 바이트 시퀀스의 전체 바이트 수를, type 속성은 바이트 시퀀스의 미디어 유형을 나타내는 소문자 ASCII 인코딩 String을 가집니다."
type: docs

url: /ko/java/com.aspose.html.io/iblob/
---
## IBlob interface

Blob 객체는 바이트 시퀀스를 가리키며, 바이트 시퀀스의 전체 바이트 수인 size 속성과, 바이트 시퀀스의 미디어 유형을 소문자 ASCII 문자열로 나타내는 type 속성을 가집니다.

```java
public interface IBlob
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) 바이트 시퀀스의 크기를 바이트 수로 반환합니다. 가져올 때, 해당 표준을 따르는 사용자 에이전트는 FileReader 또는 FileReaderSync 객체가 읽을 수 있는 전체 바이트 수를 반환해야 하며, Blob에 읽을 바이트가 없을 경우 0을 반환합니다. |
| [getType](../../com.aspose.html.io/iblob/type/) Blob의 미디어 유형을 나타내는 소문자 ASCII 인코딩 String입니다. 가져올 때, 사용자 에이전트는 Blob의 유형을 소문자 ASCII 인코딩 String으로 반환해야 하며, 이는 바이트 시퀀스로 변환했을 때 파싱 가능한 MIME 타입이어야 합니다. 유형을 결정할 수 없을 경우 빈 String(0 바이트)을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | 옵션인 start 매개변수부터 옵션인 end 매개변수 이전까지의 바이트를 포함하고, type 속성은 옵션인 contentType 매개변수의 값으로 설정된 새로운 Blob 객체를 반환합니다. |

### 또 보기

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
