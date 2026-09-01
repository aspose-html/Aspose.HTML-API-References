---
title: "Document.GetElementById"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。Document メソッド getElementById は、指定された文字列と一致する id プロパティを持つ要素を表す Element オブジェクトを返します。要素の ID は指定された場合は一意である必要があるため、特定の要素に迅速にアクセスする便利な方法です。"
type: docs

url: /ja/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Document メソッド getElementById() は、指定された文字列と一致する id プロパティを持つ要素を表す [`Element`](../../element/) オブジェクトを返します。要素の ID は指定された場合は一意である必要があるため、特定の要素に迅速にアクセスする便利な方法です。

ID を持たない要素にアクセスする必要がある場合は、querySelector() を使用して任意のセレクタで要素を検索できます。

```java
public Element GetElementById(String elementId)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementId | 文字列 | 検索対象要素の ID。ID は大文字小文字を区別する文字列で、ドキュメント内で一意です。任意の ID を持つ要素は 1 つだけです。 |

### 戻り値

指定された ID と一致する DOM 要素オブジェクトを記述する [`Element`](../../element/) オブジェクト、または一致する要素がドキュメントに見つからなかった場合は null を返します。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) を参照してください。

実践的なウェブ開発コンテンツは [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp) にあります。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

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
