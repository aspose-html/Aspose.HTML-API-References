---
title: "Element.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Element メソッド。指定されたローカル名とパッケージ URI 文字列を持つすべての要素を文書順で含む HTMLCollection オブジェクトを返します。"
type: docs

url: /ja/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

指定されたローカル名とパッケージ URI 文字列を持つすべての [`elements`](../) を文書順で含む [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| packageURI | 文字列 | パッケージ URI 文字列の表現です。 |
| localName | 文字列 | ローカル名の文字列表現です。 |

### 戻り値

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトは、[`elements`](../) の配列のようなリストです。

## 備考

公式の [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) を参照してください。

以下の[documentation](https://docs.aspose.com/html/net/)にも興味があるかもしれません。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
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

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// ユーザーコードはここに記述します
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

見つかりました: 1

カスタムパッケージのカスタムタグコンテンツはここに入ります...

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
