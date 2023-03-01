---
title: Class FormEditor
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Forms.FormEditor クラス. このクラスはHTMLFormElementこれにより.net 開発者が HTML フォームを簡単に編集できるようになります
type: docs
weight: 2930
url: /ja/net/aspose.html.forms/formeditor/
---
## FormEditor class

このクラスは、[`HTMLFormElement`](../../aspose.html/htmlformelement/)これにより、.net 開発者が HTML フォームを簡単に編集できるようになります。

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | サーバー側のフォーム ハンドラー。 HTML 4.01. の action 属性の定義を参照してください。 |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | フォーム内のフォーム コントロールの数。 |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | オリジナル[`HTMLFormElement`](../../aspose.html/htmlformelement/)の現在のインスタンスに関連付けられている`FormEditor`. |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | 指定されたインデックスで要素を返します. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP メソッド [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) フォームの送信に使用されます。 HTML 4.01. のメソッド属性定義を参照してください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | 新しい`FormEditor`に基づく[`HTMLFormElement`](../../aspose.html/htmlformelement/). |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | 新しい`FormEditor`に基づく[`HTMLFormElement`](../../aspose.html/htmlformelement/)から選択された[`Forms`](../../aspose.html/htmldocument/forms/)インデックスによるコレクション. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | 新しい`FormEditor`に基づく[`HTMLFormElement`](../../aspose.html/htmlformelement/) id. によってドキュメントから選択 |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 新しい[`HTMLFormElement`](../../aspose.html/htmlformelement/)そしてそれを関連付けました`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/)ドキュメントから切り離された状態で作成されます。ドキュメントに添付するには、適切な場所を選択して使用してください[`AppendChild`](../../aspose.html.dom/node/appendchild/)method. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | 新しい[`HTMLElement`](../../aspose.html/htmlelement/)フォームの最後に追加します. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | 新しい[`InputElement`](../inputelement/)フォームの最後に追加します. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | 新しい[`InputElement`](../inputelement/)フォームの最後に追加します. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | 管理されていないリソースと管理されているリソースを解放します。 |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | このメソッドは、フォーム全体に指定された値を入力します。 |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | 指定されたインデックスで要素を返します. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | 指定された名前の要素を返します。 |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | 列挙子を取得します。 |

### 関連項目

* class [FormElement](../formelement/)
* 名前空間 [Aspose.Html.Forms](../../aspose.html.forms/)
* 組み立て [Aspose.HTML](../../)


