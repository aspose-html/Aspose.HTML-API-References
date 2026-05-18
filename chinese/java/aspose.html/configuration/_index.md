---
title: "Configuration 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.Configuration 类。表示用于为应用程序设置环境配置的上下文对象。通过管理配置，您可以覆盖文档样式，应用自定义用户样式表，或处理来自应用程序的任何 Web 请求，以及配置脚本策略。详细信息请参阅《环境配置指南》。"
type: docs

url: /zh/java/com.aspose.html/configuration/
---
## Configuration class

该对象表示用于为应用程序设置环境设置的配置上下文对象。通过管理配置，您可以覆盖文档样式，应用自定义用户样式表，或处理来自应用程序的任何 Web 请求以及配置脚本策略。详细信息请参阅 [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/)。

```java
public class Configuration : IDisposable, IServiceProvider
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Configuration](configuration/)() | 初始化 `class` 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | 创建并配置 Configuration 对象的实例。 |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | 创建并配置 Configuration 对象的实例。 |
| [dispose](../../com.aspose.html/configuration/dispose/)() | 执行由应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | 获取请求的服务。 |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | 获取请求的服务。 |

## 备注

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) 下载完整的示例和数据文件。

## 示例

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // 此消息处理程序打印关于开始和完成处理请求的消息。
    public class LogMessageHandler : MessageHandler
    {
      // 重写 Invoke() 方法
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // 调用链中的下一个消息处理程序
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // 创建 Configuration 类的实例
      using var configuration = new Configuration();

      // 将 LogMessageHandler 添加到现有消息处理程序链中
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // 准备源文档文件的路径
      String documentPath = Path.Combine(DataDir, "input.htm");

      // 使用指定的配置初始化 HTML 文档
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
      // Prepare HTML code and save it to a file
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // 创建 Configuration 的实例
      using (var configuration = new Configuration())
      {
        // 将 'scripts' 标记为不受信任的资源
        configuration.Security |= Sandbox.Scripts;

        // 使用指定的配置初始化 HTML 文档
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // 将 HTML 转换为 PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### 另请参阅

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
