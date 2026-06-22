---
title: "HTMLDocument.Save"
second_title: "Java용 Aspose.HTML API 참조"
description: "HTMLDocument method. 문서를 지정된 url의 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 output_file_name_files 형태의 이름을 가진 인접 폴더에 저장됩니다."
type: docs

url: /ko/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

문서를 url로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + \"_files\" 로 구성됩니다.

```java
public void Save(Url url)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 [`URL`](../../url/) |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(Url) 메서드

HTML 문서를 저장하려면 전체 Url 경로—'outputFilePath'—를 지정해야 합니다. Url(url) 생성자는 지정된 url을 사용하여 [`Url`](../../url/) 클래스의 인스턴스를 생성합니다. 그런 다음 해당 인스턴스를 Save(Url) 메서드에 전달해야 합니다. 문서는 지정된 url의 로컬 파일에 저장됩니다. 이 문서에서 사용된 모든 리소스는 output_file_name + "_files" 형태의 이름을 가진 인접 폴더에 저장됩니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 또 보기

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

문서를 지정된 경로의 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접한 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 구성됩니다.

```java
public void Save(String path)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 파일 시스템 경로. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(String) 메서드는 매개변수로 출력 파일에 대한 로컬 파일 시스템 경로를 받아 해당 경로에 지정된 로컬 파일에 HTML 문서를 저장합니다. 문서에서 사용된 모든 리소스는 인접 폴더에 저장됩니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 또 보기

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

문서를 path로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + \"_files\" 로 구성됩니다.

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 파일 경로. |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(String, HTMLSaveFormat) 메서드

Save(String, HTMLSaveFormat) 메서드는 매개변수로 출력 파일에 대한 로컬 파일 시스템 경로와 saveFormat을 받습니다. [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 열거형은 문서가 저장되는 형식을 지정하며, HTML, MHTML 및 MD 형식이 가능합니다. 이 메서드는 지정된 형식으로 HTML 문서를 경로로 지정된 로컬 파일에 저장합니다. 문서에 사용된 모든 리소스는 인접 폴더에 저장됩니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary=\"boundary\";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang=\"en\" xmlns:xml=\"http://www.w3.org/XML/1998/package\"&gt;&lt;head&gt;

&lt;meta charset=\"UTF-8\"&gt;

&lt;link rel=\"stylesheet\" href=\"main.css\"&gt;

&lt;title&gt;제목&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=\"uniqueIdentifier\"&gt;ID가 있는 컨테이너 - 식별자&lt;/div&gt;

&lt;div class=\"custom-class\"&gt;CSS 클래스 컨테이너에 의해 사용자 정의됨&lt;/div&gt;

&lt;div&gt;

&lt;p class=\"pStyle\"&gt;첫 번째 pStyle 클래스 단락에 스타일 적용&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;두 번째 pStyle 클래스 단락에 스타일 적용&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;세 번째 pStyle 클래스 단락에 스타일 적용&lt;/p&gt;

&lt;span class=\"pStyle\"&gt;pStyle에 의해 스타일이 적용된 Span&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns=\"http://www.w3.org/1998/Math/MathML\"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id=\"smart class\"&gt;

&lt;p id=\"p1\" class=\"ddd kkk\"&gt;클래스 이름 =ddd kkk= 로 스타일이 지정된 단락&lt;/p&gt;

&lt;p id=\"p2\" class=\"ddd fff\"&gt;클래스 이름 =ddd fff= 로 스타일이 지정된 단락&lt;/p&gt;

&lt;p id=\"p3\" class=\"kkk fff\"&gt;클래스 이름 =kkk fff= 로 스타일이 지정된 단락&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;DIV 요소에서 인사합니다&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### 또 보기

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

문서를 url로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + \"_files\" 로 구성됩니다.

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 URL. |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(Url, HTMLSaveFormat) 메서드

HTML 문서를 저장하려면 전체 Url 경로 - 'outputFilePath' 를 지정해야 합니다. Url(url) 생성자는 지정된 url을 사용하여 [`Url`](../../url/) 클래스의 인스턴스를 생성합니다. [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 열거형은 문서가 저장되는 형식을 지정하며, HTML, MHTML 및 MD 형식이 될 수 있습니다. 그런 다음 Save(url, saveFormat) 메서드에 매개변수를 전달해야 합니다. 문서는 지정된 형식으로 url이 지정한 로컬 파일에 저장됩니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 또 보기

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

문서를 지정된 경로의 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접한 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 구성됩니다.

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 객체는 리소스 처리 프로세스 관리를 위해 사용됩니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(String, HTMLSaveOptions) 메서드

Save(String, HTMLSaveOptions) 메서드는 출력 파일에 대한 로컬 파일 시스템 경로와 [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) 클래스의 인스턴스를 매개변수로 받아, 리소스가 포함된 HTML 문서를 해당 경로의 로컬 파일에 저장합니다. HTMLSaveOptions() 생성자는 리소스 처리를 구성하는 데 사용되는 [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 속성을 가진 저장 옵션 인스턴스를 생성합니다. 문서에 사용된 모든 리소스는 인접 폴더에 저장됩니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// 옵션 클래스 인스턴스 정의
	var options = new HTMLSaveOptions();
	// 페이지 처리 제한
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 또 보기

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

문서를 url로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 다음과 같이 구성됩니다: output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 [`URL`](../../url/) |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 객체는 리소스 처리 프로세스 관리를 위해 사용됩니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(Url, HTMLSaveOptions) 메서드

HTML 문서를 저장하려면 전체 Url 경로를 지정해야 합니다. Url(url) 생성자는 지정된 url을 사용하여 [`Url`](../../url/) 클래스의 인스턴스를 생성합니다. HTMLSaveOptions() 생성자는 리소스 처리를 구성하는 데 사용되는 ResourceHandlingOptions 속성을 가진 [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) 클래스의 인스턴스를 생성합니다. Save(url, saveOptions) 메서드는 매개변수를 받아 리소스가 포함된 HTML 문서를 url이 지정한 로컬 파일에 저장합니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// 옵션 클래스 인스턴스 정의
	var options = new HTMLSaveOptions();
	// 페이지 처리 제한
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 또 보기

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | HTML 저장 옵션. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

문서를 지정된 경로의 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접한 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 구성됩니다.

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) 을 참조하십시오. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(String, MarkdownSaveOptions) 메서드

문서를 저장하려면 출력 파일에 대한 로컬 파일 시스템 경로를 지정해야 합니다. MarkdownSaveOptions() 생성자는 [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 클래스의 인스턴스를 생성하며, 다양한 속성을 제공합니다. 예를 들어, 마크다운 포맷 스타일을 설정하고, 미리 정의된 GitLab Flavored Markdown 호환 옵션을 사용하며, 리소스 처리를 구성할 수 있습니다. Save(path, saveOptions) 메서드는 출력 파일의 로컬 파일 시스템 경로와 옵션 인스턴스를 매개변수로 받아, HTML을 리소스가 포함된 마크다운 문서로 변환하여 지정된 경로의 로컬 파일에 저장합니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// 옵션 클래스 인스턴스 정의
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 또 보기

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

문서를 url로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 다음과 같이 구성됩니다: output_file_name + \"_files\".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 [`URL`](../../url/) |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [문서](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) 를 참조하십시오. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(Url, MarkdownSaveOptions) 메서드

문서를 저장하려면 전체 Url 경로를 지정해야 합니다. Url(url) 생성자는 지정된 url을 사용하여 [`Url`](../../url/) 클래스의 인스턴스를 생성합니다. MarkdownSaveOptions() 생성자는 다양한 속성을 가진 [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) 클래스의 인스턴스를 생성합니다. 예를 들어, Markdown 포맷 스타일을 설정하고, 미리 정의된 GitLab Flavored Markdown 호환 옵션을 사용하며, 리소스 처리를 구성할 수 있습니다. Save(url, saveOptions) 메서드는 url과 저장 옵션 인스턴스를 매개변수로 받아 리소스가 포함된 문서를 url이 지정한 로컬 파일에 저장합니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// 옵션 클래스 인스턴스 정의
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 또 보기

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Markdown 저장 옵션. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

문서를 지정된 경로의 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접한 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 구성됩니다.

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [문서](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) 를 참조하십시오. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(String, MHTMLSaveOptions) 메서드

문서를 저장하려면 출력 파일에 대한 로컬 파일 시스템 경로를 지정해야 합니다. MHTMLSaveOptions() 생성자는 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 클래스의 인스턴스를 초기화하며, 이 클래스는 리소스 처리 구성을 위해 사용되는 ResourceHandlingOptions 속성을 가지고 있습니다. Save(path, saveOptions) 메서드는 로컬 파일 시스템 경로와 저장 옵션 인스턴스를 매개변수로 받아, HTML을 MHTML 문서로 변환하여 지정된 경로의 로컬 파일에 저장합니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// 옵션 클래스 인스턴스 정의
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 또 보기

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

문서를 url로 지정된 로컬 파일에 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 다음과 같이 구성됩니다: output_file_name + \"_files\".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 URL. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [문서](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) 를 참조하십시오. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

## 비고

HTML 저장

대부분의 작업은 문서를 저장해야 합니다. 기존 파일을 로드하거나 처음부터 HTML 문서를 만들면 HTMLDocument.Save() 메서드 중 하나를 사용해 변경 사항을 저장할 수 있습니다. 이 메서드들은 경로, URL 또는 출력 스토리지를 지정하여 HTML을 로컬 파일에 저장할 수 있게 합니다. 저장에 대해 자세히 알아보려면 [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)을 참조하십시오.

Save(Url, MHTMLSaveOptions) 메서드

문서를 저장하려면 전체 Url 경로를 지정해야 합니다. Url(url) 생성자는 지정된 url을 사용하여 [`Url`](../../url/) 클래스의 인스턴스를 생성합니다. MHTMLSaveOptions() 생성자는 [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) 클래스의 인스턴스를 초기화하며, 이 클래스는 리소스 처리 구성을 위해 사용되는 ResourceHandlingOptions 속성을 가지고 있습니다. Save(url, saveOptions) 메서드는 url과 옵션을 매개변수로 받아, HTML을 MHTML 문서로 변환하여 url로 지정된 로컬 파일에 저장합니다.

소스 코드

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// 옵션 클래스 인스턴스 정의
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### 또 보기

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | MHTML 저장 옵션. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
