---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML for Java API 참조"
description: "Converter 메서드. 입력 스트림으로 제공된 MD 마크다운 소스를 HTML로 변환합니다. 결과는 출력 파일 경로를 통해 저장할 수 있는 HTMLDocument입니다."
type: docs

url: /ko/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

입력 스트림으로 제공된 MD(마크다운) 소스를 HTML로 변환합니다. 결과는 출력 파일 경로를 통해 저장할 수 있는 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MD(마크다운) 변환 입력 데이터 스트림. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |

### 반환 값

출력 파일 경로를 통해 저장할 수 있는 변환 결과인 새로운 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)가 생성되었습니다.

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // 스트림으로 소스 파일 열기
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 변환 프로세스 시작
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // 변환 결과 저장
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

입력 스트림으로 제공된 MD(마크다운) 소스를 HTML로 변환합니다. 결과는 출력 파일 경로를 통해 저장할 수 있는 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MD(마크다운) 변환 입력 데이터 스트림. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |

### 반환 값

출력 파일 경로를 통해 저장할 수 있는 변환 결과인 새로운 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)가 생성되었습니다.

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 스트림으로 소스 파일 열기
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 기본 구성을 사용하여 변환 프로세스 시작
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // 변환 결과 저장
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

입력 스트림으로 제공된 MD (markdown) 소스를 html로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MD(마크다운) 변환 입력 데이터 스트림. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| outputPath | String | 출력 변환 결과로서 전체 HTML 파일 경로. |

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 스트림으로 소스 파일 열기
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 변환 프로세스 시작
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

입력 스트림으로 제공된 MD (markdown) 소스를 html로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MD(마크다운) 변환 입력 데이터 스트림. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| outputPath | String | 출력 변환 결과로서 전체 HTML 파일 경로. |

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 스트림으로 소스 파일 열기
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 기본 구성을 사용하여 변환 프로세스 시작
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

전체 파일 경로로 제공된 MD(마크다운) 소스를 HTML로 변환합니다. 결과는 출력 파일 경로를 통해 저장할 수 있는 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MD(마크다운) 소스 전체 파일 경로. |

### 반환 값

출력 파일 경로를 통해 저장할 수 있는 변환 결과인 새로운 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)가 생성되었습니다.

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 변환 프로세스 시작
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // 변환 결과를 로컬 파일로 저장
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

전체 파일 경로로 제공된 MD(마크다운) 소스를 HTML로 변환합니다. 결과는 출력 파일 경로를 통해 저장할 수 있는 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MD(마크다운) 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |

### 반환 값

출력 파일 경로를 통해 저장할 수 있는 변환 결과인 새로운 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)가 생성되었습니다.

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 구성을 사용하여 변환 프로세스 시작
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // 변환 결과를 로컬 파일로 저장
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

전체 파일 경로로 제공된 MD (markdown) 소스를 html로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | 소스 Markdown 파일 경로. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| outputPath | String | 출력 변환 결과로서 전체 HTML 파일 경로. |

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 변환 프로세스 시작
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 또 보기

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

전체 파일 경로로 제공된 MD (markdown) 소스를 html로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | 소스 Markdown 파일 경로. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| outputPath | String | 출력 변환 결과로서 전체 HTML 파일 경로. |

## 비고

Markdown 변환기

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

변환 단계

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

변환 소스. 기존 로컬 MD 파일을 감지하거나 입력 데이터 스트림을 변환 소스로 생성합니다. 변환 결과. 메서드 서명에 따라 결과 출력 파일 경로를 정의하거나 직접 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)를 얻을 수 있습니다. Converter 클래스의 ConvertMarkdown() 메서드를 사용하여 MD를 HTML 결과로 저장합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 온라인 MD 변환기

무료 온라인 [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html)에서 MD를 고품질, 쉬우며 빠르게 HTML로 변환할 수 있습니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다! 또한 다른 온라인 MD 변환기도 확인할 수 있습니다: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) 및 적절한 [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/)를 찾아보세요.

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
