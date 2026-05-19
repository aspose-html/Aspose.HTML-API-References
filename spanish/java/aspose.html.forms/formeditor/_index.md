---
title: "Clase FormEditor"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.forms.FormEditor. Esta clase representa el editor sobre el HTMLFormElement que crea una forma más fácil para los desarrolladores .net de editar los formularios html."
type: docs

url: /es/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Esta clase representa el editor sobre el [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) que crea una forma más fácil para los desarrolladores .net de editar los formularios html.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) El número de controles de formulario en el formulario. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) El [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) original que está asociado con la instancia actual de `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Devuelve el elemento por el índice especificado. (2 indexadores) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crea un nuevo `FormEditor` basado en [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crea un nuevo `FormEditor` basado en [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) seleccionado de la colección [`Forms`](../../com.aspose.html/htmldocument/forms/) por índice. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Crea un nuevo `FormEditor` basado en [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) seleccionado del documento por id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crea un nuevo [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) y lo asocia con `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) se crea en un estado separado del documento; para adjuntarlo al documento, seleccione la ubicación adecuada y use el método [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Crea un nuevo [`HTMLElement`](../../com.aspose.html/htmlelement/) y lo agrega al final del formulario. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Crea un nuevo [`InputElement`](../inputelement/) y lo agrega al final del formulario. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Crea un nuevo [`InputElement`](../inputelement/) y lo agrega al final del formulario. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Libera recursos no administrados y administrados. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Devuelve el elemento por el índice especificado. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Devuelve el elemento por el nombre especificado. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Obtiene el enumerador. |

### Ver también

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
