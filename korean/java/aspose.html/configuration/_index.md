---
title: "Configuration 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.Configuration 클래스. 애플리케이션의 환경 설정을 설정하는 데 사용되는 구성 컨텍스트 객체를 나타냅니다. 구성을 관리하면 사용자 정의 스타일시트를 적용하여 문서 스타일을 재정의하거나 애플리케이션의 웹 요청을 처리하고 스크립트 정책을 구성할 수 있습니다. 자세한 내용은 Environment Configuration 가이드에 있습니다."
type: docs

url: /ko/java/com.aspose.html/configuration/
---
## Configuration class

응용 프로그램의 환경 설정을 구성하는 데 사용되는 구성 컨텍스트 객체를 나타냅니다. 구성을 관리하면서 사용자 정의 스타일시트를 적용하여 문서 스타일을 재정의하거나, 응용 프로그램의 웹 요청을 처리하고 스크립트 정책을 구성할 수 있습니다. 자세한 내용은 [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/)를 참조하십시오.

```java
public class Configuration : IDisposable, IServiceProvider
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Configuration](configuration/)() | `class`의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Configuration 객체의 인스턴스를 생성하고 구성합니다. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Configuration 객체의 인스턴스를 생성하고 구성합니다. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | 요청된 서비스를 가져옵니다. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | 요청된 서비스를 가져옵니다. |

## 비고

전체 예제와 데이터 파일은 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)에서 다운로드할 수 있습니다.

## 예제

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // 이 메시지 핸들러는 요청 처리 시작 및 종료에 대한 메시지를 출력합니다.
    public class LogMessageHandler : MessageHandler
    {
      // Invoke() 메서드를 재정의합니다.
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // 체인에서 다음 메시지 핸들러를 호출합니다.
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Configuration 클래스의 인스턴스를 생성합니다.
      using var configuration = new Configuration();

      // LogMessageHandler를 기존 메시지 처리기 체인에 추가합니다.
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // 소스 문서 파일에 대한 경로를 준비합니다.
      String documentPath = Path.Combine(DataDir, "input.htm");

      // 지정된 구성으로 HTML 문서를 초기화합니다.
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // HTML 코드를 준비하고 파일에 저장합니다.
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Configuration의 인스턴스를 생성합니다.
      using (var configuration = new Configuration())
      {
        // 'scripts'를 신뢰되지 않는 리소스로 표시합니다.
        configuration.Security |= Sandbox.Scripts;

        // 지정된 구성으로 HTML 문서를 초기화합니다.
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // HTML을 PDF로 변환
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### 또 보기

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
