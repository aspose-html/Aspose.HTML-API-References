---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。 このメソッドは DocumentType オブジェクトを返します。このオブジェクトは、ドキュメント作成時に DOMImplementation.createDocument と共に使用することも、Node.insertBefore や Node.replaceChild などのメソッドでドキュメントに挿入することもできます。"
type: docs

url: /ja/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

このメソッドは [`DocumentType`](../../documenttype/) オブジェクトを返します。このオブジェクトは、ドキュメント作成時に DOMImplementation.createDocument と共に使用することも、Node.insertBefore() や Node.replaceChild() などのメソッドでドキュメントに挿入することもできます。

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 名前 | 文字列 | 修飾名（例: svg:svg）を含む DOMString です。 |
| publicId | 文字列 | PUBLIC 識別子を含む DOMString です。 |
| systemId | 文字列 | SYSTEM 識別子を含む DOMString です。 |
| internalSubset | 文字列 | 内部サブセットです。 |

### 戻り値

この[`DocumentType`](../../documenttype/)。

## 例

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### 関連項目

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
