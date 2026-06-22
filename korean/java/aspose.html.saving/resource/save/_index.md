---
title: "Resource.Save"
second_title: "Java용 Aspose.HTML API 참조"
description: "Resource 메서드. 제공된 스트림에 리소스를 저장합니다."
type: docs

url: /ko/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

제공된 스트림에 리소스를 저장합니다.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 리소스가 저장될 스트림입니다. |
| context | ResourceHandlingContext | 리소스 처리 컨텍스트. |

### 반환 값

이 리소스는 호출을 체인할 수 있도록 합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | `[`OutputUrl`](../outputurl/)`가 `null`인 경우 발생합니다. 리소스를 저장하기 전에 [`OutputUrl`](../outputurl/)를 지정해야 합니다. 그렇지 않으면 이 리소스를 참조하는 리소스에서 올바른 참조를 지정할 수 없습니다. |

### 또 보기

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
