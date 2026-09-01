---
title: "FormSubmitter クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.forms.FormSubmitter クラス。このクラスは、指定された HTMLFormElement を準備し、フォーム要素から値を収集してリモートサーバーに送信し、レスポンスを受け取ります。"
type: docs

url: /ja/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

このクラスは、指定された [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) を準備し、フォーム要素から値を収集してリモートサーバーに送信し、レスポンスを受け取ります。

```java
public class FormSubmitter : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | `FormSubmitter` クラスの新しいインスタンスを初期化します。 |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | `FormSubmitter` クラスの新しいインスタンスを、[`HTMLFormElement`](../../com.aspose.html/htmlformelement/) に基づいて初期化します。 |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | `FormSubmitter` クラスの新しいインスタンスを、[`HTMLDocument`](../../com.aspose.html/htmldocument/) からインデックスで選択された [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) に基づいて初期化します。 |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | `FormSubmitter` クラスの新しいインスタンスを、[`HTMLDocument`](../../com.aspose.html/htmldocument/) から識別子で選択された [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) に基づいて初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | フォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | 指定されたクッキーとともにフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | 指定されたユーザー資格情報でフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | 指定されたタイムアウトでフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | 指定されたユーザー資格情報とクッキーでフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | 指定されたユーザー資格情報とタイムアウトでフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | 指定されたタイムアウトとクッキーでフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | 指定されたユーザー資格情報でフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | 指定されたユーザー資格情報、タイムアウト、クッキーでフォームデータをサーバーに送信します。 |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | 指定されたユーザー資格情報とクッキーでフォームデータをサーバーに送信します。 |

### 関連項目

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
