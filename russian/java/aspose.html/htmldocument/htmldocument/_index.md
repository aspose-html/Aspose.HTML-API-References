---
title: "HTMLDocument"
second_title: "Справочник API Aspose.HTML для Java"
description: "Конструктор HTMLDocument. Конструктор HTMLDocument создает новый объект HTML Document, который представляет веб‑страницу, загруженную в браузере, и служит точкой входа в содержимое страницы."
type: docs

url: /ru/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Конструктор HTMLDocument создает новый объект HTML Document, представляющий веб‑страницу, загруженную в браузере, и служащий точкой входа в содержимое страницы.

```java
public HTMLDocument()
```

## Примечания

Примечание: Документ создаётся со значением свойства base-url по умолчанию, равным 'about:blank'.

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

После создания объекта документа его можно позже заполнять элементами HTML. Следующий фрагмент кода демонстрирует использование конструктора HTMLDocument() по умолчанию для создания пустого HTML‑документа и сохранения его в файл.

```java
import (var document = new HTMLDocument())
{
	// Работайте с документом здесь
	...	
	
	// Сохраните документ в файл
	document.Save("document.html");
}
```

### См. также

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Конструктор HTMLDocument создает новый объект HTML Document, представляющий веб‑страницу, загруженную в браузере, и служащий точкой входа в содержимое страницы.

```java
public HTMLDocument(Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

## Примечания

Примечание: Документ создаётся со значением свойства base-url по умолчанию, равным 'about:blank'.

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

Следующий пример демонстрирует, как использовать объект конфигурации для отключения скриптов:

```java
// Подготовьте HTML‑код и сохраните его в файл
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Создайте экземпляр Configuration
import (var configuration = new Configuration())
{
	// Пометьте 'scripts' как ненадёжный ресурс
	configuration.Security |= Sandbox.Scripts;

	// Инициализируйте HTML‑документ с указанной конфигурацией
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Конвертировать HTML в PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### См. также

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Загружает HTML‑документ из URL.

Примечание: Если передать неверный URL, который недоступен в данный момент, библиотека генерирует [`DOMException`](../../../com.aspose.html.dom/domexception/) со специализированным кодом ‘NetworkError’, информируя вас о том, что выбранный ресурс не найден.

```java
public HTMLDocument(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL HTML‑документа для открытия. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

Загрузить документ со страницы 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Записать содержимое документа в выходной поток
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### См. также

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Загружает HTML‑документ из URL с указанными настройками конфигурации среды.

Примечание: Если передать неверный URL, который недоступен в данный момент, библиотека генерирует [DOMException](T:com.aspose.html.dom.DOMException) со специализированным кодом ‘NetworkError’, информируя вас о том, что выбранный ресурс не найден.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL HTML‑документа для открытия. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Подготовьте HTML‑код и сохраните его в файл
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Создайте экземпляр Configuration
import (var configuration = new Configuration())
{
	// Пометьте 'scripts' как ненадёжный ресурс
	configuration.Security |= Sandbox.Scripts;

	// Инициализируйте HTML‑документ с указанной конфигурацией
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Конвертировать HTML в PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Загружает HTML‑документ по адресу.

Примечание: Если передать неверный URL, который недоступен в данный момент, библиотека генерирует [`DOMException`](../../../com.aspose.html.dom/domexception/) со специализированным кодом ‘NetworkError’, информируя вас о том, что выбранный ресурс не найден.

```java
public HTMLDocument(String address)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| адрес | String | Адрес HTML‑документа для открытия. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

Инициализировать HTML‑документ из адреса.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### См. также

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Загружает HTML‑документ по адресу с указанными настройками конфигурации среды.

Примечание: Если передать неверный URL, который недоступен в данный момент, библиотека генерирует [`DOMException`](../../../com.aspose.html.dom/domexception/) со специализированным кодом ‘NetworkError’, информируя вас о том, что выбранный ресурс не найден.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| адрес | String | Адрес HTML‑документа для открытия. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Создайте экземпляр Configuration
import (var configuration = new Configuration())
{
	// Пометьте 'scripts' как ненадёжный ресурс
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### См. также

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Создаёт HTML‑документ из строкового содержимого с указанным базовым URI.

```java
public HTMLDocument(String content, String baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строковое содержимое, с помощью которого загружается документ. |
| baseUri | String | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Подготовьте HTML‑код
var html_code = "<p>Hello World!</p>";

// Инициализируйте документ из переменной типа String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### См. также

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Создаёт HTML‑документ из строкового содержимого с указанным базовым URI и настройками конфигурации среды.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строковое содержимое, с помощью которого загружается документ. |
| baseUri | String | Базовый URI документа. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Подготовьте HTML‑код
var html_code = "<p>Hello World!</p>";

// Инициализируйте документ из переменной типа String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### См. также

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Создаёт HTML‑документ из строкового содержимого с указанным базовым URI.

```java
public HTMLDocument(String content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строковое содержимое, с помощью которого загружается документ. |
| baseUri | Url | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Подготовьте HTML‑код
var html_code = "<p>Hello World!</p>";

// Инициализируйте документ из переменной типа String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### См. также

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Создаёт HTML‑документ из строкового содержимого с указанным базовым URI и настройками конфигурации среды.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строковое содержимое, с помощью которого загружается документ. |
| baseUri | Url | Базовый URI документа. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Подготовьте HTML‑код
var html_code = "<p>Hello World!</p>";

// Инициализируйте документ из переменной типа String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI, который используется для разрешения путей относительных ресурсов.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream), с помощью которого загружается документ. |
| baseUri | String | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Создать объект поток памяти
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Записать HTML‑код в объект памяти
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Инициализируйте документ из переменной типа String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### См. также

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI и настройками конфигурации среды.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream), с помощью которого загружается документ. |
| baseUri | String | Базовый URI документа. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Создать объект поток памяти
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Записать HTML‑код в объект памяти
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Инициализируйте документ из переменной типа String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### См. также

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI, который используется для разрешения путей относительных ресурсов.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream), с помощью которого загружается документ. |
| baseUri | Url | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Создать объект поток памяти
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Записать HTML‑код в объект памяти
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Инициализируйте документ из переменной типа String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### См. также

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Создаёт HTML‑документ из содержимого [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) с указанным базовым URI и настройками конфигурации среды.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream), с помощью которого загружается документ. |
| baseUri | Url | Базовый URI документа. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, если параметр base-uri равен null. |

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Примеры

```java
// Создать объект поток памяти
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Записать HTML‑код в объект памяти
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Инициализируйте документ из переменной типа String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Creates an HTML document from the [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) object.

```java
public HTMLDocument(RequestMessage request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [`body`](../../../com.aspose.html.net/requestmessage/content/) with document content. |

## Примечания

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### См. также

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Создаёт HTML‑документ из объекта [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [body](P:com.aspose.html.net.RequestMessage.Content) with document content. |
| конфигурация | Конфигурация | Конфигурация среды, такая как политика скриптов, пользовательская таблица стилей и т.д. |

## Примечания

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### См. также

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
