---
title: "Document.GetElementById"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。Document のメソッド getElementById は、指定された文字列と id プロパティが一致する要素を表す Element オブジェクトを返します。要素の ID は指定された場合に一意であることが求められるため、特定の要素に素早くアクセスする便利な方法です。"
type: docs

url: /ja/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

The Document のメソッド getElementById() は、指定された文字列と id プロパティが一致する要素を表す [`Element`](../../element/) オブジェクトを返します。要素の ID は指定された場合に一意である必要があるため、特定の要素に素早くアクセスする便利な手段です。

ID を持たない要素にアクセスする必要がある場合は、任意のセレクタを使用して要素を検索できる querySelector() を利用できます。

```java
public Element GetElementById(String elementId)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| elementId | 文字列 | 対象要素の ID。ID は大文字小文字を区別する文字列で、ドキュメント内で一意です。任意の ID を持つ要素は 1 つだけです。 |

### 戻り値

指定された ID と一致する DOM 要素を表す [`Element`](../../element/) オブジェクト、または一致する要素がドキュメント内に見つからなかった場合は null。

## Remarks

公式の [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) を参照してください。

Web 開発の実践コンテンツは [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp) にあります。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## 例

```java
// HTML コンテンツ
<div id="uniqueIdentifier">Container with ID - identifier</div>

// C# コード
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// ユーザーコードはここに記述します
   }
```

// コンソール出力

ID を持つコンテナ - 識別子

*inputHtmlPath - user input html file path

### 関連項目

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
