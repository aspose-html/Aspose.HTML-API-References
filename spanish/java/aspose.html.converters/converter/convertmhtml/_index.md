---
title: "Converter.ConvertMHTML"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Converter. Convertir la fuente MHTML presentada por flujo de entrada. El resultado es un archivo xps creado a partir de la ruta del archivo de salida"
type: docs

url: /es/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Convertir la fuente MHTML presentada por [flujo](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) de entrada. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Flujo de datos mhtml (.mht) de entrada. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Ruta del archivo fuente del formulario
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Convertir la fuente MHTML presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definir objeto XpsSaveOptions predeterminado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Ruta del archivo fuente del formulario
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Ruta del archivo de resultado del formulario
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definir objeto XpsSaveOptions predeterminado
	var options = new XpsSaveOptions();

	// Iniciar proceso de conversión
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Convertir la fuente MHTML presentada por [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) de entrada. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos fuente de conversión mhtml (.mht). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Ruta del archivo fuente del formulario
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Convertir la fuente MHTML presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Ruta del archivo fuente del formulario
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Ruta del archivo fuente del formulario
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos fuente de conversión mhtml (.mht). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Convertir la fuente MHTML presentada mediante ruta completa de archivo a XPS. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Convertir la fuente MHTML presentada mediante [`URL`](../../../com.aspose.html/url/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos fuente de conversión mhtml (.mht). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Convertir la fuente MHTML presentada mediante ruta completa de archivo a XPS. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Convertir la fuente MHTML presentada mediante URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a [XPS](https://docs.fileformat.com/page-description-language/xps/) a menudo es necesaria para aprovechar el formato XPS en tareas específicas. Un archivo XPS representa archivos de diseño de página basados en XML Paper Specifications, creados por Microsoft.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) donde encontrará información sobre cómo convertir MHTML a XPS usando los métodos ConvertHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a XPS

La clase Converter ofrece algunas conversiones específicas de MHTML a XPS. Para convertir MHTML a XPS, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o personalizado como fuente de conversión. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) en línea gratuito que convierte MHTML a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Convertir la fuente MHTML presentada por flujo de entrada. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Convertir la fuente MHTML presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente MHTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo docx formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Convertir la fuente MHTML presentada por flujo de entrada. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Convertir la fuente MHTML presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Convertir la fuente MHTML presentada mediante [`URL`](../../../com.aspose.html/url/). El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | Documento fuente MHTML [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Convertir la fuente MHTML presentada mediante ruta completa de archivo a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Convertir la fuente MHTML presentada mediante URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | Documento fuente MHTML [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Convertir la fuente MHTML presentada mediante ruta completa de archivo a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Convertir la fuente MHTML presentada mediante [`URL`](../../../com.aspose.html/url/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | Documento fuente MHTML [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a DOCX a menudo es necesaria para aprovechar el formato [DOCX](https://docs.fileformat.com/word-processing/docx/) en tareas específicas. DOCX es un formato bien conocido para documentos de Microsoft Word. Puede contener una amplia gama de datos, incluyendo texto, tablas, gráficos raster y vectoriales, video, sonidos y diagramas. Este formato es popular porque admite características de formato complejas y ofrece a los usuarios una variedad de opciones para crear cualquier tipo de documento.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) donde encontrará información sobre cómo convertir MHTML a DOCX usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a DOCX

La clase Converter ofrece algunas conversiones específicas de MHTML a DOCX. Para convertir MHTML a DOCX, debe seguir uno de los escenarios simples que consta de varios pasos:

Fuente de conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede usar un flujo estándar o específico personalizado como fuente de conversión. Resultado de conversión. Defina la ruta del archivo de salida del resultado o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar la [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en línea gratuito que convierte MHTML a DOCX con alta calidad, de forma fácil y rápida. ¡Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Convertir la fuente MHTML presentada por flujo de entrada. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Convertir la fuente MHTML presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Convertir la fuente MHTML presentada por flujo de entrada. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Convertir la fuente MHTML presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente MHTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Convierta la fuente MHTML presentada mediante la ruta completa del archivo a PDF. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta del archivo fuente MHTML. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Convertir la fuente MHTML presentada mediante URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Convierta la fuente MHTML presentada mediante la ruta completa del archivo a PDF. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Convertir la fuente MHTML presentada mediante [`URL`](../../../com.aspose.html/url/). El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

La conversión de MHTML a PDF a menudo es necesaria para aprovechar el formato [PDF](https://docs.fileformat.com/pdf/) en tareas específicas. PDF ofrece muchos beneficios que otros archivos no tienen. Por ejemplo, muchos programas y aplicaciones admiten documentos PDF; los archivos PDF están optimizados para la impresión y son ideales para crear copias físicas de sus documentos; puede configurar la seguridad de los archivos PDF, deshabilitando la impresión, la edición, el uso de una firma electrónica, etc.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), donde encontrará información sobre cómo convertir MHTML a PDF usando los métodos ConvertMHTML() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a PDF

La clase Converter ofrece algunas conversiones específicas de MHTML a PDF. Para convertir MHTML a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una URL remota como origen de la conversión. También puede usar un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en línea gratuito que convierte MHTML a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Convertir la fuente MHTML presentada por flujo de entrada a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Convertir la fuente MHTML presentada por ruta de archivo completa. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo de imagen formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Convertir la fuente MHTML presentada por flujo de entrada a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Convertir la fuente MHTML presentada por ruta de archivo completa. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Convertir la fuente MHTML presentada por URL. El resultado es un archivo de imagen formado por la ruta de archivo de salida.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Convierta la fuente MHTML presentada mediante la ruta completa del archivo a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Convertir la fuente MHTML presentada mediante URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Convertir la fuente MHTML presentada mediante flujo de entrada. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Secuencia de datos de entrada para la conversión MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Convierta la fuente MHTML presentada mediante la ruta completa del archivo a imagen. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente MHTML. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [` interface`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un stream de salida. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Convertir la fuente MHTML presentada mediante URL. El resultado es datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceUrl | Url | URL del documento fuente MHTML - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor MHTML

Los archivos con extensión [MHTML](https://docs.fileformat.com/web/mhtml/) representan un formato de archivo de archivo web que varias aplicaciones pueden crear. El formato se conoce como formato de archivo porque guarda el código HTML web y los recursos asociados en un solo archivo. Estos recursos incluyen cualquier elemento vinculado a la página web, como imágenes, applets, animaciones, archivos de audio, etc. Los archivos MHTML pueden abrirse en diversas aplicaciones como Internet Explorer y Microsoft Word. Las especificaciones reales del formato se detallan en [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Consulte el artículo, donde encontrará información sobre cómo convertir MHTML a imágenes en diferentes formatos usando los métodos ConvertMHTML() de la clase Converter y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML a Imagen

La clase Converter ofrece algunas conversiones específicas de MHTML a imágenes. Los formatos compatibles son [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) y [TIFF](https://docs.fileformat.com/image/tiff/). Para convertir MHTML a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Origen de la conversión. Detecte un archivo MHTML (.mht) local existente o una [`Url`](../../../com.aspose.html/url/) remota como origen de la conversión. También puede usar un stream estándar o personalizado como origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. El formato de imagen predeterminado es PNG. También puede agregar configuración como parámetro de opción. Use el método ConvertMHTML() de la clase Converter para guardar MHTML como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor MHTML en línea

Aspose.HTML ofrece un [Convertidor de MHTML a JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en línea gratuito que convierte MHTML a un archivo JPEG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga los resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
