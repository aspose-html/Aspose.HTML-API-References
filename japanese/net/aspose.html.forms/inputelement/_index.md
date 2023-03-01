---
title: Class InputElement
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Forms.InputElement クラス. InputElement はHTMLInputElement. に関連付けられたラッパーを表します
type: docs
weight: 2980
url: /ja/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement は、HTMLInputElement. に関連付けられたラッパーを表します。

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | 要素の型を取得します。 |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | 入力要素の Id 属性を表します。 |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | オプションのリストを表します |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | 入力要素の name 属性を表します。 |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | フォーム コントロールのタイプ。 |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | 'value' 属性に直接マップされる入力要素の文字列値を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | このメソッドは、ファイルを[`Files`](../../aspose.html/htmlinputelement/files/)次の Web リクエスト中に送信されるコレクション. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | チェックボックス タイプの入力要素のチェック状態を返します。 |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | このメソッドは、値を色として取得するために使用されます。このメソッドは、入力要素の型のみが "color" の場合に有効です。 |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | このメソッドは、値をDateTimeオブジェクトオブジェクト。このメソッドは、入力要素の型のみが "datetime-local" の場合に有効です。 |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | このメソッドは、値をDateTime物体。このメソッドは、入力要素の型のみが "date" の場合に有効です。 |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | このメソッドは、電子メール文字列オブジェクトとして値を取得するために使用されます。このメソッドは、input 要素のタイプのみが "email" の場合に有効です。 |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | このメソッドは、値をDateTime物体。このメソッドは、入力要素のタイプのみが "month" の場合に有効です。 |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | このメソッドは、数値として値を取得するために使用されます。このメソッドは、入力要素の型のみが "number" の場合に有効です |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | このメソッドは、パスワード文字列オブジェクトとして値を取得するために使用されます。このメソッドは、入力要素のタイプのみが "password" の場合に有効です。 |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | ラジオ タイプの入力要素のチェック状態を返します。 |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | このメソッドは、値をTimeSpan物体。このメソッドは、入力要素の型のみが "time" の場合に有効です。 |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | このメソッドは、値を次のように取得するために使用されます。[`Url`](../../aspose.html/url/)物体。このメソッドは、入力要素のタイプのみが "url" の場合に有効です。 |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | このメソッドは、週の文字列として値を取得するために使用されます。このメソッドは、入力要素の型のみが "week" の場合に有効です。 |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | チェックボックス タイプの入力要素のチェック状態を設定します。 |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | このメソッドは、入力要素の値として色を設定するために使用されます。このメソッドは、入力要素の型が「color」 の場合のみ有効です。 |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | このメソッドは、DateTime入力要素の値としてオブジェクト。このメソッドは、入力要素の型が "datetime-local" の場合のみ有効です。 |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | このメソッドは、DateTime入力要素の値としてオブジェクト。このメソッドは、入力要素の型が「date」 のみの場合に有効です。 |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | このメソッドは、電子メール文字列を入力要素の値として設定するために使用されます。このメソッドは、入力要素の型が「email」 のみの場合に有効です。 |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | このメソッドは、DateTime入力要素の値としてオブジェクト。このメソッドは、入力要素のタイプが「月」 の場合のみ有効です。 |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | このメソッドは、数値を入力要素の値として設定するために使用されます。このメソッドは、入力要素の型が "number" の場合のみ有効です。 |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | このメソッドは、パスワード文字列を入力要素の値として設定するために使用されます。このメソッドは、入力要素の型が "password" の場合のみ有効です。 |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | ラジオ タイプの入力要素のチェック状態を設定します。 |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | このメソッドは、TimeSpan入力要素の値としてオブジェクト。このメソッドは、入力要素の型が「time」 のみの場合に有効です。 |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | このメソッドは、[`Url`](../../aspose.html/url/)入力要素の値としてオブジェクト。このメソッドは、入力要素の型が "url" の場合のみ有効です。 |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | このメソッドは、入力要素の値として「週」文字列を設定するために使用されます。このメソッドは、入力要素のタイプが「週」 の場合のみ有効です。 |

### 関連項目

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* 名前空間 [Aspose.Html.Forms](../../aspose.html.forms/)
* 組み立て [Aspose.HTML](../../)


