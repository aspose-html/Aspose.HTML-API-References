---
title: "Converter.ConvertTemplate"
second_title: "Java용 Aspose.HTML API 참조"
description: "Converter 메서드. HTMLDocument로 제공된 템플릿 소스를 XML 및 JSON 템플릿 데이터와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 HTML 파일입니다."
type: docs

url: /ko/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/)로 제공된 템플릿 소스를 템플릿 데이터(XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 HTML 파일입니다.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/)로 제공된 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 폼 HTML 문서를 변환 소스로 사용
      var document = new HTMLDocument(sourcePath, new Configuration());

      // 변환 프로세스 시작
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // 리소스 정리
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

[`URL`](../../../com.aspose.html/url/) 로 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 HTML 파일입니다.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) 로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스 시작
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

[`URL`](../../../com.aspose.html/url/) 로 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 HTML 파일입니다.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) 로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

전체 파일 경로에 의해 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | 전체 파일 경로로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스 시작
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

전체 파일 경로에 의해 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | 전체 파일 경로로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 기본 구성으로 변환 프로세스 시작
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

인라인 콘텐츠에 의해 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 인라인 문자열 콘텐츠로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| baseUrl | String | HTML 템플릿의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // 인라인 소스 콘텐츠를 템플릿으로 사용
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 출력은 병합 결과로 사용
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();
	  
      // 변환 프로세스 시작
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### 또 보기

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

인라인 콘텐츠에 의해 제공된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 출력 파일 경로에 의해 생성된 html 파일입니다.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 인라인 문자열 콘텐츠로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| baseUrl | String | HTML 템플릿의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |
| outputPath | String | 출력 변환 결과로 전체 HTML 파일 경로. |

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // 인라인 소스 콘텐츠를 템플릿으로 사용
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // 폼 XML (JSON) 템플릿 데이터 파일 경로
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // TemplateData 객체 인스턴스 정의
   var templateData = new TemplateData(templateDataPath);

   // 폼 출력은 병합 결과로 사용
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // configuration 객체 인스턴스 정의
   var configuration = new Configuration();

   // 기본 TemplateLoadOptions 객체 정의
   var options = new TemplateLoadOptions();

   // 기본 구성으로 변환 프로세스 시작
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

아래는 소스를 템플릿으로 병합할 데이터 파일입니다.

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### 또 보기

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

템플릿 데이터 (XML, JSON)와 함께 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)에 표시된 템플릿 소스를 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 HTMLDocument입니다.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/)로 제공된 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();
      
      // 폼 HTML 문서를 변환 소스로 사용
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // 변환 프로세스 시작
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // 링크된 리소스와 함께 결과를 저장합니다.
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

템플릿 데이터 (XML, JSON)와 함께 [`URL`](../../../com.aspose.html/url/)에 표시된 템플릿 HTML 소스를 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) 로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL을 골격 HTML 소스 파일로 형성합니다.
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스 시작
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // 링크된 리소스와 함께 결과를 저장합니다.
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

템플릿 데이터 (XML, JSON)와 함께 [`URL`](../../../com.aspose.html/url/)에 표시된 템플릿 HTML 소스를 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) 로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL을 골격 HTML 소스 파일로 형성합니다.
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 기본 구성으로 변환 프로세스 시작
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // 링크된 리소스와 함께 결과를 저장합니다.
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

전체 파일 경로에 표시된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | 전체 파일 경로로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스 시작
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // 링크된 리소스와 함께 결과를 저장합니다.
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

전체 파일 경로에 표시된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| sourcePath | String | 전체 파일 경로로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 폼 스켈레톤 HTML 소스 파일 경로
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 결과 파일 경로
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 기본 구성으로 변환 프로세스 시작
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // 링크된 리소스와 함께 결과를 저장합니다.
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

인라인 콘텐츠에 표시된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 인라인 문자열 콘텐츠로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| baseUrl | String | HTML 템플릿의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 소스 콘텐츠를 템플릿으로 사용
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 출력은 병합 결과로 사용
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스를 시작하고 결과를 저장합니다.
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

인라인 콘텐츠에 표시된 템플릿 HTML 소스를 템플릿 데이터 (XML, JSON)와 병합합니다. 결과는 파일로 저장할 수 있는 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)입니다.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 내용 | String | 인라인 문자열 콘텐츠로 제공된 HTML 소스 스켈레톤을 병합합니다. |
| baseUrl | String | HTML 템플릿의 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |
| configuration | Configuration | 환경 구성. 애플리케이션의 환경 설정을 구성하는 데 사용되는 [`configuration`](../../../com.aspose.html/configuration/) 컨텍스트 객체를 나타냅니다. |
| 데이터 | TemplateData | 병합을 위한 템플릿 데이터 - 대체 (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 객체 인스턴스. 템플릿과 데이터 항목 이름이 대소문자를 구분하지 않고 일치하는지 여부를 결정하는 데 사용됩니다 (옵션). |

### 반환 값

변환 결과로 새로 생성된 [`HTMLDocument`](../../../com.aspose.html/htmldocument/)이며 출력 파일 경로를 통해 저장할 수 있습니다.

## 비고

템플릿 병합기

템플릿 병합의 아이디어는 HTML 템플릿을 기반으로 HTML 문서를 생성하고 데이터를 소스에서 채우는 것입니다. Aspose.HTML은 템플릿 및 XML, JSON과 같은 다양한 데이터 소스 유형과 작업하기 위한 인라인 표현식 구문을 제공합니다. 템플릿 병합 및 ConvertTemplate() 메서드 사용에 대한 자세한 내용은 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)에서 확인하십시오.

변환 (병합) 단계

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

템플릿 소스. 파일, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 객체 인스턴스 또는 인라인 콘텐츠로 HTML 템플릿 소스를 정의합니다. 변환 결과. 메서드 시그니처에 따라 직접 결과 HTMLDocument를 얻거나 결과 출력 파일 경로를 정의할 수 있습니다. [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 인스턴스를 생성합니다. Converter 클래스의 ConvertTemplate() 메서드를 사용하여 템플릿을 데이터와 병합합니다. 옵션 매개변수로 [`configuration`](../../../com.aspose.html/configuration/)을 추가할 수도 있습니다. 소스 코드

전체 예제와 데이터 파일을 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net)에서 다운로드할 수 있습니다.

## 예제

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 인라인 소스 콘텐츠를 템플릿으로 사용
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // 폼 XML (JSON) 템플릿 데이터 파일 경로
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData 객체 인스턴스 정의
      var templateData = new TemplateData(templateDataPath);

      // 폼 출력은 병합 결과로 사용
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // configuration 객체 인스턴스 정의
      var configuration = new Configuration();

      // 기본 TemplateLoadOptions 객체 정의
      var options = new TemplateLoadOptions();

      // 변환 프로세스를 시작하고 결과를 저장합니다.
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
