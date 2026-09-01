---
title: "Clase InputElement"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.forms.InputElement. El InputElement representa un contenedor que está asociado con el HTMLInputElement"
type: docs

url: /es/java/com.aspose.html.forms/inputelement/
---
## InputElement class

El InputElement representa un contenedor asociado con el HTMLInputElement.

```java
public class InputElement : FormElement<HTMLInputElement>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Obtiene el tipo del elemento. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/inputelement/id/) { get; set; } | Representa el atributo Id del elemento de entrada. |
| [getList](../../com.aspose.html.forms/inputelement/list/) Representa una lista de opciones |
| [name](../../com.aspose.html.forms/inputelement/name/) { get; set; } | Representa el atributo name del elemento de entrada. |
[getType]
[setType] Type of the form control. |
| [value](../../com.aspose.html.forms/inputelement/value/) { get; set; } | Representa el valor String del elemento de entrada que está directamente mapeado al atributo 'value'. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addFile](../../com.aspose.html.forms/inputelement/addfile/)(String) | Este método agrega archivos a la colección [`Files`](../../com.aspose.html/htmlinputelement/files/) que se enviarán durante la siguiente solicitud web. |
| [getCheckboxValue](../../com.aspose.html.forms/inputelement/getcheckboxvalue/)() | Devuelve el estado de marcado para el elemento de entrada de tipo Checkbox. |
| [getColorValue](../../com.aspose.html.forms/inputelement/getcolorvalue/)() | Este método se usa para obtener el valor como un color. Este método es válido solo si el tipo del elemento de entrada es "color". |
| [getDateTimeLocalValue](../../com.aspose.html.forms/inputelement/getdatetimelocalvalue/)() | Este método se usa para obtener el valor como un objeto DateTime. Este método es válido solo si el tipo del elemento de entrada es "datetime-local". |
| [getDateValue](../../com.aspose.html.forms/inputelement/getdatevalue/)() | Este método se usa para obtener el valor como un objeto DateTime. Este método es válido solo si el tipo del elemento de entrada es "date". |
| [getEmailValue](../../com.aspose.html.forms/inputelement/getemailvalue/)() | Este método se usa para obtener el valor como un objeto String de correo electrónico. Este método es válido solo si el tipo del elemento de entrada es "email". |
| [getMonthValue](../../com.aspose.html.forms/inputelement/getmonthvalue/)() | Este método se usa para obtener el valor como un objeto DateTime. Este método es válido solo si el tipo del elemento de entrada es "month". |
| [getNumberValue](../../com.aspose.html.forms/inputelement/getnumbervalue/)() | Este método se usa para obtener el valor como un número. Este método es válido solo si el tipo del elemento de entrada es "number". |
| [getPasswordValue](../../com.aspose.html.forms/inputelement/getpasswordvalue/)() | Este método se usa para obtener el valor como un objeto String de contraseña. Este método es válido solo si el tipo del elemento de entrada es "password". |
| [getRadioValue](../../com.aspose.html.forms/inputelement/getradiovalue/)() | Devuelve el estado de marcado para el elemento de entrada de tipo radio. |
| [getTimeValue](../../com.aspose.html.forms/inputelement/gettimevalue/)() | Este método se usa para obtener el valor como un objeto TimeSpan. Este método es válido solo si el tipo del elemento de entrada es "time". |
| [getUrlValue](../../com.aspose.html.forms/inputelement/geturlvalue/)() | Este método se usa para obtener el valor como un objeto [`Url`](../../com.aspose.html/url/). Este método es válido solo si el tipo del elemento de entrada es "url". |
| [getWeekValue](../../com.aspose.html.forms/inputelement/getweekvalue/)() | Este método se usa para obtener el valor como un String de semana. Este método es válido solo si el tipo del elemento de entrada es "week". |
| [setCheckboxValue](../../com.aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Establece el estado de marcado para el elemento de entrada de tipo Checkbox. |
| [setColorValue](../../com.aspose.html.forms/inputelement/setcolorvalue/)(Color) | Este método se usa para establecer el color como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "color". |
| [setDateTimeLocalValue](../../com.aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | Este método se usa para establecer un objeto DateTime como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "datetime-local". |
| [setDateValue](../../com.aspose.html.forms/inputelement/setdatevalue/)(DateTime) | Este método se usa para establecer un objeto DateTime como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "date". |
| [setEmailValue](../../com.aspose.html.forms/inputelement/setemailvalue/)(String) | Este método se usa para establecer un String de correo electrónico como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "email". |
| [setMonthValue](../../com.aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | Este método se usa para establecer un objeto DateTime como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "month". |
| [setNumberValue](../../com.aspose.html.forms/inputelement/setnumbervalue/)(float) | Este método se usa para establecer un número como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "number". |
| [setPasswordValue](../../com.aspose.html.forms/inputelement/setpasswordvalue/)(String) | Este método se usa para establecer un String de contraseña como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "password". |
| [setRadioValue](../../com.aspose.html.forms/inputelement/setradiovalue/)(bool) | Establece el estado de marcado para el elemento de entrada de tipo radio. |
| [setTimeValue](../../com.aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | Este método se usa para establecer un objeto TimeSpan como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "time". |
| [setUrlValue](../../com.aspose.html.forms/inputelement/seturlvalue/)(Url) | Este método se usa para establecer el objeto [`Url`](../../com.aspose.html/url/) como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "url" |
| [setWeekValue](../../com.aspose.html.forms/inputelement/setweekvalue/)(String) | Este método se usa para establecer la cadena 'week' como valor para el elemento de entrada. Este método es válido solo si el tipo del elemento de entrada es "week" |

### Ver también

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../com.aspose.html/htmlinputelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
