---
title: "Converter.ConvertSVG"
second_title: "Java용 Aspose.HTML API 참조"
description: "Converter 메서드. SVGDocument에 표시된 SVG 소스를 변환합니다. 결과는 ICreateStreamProvider 인터페이스 구현에 의해 형성된 출력 데이터입니다."
type: docs

url: /ko/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| document | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// 기본 구성으로 변환 프로세스 시작
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

전체 파일 경로에 표시된 SVG 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

전체 파일 경로에 표시된 SVG 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

인라인 콘텐츠로 제공된 SVG 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

인라인 콘텐츠로 제공된 SVG 소스를 XPS로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 DOCX 파일입니다.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| source | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 기본 구성으로 변환 프로세스 시작
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

[`URL`](../../../com.aspose.html/url/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 DOCX 파일입니다.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

[`URL`](../../../com.aspose.html/url/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 DOCX 파일입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

전체 파일 경로로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

전체 파일 경로로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

인라인 콘텐츠에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

인라인 콘텐츠에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 docx 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| outputPath | String | 출력 변환 결과로서 전체 docx 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| document | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 기본 구성으로 변환 프로세스 시작
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

[`URL`](../../../com.aspose.html/url/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 DOCX 파일입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

전체 파일 경로로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

전체 파일 경로로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

인라인 콘텐츠로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

인라인 콘텐츠로 제공된 SVG 소스를 DOCX로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/)를 참고하면 Converter 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 [DOCX](https://docs.fileformat.com/word-processing/docx/) 로 변환하는 방법과 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 DOCX로 변환

Converter 클래스는 SVG를 DOCX로 변환하는 여러 가지 방법을 제공합니다. SVG를 DOCX로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 DOCX 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 DOCX로 변환하는 무료 온라인 [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 DocSaveOptions 객체 정의
      var options = new DocSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 PDF 파일입니다.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| source | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 기본 구성으로 변환 프로세스 시작
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

[`URL`](../../../com.aspose.html/url/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 PDF 파일입니다.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

[`URL`](../../../com.aspose.html/url/) 로 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 PDF 파일입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

전체 파일 경로로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

전체 파일 경로로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

인라인 콘텐츠에 의해 제공된 SVG 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

인라인 콘텐츠에 의해 제공된 SVG 소스를 PDF로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 pdf 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| outputPath | String | 출력 변환 결과로 전체 pdf 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) 로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| document | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 기본 구성으로 변환 프로세스 시작
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

전체 파일 경로로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

전체 파일 경로로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

인라인 콘텐츠로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

인라인 콘텐츠로 제공된 SVG 소스를 PDF로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현으로 생성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 사용하면 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options)를 참조하세요. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/)를 참고하면 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 PDF로 변환하는 방법과 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 PDF로 변환

Converter 클래스는 SVG를 PDF로 변환하는 여러 가지 방법을 제공합니다. SVG를 PDF로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)를 변환 소스로 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새 [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 PDF 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML는 고품질, 쉽고 빠르게 SVG를 PDF로 변환하는 무료 온라인 [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 PdfSaveOptions 객체 정의
      var options = new PdfSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| source | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 기본 구성으로 변환 프로세스 시작
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

[`URL`](../../../com.aspose.html/url/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

[`URL`](../../../com.aspose.html/url/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

전체 파일 경로로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

전체 파일 경로로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 이미지 파일입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

인라인 콘텐츠에 의해 제공된 SVG 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 image 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

인라인 콘텐츠에 의해 제공된 SVG 소스를 이미지로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 image 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| outputPath | String | 전체 이미지 파일 경로가 출력 변환 결과로 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| document | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 변환 프로세스 시작
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

`[`URL`](../../../com.aspose.html/url/)`에 표시된 SVG 소스를 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

전체 파일 경로로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

전체 파일 경로로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

인라인 콘텐츠로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | 알려진(`[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)` 참조) 또는 사용자 정의 `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` 인터페이스 구현. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

인라인 콘텐츠로 제공된 SVG 소스를 이미지로 변환합니다. 결과는 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현에 의해 형성된 출력 데이터입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) 등을 지정할 수 있습니다. |
| provider | ICreateStreamProvider | `[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)`의 구현으로, 출력 스트림을 얻는 데 사용됩니다. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

다음 [문서](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/)를 참조하십시오. 여기에서 ConvertSVG() 메서드와 [`Converter`](../) 클래스를 사용하여 SVG를 JPG로 변환하는 방법 및 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)와 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다. 기타 인기 있는 이미지 포맷 관련 문서: [SVG를 PNG로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG를 BMP로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG를 GIF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) 및 [SVG를 TIFF로 변환](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG를 이미지로 변환

Converter 클래스는 인기 있는 포맷에서 SVG를 이미지로 변환하는 여러 옵션을 제공합니다. SVG를 이미지로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 변환 소스로 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 정의하거나 문자열 소스로 제공된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) 객체를 생성합니다. 기본 이미지 포맷은 PNG임을 참고하십시오. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 이미지 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질이며 쉽고 빠르게 SVG를 JPG로 변환하는 무료 온라인 [SVG를 JPG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-jpg)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

다양한 포맷에 대한 다른 인기 이미지 변환기는 여기에서 찾을 수 있습니다: [SVG를 PNG로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG를 BMP로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG를 GIF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-gif) 및 [SVG를 TIFF로 변환기](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 구현 중 하나를 사용합니다
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 기본 ImageSaveOptions 객체 정의
      var options = new ImageSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| source | SVGDocument | `[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)`에 표시된 변환 소스입니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // SVG 문서를 변환 소스로 형성합니다
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// 기본 구성으로 변환 프로세스 시작
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

[`URL`](../../../com.aspose.html/url/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

[`URL`](../../../com.aspose.html/url/)에 의해 제공된 SVG 소스를 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | SVG 소스 문서 [`URL`](../../../com.aspose.html/url/) - 범용 식별자(URL)의 객체 표현을 제공합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

전체 파일 경로로 제공된 SVG 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

전체 파일 경로로 제공된 SVG 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | SVG 소스 전체 파일 경로. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

인라인 콘텐츠에 의해 제공된 SVG 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

인라인 콘텐츠에 의해 제공된 SVG 소스를 XPS로 변환합니다. 결과는 출력 파일 경로에 의해 생성된 xps 파일입니다.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 문자열 형태의 인라인 SVG 콘텐츠. |
| baseUri | String | 문서의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` 객체 사용을 통해 렌더링 프로세스를 조정할 수 있습니다. 자세한 내용은 [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options)을 참조하십시오. |
| outputPath | String | 출력 변환 결과로서 전체 xps 파일 경로. |

## 비고

SVG 변환기

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/)를 참조하십시오. 여기에서 [`Converter`](../) 클래스의 ConvertSVG() 메서드를 사용하여 SVG를 XPS로 변환하는 방법과 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 및 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 매개변수를 적용하는 방법에 대한 정보를 찾을 수 있습니다.

SVG를 XPS로 변환

Converter 클래스는 SVG를 XPS로 변환하는 여러 가지 전용 변환을 제공합니다. SVG를 XPS로 변환하려면 몇 단계로 구성된 간단한 시나리오 중 하나를 따라야 합니다:

변환 소스. 기존 로컬 SVG 파일이나 원격 [`Url`](../../../com.aspose.html/url/)을 변환 소스로 감지합니다. 또한 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)을 변환 소스로 정의하거나 문자열 소스로 표시된 인라인 SVG 콘텐츠를 사용할 수도 있습니다. 변환 결과. 결과 출력 파일 경로를 정의하거나 알려진 또는 사용자 정의 [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 인터페이스 구현을 출력 데이터 버퍼로 사용합니다. 특정 또는 기본 설정으로 새로운 [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) 객체를 생성합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. Converter 클래스의 ConvertSVG() 메서드를 사용하여 사용자 시나리오에 따라 세 개 이상의 매개변수로 SVG를 XPS 결과로 저장합니다. 온라인 SVG 변환기

Aspose.HTML은 고품질, 간편하고 빠르게 SVG를 XPS로 변환하는 무료 온라인 [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps)를 제공합니다. 파일을 업로드하고 변환하면 몇 초 안에 결과를 얻을 수 있습니다!

소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 인라인 SVG 콘텐츠 형성
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // 기본 XpsSaveOptions 객체 정의
      var options = new XpsSaveOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
