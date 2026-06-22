---
title: "Converter.ConvertMHTML"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Преобразуйте источник MHTML, представленный входным потоком. Результатом будет файл XPS, сформированный по пути выходного файла."
type: docs

url: /ru/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Преобразовать MHTML‑источник, представленный входным [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Результатом является XPS‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных mhtml (.mht). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в XPS. Результат — XPS‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Определите объект XpsSaveOptions по умолчанию
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Преобразовать MHTML‑источник, представленный URL. Результат — XPS‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Определите объект XpsSaveOptions по умолчанию
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Преобразовать MHTML‑источник, представленный входным [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). Результат — XPS‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток данных исходного mhtml (.mht) для конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в XPS. Результат — XPS‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Преобразовать MHTML‑источник, представленный URL. Результат — XPS‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток данных исходного mhtml (.mht) для конвертации. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Преобразовать источник MHTML, представленный полным путем к файлу, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Преобразовать источник MHTML, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Поток данных исходного mhtml (.mht) для конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Преобразовать источник MHTML, представленный полным путем к файлу, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Преобразовать источник MHTML, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Преобразование MHTML в [XPS](https://docs.fileformat.com/page-description-language/xps/) часто требуется для использования формата XPS в специфических задачах. Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданные Microsoft.

Обратитесь к [статье](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), где вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertHTML() класса [`Converter`](../) и как применить параметры [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в XPS

Класс Converter предлагает несколько специфических для MHTML преобразований в XPS. Чтобы преобразовать MHTML в XPS, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник преобразования. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника преобразования. Вы также можете использовать стандартный или пользовательский поток в качестве источника преобразования. Результат преобразования. Укажите путь выходного файла или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат XPS с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps), который преобразует MHTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты через несколько секунд!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект XpsSaveOptions по умолчанию
      var options = new XpsSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Преобразовать MHTML‑источник, представленный входным потоком. Результатом является DOCX‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в DOCX. Результатом является DOCX‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к файлу-источнику MHTML. Он будет объединён с текущим каталогом для формирования абсолютного URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Преобразовать MHTML‑источник, представленный URL. Результат — DOCX‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Преобразовать MHTML‑источник, представленный входным потоком. Результатом является DOCX‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в DOCX. Результатом является DOCX‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Преобразовать источник MHTML, представленный [`URL`](../../../com.aspose.html/url/). Результатом будет файл docx, сформированный по пути к выходному файлу.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | Документ-источник MHTML [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу docx как результат выхода преобразования. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Преобразовать источник MHTML, представленный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Преобразовать источник MHTML, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | Документ-источник MHTML [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Преобразовать источник MHTML, представленный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить configuration в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Преобразовать источник MHTML, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | Документ-источник MHTML [`URL`](../../../com.aspose.html/url/) — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в DOCX часто требуется, чтобы воспользоваться форматом [DOCX](https://docs.fileformat.com/word-processing/docx/) для конкретных задач. DOCX — известный формат документов Microsoft Word. Он может содержать широкий спектр данных, включая текст, таблицы, растровую и векторную графику, видео, звук и диаграммы. Этот формат популярен, потому что поддерживает сложные возможности форматирования и предоставляет пользователям разнообразные варианты создания любого типа документа.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), где вы найдете информацию о том, как конвертировать MHTML в DOCX с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в DOCX

Класс Converter предлагает несколько специфических конвертаций MHTML в DOCX. Чтобы преобразовать MHTML в DOCX, следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский поток в качестве источника конвертации. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с конкретными или стандартными настройками. Вы также можете добавить configuration в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как результат DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн-конвертер MHTML.

Aspose.HTML предлагает бесплатный онлайн [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), который конвертирует MHTML в DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Создать объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Преобразовать MHTML‑источник, представленный входным потоком. Результатом является PDF‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в PDF. Результат — PDF‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Преобразовать MHTML‑источник, представленный URL. Результат — PDF‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Преобразовать MHTML‑источник, представленный входным потоком. Результатом является PDF‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Преобразовать MHTML‑источник, представленный полным путем к файлу, в PDF. Результат — PDF‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к файлу-источнику MHTML. Он будет объединён с текущим каталогом для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Преобразовать MHTML‑источник, представленный URL. Результат — PDF‑файл, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации вывода. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Преобразовать источник MHTML, указанный полным путём к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к файлу-источнику MHTML. Он будет объединён с текущим каталогом для формирования абсолютного URL. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Преобразовать источник MHTML, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Преобразовать источник MHTML, указанный полным путём к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Преобразовать источник MHTML, представленный [`URL`](../../../com.aspose.html/url/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) объект позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Конвертация MHTML в PDF часто требуется, чтобы воспользоваться форматом [PDF](https://docs.fileformat.com/pdf/) для конкретных задач. PDF обладает множеством преимуществ, которых нет у других файлов. Например, многие программы и приложения поддерживают PDF‑документы; PDF‑файлы оптимизированы для печати и идеально подходят для создания физических копий ваших документов; вы можете настроить параметры безопасности PDF‑файлов — отключить печать, редактирование, использовать электронную подпись и т.д.

Обратитесь к [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), где вы найдете информацию о том, как конвертировать MHTML в PDF с помощью методов ConvertMHTML() класса [`Converter`](../) и как применить параметры [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в PDF

Класс Converter предлагает несколько специфических преобразований MHTML в PDF. Чтобы преобразовать MHTML в PDF, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый URL в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с конкретными или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как PDF‑результат с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), который преобразует MHTML в PDF с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Преобразовать MHTML‑источник, представленный входным потоком, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Преобразовать MHTML‑источник, представленный полным путем к файлу. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Преобразовать MHTML‑источник, представленный URL. Результат — файл изображения, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Преобразовать MHTML‑источник, представленный входным потоком, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Преобразовать MHTML‑источник, представленный полным путем к файлу. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Преобразовать MHTML‑источник, представленный URL. Результат — файл изображения, сформированный путём к файлу вывода.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Преобразовать источник MHTML, указанный полным путём к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Преобразовать источник MHTML, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Преобразовать источник MHTML, представленный входным потоком. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных для конвертации MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Преобразовать источник MHTML, указанный полным путём к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MHTML. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions();

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Преобразовать источник MHTML, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL документа-источника MHTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. |

## Примечания

Конвертер MHTML

Файлы с расширением [MHTML](https://docs.fileformat.com/web/mhtml/) представляют собой формат архива веб‑страницы, который может создавать множество различных приложений. Формат известен как архивный, потому что сохраняет HTML‑код веб‑страницы и связанные ресурсы в одном файле. Эти ресурсы включают всё, что связано со страницей, например изображения, апплеты, анимацию, аудиофайлы и т.д. Файлы MHTML могут открываться в различных приложениях, таких как Internet Explorer и Microsoft Word. Подробные спецификации формата изложены в [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Обратитесь к статье, где вы найдёте информацию о том, как преобразовать MHTML в изображения разных форматов с помощью методов ConvertMHTML() класса Converter и как применить параметры [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Преобразовать MHTML в изображение

Класс Converter предлагает несколько специфических преобразований MHTML в изображения. Поддерживаемые форматы: [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) и [TIFF](https://docs.fileformat.com/image/tiff/). Чтобы преобразовать MHTML в изображение, вам следует выполнить один из простых сценариев, состоящий из нескольких шагов:

Источник конвертации. Обнаружьте существующий локальный файл MHTML (.mht) или удалённый [`Url`](../../../com.aspose.html/url/) в качестве источника конвертации. Вы также можете использовать стандартный или пользовательский специфический поток в качестве источника. Результат конвертации. Укажите путь к выходному файлу или используйте известный или пользовательский интерфейс реализации [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с конкретными или параметрами по умолчанию. Формат изображения по умолчанию — PNG. Вы также можете добавить конфигурацию в качестве параметра опции. Используйте метод ConvertMHTML() класса Converter, чтобы сохранить MHTML как изображение с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертер MHTML

Aspose.HTML предлагает бесплатный онлайн [конвертер MHTML в JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), который преобразует MHTML в файл JPEG с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать Url на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result");

      // Определите объект ImageSaveOptions по умолчанию
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Использовать одну из реализаций ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
