---
title: Class FormSubmitter
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Forms.FormSubmitter クラス. このクラスでは指定された準備を行うことができますHTMLFormElementフォーム要素から値を収集しそれらをリモートサーバーに送信して応答を受け取ります.
type: docs
weight: 2970
url: /ja/net/aspose.html.forms/formsubmitter/
---
## FormSubmitter class

このクラスでは、指定された準備を行うことができます[`HTMLFormElement`](../../aspose.html/htmlformelement/)、フォーム要素から値を収集し、それらをリモートサーバーに送信して応答を受け取ります.

```csharp
public class FormSubmitter : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | の新しいインスタンスを初期化します`FormSubmitter` class. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | の新しいインスタンスを初期化します`FormSubmitter`に基づくクラス[`HTMLFormElement`](../../aspose.html/htmlformelement/). |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | の新しいインスタンスを初期化します`FormSubmitter`に基づくクラス[`HTMLFormElement`](../../aspose.html/htmlformelement/)からインデックスで選択[`HTMLDocument`](../../aspose.html/htmldocument/). |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, string) | の新しいインスタンスを初期化します`FormSubmitter`に基づくクラス[`HTMLFormElement`](../../aspose.html/htmlformelement/)識別子によって選択された[`HTMLDocument`](../../aspose.html/htmldocument/). |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Action](../../aspose.html.forms/formsubmitter/action/) { get; set; } | サーバー側のフォーム ハンドラー。 HTML 4.01. の action 属性の定義を参照してください。 |
| [Method](../../aspose.html.forms/formsubmitter/method/) { get; set; } | HTTP メソッド [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) フォームの送信に使用されます。 HTML 4.01. のメソッド属性定義を参照してください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.html.forms/formsubmitter/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit)() | フォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | 指定した Cookie を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | 指定されたユーザー認証情報を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | 指定されたタイムアウトでフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | 指定されたユーザー認証情報と Cookie を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | 指定されたユーザー資格情報とタイムアウトを使用して、フォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | 指定されたタイムアウトと Cookie を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | 指定されたユーザー認証情報を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | 指定されたユーザー認証情報、タイムアウト、および Cookie を使用してフォーム データをサーバーに送信します。 |
| [Submit](../../aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | 指定されたユーザー認証情報と Cookie を使用してフォーム データをサーバーに送信します。 |

### 関連項目

* 名前空間 [Aspose.Html.Forms](../../aspose.html.forms/)
* 組み立て [Aspose.HTML](../../)


