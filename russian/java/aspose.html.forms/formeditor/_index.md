---
title: "Класс FormEditor"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.forms.FormEditor. Этот класс представляет редактор над HTMLFormElement, который упрощает .net-разработчикам редактирование HTML-форм."
type: docs

url: /ru/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Этот класс представляет редактор над [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), который упрощает .net-разработчикам редактирование HTML-форм.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Свойства

| Имя | Описание |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Количество элементов управления формой в форме. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Оригинальный [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), связанный с текущим экземпляром `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Возвращает элемент по указанному индексу. (2 индексатора) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Создаёт новый `FormEditor` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Создаёт новый `FormEditor` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), выбранного из коллекции [`Forms`](../../com.aspose.html/htmldocument/forms/) по индексу. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Создаёт новый `FormEditor` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), выбранного из документа по id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Создаёт новый [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) и связывает его с `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) создаётся в отсоединённом от документа состоянии; чтобы присоединить его к документу, выберите подходящее место и используйте метод [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Создаёт новый [`HTMLElement`](../../com.aspose.html/htmlelement/) и добавляет его в конец формы. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Создаёт новый [`InputElement`](../inputelement/) и добавляет его в конец формы. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Создаёт новый [`InputElement`](../inputelement/) и добавляет его в конец формы. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Освобождает неуправляемые и управляемые ресурсы. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Возвращает элемент по указанному индексу. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Возвращает элемент по указанному имени. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Получает перечислитель. |

### См. также

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
