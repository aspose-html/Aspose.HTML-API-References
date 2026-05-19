---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML for Java API 참조"
description: "Converter 메서드. 입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다."
type: docs

url: /ko/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

입력 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0)으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 입력 mhtml (.mht) 데이터 스트림. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

전체 파일 경로로 제공된 MHTML 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 폼 소스 파일 경로
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// 폼 결과 파일 경로
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 기본 XpsSaveOptions 객체 정의
	var options = new XpsSaveOptions();

	// 변환 프로세스 시작
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 폼 소스 파일 경로
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// 폼 결과 파일 경로
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// 기본 XpsSaveOptions 객체 정의
	var options = new XpsSaveOptions();

	// 변환 프로세스 시작
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

입력 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) 으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 변환 소스 mhtml(.mht) 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

전체 파일 경로로 제공된 MHTML 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 폼 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 폼 소스 파일 경로
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 변환 소스 mhtml(.mht) 데이터 스트림. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

전체 파일 경로로 제공된 MHTML 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

[`URL`](../../../com.aspose.html/url/) 로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 변환 소스 mhtml(.mht) 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

전체 파일 경로로 제공된 MHTML 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업을 위해 XPS 포맷을 활용하려면 MHTML을 [XPS](https://docs.fileformat.com/page-description-language/xps/) 로 변환해야 하는 경우가 많습니다. XPS 파일은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)를 참고하면 [`Converter`](../) 클래스의 ConvertHTML() 메서드를 사용하여 MHTML을 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수 적용 방법에 대한 정보를 얻을 수 있습니다.

MHTML을 XPS로 변환

Converter 클래스는 MHTML을 XPS로 변환하는 몇 가지 기능을 제공합니다. MHTML을 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML (.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 표준 또는 사용자 정의 특정 스트림을 변환 소스로 사용할 수 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 MHTML을 XPS 결과로 저장합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 MHTML을 XPS로 변환하는 무료 온라인 [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

전체 파일 경로로 제공된 MHTML 소스를 DOCX로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 파일 경로. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

전체 파일 경로로 제공된 MHTML 소스를 DOCX로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

[`URL`](../../../com.aspose.html/url/) 로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 형성된 docx 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과인 전체 docx 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

전체 파일 경로로 제공된 MHTML 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

전체 파일 경로로 제공된 MHTML 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

[`URL`](../../../com.aspose.html/url/) 로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [DOCX](https://docs.fileformat.com/word-processing/docx/) 형식을 활용하기 위해 MHTML을 DOCX로 변환해야 하는 경우가 많습니다. DOCX는 Microsoft Word 문서에 널리 알려진 형식입니다. 텍스트, 표, 래스터 및 벡터 그래픽, 비디오, 사운드 및 다이어그램 등 다양한 데이터를 포함할 수 있습니다. 이 형식은 복잡한 서식 기능을 지원하고 사용자가 모든 종류의 문서를 작성할 수 있는 다양한 옵션을 제공하기 때문에 인기가 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 DOCX로 변환

Converter 클래스는 MHTML을 DOCX로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 변환 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 DOCX 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 DOCX로 변환하는 무료 온라인 [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

전체 파일 경로로 제공된 MHTML 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

전체 파일 경로로 제공된 MHTML 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 파일 경로. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 pdf 파일 경로. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

전체 파일 경로로 제공된 MHTML 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 생성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 파일 경로. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

전체 파일 경로로 제공된 MHTML 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 생성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

[`URL`](../../../com.aspose.html/url/) 로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options)를 참조하십시오. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

특정 작업에 [PDF](https://docs.fileformat.com/pdf/) 형식을 활용하기 위해 MHTML을 PDF로 변환해야 하는 경우가 많습니다. PDF는 다른 파일이 제공하지 않는 많은 이점을 가지고 있습니다. 예를 들어, 많은 프로그램과 앱이 PDF 문서를 지원하며; PDF 파일은 인쇄에 최적화되어 있어 문서의 물리적 사본을 만들기에 이상적이며; PDF 파일에 대한 보안 설정을 구성할 수 있습니다 - 인쇄, 편집, 전자 서명 사용 등을 비활성화할 수 있습니다.

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

MHTML을 PDF로 변환

Converter 클래스는 MHTML을 PDF로 변환하는 몇 가지 전용 변환을 제공합니다. MHTML을 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 및 원격 Url을 변환 소스로 감지합니다. 표준 또는 사용자 지정 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0)을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 PDF 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 PDF로 변환하는 무료 온라인 [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

입력 스트림으로 제공된 MHTML 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

전체 파일 경로로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

입력 스트림으로 제공된 MHTML 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

전체 파일 경로로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

전체 파일 경로로 제공된 MHTML 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 생성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)`를 참조) 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현입니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

입력 스트림으로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | MHTML 변환 입력 데이터 스트림. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

전체 파일 경로로 제공된 MHTML 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 생성된 출력 데이터입니다.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourcePath | String | MHTML 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | [` 인터페이스`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

URL로 제공된 MHTML 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceUrl | Url | MHTML 소스 문서 URL - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 설정하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 출력 스트림을 얻는 데 사용될 [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)의 구현입니다. |

## 비고

MHTML 변환기

[MHTML](https://docs.fileformat.com/web/mhtml/) 확장자를 가진 파일은 여러 애플리케이션이 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 형식은 웹 HTML 코드와 관련 리소스를 하나의 파일에 저장하기 때문에 아카이브 형식으로 알려져 있습니다. 이러한 리소스에는 이미지, 애플릿, 애니메이션, 오디오 파일 등 웹 페이지에 연결된 모든 것이 포함됩니다. MHTML 파일은 Internet Explorer 및 Microsoft Word와 같은 다양한 애플리케이션에서 열 수 있습니다. 형식에 대한 실제 사양은 [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557)에 자세히 설명되어 있습니다.

Converter 클래스의 ConvertMHTML() 메서드를 사용하여 MHTML을 다양한 형식의 이미지로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보는 해당 기사에서 확인하십시오.

MHTML을 이미지로 변환

Converter 클래스는 MHTML을 이미지로 변환하는 몇 가지 전용 변환을 제공합니다. 지원되는 형식은 [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) 및 [TIFF](https://docs.fileformat.com/image/tiff/)입니다. MHTML을 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 MHTML(.mht) 파일 또는 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 표준 또는 사용자 지정 스트림을 소스로 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 지정 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 형식은 PNG입니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. ConvertMHTML() 메서드(Converter 클래스)를 사용하여 MHTML을 이미지 결과로 저장하며, 시나리오에 따라 세 개 이상의 매개변수가 필요합니다. 온라인 MHTML 변환기

Aspose.HTML은 고품질, 쉽고 빠르게 MHTML을 JPEG 파일로 변환하는 무료 온라인 [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 입력 파일 경로를 기반으로 Url 생성
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성을 사용하여 변환 프로세스 시작
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
