---
title: "FormEditor クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.forms.FormEditor クラス。このクラスは HTMLFormElement のエディタを表し、.net 開発者が HTML フォームを編集するための簡単な方法を提供します。"
type: docs

url: /ja/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

このクラスは [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) のエディタを表し、.net 開発者が HTML フォームを編集するための簡単な方法を提供します。

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) フォーム内のフォームコントロールの数です。 |
| [getForm](../../com.aspose.html.forms/formeditor/form/) 現在の `FormEditor` インスタンスに関連付けられている元の [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) です。 |
| [getItem](../../com.aspose.html.forms/formeditor/item/) 指定されたインデックスで要素を返します。（2 つのインデクサー） |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | `FormEditor` を新しく作成し、[`HTMLFormElement`](../../com.aspose.html/htmlformelement/) を基にします。 |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | インデックスで [`Forms`](../../com.aspose.html/htmldocument/forms/) コレクションから選択された [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) を基に新しい `FormEditor` を作成します。 |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | ドキュメントから ID で選択された [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) を基に新しい `FormEditor` を作成します。 |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 新しい [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) を作成し、`FormEditor` に関連付けます。[`HTMLFormElement`](../../com.aspose.html/htmlformelement/) はドキュメントから切り離された状態で作成されます。ドキュメントに添付するには、適切な場所を選択し、[`AppendChild`](../../com.aspose.html.dom/node/appendchild/) メソッドを使用してください。 |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | 新しい [`HTMLElement`](../../com.aspose.html/htmlelement/) を作成し、フォームの末尾に追加します。 |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | 新しい [`InputElement`](../inputelement/) を作成し、フォームの末尾に追加します。 |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | 新しい [`InputElement`](../inputelement/) を作成し、フォームの末尾に追加します。 |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | アンマネージドおよびマネージドリソースを解放します。 |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | 指定されたインデックスで要素を返します。 |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | 指定された名前で要素を返します。 |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | 列挙子を取得します。 |

### 関連項目

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
