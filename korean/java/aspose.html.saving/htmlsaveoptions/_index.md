---
title: "HTMLSaveOptions 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.saving.HTMLSaveOptions 클래스. HTML 저장 옵션을 나타냅니다. 특정 속성을 할당하여 최대 처리 깊이 등과 같은 리소스 처리를 관리할 수 있습니다. 자세한 내용은 문서 기사에서 확인하십시오."
type: docs

url: /ko/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

HTML 저장 옵션을 나타냅니다. 특정 속성을 할당하여 최대 처리 깊이와 같은 리소스 처리 등을 관리할 수 있습니다. 자세한 내용은 문서의 [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)를 참고하십시오.

```java
public class HTMLSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 리소스 처리를 구성하는 데 사용되는 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 객체를 가져옵니다. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | 출력 문서 유형이 자동으로 선택됩니다. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | 문서는 HTML 형식으로 저장됩니다. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | 문서는 XHTML 형식으로 저장됩니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // HTML 문서에 대한 출력 경로를 준비합니다 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // 링크된 문서가 포함된 간단한 HTML 파일을 준비합니다
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // 간단한 링크된 HTML 파일을 준비합니다
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // "save-with-linked-file.html"을 메모리로 로드합니다
      using (var document = new HTMLDocument(documentPath))
      {
        // 저장 옵션 인스턴스를 생성합니다
        var options = new HTMLSaveOptions();

        // The value '0'인 다음 줄은 이 인스턴스를 저장하는 동안 다른 모든 연결된 HTML 파일을 차단합니다.
        // If you remove this line or change value to the '1', the 'linked.html' file will be saved as well to the output folder
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // 저장 옵션을 사용하여 문서를 저장합니다.
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### 또 보기

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
