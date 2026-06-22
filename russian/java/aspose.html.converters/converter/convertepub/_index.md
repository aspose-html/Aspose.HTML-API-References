---
title: "Converter.ConvertEPUB"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Converter. Преобразовать источник EPUB, представленный входным потоком данных. Результатом является файл, сформированный по пути к выходному файлу."
type: docs

url: /ru/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом является файл, сформированный по пути выходного файла.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| options | ImageSaveOptions | Новые сформированные параметры изображения, такие как формат, разрешение и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) и [документацию Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Откройте существующий файл для чтения как поток
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Указать путь к выходному файлу
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Определите экземпляр параметров по умолчанию
var options = new ImageSaveOptions();

// Запустить процесс конверсии
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Преобразовать источник EPUB, представленный полным путем к файлу. Результатом является файл изображения, сформированный путем к выходному файлу. Формат изображения задаётся объектом ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB в качестве входного параметра. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Определите экземпляр объекта ImageSaveOptions по умолчанию
var options = new ImageSaveOptions(); 

// Запустить процесс конверсии
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Преобразовать источник EPUB, определённый URL. Результатом является файл изображения, сформированный путем к выходному файлу. Формат изображения задаётся объектом ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Создать Url на основе пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Определите экземпляр параметров по умолчанию
var options = new ImageSaveOptions();

// Запустить процесс конверсии
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Преобразовать источник EPUB, представленный потоком ввода данных. Результатом является файл изображения, сформированный путем к выходному файлу. Формат изображения задаётся объектом ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Откройте существующий файл для чтения как поток
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Указать путь к выходному файлу
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Определите экземпляр параметров по умолчанию
var options = new ImageSaveOptions();

// Запустить процесс конверсии с объектом конфигурации по умолчанию
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Преобразовать источник EPUB, представленный полным путем к файлу. Результатом является файл изображения, сформированный путем к выходному файлу. Формат изображения задаётся объектом ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB в качестве входного параметра. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Определите экземпляр объекта ImageSaveOptions по умолчанию
var options = new ImageSaveOptions(); 

// Запустить процесс конверсии с объектом конфигурации по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Преобразовать источник EPUB, определённый URL. Результатом является файл изображения, сформированный путем к выходному файлу. Формат изображения задаётся объектом ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [размер страницы](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [поля](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), и т.д. См. [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) класс. |
| outputPath | String | Полный путь к файлу изображения в качестве результата конвертации. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Определите URL на основе существующего файла EPUB по указанному пути. Определите путь к результирующему файлу вывода. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Также необходимо передать объекты ImageSaveOptions и Configuration для конвертации в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Создать Url на основе пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Указать путь к выходному файлу
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Определите экземпляр параметров по умолчанию
var options = new ImageSaveOptions(); 

// Запустить процесс конверсии с объектом конфигурации по умолчанию
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Преобразуйте исходный epub, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0), в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, который будет использоваться для получения выходного потока. См. расширенный пример в [Документация Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) в качестве буфера выходных данных. Создайте новый объект [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Создайте экземпляр параметров по умолчанию  
var options = new ImageSaveOptions();    

// Запустите процесс конвертации  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Преобразуйте источник EPUB, указанный путем к файлу, в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | ImageSaveOptions | Новые сформированные параметры изображения, такие как формат, разрешение и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) и [документацию Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документация Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Создайте новый объект ImageSaveOptions с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

EPUB в JPG за две строки кода

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Откройте существующий файл EPUB для чтения.
import var stream = File.OpenRead(DataDir + "input.epub");

// Вызовите метод ConvertEPUB, чтобы преобразовать код EPUB в изображение JPG
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### См. также

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Преобразуйте источник EPUB, представленный по URL, в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. класс [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. Дополнительную информацию о провайдерах см. в [Документация Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Создайте новый объект ImageSaveOptions с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Создайте экземпляр параметров по умолчанию  
var options = new ImageSaveOptions();

// Запустите процесс конвертации  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Преобразуйте исходный epub, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0), в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| провайдер | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Создайте новый объект ImageSaveOptions с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Создайте экземпляр параметров по умолчанию  
var options = new ImageSaveOptions();    


// Инициализируйте процесс конвертации с конфигурацией по умолчанию.
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Преобразуйте источник EPUB, указанный путем к файлу, в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Источник EPUB, определённый путем к файлу. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. См. пример реализации ICreateStreamProvider в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Создайте новый объект ImageSaveOptions с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Определите экземпляр объекта ImageSaveOptions по умолчанию
var options = new ImageSaveOptions(); 

// Запустить процесс конверсии с объектом конфигурации по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Преобразовать источник epub, представленный по URL, в изображение. Результатом является файл изображения, сформированный реализацией интерфейса [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | ImageSaveOptions | Использование объекта ImageSaveOptions позволяет настроить процесс рендеринга. Вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. См. пример реализации ICreateStreamProvider в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Примечания

Как преобразовать EPUB в изображение

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он был создан Международным форумом цифровой публикации (IDPF) и теперь поддерживается многими читалками и программными приложениями.

Преобразование файлов EPUB в формат PNG может быть полезным, если вам нужно включить их в презентацию PowerPoint или отправить по электронной почте. Пожалуйста, преобразуйте их в формат изображения и используйте по своему усмотрению! Вы можете использовать дополнительные параметры конвертации для получения желаемого результата.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса Converter, который группирует все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB вы найдёте следующие статьи:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Преобразовать EPUB в изображение

Чтобы преобразовать EPUB в формат файлов изображения, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В примере мы используем метод OpenRead() класса System.IO.FileStream для открытия и чтения файла EPUB из файловой системы по указанному пути. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Создайте новый объект ImageSaveOptions с требуемым ImageFormat. По умолчанию свойство Format равно PNG. Используйте метод ConvertEPUB() класса Converter, чтобы сохранить EPUB как изображение. Необходимо передать EPUB inputStream, ImageSaveOptions и выходной поток в метод ConvertEPUB() для конвертации EPUB в изображение. Онлайн‑конвертеры EPUB

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB в PNG](https://products.aspose.app/html/en/conversion/epub-to-png), который преобразует EPUB в PNG‑изображение с высоким качеством, легко и быстро. Просто загрузите файлы, выполните конвертацию и получите результаты за несколько секунд!

Возможно, вас также заинтересует конвертация конкретных форматов изображений

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Создайте экземпляр параметров по умолчанию  
var options = new ImageSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Преобразовать источник epub, представленный входным потоком, в xps. Результатом является файл xps, определённый полным путем.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток в качестве источника конвертации. См. спецификацию Stream в [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Параметры конвертации. Использование объекта [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем указать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — указать путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать источник EPUB, XpsSaveOptions и буфер выходных данных в любой форме для инициации процесса конвертации. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Откройте существующий файл EPUB для чтения
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Подготовьте путь для сохранения конвертированного файла
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Создайте экземпляр XpsSaveOptions. Установите размер страницы и измените цвет фона на LightGray
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Вызовите метод ConvertEPUB, чтобы преобразовать EPUB в XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Преобразовать источник epub, представленный путем к входному файлу EPUB, в xps. Результатом является файл xps, определённый полным путем.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Параметры конвертации. Использование объекта [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем указать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — указать путь к файлу результата. Создайте объект [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать источник EPUB, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), и буфер выходных данных в любой форме для инициации процесса конвертации. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Преобразовать источник epub, представленный URL, в файл xps, определённый полным путем. См. [Документация Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Параметры конвертации. Использование объекта [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации.

Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Преобразовать источник epub, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0), в xps. Результатом является файл xps, определённый полным путем.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. Использование объекта [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Откройте существующий файл EPUB для чтения
import var stream = File.OpenRead(DataDir + "input.epub");

// Подготовьте путь для сохранения преобразованного файла 
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Инициализируйте XpsSaveOptions 
var options = new XpsSaveOptions();
   
// Вызовите метод ConvertEPUB, чтобы преобразовать EPUB в XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Преобразовать источник epub, представленный путем к входному файлу EPUB, в xps. Результатом является файл xps, определённый полным путем.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) объект позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Преобразовать источник epub, представленный URL, в файл xps, определённый полным путем. См. [Документация Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) объект позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. |
| outputPath | String | Полный путь к файлу .xps как результат конвертации. |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустите процесс конвертации с конфигурацией по умолчанию 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Конвертировать источник epub, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0), в xps. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| options | XpsSaveOptions | Параметры конвертации. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. См. пример реализации ICreateStreamProvider в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Создайте экземпляр MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Откройте существующий файл EPUB для чтения
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Подготовьте путь для сохранения конвертированного файла
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Конвертируйте EPUB в XPS, используя класс MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Получите доступ к MemoryStream, содержащему результирующие данные
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Сбросьте результирующие данные в выходной файл
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### См. также

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Конвертировать источник epub, представленный путем к входному файлу EPUB, в xps. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | XpsSaveOptions | Параметры конвертации. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) объект позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. |
| provider | ICreateStreamProvider | Реализация интерфейса, который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем указать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — указать путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать источник EPUB, XpsSaveOptions и буфер выходных данных в любой форме для инициации процесса конвертации. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Конвертировать источник epub, представленный URL, в файл xps, определённый полным путём. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | XpsSaveOptions | Параметры конвертации. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Конвертировать источник epub, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0), в xps. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. |
| provider | ICreateStreamProvider | Реализация [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) интерфейса, который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Конвертировать источник epub, представленный путем к входному файлу EPUB, в xps. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. Использование объекта [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. |
| provider | ICreateStreamProvider | Реализация [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) интерфейса, который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Конвертировать источник epub, представленный URL, в файл xps, определённый полным путём. Результатом являются данные вывода xps, определённые известной или пользовательской реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | XpsSaveOptions | Параметры конвертации. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) объект позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Реализация [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) интерфейса, который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в XPS

Файл XPS представляет собой файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания макета, внешнего вида и информации о печати документа.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в одном классе, делая их удобными и простыми в использовании. В руководстве по EPUB Converter XPS вы найдёте следующую статью:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Конвертировать EPUB в XPS

Чтобы конвертировать EPUB в формат XPS, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Для примера мы можем задать путь к исходному файлу в качестве первого параметра метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно использовать более простой вариант — путь к файлу результата. Создайте объект XpsSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса XpsSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB в файл xps. Необходимо передать исходные данные EPUB, XpsSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект [`configuration`](../../../com.aspose.html/configuration/) контекста, который используется для настройки параметров среды приложения. Онлайн-конвертер EPUB в XPS

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) , который преобразует EPUB в файл XPS с высоким качеством, быстро и просто. Просто загрузите, конвертируйте файлы и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Создайте экземпляр параметров по умолчанию  
var options = new XpsSaveOptions();

// Запустить процесс конверсии с конфигурацией по умолчанию
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Конвертировать файл источника EPUB, указанный полным путём, в DOCX. Результатом является файл docx, определённый полным путём.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Источник конвертации, представленный входным [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();   

// Запустить процесс конверсии
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Преобразовать источник EPUB, представленный полным путем к файлу, в DOCX. Результатом является файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB в качестве входного параметра. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Определите экземпляр параметров по умолчанию
var options = new DocSaveOptions();

// Запустить процесс конвертации
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Преобразовать источник EPUB, представленный URL. Результатом является файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | Использование [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Определите экземпляр параметров по умолчанию
var options = new DocSaveOptions();

// Запустить процесс конвертации
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Преобразовать источник EPUB, представленный потоком ввода данных. Результатом является файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();   

// Запустите процесс конвертации с конфигурацией по умолчанию 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Преобразовать источник EPUB, представленный полным путем к файлу, в DOCX. Результатом является файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Определите экземпляр параметров по умолчанию
var options = new DocSaveOptions();

// Запустить процесс конвертации с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Преобразовать источник EPUB, представленный URL. Результатом является файл docx, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Полный путь к файлу .docx в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Путь к файлу результата конвертации формы
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();

// Инициализируйте процесс конвертации с конфигурацией по умолчанию.
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Конвертировать источник EPUB в виде входного потока в DOCX. Результатом является файл docx, сформированный реализацией ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();   

// Запустить процесс конверсии
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Конвертировать источник EPUB, указанный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions ();   

// Запустите процесс конвертации  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Преобразовать источник EPUB, представленный URL. Результатом являются выходные данные, сформированные реализацией интерфейса ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | DocSaveOptions | Использование [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, разрешения, CSS и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — указать путь к результирующему файлу. Создайте новый объект DocSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Сформировать URL источника по пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions ();   

// Запустить процесс конверсии
Converter.ConvertEPUB(sourceUrl, options, sp);





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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Преобразовать источник EPUB, представленный потоком ввода данных. Результатом являются выходные данные, сформированные реализацией интерфейса ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также воспользоваться более простым вариантом — указать путь к результирующему файлу. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();   

// Запустите процесс конвертации с конфигурацией по умолчанию 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Конвертировать источник EPUB, указанный полным путем к файлу, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Параметры конвертации. Использование объекта [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также воспользоваться более простым вариантом — указать путь к результирующему файлу. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions ();   

// Запустите процесс конвертации  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Конвертировать источник EPUB, указанный URL, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | DocSaveOptions | Использование [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в DOCX

DOCX — это широко известный формат документов Microsoft Word. Этот формат популярен, потому что поддерживает широкий набор возможностей форматирования и предлагает пользователям разнообразные варианты создания любого типа документа. Файлы DOCX можно открывать в Word 2007 и более поздних версиях, но не в более ранних версиях MS Word, которые поддерживают расширения файлов DOC. Конвертация EPUB в DOCX часто требуется, чтобы воспользоваться форматом DOCX для конкретных задач пользователей.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе представлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как их выполнить с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конвертеру EPUB в DOCX вы найдете следующую статью:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в DOCX

Чтобы конвертировать EPUB в формат DOCX, следует выполнить несколько шагов:

Откройте существующий файл EPUB. Например, мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также воспользоваться более простым вариантом — указать путь к результирующему файлу. Создайте новый объект [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр класса DocSaveOptions по умолчанию. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как файл docx. Необходимо передать источник EPUB в виде пути к файлу или входного потока, а также Url, экземпляр DocSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать configuration, представляющий объект контекста [`configuration`](../../../com.aspose.html/configuration/) который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в DOCX

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Converter, который преобразует EPUB в файл DOCX с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Создайте экземпляр параметров по умолчанию  
var options = new DocSaveOptions();   

// Запустите процесс конвертации с конфигурацией по умолчанию 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Путь к исходному файлу EPUB в качестве входного параметра. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Путь к результирующему файлу  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions();   

// Запустите процесс конвертации  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Преобразовать источник EPUB, представленный полным путем к файлу, в PDF. Результатом является файл pdf, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Определите экземпляр параметров по умолчанию
var options = new PdfSaveOptions();

// Запустить процесс конвертации
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### См. также

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Преобразовать источник EPUB, представленный URL. Результатом является файл pdf, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Создать Url на основе пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Определите экземпляр параметров по умолчанию
var options = new com.aspose.html.saving.PdfSaveOptions();

// Запустить процесс конвертации
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Путь к результирующему файлу  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions();   

// Запустите процесс конвертации с конфигурацией по умолчанию 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом является pdf‑файл, сформированный по пути выходного файла.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Путь к исходному файлу формы
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Определите экземпляр параметров по умолчанию
var options = new PdfSaveOptions();

// Запустить процесс конвертации с конфигурацией по умолчанию
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### См. также

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Преобразовать источник EPUB, представленный URL. Результатом является файл pdf, сформированный путем к выходному файлу.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Полный путь к файлу .pdf в качестве результата конвертации. |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Сформируйте путь к результирующему файлу вывода
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Определите экземпляр параметров по умолчанию
var options = new PdfSaveOptions();

// Запустить процесс конвертации с конфигурацией по умолчанию
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Известно (см. [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) или пользовательская реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions ();   

// Запустите процесс конвертации  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Конвертировать источник EPUB, представленный полным путём к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions();   

// Запустите процесс конвертации  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Конвертировать источник EPUB, указанный URL, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| options | PdfSaveOptions | Использование [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Определите экземпляр параметров по умолчанию
var options = new PdfSaveOptions();

// Запустить процесс конверсии
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Конвертировать источник EPUB, представленный входным потоком данных. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Stream | Входной поток в качестве источника конвертации. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главной особенностью Aspose.HTML является функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет [`com.aspose.html.converters`](../) предоставляет простой доступ к методам конвертации. Он предлагает широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Откройте существующий файл для чтения как поток  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions ();   

// Запустить процесс конвертации с объектом конфигурации по умолчанию  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Преобразовать источник EPUB, представленный полным путем к файлу, в PDF. Результатом являются выходные данные, сформированные реализацией интерфейса ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourcePath | String | Путь к исходному файлу EPUB. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Параметры конвертации. Использование объекта [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) позволяет настроить процесс рендеринга; вы можете указать размер страницы, поля, CSS и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Создайте экземпляр параметров по умолчанию  
var options = new PdfSaveOptions();   

// Запустить процесс конвертации с объектом конфигурации по умолчанию 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Конвертировать источник EPUB, указанный URL, в DOCX. Результатом являются выходные данные, сформированные реализацией интерфейса [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceUrl | Url | URL источника EPUB — предоставляет объектное представление универсального идентификатора (URL). |
| configuration | Configuration | Конфигурация окружения. Представляет объект контекста [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration), который используется для настройки параметров окружения приложения. |
| options | PdfSaveOptions | Использование [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) позволяет настроить процесс рендеринга; вы можете указать [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), и т.д. См. [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Реализация интерфейса [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), который будет использоваться для получения выходного потока. См. расширенный пример в [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Примечания

Как конвертировать EPUB в PDF

EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций. Он создан Международным форумом цифровых публикаций ([IDPF](http://idpf.org/)) и теперь поддерживается многими электронными читалками и программными приложениями. Конвертация EPUB в PDF часто требуется, чтобы воспользоваться форматом PDF. Формат PDF полностью поддерживает хранение информации такой как текст, изображения, гиперссылки, поля форм, мультимедиа, метаданные и т.д. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer и в большинстве современных браузеров, таких как Chrome, Safari, Firefox. Они оптимизированы для печати и идеально подходят для создания физических копий ваших документов; также можно настроить параметры безопасности PDF.

Главная особенность Aspose.HTML — функция конвертации. EPUB — открытый XML‑основанный формат для цифровых книг и публикаций, который можно просматривать и читать на смартфонах, планшетах и компьютерах. Пакет com.aspose.html.converters реализует простой доступ к методам конвертации. Он предоставляет широкий спектр конвертаций [EPUB](https://docs.fileformat.com/ebook/epub/) в популярные форматы, такие как [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), и [GIF](https://docs.fileformat.com/image/gif/).

В этом разделе предоставлена информация о списке поддерживаемых сценариев конвертации EPUB и о том, как выполнять их с помощью класса [`Converter`](../), который объединяет все низкоуровневые операции конвертации в один класс, делая их удобными и простыми в использовании. В руководстве по конкретному использованию EPUB Converter PDF вы найдёте следующую статью:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Конвертировать EPUB в PDF

Чтобы конвертировать EPUB в формат PDF, следует выполнить несколько шагов:

Откройте существующий файл EPUB. В качестве примера мы можем задать путь к исходному файлу как первый параметр метода ConvertEPUB. В качестве альтернативы можно использовать поток ввода или объект Url. Используйте известную или пользовательскую реализацию интерфейса ICreateStreamProvider в качестве буфера выходных данных. Можно также использовать более простой вариант — путь к файлу результата. Создайте новый объект PdfSaveOptions с набором предпочтительных параметров, таких как размер страницы, поля, CSS и т.д. Можно использовать экземпляр по умолчанию класса PdfSaveOptions. Вызовите метод ConvertEPUB() статического класса Converter, чтобы сохранить EPUB как PDF‑файл. Необходимо передать источник EPUB в виде пути к файлу или потока ввода, а также Url, экземпляр PdfSaveOptions и буфер выходных данных в любой форме для запуска процесса конвертации. Вы можете использовать конфигурацию, представляющую объект контекста [`configuration`](../../../com.aspose.html/configuration/), который используется для настройки параметров среды приложения. Онлайн‑конвертер EPUB в PDF

Aspose.HTML предлагает бесплатный онлайн‑конвертер [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf), который преобразует EPUB в PDF‑файл с высоким качеством, быстро и просто. Просто загрузите файлы, конвертируйте их и получите результаты через несколько секунд!

Исходный код

Вы можете скачать полные примеры и файлы данных с [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Примеры

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Создать Url на основе пути к входному файлу
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Обратитесь к реализации интерфейса ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Определите экземпляр параметров по умолчанию
var options = new PdfSaveOptions();

// Запустить процесс конверсии с объектом конфигурации по умолчанию
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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
