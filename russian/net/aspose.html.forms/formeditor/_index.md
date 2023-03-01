---
title: Class FormEditor
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Forms.FormEditor сорт. Этот класс представляет редактор надHTMLFormElement это упрощает разработчикам .net редактирование htmlформ.
type: docs
weight: 2930
url: /ru/net/aspose.html.forms/formeditor/
---
## FormEditor class

Этот класс представляет редактор над[`HTMLFormElement`](../../aspose.html/htmlformelement/) это упрощает разработчикам .net редактирование html-форм.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Обработчик форм на стороне сервера. См. определение атрибута действия в HTML 4.01. . |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Количество элементов управления формы в форме. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Оригинал[`HTMLFormElement`](../../aspose.html/htmlformelement/) который связан с текущим экземпляром`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Возвращает элемент по указанному индексу. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP-метод [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) используется для отправки формы. См. определение атрибута метода в HTML 4.01. . |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Создает новый`FormEditor` на основе[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Создает новый`FormEditor` на основе[`HTMLFormElement`](../../aspose.html/htmlformelement/) выбран из[`Forms`](../../aspose.html/htmldocument/forms/) коллекция по индексу. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Создает новый`FormEditor` на основе[`HTMLFormElement`](../../aspose.html/htmlformelement/) выбрано из документа по id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Создает новый[`HTMLFormElement`](../../aspose.html/htmlformelement/) и связал его с`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) создается в отсоединенном от документа состоянии; чтобы прикрепить его к документу, выберите правильное место и используйте[`AppendChild`](../../aspose.html.dom/node/appendchild/) метод. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Создает новый[`HTMLElement`](../../aspose.html/htmlelement/) и добавляет его в конец формы. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Создает новый[`InputElement`](../inputelement/) и добавляет его в конец формы. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Создает новый[`InputElement`](../inputelement/) и добавляет его в конец формы. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Освобождает неуправляемые и управляемые ресурсы. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Этот метод заполняет всю форму указанными значениями. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Возвращает элемент по указанному индексу. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Возвращает элемент по указанному имени. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Получает перечислитель. |

### Смотрите также

* class [FormElement](../formelement/)
* пространство имен [Aspose.Html.Forms](../../aspose.html.forms/)
* сборка [Aspose.HTML](../../)


