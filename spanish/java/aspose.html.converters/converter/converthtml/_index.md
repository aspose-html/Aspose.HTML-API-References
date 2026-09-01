---
title: "Converter.ConvertHTML"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Converter. Convierte la fuente HTML presentada por HTMLDocument. El resultado es un archivo docx creado en la ruta de archivo de salida."
type: docs

url: /es/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Convierte la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo docx creado en la ruta de salida.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Instancia de [`HTMLDocument`](../../../com.aspose.html/htmldocument/) como fuente de conversión. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Instanciar objeto de configuración predeterminado
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Definir ruta del archivo de salida
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Definir objeto DocSaveOptions predeterminado
        var options = new DocSaveOptions();
         
		// Iniciar proceso de conversión con el objeto de configuración predeterminado
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Convertir la fuente HTML presentada por URL. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Crear Url basado en la ruta del archivo de entrada
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Convertir la fuente HTML presentada por URL. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Crear Url basado en la ruta del archivo de entrada
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con el objeto de configuración predeterminado
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Convertir la fuente HTML presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Ruta del archivo fuente del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Convertir la fuente HTML presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Ruta del archivo fuente del formulario
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Definir objeto DocSaveOptions predeterminado
   var options = new DocSaveOptions();

   // Iniciar proceso de conversión con la configuración predeterminada
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Convertir la fuente HTML presentada por contenido en línea. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Definir objeto DocSaveOptions predeterminado
   	var options = new DocSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Convertir la fuente HTML presentada por contenido en línea. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Definir objeto DocSaveOptions predeterminado
   	var options = new DocSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Definir contenido html en línea
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Instanciar objeto de configuración predeterminado
      	var configuration = new Configuration();

      	// Crear documento HTML de una de varias maneras
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Definir la ruta del archivo de resultado sin extensión
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Usar una de las implementaciones de ICreateStreamProvider
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Definir objeto DocSaveOptions predeterminado
			var options = new DocSaveOptions();

        	// Iniciar proceso de conversión
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Formar URL de origen
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Definir la ruta del archivo de resultado sin extensión
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una implementación conocida de ICreateStreamProvider
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Formar URL de origen
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Definir la ruta del archivo de resultado sin extensión
   var resultPath = Path.Combine(OutputFolder, "result");

   // Usar una implementación conocida de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definir objeto DocSaveOptions predeterminado
   var options = new DocSaveOptions();

   // Iniciar proceso de conversión con la configuración predeterminada
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

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

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Convertir la fuente HTML presentada por la ruta completa del archivo a DOCX. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formar ruta del archivo html de origen
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Definir la ruta del archivo de resultado
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar la implementación predeterminada de ICreateStreamProvider
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Convertir la fuente HTML presentada por la ruta completa del archivo a DOCX. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formar ruta del archivo html de origen
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Definir la ruta del archivo de resultado
   var resultPath = Path.Combine(OutputFolder, "result");

   // Usar la implementación predeterminada de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definir objeto DocSaveOptions predeterminado
   var options = new DocSaveOptions();

   // Iniciar proceso de conversión con el objeto de configuración predeterminado
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Convertir la fuente HTML presentada por contenido en línea a DOCX. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Formar contenido html en línea
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Definir la ruta del archivo de resultado
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una implementación conocida de ICreateStreamProvider orientada a archivos locales
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instanciar el objeto predeterminado DocSaveOptions
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Convertir la fuente HTML presentada por contenido en línea a DOCX. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a DOCX

Un archivo DOCX es un documento de Microsoft Word que típicamente contiene texto, pero puede contener una amplia gama de datos, incluyendo tablas, gráficos raster y vectoriales, video, sonidos y diagramas. El archivo DOCX es altamente editable, fácil de usar y manejable en tamaño. Este formato es popular debido a la variedad de opciones que ofrece a los usuarios para crear cualquier tipo de documento. Este formato de archivo es uno de los más ampliamente utilizados y está disponible a través de numerosos programas.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Origen de la conversión. Detecte un archivo HTML local existente o una URL remota como origen de la conversión. Incluso puede definir contenido HTML en línea como origen de la conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado DOCX con tres o más parámetros, según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un convertidor en línea gratuito [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) que convierte HTML a DOCX con alta calidad, fácil y rápido. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Formar contenido html en línea
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Definir la ruta del archivo de resultado
   var resultPath = Path.Combine(OutputFolder, "result");

   // Usar una implementación conocida de ICreateStreamProvider orientada a archivos locales
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instanciar el objeto predeterminado DocSaveOptions
   var options = new DocSaveOptions();

   // Iniciar proceso de conversión con la configuración predeterminada
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





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

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Ruta del archivo fuente del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Instanciar objeto de configuración predeterminado
      var configuration = new Configuration();

      // Cree un documento html de una de varias maneras
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Ruta del archivo de resultado del formulario
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Defina el objeto PdfSaveOptions predeterminado
        var options = new PdfSaveOptions();

		// Instanciar proceso de conversión
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Convertir la fuente HTML presentada por URL. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Formar URL de origen basada en archivo
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Convertir la fuente HTML presentada por URL. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Formar URL de origen basada en archivo
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Defina el objeto PdfSaveOptions predeterminado
   var options = new PdfSaveOptions();

   // Iniciar proceso de conversión con el objeto de configuración predeterminado
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Convertir la fuente HTML presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Ruta del archivo fuente del formulario
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Defina el objeto PdfSaveOptions predeterminado
   var options = new PdfSaveOptions();

   // Iniciar proceso de conversión
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Convertir la fuente HTML presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Ruta del archivo fuente del formulario
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Ruta del archivo de resultado del formulario
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Defina el objeto PdfSaveOptions predeterminado
  var options = new PdfSaveOptions();

  // Iniciar proceso de conversión con la configuración predeterminada
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Convertir la fuente HTML presentada por contenido en línea a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Defina el objeto PdfSaveOptions predeterminado
   	var options = new PdfSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Convertir la fuente HTML presentada por contenido en línea a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Defina el objeto PdfSaveOptions predeterminado
  	var options = new PdfSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/) a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Definir contenido html en línea
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Instanciar objeto de configuración predeterminado
   	var configuration = new Configuration();

   	// Crear documento HTML de una de varias maneras
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Definir la ruta del archivo de resultado sin extensión
		var resultPath = Path.Combine(OutputFolder, "result");

		// Usar una de las implementaciones de ICreateStreamProvider
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Defina el objeto PdfSaveOptions predeterminado
		var options = new PdfSaveOptions();

		// Iniciar proceso de conversión
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Crear Url basado en la ruta del archivo de entrada
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result");

   // Usar una de las implementaciones de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Defina el objeto PdfSaveOptions predeterminado
   var options = new PdfSaveOptions();

   // Iniciar proceso de conversión
   Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Crear Url basado en la ruta del archivo de entrada
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Usar una de las implementaciones de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Defina el objeto PdfSaveOptions predeterminado
   var options = new PdfSaveOptions();

   // Iniciar proceso de conversión con la configuración predeterminada
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Convertir la fuente HTML presentada por la ruta completa del archivo a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Crear ruta del archivo de origen
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Ruta del archivo de resultado del formulario
   var resultPath = Path.Combine(OutputFolder, "result");

   // Usar una de las implementaciones de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Defina el objeto PdfSaveOptions predeterminado
   var options = new PdfSaveOptions();

   // Iniciar proceso de conversión
   Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Convertir la fuente HTML presentada por la ruta completa del archivo a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Crear ruta del archivo de origen
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Ruta del archivo de resultado del formulario
  var resultPath = Path.Combine(OutputFolder, "result");

  // Usar una de las implementaciones de ICreateStreamProvider
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Defina el objeto PdfSaveOptions predeterminado
  var options = new PdfSaveOptions();

  // Iniciar proceso de conversión con la configuración predeterminada
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Convertir la fuente HTML presentada por contenido en línea a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Usar una de las implementaciones de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Defina el objeto PdfSaveOptions predeterminado
  	var options = new PdfSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Convertir la fuente HTML presentada por contenido en línea a PDF. El resultado es datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión de PDF

Portable Document Format (PDF) es un tipo de documento creado por Adobe a finales de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Un archivo PDF es un conjunto de bytes que pueden agruparse en tokens según las reglas de sintaxis definidas por las especificaciones PDF. Uno o más tokens se combinan para formar entidades sintácticas de nivel superior, principalmente objetos, que son los valores de datos básicos a partir de los cuales se construye un documento PDF.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Otras conversiones de formatos populares

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a PDF](https://products.aspose.app/html/en/conversion/html-to-pdf) en línea gratuito que convierte HTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Usar una de las implementaciones de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Defina el objeto PdfSaveOptions predeterminado
 	var options = new PdfSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo mhtml (.mht) generado a partir de la ruta del archivo de salida.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar documento HTML
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Crear documento HTML de una de varias maneras
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Definir objeto MHTMLSaveOptions predeterminado
 		var options = new MHTMLSaveOptions();

		// Ruta del archivo de resultado del formulario
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Iniciar proceso de conversión
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Convertir la fuente HTML presentada por URL. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definir objeto MHTMLSaveOptions predeterminado
	var options = new MHTMLSaveOptions();

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Convertir la fuente HTML presentada por URL. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definir objeto MHTMLSaveOptions predeterminado
	var options = new MHTMLSaveOptions();

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Convertir la fuente HTML presentada por ruta de archivo completa a MHTML. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definir objeto MHTMLSaveOptions predeterminado
	var options = new MHTMLSaveOptions();

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Convertir la fuente HTML presentada por ruta de archivo completa a MHTML. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definir objeto MHTMLSaveOptions predeterminado
	var options = new MHTMLSaveOptions();

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Convertir la fuente HTML presentada por contenido en línea a MHTML. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede añadir la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
  	var options = new MHTMLSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Convertir la fuente HTML presentada por contenido en línea a MHTML. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo mhtml (.mht) como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado MHTML con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml) en línea gratuito que convierte HTML a MHTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
 	var options = new MHTMLSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo markdown (.md) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Ruta del archivo fuente del formulario
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Ruta del archivo de resultado del formulario
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Definir instancia del objeto de opciones de guardado
			var options = new MarkdownSaveOptions();

			// Iniciar proceso de conversión
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Convertir la fuente HTML presentada por URL. El resultado es un archivo markdown (.md) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Ruta del archivo de resultado del formulario
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definir instancia del objeto de opciones de guardado
	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Convertir la fuente HTML presentada por URL. El resultado es un archivo markdown (.md) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Ruta del archivo de resultado del formulario
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definir instancia del objeto de opciones de guardado
	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Convertir la fuente HTML presentada por ruta de archivo completa a Markdown. El resultado es un archivo markdown (.md) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Ruta del archivo de resultado del formulario
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definir instancia del objeto de opciones de guardado
	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Convertir la fuente HTML presentada por ruta de archivo completa a Markdown. El resultado es un archivo markdown (.md) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Ruta del archivo de resultado del formulario
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definir instancia del objeto de opciones de guardado
	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Convertir la fuente HTML presentada por contenido en línea a Markdown. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
  	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Convertir la fuente HTML presentada por contenido en línea a Markdown. El resultado es un archivo mhtml (.mht) formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo md como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Otras conversiones de formatos populares

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado Markdown con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [HTML a Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en línea gratuito que convierte HTML a MD con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
 	var options = new MarkdownSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Ruta del archivo fuente del formulario
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Ruta del archivo de resultado del formulario
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Crear documento HTML de una de varias maneras
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Definir instancia del objeto de opciones de guardado
        	var options = new XpsSaveOptions();

        	// Iniciar proceso de conversión
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Convertir la fuente HTML presentada por URL. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Ruta del archivo de resultado del formulario
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Convertir la fuente HTML presentada por URL. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Ruta del archivo de resultado del formulario
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
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

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Convertir la fuente HTML presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Ruta del archivo de resultado del formulario
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Convertir la fuente HTML presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Ruta del archivo de resultado del formulario
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
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

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Convertir la fuente HTML presentada por contenido en línea a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información consulte la [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
  	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Convertir la fuente HTML presentada por contenido en línea a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definir objeto de opciones de guardado predeterminado
 	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Crear documento HTML de una de varias maneras
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Definir instancia del objeto de opciones de guardado
    	var options = new XpsSaveOptions();

		// Utilice una de las implementaciones conocidas de ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Iniciar proceso de conversión
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL del documento fuente HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Usar una de las implementaciones de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL de origen HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Usar una de las implementaciones de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Convertir la fuente HTML presentada por la ruta completa del archivo a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Usar una de las implementaciones de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Convertir la fuente HTML presentada por la ruta completa del archivo a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Usar una de las implementaciones de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definir instancia del objeto de opciones de guardado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Convertir la fuente HTML presentada mediante contenido en línea a XPS. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) que convierte HTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Usar una de las implementaciones de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definir objeto de opciones de guardado predeterminado
  	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Convertir la fuente HTML presentada mediante contenido en línea a XPS. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversión a XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML a XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida del resultado o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones personalizadas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Utilice el método ConvertHTML() de la clase Converter para guardar HTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un [Convertidor de HTML a XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en línea gratuito que convierte HTML a XPS con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Intente usar otras conversiones de formatos populares

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Usar una de las implementaciones de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definir objeto de opciones de guardado predeterminado
 	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Convertir la fuente HTML presentada mediante [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Ruta del archivo fuente del formulario
var sourcePath = Path.Combine(InputFolder, "source.html");

// Ruta del archivo de resultado del formulario
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Convertir la fuente HTML presentada por URL. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL de origen HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Convertir la fuente HTML presentada por URL. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL de origen HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Convertir la fuente HTML presentada por ruta de archivo completa a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | Para obtener más información sobre la clase [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), lea el artículo [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Defina la instancia del objeto de opciones de guardado. PNG es el formato de imagen por defecto.
	var options = new ImageSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Convertir la fuente HTML presentada por ruta de archivo completa a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | Para obtener más información sobre la clase [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), lea el artículo [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Defina la instancia del objeto de opciones de guardado. PNG es el formato de imagen por defecto.
	var options = new ImageSaveOptions();

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Convertir la fuente HTML presentada por contenido en línea a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | Nuevas opciones de imagen creadas, como formato, resolución, etc. Vea la clase [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definir objeto de opciones de guardado predeterminado
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Convertir la fuente HTML presentada por contenido en línea a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | Nuevas opciones de imagen creadas, como formato, resolución, etc. Vea la clase [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definir objeto de opciones de guardado predeterminado
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Convertir la fuente HTML presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | HTMLDocument | Fuente de conversión presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result");

	// Crear documento HTML de una de varias maneras
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Definir instancia del objeto de opciones de guardado
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Usar una de las implementaciones de ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Iniciar proceso de conversión
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL de origen HTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Ruta del archivo de resultado del formulario
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Usar una de las implementaciones de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Convertir la fuente HTML presentada por URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL de origen HTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Crear Url basado en la ruta del archivo de entrada
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Usar una de las implementaciones de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Convertir la fuente HTML presentada mediante la ruta completa del archivo a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente HTML. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Ruta del archivo de resultado del formulario
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilice una de las implementaciones conocidas de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Convertir la fuente HTML presentada mediante la ruta completa del archivo a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la interfaz, que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Ruta del archivo de resultado del formulario
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definir instancia del objeto de opciones de guardado
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilice una de las implementaciones conocidas de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Convertir la fuente HTML presentada mediante contenido en línea a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definir objeto de opciones de guardado predeterminado
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilice una de las implementaciones conocidas de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Convertir la fuente HTML presentada mediante contenido en línea a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido html en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration `](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno de la aplicación. |
| options | ImageSaveOptions | El uso del objeto ImageSaveOptions le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. Más información sobre los proveedores en la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Observaciones

Cómo convertir HTML a Imagen

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

El principal punto destacado de Aspose.HTML es la función de conversión. Convertir entre formatos es necesario por diversas razones: trabajar en un formato familiar y conveniente o aprovechar diferentes formatos para tareas específicas. El paquete com.aspose.html.converters implementa un acceso fácil a los métodos de conversión. Proporciona una amplia gama de conversiones de HTML a formatos populares, como [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), y [MD](https://docs.fileformat.com/word-processing/md/).

Este artículo brinda información sobre la lista de conversiones HTML compatibles y cómo realizarlas usando la clase [`Converter`](../) que agrupa todas las operaciones de conversión de bajo nivel en una sola clase para que sean cómodas y fáciles de usar. En la guía del Conversor HTML, encontrará los siguientes artículos:

Conversiones de imágenes

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Otras conversiones de formatos populares

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir HTML a Imagen

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecte un archivo HTML local existente o una URL remota como fuente de conversión. Incluso puede definir contenido HTML en línea como fuente de conversión o crear un documento HTML (HTMLDocument) de cualquier manera. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con el [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requerido. Por defecto, la propiedad Format es PNG. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertHTML() de la clase Converter para guardar HTML como una imagen con tres o más parámetros según el escenario del usuario. Convertidores HTML en línea

Aspose.HTML ofrece un conversor en línea gratuito [HTML a PNG](https://products.aspose.app/html/en/conversion/html-to-png) que convierte HTML a imágenes con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

También puede estar interesado en la conversión de formatos de imagen específicos

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formar contenido html en línea		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definir objeto de opciones de guardado predeterminado
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilice una de las implementaciones conocidas de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Iniciar proceso de conversión con la configuración predeterminada
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | HTMLDocument | Fuente de conversión. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento. |
| configuración | Configuración | La configuración del entorno. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta de origen del archivo HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuración | Configuración | La configuración del entorno. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Contenido HTML de cadena en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Convertir documento html a texto. El resultado es un archivo TXT.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Contenido HTML de cadena en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuración | Configuración | La configuración del entorno. |
| opciones | TextSaveOptions | Opciones de conversión. |
| outputPath | Cadena | Ruta del archivo de salida. |

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
