---
title: "Configuration Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.Configuration class. Представляет объект контекста конфигурации, используемый для настройки параметров среды приложения. Управляя конфигурацией, вы можете переопределять стиль документа, применяя пользовательскую таблицу стилей, или обрабатывать любые веб‑запросы от приложения, а также настраивать политику скриптов. Подробности находятся в руководстве по конфигурации среды."
type: docs

url: /ru/java/com.aspose.html/configuration/
---
## Configuration class

Представляет объект контекста конфигурации, используемый для настройки параметров среды приложения. Управляя конфигурацией, вы можете переопределять стиль документа, применяя пользовательскую таблицу стилей, обрабатывать любые веб‑запросы от приложения, а также настраивать политику скриптов. Подробности находятся в [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Configuration](configuration/)() | Инициализирует новый экземпляр `class`. |

## Свойства

| Имя | Описание |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Создайте и настройте экземпляр объекта Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Создайте и настройте экземпляр объекта Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Получает запрошенный сервис. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Получает запрошенный сервис. |

## Примечания

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Этот обработчик сообщений выводит сообщение о начале и завершении обработки запроса
    public class LogMessageHandler : MessageHandler
    {
      // Переопределите метод Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Вызовите следующий обработчик сообщений в цепочке
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Создайте экземпляр класса Configuration
      using var configuration = new Configuration();

      // Добавьте LogMessageHandler в цепочку существующих обработчиков сообщений
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Подготовьте путь к файлу исходного документа
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Инициализируйте HTML‑документ с указанной конфигурацией
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
      // Подготовьте HTML‑код и сохраните его в файл
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Создайте экземпляр Configuration
      using (var configuration = new Configuration())
      {
        // Пометьте 'scripts' как недоверенный ресурс
        configuration.Security |= Sandbox.Scripts;

        // Инициализируйте HTML‑документ с указанной конфигурацией
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Конвертировать HTML в PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### См. также

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
