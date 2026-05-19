---
title: "Resource 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.Resource 클래스. 이 클래스는 리소스를 설명하고 이를 처리하기 위한 메서드를 제공합니다."
type: docs

url: /ko/java/com.aspose.html.saving/resource/
---
## Resource class

이 클래스는 리소스를 설명하고 이를 처리하기 위한 메서드를 제공합니다.

```java
public class Resource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) 이 리소스의 [`MimeType`](../../com.aspose.html/mimetype/)을 반환합니다. 리소스를 찾을 수 없는 경우 `null`일 수 있습니다. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) 이 리소스에 대한 원래 참조를 포함하는 문자열을 반환합니다. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) 이 리소스가 위치한 위치를 나타내는 URL을 반환합니다. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) 현재 리소스의 상태를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | 이 리소스를 Base64로 인코딩하여 부모에 포함합니다. 인코딩 결과는 [`OutputUrl`](./outputurl/)에 기록됩니다. |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | 제공된 스트림에 리소스를 저장합니다. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | 처리 후 리소스가 위치할 새 URL을 지정합니다. |

### 또 보기

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
