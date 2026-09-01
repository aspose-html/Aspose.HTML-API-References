---
title: "Converter.ConvertMarkdown"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del convertidor. Convierte la fuente markdown MD presentada por el flujo de entrada a html. El resultado es HTMLDocument que puede guardarse mediante la ruta de archivo de salida."
type: docs

url: /es/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Convertir la fuente MD (markdown) presentada por el flujo de entrada a html. El resultado es [`HTMLDocument`](../../../com.aspose.html/htmldocument/) que puede guardarse mediante la ruta de archivo de salida.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Flujo de datos de entrada de conversión MD (Markdown). |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |

### Valor devuelto

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Abrir archivo fuente como flujo
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Iniciar proceso de conversión
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Guardar resultado de la conversión
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Convertir la fuente MD (markdown) presentada por el flujo de entrada a html. El resultado es [`HTMLDocument`](../../../com.aspose.html/htmldocument/) que puede guardarse mediante la ruta de archivo de salida.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Flujo de datos de entrada de conversión MD (Markdown). |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |

### Valor devuelto

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Abrir archivo fuente como flujo
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Guardar resultado de la conversión
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Convertir la fuente MD (markdown) presentada por flujo de entrada a html. El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Flujo de datos de entrada de conversión MD (Markdown). |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| outputPath | Cadena | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Abrir archivo fuente como flujo
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Iniciar proceso de conversión
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Ver también

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Convertir la fuente MD (markdown) presentada por flujo de entrada a html. El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Flujo de datos de entrada de conversión MD (Markdown). |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| outputPath | Cadena | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Abrir archivo fuente como flujo
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Convertir la fuente MD (markdown) presentada por la ruta completa del archivo a html. El resultado es [`HTMLDocument`](../../../com.aspose.html/htmldocument/) que puede guardarse mediante la ruta de archivo de salida.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MD (Markdown). |

### Valor devuelto

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Iniciar proceso de conversión
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Guardar resultado de la conversión como archivo local
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Convertir la fuente MD (markdown) presentada por la ruta completa del archivo a html. El resultado es [`HTMLDocument`](../../../com.aspose.html/htmldocument/) que puede guardarse mediante la ruta de archivo de salida.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MD (Markdown). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |

### Valor devuelto

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Iniciar proceso de conversión con la configuración predeterminada
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Guardar resultado de la conversión como archivo local
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Convertir la fuente MD (markdown) presentada por ruta de archivo completa a html. El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta al archivo Markdown fuente. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| outputPath | Cadena | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Iniciar proceso de conversión
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Ver también

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Convertir la fuente MD (markdown) presentada por ruta de archivo completa a html. El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta al archivo Markdown fuente. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| outputPath | Cadena | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Convertidor de Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Pasos de conversión

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Fuente de conversión. Detecta un archivo MD local existente o crea un flujo de datos de entrada como fuente de conversión. Resultado de la conversión. Puedes obtener directamente [`HTMLDocument`](../../../com.aspose.html/htmldocument/) o definir la ruta de archivo de salida del resultado según la firma del método. Usa el método ConvertMarkdown() de la clase Converter para guardar MD como un resultado html. También puedes añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro opcional. Convertidor MD en línea

También puede interesarle un [Convertidor de MD a HTML](https://products.aspose.app/html/en/conversion/md-to-html) gratuito en línea que convierte MD a HTML con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos. Además, puede consultar otros convertidores de MD en línea: [MD a PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD a DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD a XPS](https://products.aspose.app/html/en/conversion/md-to-xps) y encontrar los [convertidores de MD a imagen](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
