---
title: "Document.CreateElement"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。HTML ドキュメントにおいて、document.createElement メソッドは tagName で指定された HTML 要素を作成し、tagName が認識されない場合は HTMLUnknownElement を返します"
type: docs

url: /ja/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

HTML ドキュメントでは、document.createElement() メソッドは tagName で指定された HTML 要素を作成し、tagName が認識されない場合は [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) を返します。

```java
public Element CreateElement(String localName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | 文字列 | 作成する要素のタイプを指定する文字列です。作成された要素の nodeName は tagName の値で初期化されます。このメソッドでは修飾名（例: "html:a"）を使用しないでください。HTML ドキュメント上で呼び出された場合、createElement() は要素を作成する前に tagName を小文字に変換します。 |

### 戻り値

新しい [`Element`](../../element/)。

## サンプル

```java
var element = document.CreateElement(tagName);
```

### 関連項目

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
