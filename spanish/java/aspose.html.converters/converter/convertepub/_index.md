---
title: "Converter.ConvertEPUB"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Converter. Convierta la fuente EPUB presentada mediante un stream de entrada de datos. El resultado es un archivo formado por la ruta del archivo de salida."
type: docs

url: /es/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo generado por la ruta de archivo de salida.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| options | ImageSaveOptions | Nuevas opciones de imagen creadas, como formato, resolución, etc. Vea la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) y la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Abrir archivo existente para leer como flujo
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definir ruta del archivo de salida
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definir instancia de opciones predeterminadas
var options = new ImageSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Convertir la fuente EPUB presentada por ruta de archivo completa. El resultado es un archivo de imagen creado a partir de la ruta de archivo de salida. El formato de imagen se especifica mediante el objeto ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB como parámetro de entrada. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definir instancia predeterminada del objeto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Convertir la fuente EPUB definida por URL. El resultado es un archivo de imagen creado a partir de la ruta de archivo de salida. El formato de imagen se especifica mediante el objeto ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definir instancia de opciones predeterminadas
var options = new ImageSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo de imagen creado a partir de la ruta de archivo de salida. El formato de imagen se especifica mediante el objeto ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Abrir archivo existente para leer como flujo
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Definir ruta del archivo de salida
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definir instancia de opciones predeterminadas
var options = new ImageSaveOptions();

// Iniciar proceso de conversión con el objeto de configuración predeterminado
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Convertir la fuente EPUB presentada por ruta de archivo completa. El resultado es un archivo de imagen creado a partir de la ruta de archivo de salida. El formato de imagen se especifica mediante el objeto ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB como parámetro de entrada. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definir instancia predeterminada del objeto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Iniciar proceso de conversión con el objeto de configuración predeterminado
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Convertir la fuente EPUB definida por URL. El resultado es un archivo de imagen creado a partir de la ruta de archivo de salida. El formato de imagen se especifica mediante el objeto ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [tamaño de página](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), los [márgenes](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), el [tipo de medio CSS](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), etc. Consulte la clase [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Defina la URL basada en el archivo EPUB existente en la ruta especificada. Defina la ruta del archivo de salida resultante. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. También necesita pasar el objeto ImageSaveOptions y el objeto Configuration a la conversión de imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Definir ruta del archivo de salida
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Definir instancia de opciones predeterminadas
var options = new ImageSaveOptions(); 

// Iniciar proceso de conversión con el objeto de configuración predeterminado
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Convertir la fuente EPUB presentada por el [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) de entrada a una imagen. El resultado es un archivo de imagen generado mediante la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crear instancia de opciones predeterminadas  
var options = new ImageSaveOptions();    

// Iniciar proceso de conversión  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Convertir la fuente EPUB presentada por la ruta del archivo a una imagen. El resultado es un archivo de imagen generado mediante la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | Nuevas opciones de imagen creadas, como formato, resolución, etc. Vea la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) y la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Cree un nuevo objeto ImageSaveOptions con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

EPUB a JPG en dos líneas de código

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Abrir un archivo EPUB existente para leer.
import var stream = File.OpenRead(DataDir + "input.epub");

// Invoca el método ConvertEPUB para convertir el código EPUB a una imagen JPG      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Convierte la fuente epub presentada por URL a una imagen. El resultado es un archivo de imagen formado por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la clase [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Cree un nuevo objeto ImageSaveOptions con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crear instancia de opciones predeterminadas  
var options = new ImageSaveOptions();

// Iniciar proceso de conversión  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Convertir la fuente EPUB presentada por el [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) de entrada a una imagen. El resultado es un archivo de imagen generado mediante la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| proveedor | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Cree un nuevo objeto ImageSaveOptions con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Crear instancia de opciones predeterminadas  
var options = new ImageSaveOptions();    


// Inicia el proceso de conversión con la configuración predeterminada  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Convierte la fuente epub presentada por ruta de archivo a una imagen. El resultado es un archivo de imagen formado por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Fuente EPUB definida por ruta de archivo. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Ver ejemplo de implementación de ICreateStreamProvider en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Cree un nuevo objeto ImageSaveOptions con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Definir instancia predeterminada del objeto ImageSaveOptions
var options = new ImageSaveOptions(); 

// Iniciar proceso de conversión con el objeto de configuración predeterminado
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Convertir la fuente epub presentada por URL a imagen. El resultado es un archivo de imagen formado por la implementación de la interfaz [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Ver ejemplo de implementación de ICreateStreamProvider en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a Imagen

EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar. Fue creado por el International Digital Publishing Forum (IDPF) y ahora es compatible con muchos lectores electrónicos y aplicaciones de software.

Convertir archivos EPUB al formato PNG puede ser útil si necesita incluir archivos en una presentación de PowerPoint o enviarlos por correo electrónico. ¡Conviértalos al formato de imagen y úselos como desee! Puede usar parámetros de conversión adicionales para obtener el resultado deseado.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección brinda información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando una clase Converter que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Convertidor de EPUB, encontrará los siguientes artículos:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB a Imagen

Para convertir EPUB al formato de archivo de imagen, debe seguir algunos pasos:

Abrir un archivo EPUB existente. En el ejemplo, utilizamos el método OpenRead() de la clase System.IO.FileStream para abrir y leer un archivo EPUB del sistema de archivos en la ruta especificada. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Cree un nuevo objeto ImageSaveOptions con el ImageFormat requerido. Por defecto, la propiedad Format es PNG. Utilice el método ConvertEPUB() de la clase Converter para guardar el EPUB como una imagen. Necesita pasar el inputStream del EPUB, ImageSaveOptions y el flujo de salida al método ConvertEPUB() para la conversión de EPUB a imagen. Convertidores EPUB en línea

Aspose.HTML ofrece un convertidor en línea gratuito [EPUB a PNG](https://products.aspose.app/html/en/conversion/epub-to-png) que convierte EPUB a una imagen PNG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Crear instancia de opciones predeterminadas  
var options = new ImageSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Convertir la fuente epub presentada por flujo de entrada a xps. El resultado es un archivo xps definido por ruta completa.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de entrada como fuente de conversión. Ver la especificación de Stream en la [fuente oficial](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el tamaño de página, márgenes, CSS, etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utilizar una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crear un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilizar el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha de origen del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Conversor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Abrir un archivo EPUB existente para lectura
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Prepare una ruta para guardar el archivo convertido 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Cree una instancia de XpsSaveOptions. Configure el tamaño de página y cambie el color de fondo a LightGray 
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
   
  // Llame al método ConvertEPUB para convertir EPUB a XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Convertir la fuente epub presentada por ruta de archivo EPUB de entrada a xps. El resultado es un archivo xps definido por ruta completa.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utilizar una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crear un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilizar el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha de origen del EPUB, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Conversor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Convertir la fuente epub presentada por URL a archivo xps definido por ruta completa. Ver [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión.

Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Convertir la fuente epub presentada por [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) de entrada a xps. El resultado es un archivo xps definido por ruta completa.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Abrir un archivo EPUB existente para lectura
import var stream = File.OpenRead(DataDir + "input.epub");

// Prepare una ruta para guardar el archivo convertido
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Inicialice XpsSaveOptions
var options = new XpsSaveOptions();
   
// Llame al método ConvertEPUB para convertir EPUB a XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Convertir la fuente epub presentada por ruta de archivo EPUB de entrada a xps. El resultado es un archivo xps definido por ruta completa.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) permite ajustar el proceso de renderizado; puede especificar el tamaño de página, los márgenes, CSS, etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Convertir la fuente epub presentada por URL a archivo xps definido por ruta completa. Ver [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) permite ajustar el proceso de renderizado; puede especificar el tamaño de página, los márgenes, CSS, etc. |
| outputPath | Cadena | Ruta completa del archivo .xps como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Inicie el proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Convierta la fuente EPUB presentada mediante la entrada [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) a xps. El resultado es datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Vea el ejemplo de implementación de ICreateStreamProvider en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Cree una instancia de MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Abrir un archivo EPUB existente para lectura
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Prepare una ruta para guardar el archivo convertido 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Convierta EPUB a XPS usando la clase MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Obtenga acceso al flujo de memoria que contiene los datos resultantes
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Vacíe los datos resultantes al archivo de salida
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Convierta la fuente EPUB presentada mediante la ruta del archivo EPUB de entrada a xps. El resultado son datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) permite ajustar el proceso de renderizado; puede especificar el tamaño de página, los márgenes, CSS, etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Vea un ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utilizar una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crear un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilizar el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha de origen del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Conversor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Convierta la fuente EPUB presentada mediante una URL a un archivo xps definido por una ruta completa. El resultado son datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) permite ajustar el proceso de renderizado; puede especificar el tamaño de página, los márgenes, CSS, etc. Vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Vea un ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Convierta la fuente EPUB presentada mediante la entrada [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) a xps. El resultado es datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Vea un ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Convierta la fuente EPUB presentada mediante la ruta del archivo EPUB de entrada a xps. El resultado son datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el tamaño de página, márgenes, CSS, etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Vea un ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Convierta la fuente EPUB presentada mediante una URL a un archivo xps definido por una ruta completa. El resultado son datos de salida xps definidos por una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | Opciones de conversión. El uso del objeto [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) permite ajustar el proceso de renderizado; puede especificar el [`tamaño de página`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`márgenes`](../../../com.aspose.html.drawing/page/margin/), el [`tipo de medio CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Vea un ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a XPS

Un archivo XPS representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a XPS, encontrará el siguiente artículo:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB a XPS

Para convertir el formato de archivo EPUB a XPS, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Use una implementación conocida o personalizada de la interfaz `ICreateStreamProvider` como búfer de datos de salida. Podemos usar una alternativa más simple como ruta de archivo de salida resultante. Cree un nuevo objeto XpsSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase XpsSaveOptions. Utilice el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo xps. Necesita pasar la fecha fuente del EPUB, XpsSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer los ajustes del entorno para la aplicación. Convertidor en línea de EPUB a XPS

Aspose.HTML ofrece un conversor en línea gratuito de [EPUB a XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Crear instancia de opciones predeterminadas  
var options = new XpsSaveOptions();

// Iniciar proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Convertir el archivo fuente EPUB presentado por ruta completa a DOCX. El resultado es un archivo docx definido por la ruta completa.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Fuente de conversión presentada mediante la entrada [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Ver la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();   

// Iniciar proceso de conversión
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Convertir la fuente EPUB presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB como parámetro de entrada. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definir instancia de opciones predeterminadas
var options = new DocSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Convertir la fuente EPUB presentada por URL. El resultado es un archivo docx creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), las [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definir instancia de opciones predeterminadas
var options = new DocSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo docx creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Ver la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();   

// Inicie el proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Convertir la fuente EPUB presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) permite afinar el proceso de renderizado; puedes especificar el tamaño de página, los márgenes, CSS, etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definir instancia de opciones predeterminadas
var options = new DocSaveOptions();

// Iniciar proceso de conversión con configuración predeterminada
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Convertir la fuente EPUB presentada por URL. El resultado es un archivo docx creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), las [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .docx como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Ruta del archivo de resultado de la conversión del formulario
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();

// Inicia el proceso de conversión con la configuración predeterminada  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Convertir la fuente EPUB como flujo de entrada a DOCX. El resultado es un archivo docx generado por la implementación de ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Ver la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();   

// Iniciar proceso de conversión
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Convertir la fuente EPUB presentada mediante la ruta completa del archivo a DOCX. El resultado es datos de salida generados por la implementación de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Ver la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions ();   

// Iniciar proceso de conversión  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Convertir la fuente EPUB presentada por URL. El resultado son datos de salida generados por la implementación de la interfaz ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el tamaño de página, los márgenes, las resoluciones, CSS, etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto DocSaveOptions con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Forma la URL de origen mediante la ruta de archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions ();   

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado son datos de salida generados por la implementación de la interfaz ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), las [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();   

// Inicie el proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Convertir la fuente EPUB presentada mediante la ruta completa del archivo a DOCX. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | Opciones de conversión. El uso del objeto [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Ver la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions ();   

// Iniciar proceso de conversión  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Convertir la fuente EPUB presentada mediante URL. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | DocSaveOptions | El uso de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), las [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) que se utilizará para obtener un flujo de salida. Consulta el ejemplo avanzado en la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a DOCX

DOCX es un formato bien conocido para documentos de Microsoft Word. Este formato es popular porque admite una amplia gama de características de formato y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento. Los archivos DOCX pueden abrirse con Word 2007 y versiones posteriores, pero no con las versiones anteriores de MS Word, que solo admiten extensiones de archivo DOC. La conversión de EPUB a DOCX suele ser necesaria para aprovechar el formato DOCX en tareas específicas del usuario.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo realizarlos usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a DOCX, encontrarás el siguiente artículo:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a DOCX

Para convertir el formato de archivo EPUB a DOCX, debes seguir algunos pasos:

Abrir un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como primer parámetro del método ConvertEPUB. Utiliza una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como ruta de archivo de salida resultante. Crea un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con varios parámetros preferidos como tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase DocSaveOptions. Usa el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo docx. Necesitas pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia de DocSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puedes usar la configuración que representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. Conversor EPUB a DOCX en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) que convierte EPUB a archivo DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente carga, convierte tus archivos y obtén los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Crear instancia de opciones predeterminadas  
var options = new DocSaveOptions();   

// Inicie el proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo pdf generado por la ruta de archivo de salida.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Ruta del archivo fuente EPUB como parámetro de entrada. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Ruta del archivo de resultado del formulario  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions();   

// Iniciar proceso de conversión  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Convertir la fuente EPUB presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objeto con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definir instancia de opciones predeterminadas
var options = new PdfSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Convertir la fuente EPUB presentada por URL. El resultado es un archivo pdf creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), los [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definir instancia de opciones predeterminadas
var options = new com.aspose.html.saving.PdfSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo pdf generado por la ruta de archivo de salida.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Ruta del archivo de resultado del formulario  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions();   

// Inicie el proceso de conversión con la configuración predeterminada
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Convertir la fuente EPUB presentada por flujo de datos de entrada. El resultado es un archivo pdf generado por la ruta de archivo de salida.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definir instancia de opciones predeterminadas
var options = new PdfSaveOptions();

// Iniciar proceso de conversión con configuración predeterminada
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Convertir la fuente EPUB presentada por URL. El resultado es un archivo pdf creado a partir de la ruta de archivo de salida.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | PdfSaveOptions | El uso de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), los [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo .pdf como resultado de la conversión. |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Formar la ruta del archivo de resultado de salida
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definir instancia de opciones predeterminadas
var options = new PdfSaveOptions();

// Iniciar proceso de conversión con configuración predeterminada
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Convertir la fuente EPUB presentada mediante un flujo de entrada de datos. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions ();   

// Iniciar proceso de conversión  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Convertir la fuente EPUB presentada mediante la ruta completa del archivo a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions();   

// Iniciar proceso de conversión  
Converter.ConvertEPUB(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Convertir la fuente EPUB presentada mediante URL. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), los [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definir instancia de opciones predeterminadas
var options = new PdfSaveOptions();

// Iniciar proceso de conversión
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Convertir la fuente EPUB presentada mediante un flujo de entrada de datos. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Stream de entrada como origen de la conversión. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) permite afinar el proceso de renderizado; puedes especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulta la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

La principal característica de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que se pueden ver y leer en smartphones, tabletas y computadoras. El paquete [`com.aspose.html.converters`](../) implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Abrir archivo existente para leer como flujo  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions ();   

// Iniciar el proceso de conversión con el objeto de configuración predeterminado  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Convertir la fuente EPUB presentada por ruta de archivo completa a PDF. El resultado son datos de salida generados por la implementación de la interfaz ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente EPUB. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | PdfSaveOptions | Opciones de conversión. El uso del objeto [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) le permite ajustar el proceso de renderizado; puede especificar el tamaño de página, márgenes, CSS, etc. Consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Crear instancia de opciones predeterminadas  
var options = new PdfSaveOptions();   

// Iniciar el proceso de conversión con el objeto de configuración predeterminado 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Convertir la fuente EPUB presentada mediante URL. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL de origen EPUB - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto de [configuración](https://apireference.aspose.com/html/net/aspose.html/configuration) que se utiliza para establecer los ajustes del entorno para la aplicación. |
| options | PdfSaveOptions | El uso de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado; puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), los [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la interfaz [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), que se utilizará para obtener un flujo de salida. Consulte el ejemplo avanzado en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Observaciones

Cómo convertir EPUB a PDF

EPUB es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital. Fue creado por el International Digital Publishing Forum ([IDPF](http://idpf.org/)), y ahora es compatible con muchos lectores electrónicos y aplicaciones de software. La conversión de EPUB a PDF suele ser necesaria para aprovechar el formato PDF. El formato de archivo PDF tiene la capacidad completa de contener información como texto, imágenes, hipervínculos, campos de formulario, medios enriquecidos, metadatos, etc. Los archivos PDF pueden abrirse en Adobe Acrobat Reader/Writer y en la mayoría de los navegadores modernos como Chrome, Safari, Firefox. Están optimizados para la impresión y son ideales para crear copias físicas de tus documentos; también puedes configurar la seguridad del PDF.

El principal punto destacado de Aspose.HTML es la función de conversión. EPUB es un formato abierto basado en XML para libros y publicaciones digitales, que puede verse y leerse en smartphones, tabletas y computadoras. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de [EPUB](https://docs.fileformat.com/ebook/epub/) a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), y [GIF](https://docs.fileformat.com/image/gif/).

Esta sección proporciona información sobre la lista de escenarios de conversión de EPUB compatibles y cómo ejecutarlos usando una clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una única clase para que sean cómodas y fáciles de usar. En la guía específica del Conversor EPUB a PDF, encontrará el siguiente artículo:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB a PDF

Para convertir el formato de archivo EPUB a PDF, debe seguir algunos pasos:

Abra un archivo EPUB existente. Por ejemplo, podemos definir la ruta del archivo fuente como el primer parámetro del método ConvertEPUB. Como alternativa, podemos usar un flujo de entrada o una instancia de objeto Url. Utilice una implementación conocida o personalizada de la interfaz ICreateStreamProvider como búfer de datos de salida. También podemos usar una alternativa más simple como la ruta del archivo de salida resultante. Cree un nuevo objeto PdfSaveOptions con varios parámetros preferidos como el tamaño de página, márgenes, CSS, etc. Es posible usar la instancia predeterminada de la clase PdfSaveOptions. Use el método ConvertEPUB() de la clase estática Converter para guardar el EPUB como un archivo pdf. Necesita pasar la fuente del EPUB como ruta de archivo o flujo de entrada, así como Url, la instancia PdfSaveOptions y el búfer de datos de salida en cualquier forma para iniciar el proceso de conversión. Puede usar la configuración que representa el [`configuration`](../../../com.aspose.html/configuration/) objeto de contexto que se utiliza para configurar los ajustes del entorno para la aplicación. Conversor EPUB a PDF en línea

Aspose.HTML ofrece un conversor en línea gratuito [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) que convierte archivos EPUB a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Crear Url basado en la ruta del archivo de entrada
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Consultar la implementación de la interfaz ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definir instancia de opciones predeterminadas
var options = new PdfSaveOptions();

// Iniciar proceso de conversión con el objeto de configuración predeterminado
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
