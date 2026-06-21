---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IStyleSheet プロパティ。このスタイルシートを文書に関連付けるノードです。HTML の場合、対応する LINK または STYLE 要素になることがあります。XML の場合、リンクする処理命令になることがあります。他のスタイルシートに含まれるスタイルシートの場合、この属性の値は null です。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

このスタイルシートを文書に関連付けるノードです。HTML の場合、対応する LINK または STYLE 要素になることがあります。XML の場合、リンクする処理命令になることがあります。他のスタイルシートに含まれるスタイルシートの場合、この属性の値は null です。

```java
public Node OwnerNode { get; }
```

### Property Value

ownerNode 属性は所有ノードを返す必要があります。

## 備考

@import などで他のスタイルシートに含まれるスタイルシートの場合、このプロパティの値は null です。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
