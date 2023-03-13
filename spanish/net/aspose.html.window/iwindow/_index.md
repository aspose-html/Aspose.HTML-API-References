---
title: Interface IWindow
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Window.IWindow interfaz. El objeto ventana representa una ventana que contiene un documento DOM.
type: docs
weight: 5850
url: /es/net/aspose.html.window/iwindow/
---
## IWindow interface

El objeto ventana representa una ventana que contiene un documento DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | El atributo del documento debe devolver el objeto Documento más reciente del objeto Ventana. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | El objeto frameElement de un Documento. |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | El atributo de ubicación de la interfaz de la ventana debe devolver el objeto de ubicación para el documento de ese objeto de ventana. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | El atributo de nombre del objeto Ventana debe, al obtenerse, devolver el nombre actual del contexto de exploración y, al establecerse, establecer el nombre del contexto de exploración en el nuevo valor. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | El atributo IDL de apertura en el objeto Ventana, al obtenerlo, debe devolver el objeto WindowProxy del contexto de exploración a partir del cual se creó el contexto de exploración actual (su contexto de exploración de apertura), si lo hay, si todavía está disponible y si el contexto de navegación actual no ha repudiado a su abridor; de lo contrario, debe devolver nulo. En la configuración, si el nuevo valor es nulo, el contexto de navegación actual debe rechazar su abridor; si el nuevo valor es cualquier otra cosa, entonces el agente de usuario debe llamar al método interno [[DefineOwnProperty]] del objeto Ventana, pasando el nombre de propiedad "abridor" como clave de propiedad, y el Descriptor de propiedad { [[Valor]]: valor , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } como descriptor de propiedad, donde value es el nuevo valor. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | El atributo IDL principal en el objeto Ventana de un Documento en un contexto de navegación b debe devolver el objeto WindowProxy del contexto de navegación principal, si lo hay (es decir, si b es un contexto de navegación secundario), o el objeto WindowProxy del contexto de navegación contexto b en sí mismo, de lo contrario (es decir, si es un contexto de navegación de nivel superior o un contexto de navegación anidado separado). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Devuelve el objeto WindowProxy del contexto de navegación del objeto Ventana. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | El atributo IDL superior en el objeto Ventana de un Documento en un contexto de exploración b debe devolver el objeto WindowProxy de su contexto de exploración de nivel superior (que sería su propio objeto WindowProxy si fuera un contexto de exploración de nivel superior), si tiene uno, o su propio objeto WindowProxy de lo contrario (por ejemplo, si fuera un contexto de navegación anidado separado). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Devuelve el objeto WindowProxy del contexto de navegación del objeto Ventana. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | Muestra una alerta modal con el mensaje dado y espera a que el usuario lo descarte |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | Muestra un indicador modal Aceptar/Cancelar con el mensaje dado, espera a que el usuario lo descarte y devuelve verdadero si el usuario hace clic en Aceptar y falso si el usuario hace clic en Cancelar. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | Muestra un indicador de campo de texto modal con el mensaje dado, espera a que el usuario lo descarte y devuelve el valor que el usuario ingresó. Si el usuario cancela la solicitud, devuelve nulo en su lugar. Si el segundo argumento está presente, entonces el valor dado se usa como predeterminado. |

### Ver también

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* espacio de nombres [Aspose.Html.Window](../../aspose.html.window/)
* asamblea [Aspose.HTML](../../)


