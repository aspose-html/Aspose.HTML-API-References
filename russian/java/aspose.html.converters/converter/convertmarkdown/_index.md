---
title: "Converter.ConvertMarkdown"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Преобразовать исходный MD‑markdown, представленный входным потоком, в html. Результатом является HTMLDocument, который можно сохранить по пути выходного файла."
type: docs

url: /ru/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Преобразовать исходный MD (markdown), представленный входным потоком, в html. Результатом является [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить по пути выходного файла.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных конвертации MD (Markdown). |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |

### Возвращаемое значение

Созданный новый [`HTMLDocument`](../../../com.aspose.html/htmldocument/) как результат конвертации, который можно сохранить по пути выходного файла.

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Открыть исходный файл как поток
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Запустить процесс конверсии
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Сохранить результат конвертации
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Преобразовать исходный MD (markdown), представленный входным потоком, в html. Результатом является [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить по пути выходного файла.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных конвертации MD (Markdown). |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |

### Возвращаемое значение

Созданный новый [`HTMLDocument`](../../../com.aspose.html/htmldocument/) как результат конвертации, который можно сохранить по пути выходного файла.

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Открыть исходный файл как поток
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Сохранить результат конвертации
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Преобразовать MD (markdown)‑источник, представленный входным потоком, в html. Результатом является html‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных конвертации MD (Markdown). |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| outputPath | String | Полный путь к html‑файлу как результат выхода конвертации. |

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Открыть исходный файл как поток
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Запустить процесс конверсии
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### См. также

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Преобразовать MD (markdown)‑источник, представленный входным потоком, в html. Результатом является html‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток данных конвертации MD (Markdown). |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| outputPath | String | Полный путь к html‑файлу как результат выхода конвертации. |

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Открыть исходный файл как поток
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Запустить процесс конверсии с конфигурацией по умолчанию
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Преобразовать исходный MD (markdown), представленный полным путем к файлу, в html. Результатом является [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить по пути выходного файла.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MD (Markdown). |

### Возвращаемое значение

Созданный новый [`HTMLDocument`](../../../com.aspose.html/htmldocument/) как результат конвертации, который можно сохранить по пути выходного файла.

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Запустить процесс конверсии
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Сохранить результат конвертации как локальный файл
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Преобразовать исходный MD (markdown), представленный полным путем к файлу, в html. Результатом является [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить по пути выходного файла.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к файлу источника MD (Markdown). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |

### Возвращаемое значение

Созданный новый [`HTMLDocument`](../../../com.aspose.html/htmldocument/) как результат конвертации, который можно сохранить по пути выходного файла.

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Запустить процесс конверсии с конфигурацией по умолчанию
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Сохранить результат конвертации как локальный файл
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Преобразовать MD (markdown)‑источник, представленный полным путем к файлу, в html. Результатом является html‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу Markdown. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| outputPath | String | Полный путь к html‑файлу как результат выхода конвертации. |

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Запустить процесс конверсии
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### См. также

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Преобразовать MD (markdown)‑источник, представленный полным путем к файлу, в html. Результатом является html‑файл, сформированный по пути выходного файла.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу Markdown. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| outputPath | String | Полный путь к html‑файлу как результат выхода конвертации. |

## Примечания

Конвертер Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Этапы конвертации

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружить существующий локальный файл MD или создать входной поток данных как источник конвертации. Результат конвертации. Вы можете получить непосредственно [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или задать путь выходного файла результата в зависимости от сигнатуры метода. Используйте метод ConvertMarkdown() класса Converter, чтобы сохранить MD в виде html‑результата. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Онлайн‑конвертер MD

Возможно, вас также заинтересует бесплатный онлайн‑инструмент [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html), который преобразует MD в HTML с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд! Также вы можете ознакомиться с другими онлайн‑конвертерами MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) и найти подходящие [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
