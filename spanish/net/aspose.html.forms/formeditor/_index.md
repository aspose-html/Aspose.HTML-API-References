---
title: Class FormEditor
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Forms.FormEditor clase. Esta clase representa el editor sobre elHTMLFormElement que crea una forma más fácil para que los desarrolladores de .net editen los formularios html.
type: docs
weight: 2930
url: /es/net/aspose.html.forms/formeditor/
---
## FormEditor class

Esta clase representa el editor sobre el[`HTMLFormElement`](../../aspose.html/htmlformelement/) que crea una forma más fácil para que los desarrolladores de .net editen los formularios html.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Manejador de formularios del lado del servidor. Ver la definición del atributo de acción en HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | El número de controles de formulario en el formulario. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | El original[`HTMLFormElement`](../../aspose.html/htmlformelement/) que está asociado con la instancia actual de`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Devuelve el elemento por índice especificado. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | método HTTP [[RFC 2616 de la IETF](http://www.ietf.org/rfc/rfc2616.txt) utilizado para enviar el formulario. Ver la definición de atributo de método en HTML 4.01. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crea un nuevo`FormEditor` Residencia en[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crea un nuevo`FormEditor` Residencia en[`HTMLFormElement`](../../aspose.html/htmlformelement/) seleccionado de la[`Forms`](../../aspose.html/htmldocument/forms/) colección por index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Crea un nuevo`FormEditor` Residencia en[`HTMLFormElement`](../../aspose.html/htmlformelement/) seleccionado del documento por id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crea un nuevo[`HTMLFormElement`](../../aspose.html/htmlformelement/) y lo asoció con`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) se crea en el estado separado del documento; para adjuntarlo al documento, seleccione la ubicación adecuada y use[`AppendChild`](../../aspose.html.dom/node/appendchild/) método. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Crea un nuevo[`HTMLElement`](../../aspose.html/htmlelement/) y lo agrega al final del formulario. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Crea un nuevo[`InputElement`](../inputelement/) y lo agrega al final del formulario. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Crea un nuevo[`InputElement`](../inputelement/) y lo agrega al final del formulario. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Libera recursos administrados y no administrados. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Este método llena todo el formulario con los valores especificados. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Devuelve el elemento por índice especificado. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Devuelve el elemento por el nombre especificado. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Obtiene el enumerador. |

### Ver también

* class [FormElement](../formelement/)
* espacio de nombres [Aspose.Html.Forms](../../aspose.html.forms/)
* asamblea [Aspose.HTML](../../)


