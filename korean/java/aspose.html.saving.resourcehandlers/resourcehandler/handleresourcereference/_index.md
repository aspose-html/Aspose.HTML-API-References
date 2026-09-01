---
title: "ResourceHandler.HandleResourceReference"
second_title: "Java용 Aspose.HTML API 참조"
description: "ResourceHandler 메서드. 이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리 중인 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리되는 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resource | Resource | 처리될 [`Resource`](../../../com.aspose.html.saving/resource/)입니다. |
| context | ResourceHandlingContext | 리소스 처리 컨텍스트. |

### 반환 값

현재 처리 중인 리소스에 대한 참조를 나타내며 상위 리소스에 기록될 문자열입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | `[`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/)`가 `null`이고 [`Status`](../../../com.aspose.html.saving/resource/status/)가 Saved인 경우 발생합니다. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/)를 저장된 리소스에 지정해야 하며, 그렇지 않으면 이 리소스를 참조하는 리소스에서 올바른 참조를 지정할 수 없습니다. |

### 또 보기

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
