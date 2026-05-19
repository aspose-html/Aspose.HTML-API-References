---
title: "Converter.ConvertTemplate"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Объединить источник шаблона, представленный HTMLDocument, с данными шаблона XML JSON. Результатом является html‑файл, сформированный по пути вывода файла."
type: docs

url: /ru/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Объединить источник шаблона, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), с данными шаблона (XML, JSON). Результатом является html‑файл, сформированный по пути вывода файла.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| template | HTMLDocument | Объединение скелета источника, представленного [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Укажите HTML‑документ формы в качестве источника преобразования
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Запустить процесс конверсии
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Очистить ресурсы
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Объедините HTML‑источник шаблона, представленный по [`URL`](../../../com.aspose.html/url/), с данными шаблона (XML, JSON). Результатом будет HTML‑файл, созданный по указанному пути вывода.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Слияние HTML‑скелета источника, представленного по [`URL`](../../../com.aspose.html/url/). |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL исходного HTML‑скелета формы
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Объедините HTML‑источник шаблона, представленный по [`URL`](../../../com.aspose.html/url/), с данными шаблона (XML, JSON). Результатом будет HTML‑файл, созданный по указанному пути вывода.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Слияние HTML‑скелета источника, представленного по [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL исходного HTML‑скелета формы
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData 
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Объединить HTML‑источник шаблона, представленный полным путем к файлу, с данными шаблона (XML, JSON). Результатом является файл html, сформированный по пути выходного файла.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Слияние HTML‑скелета источника, представленного полным путем к файлу. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Объединить HTML‑источник шаблона, представленный полным путем к файлу, с данными шаблона (XML, JSON). Результатом является файл html, сформированный по пути выходного файла.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Слияние HTML‑скелета источника, представленного полным путем к файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Объединить HTML‑источник шаблона, представленный встроенным содержимым, с данными шаблона (XML, JSON). Результатом является файл html, сформированный по пути выходного файла.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Слияние HTML‑скелета источника, представленного встроенным содержимым String. |
| baseUrl | String | Базовый URI HTML‑шаблона. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Укажите встроенное содержимое источника в качестве шаблона
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
       
      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Укажите вывод в качестве результата слияния 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();
	  
      // Запустить процесс конверсии
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

### См. также

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Объединить HTML‑источник шаблона, представленный встроенным содержимым, с данными шаблона (XML, JSON). Результатом является файл html, сформированный по пути выходного файла.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Слияние HTML‑скелета источника, представленного встроенным содержимым String. |
| baseUrl | String | Базовый URI HTML‑шаблона. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |
| outputPath | String | Полный путь к html‑файлу как результат вывода конвертации. |

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Укажите встроенное содержимое источника в качестве шаблона
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
    
   // Укажите путь к файлу данных шаблона формы в формате xml (json)
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Определите экземпляр объекта TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Укажите вывод в качестве результата слияния 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Определите экземпляр объекта configuration
   var configuration = new Configuration();

   // Определите объект TemplateLoadOptions по умолчанию
   var options = new TemplateLoadOptions();

   // Запустить процесс конверсии с конфигурацией по умолчанию
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Ниже находится файл данных для объединения с источником в качестве шаблона

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

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Объедините шаблонный источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), с данными шаблона (XML, JSON). Результатом будет новый сформированный HTMLDocument, который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| template | HTMLDocument | Объединение скелета источника, представленного [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();
      
      // Укажите HTML‑документ формы в качестве источника преобразования
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Запустить процесс конверсии
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Сохранить результат со связанными ресурсами
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Объедините шаблонный HTML‑источник, представленный [`URL`](../../../com.aspose.html/url/), с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Слияние HTML‑скелета источника, представленного по [`URL`](../../../com.aspose.html/url/). |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Сформировать URL для скелетного HTML‑файла-источника
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Сохранить результат со связанными ресурсами
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Объедините шаблонный HTML‑источник, представленный [`URL`](../../../com.aspose.html/url/), с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Слияние HTML‑скелета источника, представленного по [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Сформировать URL для скелетного HTML‑файла-источника
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Сохранить результат со связанными ресурсами
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

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

Объедините шаблонный HTML‑источник, представленный полным путем к файлу, с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Слияние HTML‑скелета источника, представленного полным путем к файлу. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Сохранить результат со связанными ресурсами
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Объедините шаблонный HTML‑источник, представленный полным путем к файлу, с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Слияние HTML‑скелета источника, представленного полным путем к файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите путь к файлу исходного HTML‑скелета формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустить процесс конверсии с конфигурацией по умолчанию
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Сохранить результат со связанными ресурсами
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Объедините шаблонный HTML‑источник, представленный встроенным содержимым, с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Слияние HTML‑скелета источника, представленного встроенным содержимым String. |
| baseUrl | String | Базовый URI HTML‑шаблона. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите встроенное содержимое источника в качестве шаблона
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

      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Укажите вывод в качестве результата слияния 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустите процесс конвертации и сохраните результат
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

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Объедините шаблонный HTML‑источник, представленный встроенным содержимым, с данными шаблона (XML, JSON). Результатом будет новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/), который можно сохранить в файл.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Слияние HTML‑скелета источника, представленного встроенным содержимым String. |
| baseUrl | String | Базовый URI HTML‑шаблона. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| данные | TemplateData | Данные шаблона для слияния — подстановки (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) экземпляр объекта. Он используется для определения, совпадают ли имена шаблона и элементов данных, независимо от регистра (опции). |

### Возвращаемое значение

Новый сформированный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в качестве результата конвертации, который можно сохранить по пути вывода файла.

## Примечания

Объединитель шаблонов

Идея слияния шаблонов состоит в том, чтобы создать HTML‑документ на основе HTML‑шаблона и заполнить его данными из источника. Aspose.HTML предоставляет синтаксис встроенных выражений для работы с шаблонами и различными типами источников данных, такими как XML и JSON. См. [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/), где вы можете найти дополнительную информацию о слиянии шаблонов и использовании метода ConvertTemplate().

Шаги преобразования (слияния)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Источник шаблона. Определите источник HTML‑шаблона через файл, [`URL`](../../../com.aspose.html/url/), экземпляр объекта [`HTMLDocument`](../../../com.aspose.html/htmldocument/) или даже через встроенное содержимое. Результат преобразования. Вы можете получить непосредственно полученный HTMLDocument или задать путь к выходному файлу в зависимости от сигнатуры метода. Создайте экземпляр [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Используйте метод ConvertTemplate() класса Converter для слияния шаблона с данными. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Укажите встроенное содержимое источника в качестве шаблона
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
       
      // Укажите путь к файлу данных шаблона формы в формате xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Определите экземпляр объекта TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Укажите вывод в качестве результата слияния 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Определите экземпляр объекта configuration
      var configuration = new Configuration();

      // Определите объект TemplateLoadOptions по умолчанию
      var options = new TemplateLoadOptions();

      // Запустите процесс конвертации и сохраните результат
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

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
