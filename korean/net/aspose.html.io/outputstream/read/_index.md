---
title: OutputStream.Read
second_title: .NET API 참조용 Aspose.HTML
description: OutputStream 방법. 래핑된 출력 stream 에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내의 위치를 이동합니다.
type: docs
weight: 100
url: /ko/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

래핑된 출력 stream 에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내의 위치를 이동합니다.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | Byte[] | 바이트 배열입니다. 이 메서드가 반환되면 버퍼에는 offset과 (offset + count - 1) 사이의 값이 래핑된 출력 스트림에서 읽은 바이트로 대체된 specified 바이트 배열이 포함됩니다. |
| offset | Int32 | 래핑된 출력 스트림에서 데이터 read 를 저장하기 시작할 버퍼의 0기반 바이트 오프셋입니다. |
| count | Int32 | 래핑된 출력 스트림에서 읽을 최대 바이트 수입니다. |

### 반환 값

버퍼로 읽은 총 바이트 수입니다. 이것은 많은 바이트가 현재 사용 가능하지 않은 경우 요청된 바이트의 number 보다 작거나 스트림 끝에 도달한 경우 영(0) 일 수 있습니다.

### 또한보십시오

* class [OutputStream](../)
* 네임스페이스 [Aspose.Html.IO](../../outputstream/)
* 집회 [Aspose.HTML](../../../)


