---
title: "HTMLDocument.Save"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLDocument. Сохраняет документ в локальный файл, указанный URL. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name _files."
type: docs

url: /ru/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\".

```java
public void Save(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный [`URL`](../../url/) для выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Метод Save(Url)

Необходимо указать полный путь Url — 'outputFilePath' для сохранения HTML‑документа. Конструктор Url(url) создаёт экземпляр класса [`Url`](../../url/) с указанным URL. Затем следует передать этот экземпляр в метод Save(Url). Документ будет сохранён в локальный файл, указанный URL. Все ресурсы, используемые в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + "_files".

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### См. также

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```java
public void Save(String path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Путь в локальной файловой системе к выходному файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Метод Save(String) принимает в качестве параметра путь в локальной файловой системе к выходному файлу и сохраняет HTML‑документ в локальный файл, указанный путем. Все ресурсы, используемые в документе, будут сохранены в соседнюю папку.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### См. также

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Сохраняет документ в локальный файл, указанный путем. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(String, HTMLSaveFormat) Метод

Метод Save(String, HTMLSaveFormat) принимает в качестве параметров путь в локальной файловой системе к выходному файлу и параметр saveFormat. Перечисление [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) указывает формат, в котором сохраняется документ; это может быть форматы HTML, MHTML и MD. Метод сохраняет HTML‑документ в указанном формате в локальный файл, указанный в пути. Все ресурсы, используемые в документе, будут сохранены в соседнюю папку.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Заголовок&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Контейнер с ID - идентификатор&lt;/div&gt;

&lt;div class="custom-class"&gt;Настроено контейнером CSS‑класса&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Первый абзац, стилизованный классом pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Второй абзац, стилизованный классом pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Третий абзац, стилизованный классом pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;Span, стилизованный классом pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id=\"p1\" class=\"ddd kkk\"&gt;Параграф, стилизованный классом с именем =ddd kkk=&lt;/p&gt;

&lt;p id=\"p2\" class=\"ddd fff\"&gt;Параграф, стилизованный классом с именем =ddd fff=&lt;/p&gt;

&lt;p id=\"p3\" class=\"kkk fff\"&gt;Параграф, стилизованный классом с именем =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Привет из элемента DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### См. также

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(Url, HTMLSaveFormat) Метод

Необходимо указать полный путь Url - 'outputFilePath' для сохранения HTML‑документа. Конструктор Url(url) создает экземпляр класса [`Url`](../../url/) с указанным url. Перечисление [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) определяет формат, в котором сохраняется документ; это может быть форматы HTML, MHTML и MD. Затем следует передать параметры методу Save(url, saveFormat). Документ будет сохранён в указанном формате в локальный файл, указанный url.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### См. также

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Формат, в котором сохраняется документ. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveOptions | HTMLSaveOptions | Объект [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) предназначен для управления процессом обработки ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(String, HTMLSaveOptions) Метод

Метод Save(String, HTMLSaveOptions) принимает в качестве параметров путь в локальной файловой системе к выходному файлу, экземпляр класса [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) и сохраняет HTML‑документ с ресурсами в локальный файл, указанный путем. Конструктор HTMLSaveOptions() создает экземпляр параметров сохранения, содержащий свойства [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/), используемые для настройки обработки ресурсов. Все ресурсы, используемые в документе, будут сохранены в соседнюю папку.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Определите экземпляр класса параметров
	var options = new HTMLSaveOptions();
	// Ограничение обработки страниц
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### См. также

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный [`URL`](../../url/) для выходного файла. |
| saveOptions | HTMLSaveOptions | Объект [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) предназначен для управления процессом обработки ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(Url, HTMLSaveOptions) Метод

Необходимо указать полный путь Url для сохранения HTML‑документа. Конструктор Url(url) создает экземпляр класса [`Url`](../../url/) с указанным url. Конструктор HTMLSaveOptions() создает экземпляр класса [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/), содержащий свойства ResourceHandlingOptions, используемые для настройки обработки ресурсов. Метод Save(url, saveOptions) принимает параметры и сохраняет HTML‑документ с ресурсами в локальный файл, указанный url.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Определите экземпляр класса параметров
	var options = new HTMLSaveOptions();
	// Ограничение обработки страниц
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### См. также

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Параметры сохранения HTML. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveOptions | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Документацию Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(String, MarkdownSaveOptions) Метод

Необходимо указать путь в локальной файловой системе к выходному файлу для сохранения документа. Конструктор MarkdownSaveOptions() создает экземпляр класса [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) с набором свойств. Например, можно задать стиль форматирования markdown, использовать предопределённые параметры, совместимые с GitLab Flavored Markdown, и настроить обработку ресурсов. Метод Save(path, saveOptions) принимает путь в локальной файловой системе к выходному файлу и экземпляр параметров в качестве аргументов и сохраняет HTML как документ Markdown с ресурсами в локальный файл, указанный путем.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Определите экземпляр класса параметров
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### См. также

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный [`URL`](../../url/) для выходного файла. |
| saveOptions | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [документацию](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Save(Url, MarkdownSaveOptions) Метод

Необходимо указать полный путь Url для сохранения документа. Конструктор Url(url) создаёт экземпляр класса [`Url`](../../url/) с указанным url. Конструктор MarkdownSaveOptions() создаёт экземпляр класса [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) с набором свойств. Например, можно задать стиль форматирования Markdown, использовать предопределённые параметры, совместимые с GitLab Flavored Markdown, и настроить обработку ресурсов. Метод Save(url, saveOptions) принимает экземпляры url и параметров сохранения в качестве аргументов и сохраняет документ с ресурсами в локальный файл, указанный url.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Определите экземпляр класса параметров
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### См. также

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Параметры сохранения Markdown. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Сохраняет документ в локальный файл, указанный путём. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | String | Локальный путь к выходному файлу. |
| saveOptions | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [документацию](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `path` не является действительным локальным путем к файлу. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Метод Save(String, MHTMLSaveOptions)

Необходимо указать путь в локальной файловой системе к файлу вывода для сохранения документа. Конструктор MHTMLSaveOptions() инициализирует экземпляр класса [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/), который имеет свойство ResourceHandlingOptions, используемое для настройки обработки ресурсов. Метод Save(path, saveOptions) принимает путь в локальной файловой системе к файлу вывода и экземпляр параметров сохранения в качестве параметров и сохраняет HTML как документ MHTML в локальный файл, указанный в path.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Определите экземпляр класса параметров
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### См. также

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Сохраняет документ в локальный файл, указанный URL. Все ресурсы, использованные в этом документе, будут сохранены в соседнюю папку, имя которой будет сформировано как: output_file_name + \"_files\".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | Локальный URL выходного файла. |
| saveOptions | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [документацию](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Вызывается, если указанный `url` не является действительным локальным URL файла. |

## Примечания

Сохранить HTML

Большинство задач, которые вам нужно выполнить, требуют сохранения документа. После загрузки существующего файла или создания HTML‑документа с нуля, вы можете сохранить изменения, используя один из методов HTMLDocument.Save(). Методы позволяют сохранять HTML в локальный файл, указанный путем, URL или хранилищем вывода. Обратитесь к [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) для получения дополнительной информации о сохранении.

Метод Save(Url, MHTMLSaveOptions)

Необходимо указать полный путь Url для сохранения документа. Конструктор Url(url) создает экземпляр класса [`Url`](../../url/) с указанным url. Конструктор MHTMLSaveOptions() инициализирует экземпляр класса [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/), который имеет свойство ResourceHandlingOptions, используемое для настройки обработки ресурсов. Метод Save(url, saveOptions) принимает url и параметры в качестве аргументов и сохраняет HTML как документ MHTML в локальный файл, указанный в url.

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Примеры

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Определите экземпляр класса параметров
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### См. также

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Сохраняет содержимое документа и ресурсы, используя [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Обработчик ресурсов [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Параметры сохранения MHTML. |

### См. также

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
