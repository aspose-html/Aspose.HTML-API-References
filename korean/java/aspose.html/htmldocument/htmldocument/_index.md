---
title: "HTMLDocument"
second_title: "Aspose.HTML for Java API 참조"
description: "HTMLDocument 생성자. HTMLDocument 생성자는 브라우저에 로드된 웹 페이지이며 페이지 내용에 대한 진입점 역할을 하는 새로운 HTML Document 객체를 생성합니다."
type: docs

url: /ko/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

HTMLDocument 생성자는 브라우저에 로드된 웹 페이지이며 페이지 콘텐츠에 대한 진입점 역할을 하는 새로운 HTML Document 객체를 생성합니다.

```java
public HTMLDocument()
```

## 비고

참고: 문서는 base-url 속성에 대해 기본값으로 'about:blank'가 설정된 상태로 생성됩니다.

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

문서 객체가 생성된 후에는 나중에 HTML 요소들로 채울 수 있습니다. 다음 코드 스니펫은 기본 HTMLDocument() 생성자를 사용하여 빈 HTML 문서를 만들고 파일에 저장하는 방법을 보여줍니다.

```java
import (var document = new HTMLDocument())
{
	// 여기서 문서를 작업하세요
	...	
	
	// 문서를 파일에 저장합니다
	document.Save("document.html");
}
```

### 또 보기

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

HTMLDocument 생성자는 브라우저에 로드된 웹 페이지이며 페이지 콘텐츠에 대한 진입점 역할을 하는 새로운 HTML Document 객체를 생성합니다.

```java
public HTMLDocument(Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

## 비고

참고: 문서는 base-url 속성에 대해 기본값으로 'about:blank'가 설정된 상태로 생성됩니다.

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

다음 예제는 구성 객체를 사용하여 스크립트를 비활성화하는 방법을 보여줍니다:

```java
// Prepare HTML code and save it to a file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration의 인스턴스를 생성합니다
import (var configuration = new Configuration())
{
	// 'scripts'를 신뢰되지 않는 리소스로 표시합니다
	configuration.Security |= Sandbox.Scripts;

	// 지정된 구성으로 HTML 문서를 초기화합니다
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML을 PDF로 변환
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### 또 보기

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

URL에서 HTML 문서를 로드합니다.

참고: 현재 접근할 수 없는 잘못된 URL을 전달하면, 라이브러리는 선택한 리소스를 찾을 수 없음을 알리기 위해 특수 코드 ‘NetworkError’를 가진 [`DOMException`](../../../com.aspose.html.dom/domexception/)을 발생시킵니다.

```java
public HTMLDocument(Url url)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 열어야 할 HTML 문서 URL. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

‘https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html’ 웹 페이지에서 문서를 로드합니다:

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// 문서 내용을 출력 스트림에 씁니다
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### 또 보기

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

지정된 환경 구성 설정과 함께 URL에서 HTML 문서를 로드합니다.

참고: 현재 접근할 수 없는 잘못된 URL을 전달하면, 라이브러리는 선택한 리소스를 찾을 수 없음을 알리기 위해 특수 코드 ‘NetworkError’를 가진 [DOMException](T:com.aspose.html.dom.DOMException) 을 발생시킵니다.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 열어야 할 HTML 문서 URL. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Prepare HTML code and save it to a file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration의 인스턴스를 생성합니다
import (var configuration = new Configuration())
{
	// 'scripts'를 신뢰되지 않는 리소스로 표시합니다
	configuration.Security |= Sandbox.Scripts;

	// 지정된 구성으로 HTML 문서를 초기화합니다
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML을 PDF로 변환
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### 또 보기

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

주소에서 HTML 문서를 로드합니다.

참고: 현재 접근할 수 없는 잘못된 URL을 전달하면, 라이브러리는 선택한 리소스를 찾을 수 없음을 알리기 위해 특수 코드 ‘NetworkError’를 가진 [`DOMException`](../../../com.aspose.html.dom/domexception/)을 발생시킵니다.

```java
public HTMLDocument(String address)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 주소 | String | 열어야 할 HTML 문서 주소. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

주소에서 HTML 문서를 초기화합니다.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### 또 보기

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

지정된 환경 구성 설정과 함께 주소에서 HTML 문서를 로드합니다.

참고: 현재 접근할 수 없는 잘못된 URL을 전달하면, 라이브러리는 선택한 리소스를 찾을 수 없음을 알리기 위해 특수 코드 ‘NetworkError’를 가진 [`DOMException`](../../../com.aspose.html.dom/domexception/)을 발생시킵니다.

```java
public HTMLDocument(String address, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 주소 | String | 열어야 할 HTML 문서 주소. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// Configuration의 인스턴스를 생성합니다
import (var configuration = new Configuration())
{
	// 'scripts'를 신뢰되지 않는 리소스로 표시합니다
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### 또 보기

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

지정된 base-uri와 함께 문자열 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(String content, String baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서를 로드할 문자열 내용. |
| baseUri | String | 문서의 기본 URI. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// HTML 코드를 준비합니다
var html_code = "<p>Hello World!</p>";

// String 변수에서 문서를 초기화합니다
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 또 보기

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

지정된 base-uri 및 환경 구성 설정과 함께 문자열 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서를 로드할 문자열 내용. |
| baseUri | String | 문서의 기본 URI. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// HTML 코드를 준비합니다
var html_code = "<p>Hello World!</p>";

// String 변수에서 문서를 초기화합니다
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 또 보기

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

지정된 base-uri와 함께 문자열 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(String content, Url baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서를 로드할 문자열 내용. |
| baseUri | Url | 문서의 기본 URI. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// HTML 코드를 준비합니다
var html_code = "<p>Hello World!</p>";

// String 변수에서 문서를 초기화합니다
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 또 보기

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

지정된 base-uri 및 환경 구성 설정과 함께 문자열 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서를 로드할 문자열 내용. |
| baseUri | Url | 문서의 기본 URI. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// HTML 코드를 준비합니다
var html_code = "<p>Hello World!</p>";

// String 변수에서 문서를 초기화합니다
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 또 보기

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

지정된 base-uri를 사용하여 상대 리소스 경로를 해결하는 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(Stream content, String baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | Stream | 문서를 로드할 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 내용. |
| baseUri | String | 문서의 기본 URI. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// 메모리 스트림 객체를 생성합니다
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML 코드를 메모리 객체에 씁니다
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 변수에서 문서를 초기화합니다
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 또 보기

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

지정된 base-uri 및 환경 구성 설정과 함께 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | Stream | 문서를 로드할 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 내용. |
| baseUri | String | 문서의 기본 URI. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// 메모리 스트림 객체를 생성합니다
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML 코드를 메모리 객체에 씁니다
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 변수에서 문서를 초기화합니다
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 또 보기

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

지정된 base-uri를 사용하여 상대 리소스 경로를 해결하는 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | Stream | 문서를 로드할 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 내용. |
| baseUri | Url | 문서의 기본 URI. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// 메모리 스트림 객체를 생성합니다
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML 코드를 메모리 객체에 씁니다
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 변수에서 문서를 초기화합니다
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 또 보기

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

지정된 base-uri 및 환경 구성 설정과 함께 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 콘텐츠에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | Stream | 문서를 로드할 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 내용. |
| baseUri | Url | 문서의 기본 URI. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | base-uri 매개변수가 null이면 예외가 발생합니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 예제

```java
// 메모리 스트림 객체를 생성합니다
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML 코드를 메모리 객체에 씁니다
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 변수에서 문서를 초기화합니다
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 또 보기

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

`[`RequestMessage`](../../../com.aspose.html.net/requestmessage/)` 객체에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(RequestMessage request)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| request | RequestMessage | 문서 내용을 포함하는 [`body`](../../../com.aspose.html.net/requestmessage/content/)를 포함하는 요청 메시지입니다. |

## 비고

정의에 따르면, 메시지 핸들러는 Web 요청을 받아 Web 응답을 반환하는 클래스입니다. 다시 말해, 메시지 핸들러는 입력 중에 Web 서비스 요청을 처리하거나 출력 중에 응답을 처리하는 데 사용됩니다.

이 생성자를 사용하는 방법에 대한 더 많은 시나리오를 보려면 [docs site](https://docs.aspose.com/html/net/message-handlers/)을 방문해 주세요.

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

[RequestMessage](T:com.aspose.html.net.RequestMessage) 객체에서 HTML 문서를 생성합니다.

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| request | RequestMessage | 문서 내용을 포함하는 [body](P:com.aspose.html.net.RequestMessage.Content)를 포함하는 요청 메시지입니다. |
| 구성 | 구성 | 스크립트 정책, 사용자 정의 스타일시트 등과 같은 환경 구성 |

## 비고

정의에 따르면, 메시지 핸들러는 Web 요청을 받아 Web 응답을 반환하는 클래스입니다. 다시 말해, 메시지 핸들러는 입력 중에 Web 서비스 요청을 처리하거나 출력 중에 응답을 처리하는 데 사용됩니다.

이 생성자를 사용하는 방법에 대한 더 많은 시나리오를 보려면 [docs site](https://docs.aspose.com/html/net/message-handlers/)을 방문해 주세요.

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
