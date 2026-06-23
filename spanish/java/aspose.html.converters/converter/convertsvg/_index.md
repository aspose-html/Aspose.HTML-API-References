---
title: "Converter.ConvertSVG"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Converter. Convierte la fuente SVG presentada por SVGDocument. El resultado es datos de salida formados por la implementación de la interfaz ICreateStreamProvider"
type: docs

url: /es/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Convierte la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Iniciar proceso de conversión con la configuración predeterminada
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Convertir la fuente SVG presentada por la ruta completa del archivo a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Convertir la fuente SVG presentada por la ruta completa del archivo a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Convertir la fuente SVG presentada por contenido en línea a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Convertir la fuente SVG presentada por contenido en línea a XPS. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Convertir la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Convertir la fuente SVG presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Convertir la fuente SVG presentada por ruta de archivo completa a DOCX. El resultado es un archivo docx formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Convertir la fuente SVG presentada por contenido en línea. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Convertir la fuente SVG presentada por contenido en línea. El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | Cadena | Ruta completa del archivo docx como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Convierte la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, sp);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo docx formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Convertir la fuente SVG presentada por la ruta completa del archivo a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Convertir la fuente SVG presentada por la ruta completa del archivo a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Convertir la fuente SVG presentada por contenido en línea a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Ver también

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Convertir la fuente SVG presentada por contenido en línea a DOCX. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | DocSaveOptions | El uso del objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) donde encontrará información sobre cómo convertir SVG a [DOCX](https://docs.fileformat.com/word-processing/docx/) usando los métodos ConvertSVG() de la clase Converter y cómo aplicar los parámetros [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a DOCX

La clase Converter ofrece múltiples conversiones específicas de SVG a DOCX. Para convertir SVG a DOCX, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado DOCX con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a DOCX](https://products.aspose.app/svg/en/conversion/svg) en línea gratuito que convierte SVG a DOCX con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto DocSaveOptions predeterminado
      var options = new DocSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Convertir la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Convertir la fuente SVG presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Convertir la fuente SVG presentada por ruta de archivo completa a PDF. El resultado es un archivo pdf formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Convertir la fuente SVG presentada por contenido en línea a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Convertir la fuente SVG presentada por contenido en línea a PDF. El resultado es un archivo pdf formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | Cadena | Ruta completa del archivo pdf como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Convertir la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) a PDF. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Convertir la fuente SVG presentada por la ruta completa del archivo a PDF. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Convertir la fuente SVG presentada por la ruta completa del archivo a PDF. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Convertir la fuente SVG presentada por contenido en línea a PDF. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Ver también

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Convertir la fuente SVG presentada por contenido en línea a PDF. El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | PdfSaveOptions | El uso del objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) donde encontrará información sobre cómo convertir SVG a PDF usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a PDF

La clase Converter ofrece múltiples conversiones específicas de SVG a PDF. Para convertir SVG a PDF, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado PDF con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) en línea gratuito que convierte SVG a PDF con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Defina el objeto PdfSaveOptions predeterminado
      var options = new PdfSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Convertir la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado es un archivo de imagen creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión con la configuración predeterminada
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo de imagen creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo de imagen creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Convertir la fuente SVG presentada por ruta de archivo completa a imagen. El resultado es un archivo de imagen formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Convertir la fuente SVG presentada por ruta de archivo completa a imagen. El resultado es un archivo de imagen formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Convertir la fuente SVG presentada por contenido en línea a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Convertir la fuente SVG presentada por contenido en línea a imagen. El resultado es un archivo de imagen formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | Cadena | Ruta completa del archivo de imagen como resultado de la conversión. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Convierte la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Iniciar proceso de conversión
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado son datos de salida formados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Convertir la fuente SVG presentada por la ruta completa del archivo a imagen. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Convertir la fuente SVG presentada por la ruta completa del archivo a imagen. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Convertir la fuente SVG presentada por contenido en línea a imagen. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Conocida (ver [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) o implementación personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Ver también

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Convertir la fuente SVG presentada por contenido en línea a imagen. El resultado son datos de salida generados por la implementación de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | ImageSaveOptions | El uso del objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) le permite ajustar el proceso de renderizado. Puede especificar el [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), los [`margins`](../../../com.aspose.html.drawing/page/margin/), el [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementación de la [`interfaz`](../../../com.aspose.html.io/icreatestreamprovider/), que se utilizará para obtener un flujo de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) donde encontrará información sobre cómo convertir SVG a JPG usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Otros artículos relacionados con formatos de imagen populares: [Conversión de SVG a PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [Conversión de SVG a BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [Conversión de SVG a GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) y [Conversión de SVG a TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG a Imagen

La clase Converter ofrece múltiples conversiones específicas de SVG a imagen en formatos populares. Para convertir SVG a imagen, debe seguir uno de los escenarios simples que consta de unos pocos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o una [`Url`](../../../com.aspose.html/url/) remota como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o utilice una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) con configuraciones específicas o predeterminadas. Observe que el formato de imagen predeterminado es PNG. También puede agregar [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar SVG como un resultado de imagen con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor de SVG a JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) en línea gratuito que convierte SVG a JPG con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos!

Otros convertidores de imágenes populares para diferentes formatos se pueden encontrar aquí: [Convertidor de SVG a PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Convertidor de SVG a BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Convertidor de SVG a GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) y [Convertidor de SVG a TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Usar una de las implementaciones de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definir objeto ImageSaveOptions predeterminado
      var options = new ImageSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Convertir la fuente SVG presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). El resultado es un archivo xps creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | SVGDocument | Fuente de conversión presentada por [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Crear documento SVG como fuente de conversión
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Iniciar proceso de conversión con la configuración predeterminada
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo xps creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Convertir la fuente SVG presentada por [`URL`](../../../com.aspose.html/url/). El resultado es un archivo xps creado a partir de la ruta del archivo de salida.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | Documento fuente SVG [`URL`](../../../com.aspose.html/url/) - proporciona una representación de objeto de un identificador universal (URL). |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Ver también

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Convertir la fuente SVG presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Convertir la fuente SVG presentada por ruta de archivo completa a XPS. El resultado es un archivo xps formado por la ruta de archivo de salida.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourcePath | Cadena | Ruta completa del archivo fuente SVG. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Convertir la fuente SVG presentada por contenido en línea a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Convertir la fuente SVG presentada por contenido en línea a XPS. El resultado es un archivo xps formado por la ruta del archivo de salida.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | Cadena como contenido SVG en línea. |
| baseUri | Cadena | El URI base del documento. Se combinará con la ruta del directorio actual para formar una URL absoluta. |
| configuration | Configuration | La configuración del entorno. Representa el objeto de contexto [`configuration`](../../../com.aspose.html/configuration/) que se utiliza para establecer la configuración del entorno para la aplicación. |
| options | XpsSaveOptions | El uso del objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) le permite ajustar el proceso de renderizado. Para más información vea la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | Cadena | Ruta completa del archivo xps como resultado de la conversión de salida. |

## Observaciones

Convertidor SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Consulte el [artículo](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) donde encontrará información sobre cómo convertir SVG a XPS usando los métodos ConvertSVG() de la clase [`Converter`](../) y cómo aplicar los parámetros [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) y [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG a XPS

La clase Converter ofrece múltiples conversiones específicas de SVG a XPS. Para convertir SVG a XPS, debe seguir uno de los escenarios simples que consta de algunos pasos:

Fuente de conversión. Detecte un archivo SVG local existente o un [`Url`](../../../com.aspose.html/url/) remoto como fuente de conversión. También puede definir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) como fuente de conversión o incluso usar contenido SVG en línea presentado por una cadena de origen. Resultado de la conversión. Defina la ruta del archivo de salida o use una implementación conocida o personalizada de la interfaz [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) como búfer de datos de salida. Cree un nuevo objeto [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) con configuraciones específicas o predeterminadas. También puede añadir [`configuration`](../../../com.aspose.html/configuration/) como parámetro de opción. Use el método ConvertSVG() de la clase Converter para guardar el SVG como un resultado XPS con tres o más parámetros según el escenario del usuario. Convertidor SVG en línea

Aspose.HTML ofrece un [Convertidor SVG a XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) en línea gratuito que convierte SVG a XPS con alta calidad, de forma fácil y rápida. Simplemente cargue, convierta sus archivos y obtenga resultados en unos segundos.

Código fuente

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formato de contenido SVG en línea
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Ruta del archivo de resultado del formulario
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definir objeto XpsSaveOptions predeterminado
      var options = new XpsSaveOptions();

      // Iniciar proceso de conversión con la configuración predeterminada
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Ver también

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
