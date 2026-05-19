---
title: "Converter.ConvertTemplate"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Converter. Fusiona la fuente de plantilla presentada por HTMLDocument con los datos de plantilla XML JSON. El resultado es un archivo html formado por la ruta de archivo de salida."
type: docs

url: /es/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Fusiona la fuente de plantilla presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/) con los datos de plantilla (XML, JSON). El resultado es un archivo html formado por la ruta de archivo de salida.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| template | HTMLDocument | Fusionando el esqueleto fuente presentado por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Documento HTML del formulario como fuente de conversión
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Iniciar el proceso de conversión
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Liberar recursos
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Fusionar la fuente HTML de la plantilla presentada por [`URL`](../../../com.aspose.html/url/) con los datos de la plantilla (XML, JSON). El resultado es un archivo HTML generado en la ruta del archivo de salida.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Fusión del esqueleto de la fuente HTML presentado por [`URL`](../../../com.aspose.html/url/). |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL de la fuente del esqueleto HTML del formulario
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Fusionar la fuente HTML de la plantilla presentada por [`URL`](../../../com.aspose.html/url/) con los datos de la plantilla (XML, JSON). El resultado es un archivo HTML generado en la ruta del archivo de salida.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Fusión del esqueleto de la fuente HTML presentado por [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL de la fuente del esqueleto HTML del formulario
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión con la configuración predeterminada
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Combinar la fuente HTML de plantilla presentada por la ruta completa del archivo con los datos de plantilla (XML, JSON). El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | String | Fusión del esqueleto de la fuente HTML presentado por la ruta completa del archivo. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Combinar la fuente HTML de plantilla presentada por la ruta completa del archivo con los datos de plantilla (XML, JSON). El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | String | Fusión del esqueleto de la fuente HTML presentado por la ruta completa del archivo. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión con la configuración predeterminada
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Combinar la fuente HTML de plantilla presentada por contenido en línea con los datos de plantilla (XML, JSON). El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | String | Fusión del esqueleto de la fuente HTML presentado por contenido de cadena en línea. |
| baseUrl | String | URI base de la plantilla HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Contenido fuente en línea del formulario como plantilla
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
       
      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Salida del formulario como resultado de la fusión
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();
	  
      // Iniciar el proceso de conversión
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

### Ver también

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Combinar la fuente HTML de plantilla presentada por contenido en línea con los datos de plantilla (XML, JSON). El resultado es un archivo html formado por la ruta del archivo de salida.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | String | Fusión del esqueleto de la fuente HTML presentado por contenido de cadena en línea. |
| baseUrl | String | URI base de la plantilla HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |
| outputPath | String | Ruta completa del archivo html como resultado de salida de la conversión. |

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Contenido fuente en línea del formulario como plantilla
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
    
   // Ruta del archivo de datos de plantilla XML (JSON) del formulario
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Defina una instancia del objeto TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Salida del formulario como resultado de la fusión
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Defina una instancia del objeto configuration
   var configuration = new Configuration();

   // Defina el objeto TemplateLoadOptions predeterminado
   var options = new TemplateLoadOptions();

   // Iniciar el proceso de conversión con la configuración predeterminada
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

A continuación se muestra el archivo de datos para combinar con la fuente como plantilla

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

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Combina la fuente de la plantilla presentada por [`HTMLDocument`](../../../com.aspose.html/htmldocument/) con los datos de la plantilla (XML, JSON). El resultado es un nuevo HTMLDocument formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| template | HTMLDocument | Fusionando el esqueleto fuente presentado por [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();
      
      // Documento HTML del formulario como fuente de conversión
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Iniciar el proceso de conversión
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Guardar el resultado con recursos vinculados
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Combina la fuente HTML de la plantilla presentada por [`URL`](../../../com.aspose.html/url/) con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Fusión del esqueleto de la fuente HTML presentado por [`URL`](../../../com.aspose.html/url/). |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formar URL al archivo fuente HTML esqueleto
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Guardar el resultado con recursos vinculados
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Combina la fuente HTML de la plantilla presentada por [`URL`](../../../com.aspose.html/url/) con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Fusión del esqueleto de la fuente HTML presentado por [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formar URL al archivo fuente HTML esqueleto
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión con la configuración predeterminada
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Guardar el resultado con recursos vinculados
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

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

Combina la fuente HTML de la plantilla presentada por la ruta completa del archivo con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | String | Fusión del esqueleto de la fuente HTML presentado por la ruta completa del archivo. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Guardar el resultado con recursos vinculados
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Combina la fuente HTML de la plantilla presentada por la ruta completa del archivo con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | String | Fusión del esqueleto de la fuente HTML presentado por la ruta completa del archivo. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Ruta del archivo fuente del esqueleto HTML del formulario
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión con la configuración predeterminada
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Guardar el resultado con recursos vinculados
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Combina la fuente HTML de la plantilla presentada por contenido en línea con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | String | Fusión del esqueleto de la fuente HTML presentado por contenido de cadena en línea. |
| baseUrl | String | URI base de la plantilla HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenido fuente en línea del formulario como plantilla
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

      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Salida del formulario como resultado de la fusión
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión y guardar el resultado
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

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Combina la fuente HTML de la plantilla presentada por contenido en línea con los datos de la plantilla (XML, JSON). El resultado es un nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado que puede guardarse como archivo.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | String | Fusión del esqueleto de la fuente HTML presentado por contenido de cadena en línea. |
| baseUrl | String | URI base de la plantilla HTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| datos | TemplateData | Datos de plantilla para la fusión - sustitución (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instancia de objeto. Se utiliza para determinar si los nombres de la plantilla y del elemento de datos coinciden, sin importar mayúsculas o minúsculas (opciones). |

### Valor de retorno

Nuevo [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formado como resultado de la conversión que puede guardarse mediante la ruta de archivo de salida.

## Observaciones

Fusionador de Plantilla

La idea de la fusión de plantillas es crear un documento HTML basado en una plantilla HTML y completarlo a partir de una fuente de datos. Aspose.HTML proporciona la sintaxis de expresiones en línea para trabajar con plantillas y varios tipos de fuentes de datos, como XML y JSON. Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-template/) donde puede encontrar más información sobre la fusión de plantillas y el uso del método ConvertTemplate().

Pasos de conversión (fusión)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Fuente de la plantilla. Defina la fuente de la plantilla HTML mediante archivo, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instancia de objeto o incluso mediante contenido en línea. Resultado de la conversión. Puede obtener directamente el HTMLDocument resultante o definir la ruta del archivo de salida del resultado según la firma del método. Cree una instancia de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilice el método ConvertTemplate() de la clase Converter para fusionar la plantilla con los datos. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenido fuente en línea del formulario como plantilla
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
       
      // Ruta del archivo de datos de plantilla XML (JSON) del formulario
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Defina una instancia del objeto TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Salida del formulario como resultado de la fusión
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Defina una instancia del objeto configuration
      var configuration = new Configuration();

      // Defina el objeto TemplateLoadOptions predeterminado
      var options = new TemplateLoadOptions();

      // Iniciar el proceso de conversión y guardar el resultado
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

### Ver también

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
