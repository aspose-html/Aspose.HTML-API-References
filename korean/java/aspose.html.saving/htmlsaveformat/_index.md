---
title: "HTMLSaveFormat 열거형"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.HTMLSaveFormat 열거형. 문서가 저장되는 형식을 지정합니다. HTMLDocument 저장에 대한 자세한 내용은 문서에서 확인할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

문서가 저장되는 형식을 지정합니다. [`HTMLDocument`](../../com.aspose.html/htmldocument/) 저장에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)에서 확인할 수 있습니다.

```java
public enum HTMLSaveFormat
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Original | `0` | 문서는 원래 형식으로 저장됩니다. |
| Markdown | `1` | 문서는 Markdown 형식으로 저장됩니다. |
| MHTML | `2` | 문서는 MHTML 형식으로 저장됩니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // 문서 저장을 위한 출력 경로를 준비합니다
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // HTML 코드를 준비합니다
  var html_code = "<H2>Hello World!</H2>";
   
  // String 변수에서 문서를 초기화합니다
  using (var document = new HTMLDocument(html_code, "."))
  {
    // 문서를 Markdown 파일로 저장합니다
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### 또 보기

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
