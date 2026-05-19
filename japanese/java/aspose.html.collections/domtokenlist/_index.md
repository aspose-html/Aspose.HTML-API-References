---
title: "DOMTokenList クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.collections.DOMTokenList クラス。DOMTokenList クラスはスペースで区切られたトークンの集合を表します。JavaScript の配列オブジェクトと同様に、0 からインデックス付けされます。DOMTokenList は常に大文字小文字を区別します。"
type: docs

url: /ja/java/com.aspose.html.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList クラスは、スペースで区切られたトークンの集合を表します。JavaScript の Array オブジェクトと同様に 0 からインデックス付けされます。DOMTokenList は常に大文字小文字を区別します。

```java
public class DOMTokenList : DOMObject, IEnumerable<String>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.collections/domtokenlist/item/) インデックスでリスト内の項目を返します。インデックスがリストの長さ以上の場合は null を返します。 |
| [getLength](../../com.aspose.html.collections/domtokenlist/length/) このリストに格納されているトークン数を表す ulong を返します。 |
[getValue]
[setValue] Gets or sets the value of a corresponding attribute. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [add](../../com.aspose.html.collections/domtokenlist/add/)(params String[]) | 指定されたトークンをリストに追加します。 |
| [contains](../../com.aspose.html.collections/domtokenlist/contains/)(String) | リストが指定されたトークンを含んでいる場合は true、そうでなければ false を返します。 |
| [getEnumerator](../../com.aspose.html.collections/domtokenlist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [remove](../../com.aspose.html.collections/domtokenlist/remove/)(params String[]) | 指定されたトークンをリストから削除します。 |
| [replace](../../com.aspose.html.collections/domtokenlist/replace/)(String, String) | 既存のトークンを新しいトークンに置き換えます。最初のトークンが存在しない場合は何もしません。 |
| [supports](../../com.aspose.html.collections/domtokenlist/supports/)(String) | 指定されたトークンが関連属性のサポート対象トークンに含まれている場合は true を返します。 |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle)(String) | トークンがリストに存在すれば削除し、存在しなければリストに追加します。 |
| [toggle](../../com.aspose.html.collections/domtokenlist/toggle/#toggle_1)(String, bool) | トークンがリストに存在すれば削除し、存在しなければリストに追加します。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
