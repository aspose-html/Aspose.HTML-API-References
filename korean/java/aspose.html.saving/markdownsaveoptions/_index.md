---
title: "MarkdownSaveOptions 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.saving.MarkdownSaveOptions 클래스. Markdown 저장 옵션을 나타냅니다. 예를 들어 미리 정의된 GitLab Flavored Markdown 호환 옵션을 사용하여 markdown 서식 스타일을 설정하고 리소스 처리를 구성할 수 있습니다. 자세한 내용은 기사에서 확인하세요."
type: docs

url: /ko/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown 저장 옵션을 나타냅니다. 예를 들어, Markdown 서식 스타일을 설정하고, 미리 정의된 GitLab Flavored Markdown 호환 옵션을 사용하며, 리소스 처리를 구성할 수 있습니다. 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options)를 참고하십시오.

```java
public class MarkdownSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | `MarkdownSaveOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) 기본 Markdown 문서와 호환되는 옵션 집합을 반환합니다. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) GitLab Flavored Markdown과 호환되는 옵션 집합을 반환합니다. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
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
	 // 변환된 파일 저장을 위한 경로를 준비합니다 
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // HTML 코드를 준비하고 파일에 저장합니다.
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // SaveOptions의 인스턴스를 생성하고 규칙을 설정합니다: 
      // - <a> 및 <p> 요소만 Markdown으로 변환됩니다.
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // ConvertHTML 메서드를 호출하여 HTML을 Markdown으로 변환합니다.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### 또 보기

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
