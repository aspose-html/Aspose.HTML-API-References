---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。Document インターフェイスの getElementsByTagName メソッドは、指定されたタグ名を持つ要素の HTMLCollection を返します"
type: docs

url: /ja/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

[`Document`](../) インターフェイスの getElementsByTagName メソッドは、指定されたタグ名を持つ要素の [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) を返します。

ルートノードを含む完全なドキュメントが検索されます。返される [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) はライブであり、document.getElementsByTagName() を再度呼び出すことなく、DOM ツリーと自動的に同期するように自動で更新されます。

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| タグ名 | 文字列 | 要素の名前を表す文字列。特別な文字列 "*" はすべての要素を表します。 |

### 戻り値

ツリー内に出現する順序で見つかった要素のライブ [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) を参照してください。

Web 開発の実践コンテンツは [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp) にあります。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // ユーザーコードはここに記述します
}
```

# Console output

見つかりました: 6

pStyle クラスでスタイル設定された最初の段落

pStyle クラスでスタイル設定された2番目の段落

pStyle クラスでスタイル設定された3番目の段落

クラス名 =ddd kkk= でスタイル設定された段落

クラス名 =ddd fff= でスタイル設定された段落

クラス名 =kkk fff= でスタイル設定された段落

*inputHtmlPath - user input html file path

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
