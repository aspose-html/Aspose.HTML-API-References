---
title: "Converter.ConvertSVG"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Конвертировать SVG‑источник, представленный SVGDocument. Результатом являются выходные данные, сформированные реализацией интерфейса ICreateStreamProvider"
type: docs

url: /ru/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Конвертировать SVG‑источник, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Запустить процесс конверсии с конфигурацией по умолчанию
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Конвертировать SVG‑источник, представленный полным путем к файлу, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Конвертировать SVG‑источник, представленный полным путем к файлу, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Преобразовать источник SVG, представленный встроенным содержимым, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Преобразовать источник SVG, представленный встроенным содержимым, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Преобразовать источник SVG, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом является файл DOCX, сформированный по пути выходного файла.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Преобразовать источник SVG, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл DOCX, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Преобразовать источник SVG, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл DOCX, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Преобразовать источник SVG, представленный полным путем к файлу, в DOCX. Результат — DOCX‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Преобразовать источник SVG, представленный полным путем к файлу, в DOCX. Результат — DOCX‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Преобразовать источник SVG, представленный встроенным содержимым. Результатом является файл docx, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Преобразовать источник SVG, представленный встроенным содержимым. Результатом является файл docx, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Конвертировать SVG‑источник, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Преобразовать источник SVG, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл DOCX, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Преобразовать источник SVG, указанный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Преобразовать источник SVG, указанный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Преобразовать источник SVG, представленный встроенным содержимым, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Преобразовать источник SVG, представленный встроенным содержимым, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование объекта [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , где вы найдете информацию о том, как преобразовать SVG в [DOCX](https://docs.fileformat.com/word-processing/docx/) с помощью методов ConvertSVG() класса Converter и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в DOCX

Класс Converter предлагает несколько специфических для SVG преобразований в DOCX. Чтобы преобразовать SVG в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат DOCX с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg), который преобразует SVG в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Преобразовать источник SVG, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в PDF. Результатом является файл PDF, сформированный по пути выходного файла.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Преобразовать источник SVG, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл PDF, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Преобразовать источник SVG, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл PDF, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Преобразовать источник SVG, представленный полным путем к файлу, в PDF. Результат — PDF‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Преобразовать источник SVG, представленный полным путем к файлу, в PDF. Результат — PDF‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Преобразовать источник SVG, представленный встроенным содержимым, в PDF. Результатом является файл pdf, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Преобразовать источник SVG, представленный встроенным содержимым, в PDF. Результатом является файл pdf, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Преобразовать источник SVG, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Преобразовать источник SVG, указанный полным путем к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Преобразовать источник SVG, указанный полным путем к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Преобразовать источник SVG, представленный встроенным содержимым, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Преобразовать источник SVG, представленный встроенным содержимым, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , где вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать SVG в PDF

Класс Converter предлагает несколько специфических для SVG преобразований в PDF. Чтобы преобразовать SVG в PDF, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника. Вы также можете задать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) в качестве источника или даже использовать встроенное SVG‑содержимое, представленное строкой‑источником. Результат конвертации. Укажите путь к выходному файлу или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или значениями по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат PDF с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑инструмент [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), который преобразует SVG в PDF с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Преобразуйте SVG‑источник, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом будет файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Преобразуйте SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Преобразуйте SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Преобразовать источник SVG, представленный полным путем к файлу, в изображение. Результат — файл изображения, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Преобразовать источник SVG, представленный полным путем к файлу, в изображение. Результат — файл изображения, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Преобразовать источник SVG, представленный встроенным содержимым, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Преобразовать источник SVG, представленный встроенным содержимым, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Конвертировать SVG‑источник, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Конвертировать SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Преобразуйте SVG‑источник, представленный полным путем к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Преобразуйте SVG‑источник, представленный полным путем к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Преобразуйте SVG‑источник, представленный встроенным содержимым, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Преобразуйте SVG‑источник, представленный встроенным содержимым, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), где вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Другие статьи, связанные с популярными форматами изображений: [преобразование SVG в PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [преобразование SVG в BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [преобразование SVG в GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) и [преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Преобразовать SVG в изображение

Класс Converter предлагает несколько специфических для SVG преобразований в изображение в популярных форматах. Чтобы преобразовать SVG в изображение, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл SVG или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете указать [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник преобразования или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат преобразования. Укажите путь выходного файла результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или значениями по умолчанию. Обратите внимание, что формат изображения по умолчанию — PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат изображения с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑конвертер [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), который преобразует SVG в JPG с высоким качеством, легко и быстро. Просто загрузите, конвертируйте ваши файлы и получите результаты через несколько секунд!

Другие популярные конвертеры изображений для различных форматов можно найти здесь: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) и [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Преобразуйте SVG‑источник, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Результатом будет файл XPS, сформированный по пути выходного файла.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | SVGDocument | Источник конвертации, представленный [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Сформировать SVG‑документ в качестве источника конвертации
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Запустить процесс конверсии с конфигурацией по умолчанию
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Преобразуйте SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл XPS, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создайте Url на основе входного пути к файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Преобразуйте SVG‑источник, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл XPS, сформированный по пути выходного файла.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | SVG‑исходный документ [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Преобразовать источник SVG, представленный полным путем к файлу, в XPS. Результат — XPS‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Преобразовать источник SVG, представленный полным путем к файлу, в XPS. Результат — XPS‑файл, созданный по пути к выходному файлу.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к SVG‑источнику. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Преобразовать источник SVG, представленный встроенным содержимым, в XPS. Результатом является файл xps, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Преобразовать источник SVG, представленный встроенным содержимым, в XPS. Результатом является файл xps, сформированный по пути выходного файла.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка в качестве встроенного SVG‑содержимого. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Обратитесь к [статья](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), где вы найдете информацию о том, как конвертировать SVG в XPS с помощью методов ConvertSVG() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Конвертировать SVG в XPS

Класс Converter предлагает несколько специфических для SVG конвертаций в XPS. Чтобы конвертировать SVG в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный SVG‑файл или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете определить [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) как источник конвертации или даже использовать встроенное SVG‑содержимое, представленное строковым источником. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertSVG() класса Converter, чтобы сохранить SVG как результат XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер SVG

Aspose.HTML предлагает бесплатный онлайн‑[Конвертер SVG в XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps), который конвертирует SVG в XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Формировать встроенное SVG‑содержимое
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
