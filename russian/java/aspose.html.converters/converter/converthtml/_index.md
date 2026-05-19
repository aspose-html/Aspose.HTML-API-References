---
title: "Converter.ConvertHTML"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Преобразует HTML‑источник, представленный объектом HTMLDocument. Результатом является файл docx, сформированный по пути выходного файла."
type: docs

url: /ru/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Преобразовать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом является файл docx, сформированный по пути выходного файла.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) экземпляр в качестве источника преобразования. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Создать объект конфигурации по умолчанию
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Указать путь к выходному файлу
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Определить объект DocSaveOptions по умолчанию
        var options = new DocSaveOptions();
         
		// Запустить процесс конверсии с объектом конфигурации по умолчанию
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Преобразовать источник HTML, представленный URL. Результат — файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Преобразовать источник HTML, представленный URL. Результат — файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Создать URL на основе пути к входному файлу
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии с объектом конфигурации по умолчанию
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Преобразовать источник HTML, представленный полным путем к файлу, в DOCX. Результат — файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Преобразовать источник HTML, представленный полным путем к файлу, в DOCX. Результат — файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Путь к исходному файлу формы
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Определить объект DocSaveOptions по умолчанию
   var options = new DocSaveOptions();

   // Запустить процесс конверсии с конфигурацией по умолчанию
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Преобразовать HTML‑источник, представленный во встроенном содержимом. Результатом является docx‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Определить объект DocSaveOptions по умолчанию
   	var options = new DocSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Преобразовать HTML‑источник, представленный во встроенном содержимом. Результатом является docx‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Полный путь к файлу docx как результат преобразования. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Определить объект DocSaveOptions по умолчанию
   	var options = new DocSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Преобразовать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Определить встроенный html‑контент
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Создать объект конфигурации по умолчанию
      	var configuration = new Configuration();

      	// Создать HTML‑документ одним из нескольких способов
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Определить путь к результирующему файлу без расширения
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Использовать одну из реализаций ICreateStreamProvider
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Определить объект DocSaveOptions по умолчанию
			var options = new DocSaveOptions();

        	// Запустить процесс конверсии
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Сформировать URL источника
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Определить путь к результирующему файлу без расширения
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать известную реализацию ICreateStreamProvider
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Сформировать URL источника
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Определить путь к результирующему файлу без расширения
   var resultPath = Path.Combine(OutputFolder, "result");

   // Использовать известную реализацию ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Определить объект DocSaveOptions по умолчанию
   var options = new DocSaveOptions();

   // Запустить процесс конверсии с конфигурацией по умолчанию
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

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

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Преобразовать HTML‑источник, представленный полным путём к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Сформировать путь к html‑файлу источника
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Определить путь к результирующему файлу
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать реализацию ICreateStreamProvider по умолчанию
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Определить объект DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Преобразовать HTML‑источник, представленный полным путём к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Сформировать путь к html‑файлу источника
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Определить путь к результирующему файлу
   var resultPath = Path.Combine(OutputFolder, "result");

   // Использовать реализацию ICreateStreamProvider по умолчанию
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Определить объект DocSaveOptions по умолчанию
   var options = new DocSaveOptions();

   // Запустить процесс конверсии с объектом конфигурации по умолчанию
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Преобразовать HTML‑источник, представленный встроенным контентом, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Сформировать встроенный html‑контент
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Определить путь к результирующему файлу
      var resultPath = Path.Combine(OutputFolder, "result");

      // Использовать известную реализацию ICreateStreamProvider, ориентированную на локальные файлы
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Создать экземпляр объекта DocSaveOptions по умолчанию
      var options = new DocSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Преобразовать HTML‑источник, представленный встроенным контентом, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) использование объекта позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация в DOCX

Файл DOCX — это документ Microsoft Word, который обычно содержит текст, но может включать широкий спектр данных, включая таблицы, растровую и векторную графику, видео, звуки и диаграммы. Файл DOCX легко редактировать, он прост в использовании и имеет управляемый размер. Этот формат популярен благодаря разнообразию возможностей, которые он предоставляет пользователям для создания любых типов документов. Этот файловый формат является одним из самых широко используемых и доступен во множестве программ.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с пользовательскими или стандартными настройками. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML в виде результата DOCX с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx), который преобразует HTML в DOCX с высоким качеством, быстро и просто. Просто загрузите, конвертируйте свои файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Сформировать встроенный html‑контент
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Определить путь к результирующему файлу
   var resultPath = Path.Combine(OutputFolder, "result");

   // Использовать известную реализацию ICreateStreamProvider, ориентированную на локальные файлы
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Создать экземпляр объекта DocSaveOptions по умолчанию
   var options = new DocSaveOptions();

   // Запустить процесс конверсии с конфигурацией по умолчанию
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





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

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Преобразовать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом является PDF‑файл, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Путь к исходному файлу формы
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Создать объект конфигурации по умолчанию
      var configuration = new Configuration();

      // Создайте HTML‑документ одним из нескольких способов
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Путь к файлу результата формы
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Определите объект PdfSaveOptions по умолчанию
        var options = new PdfSaveOptions();

		// Создайте экземпляр процесса конвертации
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Преобразовать HTML‑источник, представленный по URL. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Сформируйте URL источника на основе файла
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Путь к файлу результата формы
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Определите объект PdfSaveOptions по умолчанию
      var options = new PdfSaveOptions();

      // Запустить процесс конверсии
      Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Преобразовать HTML‑источник, представленный по URL. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Сформируйте URL источника на основе файла
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Определите объект PdfSaveOptions по умолчанию
   var options = new PdfSaveOptions();

   // Запустить процесс конверсии с объектом конфигурации по умолчанию
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Преобразовать источник HTML, представленный полным путем к файлу, в PDF. Результат — файл pdf, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Путь к исходному файлу формы
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Определите объект PdfSaveOptions по умолчанию
   var options = new PdfSaveOptions();

   // Запустить процесс конверсии
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Преобразовать источник HTML, представленный полным путем к файлу, в PDF. Результат — файл pdf, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Путь к исходному файлу формы
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Путь к файлу результата формы
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Определите объект PdfSaveOptions по умолчанию
  var options = new PdfSaveOptions();

  // Запустить процесс конверсии с конфигурацией по умолчанию
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в PDF. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Определите объект PdfSaveOptions по умолчанию
   	var options = new PdfSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в PDF. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Полный путь к pdf‑файлу как результат конвертации. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Определите объект PdfSaveOptions по умолчанию
  	var options = new PdfSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Конвертировать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/) в PDF. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Определить встроенный html‑контент
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Создать объект конфигурации по умолчанию
   	var configuration = new Configuration();

   	// Создать HTML‑документ одним из нескольких способов
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Определить путь к результирующему файлу без расширения
		var resultPath = Path.Combine(OutputFolder, "result");

		// Использовать одну из реализаций ICreateStreamProvider
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Определите объект PdfSaveOptions по умолчанию
		var options = new PdfSaveOptions();

		// Запустить процесс конверсии
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Создать URL на основе пути к входному файлу
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result");

   // Использовать одну из реализаций ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Определите объект PdfSaveOptions по умолчанию
   var options = new PdfSaveOptions();

   // Запустить процесс конверсии
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Создать URL на основе пути к входному файлу
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Использовать одну из реализаций ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Определите объект PdfSaveOptions по умолчанию
   var options = new PdfSaveOptions();

   // Запустить процесс конверсии с конфигурацией по умолчанию
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

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

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Конвертировать HTML‑источник, указанный полным путём к файлу, в PDF. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Создайте путь к исходному файлу
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Путь к файлу результата формы
   var resultPath = Path.Combine(OutputFolder, "result");

   // Использовать одну из реализаций ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Определите объект PdfSaveOptions по умолчанию
   var options = new PdfSaveOptions();

   // Запустить процесс конверсии
   Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Конвертировать HTML‑источник, указанный полным путём к файлу, в PDF. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Создайте путь к исходному файлу
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Путь к файлу результата формы
  var resultPath = Path.Combine(OutputFolder, "result");

  // Использовать одну из реализаций ICreateStreamProvider
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Определите объект PdfSaveOptions по умолчанию
  var options = new PdfSaveOptions();

  // Запустить процесс конверсии с конфигурацией по умолчанию
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Конвертировать HTML‑источник, представленный встроенным содержимым, в PDF. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Использовать одну из реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Определите объект PdfSaveOptions по умолчанию
  	var options = new PdfSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Конвертировать HTML‑источник, представленный встроенным содержимым, в PDF. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование объекта [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как конвертировать HTML в PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация PDF

Portable Document Format (PDF) — это тип документа, созданный компанией Adobe в 1990‑х годах. Цель этого формата файлов заключалась в том, чтобы ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. PDF‑файл представляет собой набор байтов, которые могут быть сгруппированы в токены в соответствии с синтаксическими правилами, определёнными спецификациями PDF. Один или несколько токенов объединяются в более высокоуровневые синтаксические сущности, в основном объекты, которые являются базовыми значениями данных, из которых строится PDF‑документ.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Другие популярные конвертации форматов

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как PDF‑результат с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) который конвертирует HTML в PDF с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Использовать одну из реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Определите объект PdfSaveOptions по умолчанию
 	var options = new PdfSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Конвертировать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом является файл mhtml (.mht), сформированный по пути к файлу вывода.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Сформировать HTML‑документ
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Создать HTML‑документ одним из нескольких способов
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Определить объект MHTMLSaveOptions по умолчанию
 		var options = new MHTMLSaveOptions();

		// Путь к файлу результата формы
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Запустить процесс конверсии
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Преобразовать источник HTML, представленный URL. Результат — файл mhtml (.mht), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Определить объект MHTMLSaveOptions по умолчанию
	var options = new MHTMLSaveOptions();

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Преобразовать источник HTML, представленный URL. Результат — файл mhtml (.mht), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Определить объект MHTMLSaveOptions по умолчанию
	var options = new MHTMLSaveOptions();

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Преобразовать источник HTML, представленный полным путем к файлу, в MHTML. Результат — файл mhtml (.mht), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Определить объект MHTMLSaveOptions по умолчанию
	var options = new MHTMLSaveOptions();

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Преобразовать источник HTML, представленный полным путем к файлу, в MHTML. Результат — файл mhtml (.mht), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Определить объект MHTMLSaveOptions по умолчанию
	var options = new MHTMLSaveOptions();

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в MHTML. Результатом является файл mhtml (.mht), сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержание в качестве источника конвертации или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конвертации. Укажите путь к результирующему файлу вывода или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или стандартными настройками. Также можно добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опций. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как результат MHTML с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
  	var options = new MHTMLSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в MHTML. Результатом является файл mhtml (.mht), сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MHTMLSaveOptions | Использование объекта [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Полный путь к файлу mhtml (.mht) как результат конвертации. |

## Примечания

Как конвертировать HTML в MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Конвертировать HTML в MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата MHTML с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) который конвертирует HTML в MHTML с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
 	var options = new MHTMLSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Преобразовать исходный HTML, представленный объектом [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом будет файл markdown (.md), сформированный по пути к выходному файлу.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Путь к исходному файлу формы
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Путь к файлу результата формы
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Определить экземпляр объекта параметров сохранения
			var options = new MarkdownSaveOptions();

			// Запустить процесс конверсии
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Преобразовать источник HTML, представленный URL. Результат — файл markdown (.md), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Путь к файлу результата формы
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Определить экземпляр объекта параметров сохранения
	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Преобразовать источник HTML, представленный URL. Результат — файл markdown (.md), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Путь к файлу результата формы
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Определить экземпляр объекта параметров сохранения
	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Преобразовать источник HTML, представленный полным путем к файлу, в Markdown. Результат — файл markdown (.md), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Путь к файлу результата формы
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Определить экземпляр объекта параметров сохранения
	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Преобразовать источник HTML, представленный полным путем к файлу, в Markdown. Результат — файл markdown (.md), сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Путь к файлу результата формы
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Определить экземпляр объекта параметров сохранения
	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в Markdown. Результатом является файл mhtml (.mht), сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
  	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в Markdown. Результатом является файл mhtml (.mht), сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | MarkdownSaveOptions | Использование объекта [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Полный путь к файлу md в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Другие популярные конвертации форматов

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата Markdown с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md), который преобразует HTML в MD с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
 	var options = new MarkdownSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Преобразовать исходный HTML, представленный объектом [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом будет файл xps, сформированный по пути к выходному файлу.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Путь к исходному файлу формы
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Путь к файлу результата формы
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Создать HTML‑документ одним из нескольких способов
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Определить экземпляр объекта параметров сохранения
        	var options = new XpsSaveOptions();

        	// Запустить процесс конверсии
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Преобразовать HTML‑источник, представленный по URL. Результатом является xps‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Путь к файлу результата формы
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, outputPath);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Преобразовать HTML‑источник, представленный по URL. Результатом является xps‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Путь к файлу результата формы
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
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

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Преобразовать источник HTML, представленный полным путем к файлу, в XPS. Результат — файл xps, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Путь к файлу результата формы
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Преобразовать источник HTML, представленный полным путем к файлу, в XPS. Результат — файл xps, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Путь к файлу результата формы
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
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

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в XPS. Результатом является xps‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. Для получения дополнительной информации см. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
  	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в XPS. Результатом является xps‑файл, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| outputPath | String | Полный путь к файлу xps в качестве результата конверсии. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Определить объект параметров сохранения по умолчанию
 	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Преобразовать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Создать HTML‑документ одним из нескольких способов
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Определить экземпляр объекта параметров сохранения
    	var options = new XpsSaveOptions();

		// Используйте одну из известных реализаций ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Запустить процесс конверсии
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML‑документа — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Использовать одну из реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Использовать одну из реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Преобразовать исходный HTML, представленный полным путём к файлу, в XPS. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Использовать одну из реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Преобразовать исходный HTML, представленный полным путём к файлу, в XPS. Результатом являются данные вывода, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Использовать одну из реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Определить экземпляр объекта параметров сохранения
	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Преобразовать HTML‑источник, представленный встроенным содержимым, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в XPS](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Использовать одну из реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Определить объект параметров сохранения по умолчанию
  	var options = new XpsSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Преобразовать HTML‑источник, представленный встроенным содержимым, в XPS. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Использование объекта [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Преобразование в XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Преобразовать HTML в XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Источник конверсии. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конверсии. Вы также можете задать встроенное HTML‑содержимое в качестве источника конверсии или создать HTML‑документ (HTMLDocument) любым способом. Результат конверсии. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера данных вывода. Создайте новый объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с пользовательскими или параметрами по умолчанию. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter для сохранения HTML как результата XPS с тремя или более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑инструмент [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps), который преобразует HTML в XPS с высоким качеством, быстро и просто. Просто загрузите файлы, выполните конверсию и получите результаты за несколько секунд!

Попробуйте использовать другие популярные конвертации форматов

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Использовать одну из реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Определить объект параметров сохранения по умолчанию
 	var options = new XpsSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Преобразовать HTML‑источник, представленный объектом [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом будет файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "source.html");

// Путь к файлу результата формы
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Запустить процесс конверсии
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Преобразовать источник HTML, представленный URL. Результат — файл изображения, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Преобразовать источник HTML, представленный URL. Результат — файл изображения, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Преобразовать источник HTML, представленный полным путем к файлу, в изображение. Результат — файл изображения, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Чтобы узнать больше о классе [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), пожалуйста, прочитайте статью [Тонкая настройка конвертеров](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Определите экземпляр объекта параметров сохранения. По умолчанию формат изображения — PNG.
	var options = new ImageSaveOptions();

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Преобразовать источник HTML, представленный полным путем к файлу, в изображение. Результат — файл изображения, сформированный путем к выходному файлу.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Чтобы узнать больше о классе [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), пожалуйста, прочитайте статью [Тонкая настройка конвертеров](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Определите экземпляр объекта параметров сохранения. По умолчанию формат изображения — PNG.
	var options = new ImageSaveOptions();

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Новые сформированные параметры изображения, такие как формат, разрешение и т.д. См. класс [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [Документацию Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Определить объект параметров сохранения по умолчанию
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Преобразовать HTML‑источник, представленный во встроенном содержимом, в изображение. Результатом является файл изображения, сформированный по пути выходного файла.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Новые сформированные параметры изображения, такие как формат, разрешение и т.д. См. класс [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) и [Документацию Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Определить объект параметров сохранения по умолчанию
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Преобразовать HTML‑источник, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | HTMLDocument | Источник конвертации, представленный [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Использование объекта [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) позволяет настроить процесс рендеринга. |
| provider | ICreateStreamProvider | Реализация [`интерфейса`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result");

	// Создать HTML‑документ одним из нескольких способов
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Определить экземпляр объекта параметров сохранения
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Использовать одну из реализаций ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Запустить процесс конверсии
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Путь к файлу результата формы
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Использовать одну из реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Преобразовать HTML‑источник, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL исходного HTML — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документации Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Создать URL на основе пути к входному файлу
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Использовать одну из реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Преобразовать HTML‑источник, представленный полным путем к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Полный путь к исходному HTML‑файлу. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документации Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Путь к файлу результата формы
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Используйте одну из известных реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Преобразовать HTML‑источник, представленный полным путем к файлу, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документации Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Путь к исходному файлу формы
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Путь к файлу результата формы
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Определить экземпляр объекта параметров сохранения
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Используйте одну из известных реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Преобразовать HTML‑источник, представленный встроенным содержимым, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Известная (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Определить объект параметров сохранения по умолчанию
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Используйте одну из известных реализаций ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Преобразовать HTML‑источник, представленный встроенным содержимым, в изображение. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Строка как встроенный html‑контент. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration `](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), которая будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документации Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать HTML в изображение

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Основная особенность Aspose.HTML — функция конвертации. Преобразование между форматами требуется по разным причинам: для работы в знакомом, удобном формате или для использования различных форматов для конкретных задач. Пакет com.aspose.html.converters обеспечивает простой доступ к методам конвертации. Он предоставляет широкий спектр HTML‑конвертаций в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), и [MD](https://docs.fileformat.com/word-processing/md/).

В этой статье представлена информация о списке поддерживаемых HTML‑конвертаций и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по HTML Converter вы найдёте следующие статьи:

Конвертация изображений

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Другие популярные конвертации форматов

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Преобразовать HTML в изображение

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Источник конвертации. Обнаружьте существующий локальный HTML‑файл или удалённый URL в качестве источника конвертации. Вы также можете задать встроенное HTML‑содержимое как источник конвертации или создать HTML‑документ (HTMLDocument) любым способом. Результат конвертации. Укажите путь к выходному файлу результата или используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). По умолчанию свойство Format имеет значение PNG. Вы также можете добавить [`configuration`](../../../com.aspose.html/configuration/) в качестве параметра опции. Используйте метод ConvertHTML() класса Converter, чтобы сохранить HTML как изображение с тремя и более параметрами в зависимости от сценария пользователя. Онлайн‑конвертеры HTML

Aspose.HTML предлагает бесплатный онлайн‑конвертер [HTML в PNG](https://products.aspose.app/html/en/conversion/html-to-png), который преобразует HTML в изображения с высоким качеством, просто и быстро. Просто загрузите, конвертируйте файлы и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Формировать встроенный html‑контент		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Путь к файлу результата формы
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Определить объект параметров сохранения по умолчанию
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Используйте одну из известных реализаций ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Запустить процесс конверсии с конфигурацией по умолчанию
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | HTMLDocument | Источник конвертации. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |
| конфигурация | Конфигурация | Конфигурация среды. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному HTML‑файлу. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| конфигурация | Конфигурация | Конфигурация среды. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Встроенное строковое HTML‑содержимое. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Преобразовать документ html в текст. Результат — файл TXT.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Встроенное строковое HTML‑содержимое. |
| baseUri | String | Базовый URI документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| конфигурация | Конфигурация | Конфигурация среды. |
| options | TextSaveOptions | Параметры конвертации. |
| outputPath | String | Путь к выходному файлу. |

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
