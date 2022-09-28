---
title: InputElement
second_title: Referencia de API de Aspose.HTML para .NET
description: InputElement representa un contenedor asociado con HTMLInputElement.
type: docs
weight: 2970
url: /es/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement representa un contenedor asociado con HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype) { get; } | Obtiene el tipo del elemento. |
| [HtmlElement](../../aspose.html.forms/formelement`1/htmlelement) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id) { get; set; } | Representa el atributo Id del elemento de entrada. |
| [List](../../aspose.html.forms/inputelement/list) { get; } | Representa una lista de opciones |
| override [Name](../../aspose.html.forms/inputelement/name) { get; set; } | Representa el atributo de nombre del elemento de entrada. |
| [Type](../../aspose.html.forms/inputelement/type) { get; set; } | Tipo del control de formulario. |
| override [Value](../../aspose.html.forms/inputelement/value) { get; set; } | Representa el valor de cadena del elemento de entrada que se asigna directamente al atributo 'valor'. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile)(string) | Este método agrega archivos al[`Files`](../../aspose.html/htmlinputelement/files) colección que se enviará durante la próxima solicitud web. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue)() | Devuelve el estado de verificación del elemento de entrada con el tipo de casilla de verificación . |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue)() | Este método se utiliza para obtener el valor como un color. Este método es válido si solo el tipo del elemento de entrada es "color" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue)() | Este método se utiliza para obtener el valor comoDateTime objeto Objeto. Este método es válido si solo el tipo del elemento de entrada es "datetime-local" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue)() | Este método se utiliza para obtener el valor comoDateTime objeto. Este método es válido si solo el tipo del elemento de entrada es "fecha" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue)() | Este método se usa para obtener el valor como un objeto de cadena de correo electrónico. Este método es válido si solo el tipo del elemento de entrada es "email" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue)() | Este método se utiliza para obtener el valor comoDateTime objeto. Este método es válido si solo el tipo del elemento de entrada es "mes" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue)() | Este método se usa para obtener el valor como un número. Este método es válido si solo el tipo del elemento de entrada es "número" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue)() | Este método se usa para obtener el valor como un objeto de cadena de contraseña. Este método es válido si solo el tipo del elemento de entrada es "contraseña" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue)() | Devuelve el estado de verificación del elemento de entrada con el tipo de radio. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue)() | Este método se utiliza para obtener el valor comoTimeSpanobjeto. Este método es válido si solo el tipo del elemento de entrada es "tiempo" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue)() | Este método se utiliza para obtener el valor como[`Url`](../../aspose.html/url) objeto. Este método es válido si solo el tipo del elemento de entrada es "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue)() | Este método se usa para obtener el valor como una cadena de semana. Este método es válido si solo el tipo del elemento de entrada es "semana" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue)(bool) | Establece el estado de comprobación para el elemento de entrada con el tipo Casilla de verificación. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue)(Color) | Este método se utiliza para establecer el color como valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue)(DateTime) | Este método se utiliza para establecerDateTime objeto como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue)(DateTime) | Este método se utiliza para establecerDateTime objeto como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "fecha" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue)(string) | Este método se utiliza para establecer la cadena de correo electrónico como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "email" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue)(DateTime) | Este método se utiliza para establecerDateTime objeto como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "mes" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue)(float) | Este método se utiliza para establecer el número como valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "número" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue)(string) | Este método se utiliza para establecer una cadena de contraseña como valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "contraseña" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue)(bool) | Establece el estado de verificación para el elemento de entrada con el tipo de radio. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue)(TimeSpan) | Este método se utiliza para establecerTimeSpan objeto como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "tiempo" |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue)(Url) | Este método se utiliza para establecer[`Url`](../../aspose.html/url) objeto como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue)(string) | Este método se usa para establecer la cadena 'semana' como un valor para el elemento de entrada. Este método es válido si solo el tipo del elemento de entrada es "semana" |

### Ver también

* class [FormElement&lt;T&gt;](../formelement-1)
* class [HTMLInputElement](../../aspose.html/htmlinputelement)
* espacio de nombres [Aspose.Html.Forms](../../aspose.html.forms)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
