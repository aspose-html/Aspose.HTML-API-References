---
title: "FormEditor-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.forms.FormEditor-klass. Denna klass representerar redigeraren över HTMLFormElement som skapar ett enklare sätt för .net-utvecklare att redigera HTML-formulär."
type: docs

url: /sv/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Denna klass representerar redigeraren över [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som skapar ett enklare sätt för .net-utvecklare att redigera HTML-formulär.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Antalet formulärkontroller i formuläret. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Det ursprungliga [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som är associerat med den aktuella instansen av `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Returnerar elementet efter angivet index. (2 indexerare) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Skapar en ny `FormEditor` baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Skapar en ny `FormEditor` baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som valts från [`Forms`](../../com.aspose.html/htmldocument/forms/) samlingen efter index. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Skapar en ny `FormEditor` baserad på [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) som valts från dokumentet efter id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Skapar ett nytt [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) och associerar det med `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) skapas i ett frånkopplat tillstånd från dokumentet; för att fästa det i dokumentet, vänligen välj rätt plats och använd [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) metoden. |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Skapar ett nytt [`HTMLElement`](../../com.aspose.html/htmlelement/) och lägger till det i slutet av formuläret. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Skapar ett nytt [`InputElement`](../inputelement/) och lägger till det i slutet av formuläret. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Skapar ett nytt [`InputElement`](../inputelement/) och lägger till det i slutet av formuläret. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Frigör ohanterade och hanterade resurser. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Returnerar elementet efter angivet index. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Returnerar elementet efter angivet namn. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Hämtar enumeratorn. |

### Se även

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
