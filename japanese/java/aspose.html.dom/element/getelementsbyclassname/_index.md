---
title: "Element.GetElementsByClassName"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Element メソッド。 引数で指定されたすべてのクラスを持つ要素を含む HTMLCollection オブジェクトを返します。"
type: docs

url: /ja/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

引数で指定されたすべてのクラスを持つ要素を含む [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。これは、[`element`](../) 内のすべての要素を対象とし、指定されたクラスをすべて持っています。

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| classNames | 文字列 | 文字列文字列は、クラス（クラス名）を表すユニークな空白区切りトークンの順序なし集合を含みます。 |

### 戻り値

[`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) オブジェクトは、[`elements`](../) の配列のようなリストです。

## 備考

公式の[spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname)を参照してください。

以下の[documentation](https://docs.aspose.com/html/net/)にも興味があるかもしれません。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
# HTML source content
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// ユーザーコードはここに記述します
}
```

*inputHtmlPath - user input html file path.

# Console output

見つかりました: 2

pStyleクラスでスタイル設定された段落の内容...

pStyle クラスでスタイル設定された div 要素...

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
