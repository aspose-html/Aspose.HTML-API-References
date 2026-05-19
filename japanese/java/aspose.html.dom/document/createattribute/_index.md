---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。Document.createAttribute メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは Attr インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。"
type: docs

url: /ja/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Document.createAttribute() メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [`Attr`](../../attr/) インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| localName | 文字列 | name は属性の名前を含む文字列です。 |

### 戻り値

[`Attr`](../../attr/) ノードです。

## 例

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### 関連項目

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
