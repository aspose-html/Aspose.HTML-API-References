---
title: "Resource.Embed"
second_title: "Aspose.HTML for Java API 참조"
description: "Resource 메서드. 이 리소스를 Base64로 인코딩하여 부모에 포함합니다. 인코딩 결과는 OutputUrl에 기록됩니다"
type: docs

url: /ko/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

이 리소스를 Base64로 인코딩하여 부모에 포함합니다. 인코딩 결과는 [`OutputUrl`](../outputurl/)에 기록됩니다.

```java
public Resource Embed(ResourceHandlingContext context)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 컨텍스트 | ResourceHandlingContext | 리소스 처리 컨텍스트. |

### 반환 값

이 리소스는 호출을 체인할 수 있도록 합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | 결과를 삽입할 위치가 없기 때문에 [`ParentResource`](../../resourcehandlingcontext/parentresource/)가 없을 경우 발생합니다. |

### 또 보기

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
