---
title: "Document.GetElementsByClassName"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。Document インターフェイスの getElementsByClassName メソッドは、指定されたすべてのクラス名を持つすべての子要素の配列に似たオブジェクトを返します。"
type: docs

url: /ja/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

「[`Document`](../)」インターフェイスの getElementsByClassName メソッドは、指定されたすべてのクラス名を持つすべての子要素の配列に似たオブジェクトを返します。

document オブジェクトで呼び出すと、ルートノードを含む文書全体が検索されます。また、任意の要素で getElementsByClassName() を呼び出すこともでき、その場合は指定されたルート要素の子孫で、指定されたクラス名を持つ要素のみが返されます。

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| classNames | 文字列 | 文字列 String は、クラス（クラス名）を表す一意のスペース区切りトークンの順序なし集合を含みます。 |

### 戻り値

見つかった要素のライブ [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/)。

## Remarks

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) を参照してください。

実践的なウェブ開発コンテンツは [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp) で見つけることができます。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## 例

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// HTML コンテンツ
<div class="custom-class">Customized by css class container</div>

// C# コード
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// ユーザーコードはここに記述します
}
```

// コンソール出力

見つかりました: 1

CSS クラス container によってカスタマイズされました。

*inputHtmlPath - user input html file path

```java
// CSS スタイリング
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// HTML コンテンツ
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// ユーザーコードはここに記述します
}
```

# Console output

見つかりました: 2

クラス名 =ddd kkk= によってスタイルが適用された段落

要素タイプ: Aspose.Html.HTMLParagraphElement

クラス名 =ddd fff= によってスタイルが適用された段落

要素タイプ: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// CSS スタイリング
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// ユーザーコードはここに記述します
}
```

# Console output

見つかりました: 4

pStyle クラスの段落で最初にスタイルが適用されました

要素タイプ: Aspose.Html.HTMLParagraphElement

pStyle クラスの段落で2番目にスタイルが適用されました

要素タイプ: Aspose.Html.HTMLParagraphElement

pStyle クラスの段落で3番目にスタイルが適用されました

要素タイプ: Aspose.Html.HTMLParagraphElement

pStyle によってスタイル付けされた Span

要素タイプ: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
