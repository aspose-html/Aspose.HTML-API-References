---
title: "Класс FormSubmitter"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.forms.FormSubmitter. Этот класс позволяет подготовить указанный HTMLFormElement, собирает значения из элемента формы, отправляет их на удалённый сервер и получает ответ"
type: docs

url: /ru/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

Этот класс позволяет подготовить указанный [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), собрать значения из элемента формы, отправить их на удалённый сервер и получить ответ.

```java
public class FormSubmitter : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | Инициализирует новый экземпляр класса `FormSubmitter`. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | Инициализирует новый экземпляр класса `FormSubmitter` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | Инициализирует новый экземпляр класса `FormSubmitter` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), выбранного по индексу из [`HTMLDocument`](../../com.aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | Инициализирует новый экземпляр класса `FormSubmitter` на основе [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), выбранного по идентификатору из [`HTMLDocument`](../../com.aspose.html/htmldocument/). |

## Свойства

| Имя | Описание |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Методы

| Имя | Описание |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | Освобождает неуправляемые и — при желании — управляемые ресурсы. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | Отправляет данные формы на сервер. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | Отправляет данные формы на сервер с указанными cookie. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | Отправляет данные формы на сервер с указанными учетными данными пользователя. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | Отправляет данные формы на сервер с указанным тайм-аутом. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | Отправляет данные формы на сервер с указанными учетными данными пользователя и куки. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | Отправляет данные формы на сервер с указанными учетными данными пользователя и тайм-аутом. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | Отправляет данные формы на сервер с указанным тайм-аутом и куки. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | Отправляет данные формы на сервер с указанными учетными данными пользователя. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | Отправляет данные формы на сервер с указанными учетными данными пользователя, тайм-аутом и куки. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | Отправляет данные формы на сервер с указанными учетными данными пользователя и куки. |

### См. также

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
