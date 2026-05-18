---
title: "FormSubmitter 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.forms.FormSubmitter 类。此类允许准备指定的 HTMLFormElement，收集表单元素的值，将其提交到远程服务器并接收响应。"
type: docs

url: /zh/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

此类允许准备指定的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)，收集表单元素的值，提交它们到远程服务器并接收响应。

```java
public class FormSubmitter : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | 初始化 `FormSubmitter` 类的新实例。 |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | 基于 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 初始化 `FormSubmitter` 类的新实例。 |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | 基于从 [`HTMLDocument`](../../com.aspose.html/htmldocument/) 中按索引选择的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 初始化 `FormSubmitter` 类的新实例。 |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | 基于从 [`HTMLDocument`](../../com.aspose.html/htmldocument/) 中按标识符选择的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 初始化 `FormSubmitter` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | 将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | 使用指定的 cookie 将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | 使用指定的用户凭据将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | 使用指定的超时时间将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | 使用指定的用户凭据和 Cookie 将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | 使用指定的用户凭据和超时时间将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | 使用指定的超时时间和 Cookie 将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | 使用指定的用户凭据将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | 使用指定的用户凭据、超时时间和 Cookie 将表单数据提交到服务器。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | 使用指定的用户凭据和 Cookie 将表单数据提交到服务器。 |

### 另请参阅

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
