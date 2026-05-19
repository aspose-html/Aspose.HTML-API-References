---
title: "Interfaz IWindow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.window.IWindow. El objeto window representa una ventana que contiene un documento DOM."
type: docs

url: /es/java/com.aspose.html.window/iwindow/
---
## IWindow interface

El objeto window representa una ventana que contiene un documento DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) El atributo document debe devolver el objeto Document más reciente del objeto Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) El objeto frameElement de un Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Devuelve un objeto Storage que le permite guardar pares clave/valor en el agente de usuario. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) El atributo location de la interfaz Window debe devolver el objeto Location para el Document de ese objeto Window. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) El atributo IDL opener en el objeto Window, al obtenerlo, debe devolver el objeto WindowProxy del contexto de navegación desde el cual se creó el contexto de navegación actual (su contexto de navegación opener), si existe, si aún está disponible y si el contexto de navegación actual no ha renunciado a su opener; de lo contrario, debe devolver null. Al establecerlo, si el nuevo valor es null entonces el contexto de navegación actual debe renunciar a su opener; si el nuevo valor es cualquier otro, el agente de usuario debe llamar al método interno [[DefineOwnProperty]] del objeto Window, pasando el nombre de la propiedad \"opener\" como clave de la propiedad, y el Descriptor de Propiedad { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } como descriptor de la propiedad, donde value es el nuevo valor. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) El atributo IDL parent en el objeto Window de un Document en un contexto de navegación b debe devolver el objeto WindowProxy del contexto de navegación padre, si existe (es decir, si b es un contexto de navegación hijo), o el objeto WindowProxy del propio contexto de navegación b, de lo contrario (es decir, si es un contexto de navegación de nivel superior o un contexto de navegación anidado separado). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Devuelve el objeto WindowProxy del contexto de navegación del objeto Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) El atributo IDL top en el objeto Window de un Document en un contexto de navegación b debe devolver el objeto WindowProxy de su contexto de navegación de nivel superior (que sería su propio objeto WindowProxy si fuera un contexto de navegación de nivel superior), si tiene uno, o su propio objeto WindowProxy en caso contrario (p. ej., si era un contexto de navegación anidado separado). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Devuelve el objeto WindowProxy del contexto de navegación del objeto Window. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Muestra una alerta modal con el mensaje proporcionado y espera a que el usuario la cierre. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Toma los datos de entrada, en forma de una cadena Unicode que contiene datos binarios codificados en base64, los decodifica y devuelve una cadena compuesta por caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores de 0x00 a 0xFF respectivamente, correspondiente a esos datos binarios. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Toma los datos de entrada, en forma de una cadena Unicode que contiene solo caracteres en el rango U+0000 a U+00FF, cada uno representando un byte binario con valores de 0x00 a 0xFF respectivamente, y los convierte a su representación base64, la cual devuelve. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Muestra un cuadro de diálogo modal de OK/Cancelar con el mensaje proporcionado, espera a que el usuario lo cierre y devuelve true si el usuario pulsa OK y false si pulsa Cancelar. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Devuelve un nuevo objeto MediaQueryList que puede usarse para determinar si el documento coincide con la cadena de consulta de medios, así como para monitorizar el documento y detectar cuándo coincide (o deja de coincidir) con esa consulta de medios. Consulte la especificación del módulo CSSOM View: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Muestra un cuadro de diálogo modal con un campo de texto y el mensaje proporcionado, espera a que el usuario lo cierre y devuelve el valor introducido por el usuario. Si el usuario cancela el cuadro de diálogo, devuelve null. Si se proporciona el segundo argumento, el valor dado se utiliza como predeterminado. |

### Ver también

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
