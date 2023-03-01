---
title: Class DOMTokenList
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Collections.DOMTokenList クラス. DOMTokenList クラスはスペースで区切られたトークンのセットを表します JavaScript Array オブジェクトと同様に0 から始まるインデックスが付けられます DOMTokenList は常に大文字と小文字を区別します.
type: docs
weight: 20
url: /ja/net/aspose.html.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList クラスは、スペースで区切られたトークンのセットを表します。 JavaScript Array オブジェクトと同様に、0 から始まるインデックスが付けられます。 DOMTokenList は常に大文字と小文字を区別します.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.html.collections/domtokenlist/item/) { get; } | インデックスによってリスト内の項目を返します。インデックスがリストの長さ以上の場合は null を返します。 |
| [Length](../../aspose.html.collections/domtokenlist/length/) { get; } | このリストに格納されているトークンの数を表す ulong を返します。 |
| [Value](../../aspose.html.collections/domtokenlist/value/) { get; set; } | 対応する属性の値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.html.collections/domtokenlist/add/)(params string[]) | 指定したトークンをリストに追加します。 |
| [Contains](../../aspose.html.collections/domtokenlist/contains/)(string) | リストに特定のトークンが含まれている場合は true、そうでない場合は false を返します。 |
| [GetEnumerator](../../aspose.html.collections/domtokenlist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [Remove](../../aspose.html.collections/domtokenlist/remove/)(params string[]) | 指定したトークンをリストから削除します。 |
| [Replace](../../aspose.html.collections/domtokenlist/replace/)(string, string) | 既存のトークンを新しいトークンに置き換えます。最初のトークンが存在しない場合は何もしません. |
| [Supports](../../aspose.html.collections/domtokenlist/supports/)(string) | 指定されたトークンが関連付けられた属性のサポートされているトークンにある場合は true を返します。 |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle)(string) | トークンが存在する場合はリストから削除し、存在しない場合はトークンをリストに追加します。 |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle_1)(string, bool?) | トークンが存在する場合はリストから削除し、存在しない場合はトークンをリストに追加します。 |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* 名前空間 [Aspose.Html.Collections](../../aspose.html.collections/)
* 組み立て [Aspose.HTML](../../)


