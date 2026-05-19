---
title: "IFile 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.io.IFile 인터페이스. File 객체는 name 속성이 String인 Blob 객체이며, 웹 애플리케이션 내에서 생성자를 통해 생성될 수 있거나 기본 OS 파일 시스템의 파일에서 바이트 시퀀스를 참조합니다."
type: docs

url: /ko/java/com.aspose.html.io/ifile/
---
## IFile interface

File 객체는 name 속성을 가진 Blob 객체이며, 이는 문자열입니다; 웹 애플리케이션 내에서 생성자를 통해 생성될 수 있거나, 기본(OS) 파일 시스템의 파일에서 바이트 시퀀스를 참조합니다.

```java
public interface IFile : IBlob
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) 파일의 마지막 수정 날짜. 가져올 때, 사용자 에이전트가 이 정보를 제공할 수 있다면, 이 메서드는 파일이 마지막으로 수정된 시간을 Unix Epoch 이후 밀리초 수로 나타낸 long long 값을 반환해야 합니다. |
| [getName](../../com.aspose.html.io/ifile/name/) 파일의 이름. 가져올 때, 이 메서드는 파일 이름을 String으로 반환해야 합니다. |

### 또 보기

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
