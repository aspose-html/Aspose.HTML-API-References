---
title: Interface IBlob
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.IO.IBlob 상호 작용. Blob 객체는 바이트 시퀀스를 참조하며 바이트 시퀀스의 총 바이트 수인 크기 속성과 바이트 시퀀스의 미디어 유형을 나타내는 소문자 ASCII 인코딩 문자열인 유형 속성을 가집니다. .
type: docs
weight: 3700
url: /ko/net/aspose.html.io/iblob/
---
## IBlob interface

Blob 객체는 바이트 시퀀스를 참조하며 바이트 시퀀스의 총 바이트 수인 크기 속성과 바이트 시퀀스의 미디어 유형을 나타내는 소문자 ASCII 인코딩 문자열인 유형 속성을 가집니다. .

```csharp
public interface IBlob
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | 바이트 시퀀스의 크기를 바이트 수로 반환합니다. 가져올 때 준수하는 사용자 에이전트는 FileReader 또는 FileReaderSync 개체에서 읽을 수 있는 총 바이트 수를 반환하거나 Blob에 읽을 바이트가 없는 경우 0을 반환해야 합니다. . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | Blob의 미디어 유형을 나타내는 소문자의 ASCII 인코딩된 문자열입니다. 유형을 결정할 수 없는 경우 구문 분석 가능한 MIME 유형, 또는 빈 문자열(0바이트)입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | 선택적인 시작 매개변수에서 선택적인 종료 매개변수인 까지의 바이트 범위와 선택적인 contentType 매개변수의 값인 type 속성을 가진 새 Blob 객체를 반환합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.IO](../../aspose.html.io/)
* 집회 [Aspose.HTML](../../)


