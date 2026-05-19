---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。指定されたタグ名を持ち、指定されたパッケージに属する要素のリストを返します。ルートノードを含む文書全体が検索されます"
type: docs

url: /ja/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

指定されたパッケージに属する、指定されたタグ名を持つ要素のリストを返します。ルートノードを含むドキュメント全体が検索されます。

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| packageURI | 文字列 | 検索対象要素のパッケージ URI。 |
| localName | 文字列 | 検索対象の要素のローカル名、またはすべての要素に一致する特別な値 * のいずれかです。 |

### 戻り値

ツリーに現れる順序で見つかった要素のライブ [`NodeList`](../../../com.aspose.html.collections/nodelist/)（ただし下記の注意を参照）。

## Remarks

公式の [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) を参照してください。

Web 開発の実践コンテンツは [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp) にあります。

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## 例

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // ユーザーコードはここに記述します
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// ユーザーコードはここに記述します
}
```

# Console output

見つかりました: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### 関連項目

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
