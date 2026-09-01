---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Element メソッド。指定されたタグ名を持つすべての要素を文書順で含む HTMLCollection オブジェクトを返します"
type: docs

url: /ja/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

指定されたタグ名を持つすべての[`elements`](../) を文書順で含む [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。

```java
public HTMLCollection GetElementsByTagName(String name)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | タグ名。タグ名の文字列表現です。 |

### 戻り値

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトは、[`elements`](../) の配列のようなリストです。

## 備考

公式の[spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname)を参照してください。

以下の[documentation](https://docs.aspose.com/html/net/)にも興味があるかもしれません。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
# Html input content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// ユーザーコードはここに記述します

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// ユーザーコードはここに記述します
}
```

*inputHtmlPath - user input html file.

# Console output

見つかりました: 3

pStyleクラスでスタイル設定された段落の内容...

2番目の段落の内容...

3番目の段落の内容...

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
