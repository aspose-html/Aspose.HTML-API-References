---
title: "MHTMLSaveOptions 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.saving.MHTMLSaveOptions 클래스. MHTML 저장 옵션을 나타냅니다. 특정 속성을 할당하여 최대 처리 깊이 등과 같은 리소스 처리를 관리할 수 있습니다. 자세한 내용은 문서 기사에서 확인하세요."
type: docs

url: /ko/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

MHTML 저장 옵션을 나타냅니다. 특정 속성을 할당하여 최대 처리 깊이 등과 같은 리소스 처리를 관리할 수 있습니다. 자세한 내용은 문서의 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options)를 참조하십시오.

```java
public class MHTMLSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) 리소스 처리를 구성하는 데 사용되는 [`ResourceHandlingOptions`](../resourcehandlingoptions/) 객체를 가져옵니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 찾을 수 있습니다.

## 예제

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // 다른 파일에 대한 링크가 포함된 HTML 코드를 준비하고 이를 'document.html' 파일로 저장합니다.
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // HTML 코드를 준비하고 이를 'document2.html' 파일로 저장합니다.
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // 리소스 연결 깊이 값을 1로 변경하여 직접 연결된 리소스를 가진 문서를 변환합니다.
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML을 MHTML로 변환
      Converter.ConvertHTML("document.html", options, savePath);  
```

### 또 보기

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
