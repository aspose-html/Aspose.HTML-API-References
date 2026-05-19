---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IStyleSheet プロパティ。スタイルシートのインクルージョン概念をサポートするスタイルシート言語の場合、この属性は存在すればインクルード元のスタイルシートを表します。スタイルシートがトップレベルのスタイルシートであるか、インクルージョンをサポートしない言語の場合、この属性の値は null です。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

スタイルシートのインクルージョン概念をサポートするスタイルシート言語では、この属性は存在すればインクルード元のスタイルシートを表します。スタイルシートがトップレベルのスタイルシートである場合、またはインクルージョンをサポートしない言語の場合、この属性の値は null です。

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

parentStyleSheet 属性は、親の [`CSS style sheet`](../../icssstylesheet/) を返す必要があります。

## Remarks

現在のスタイルシートがトップレベルのスタイルシートであるか、スタイルシートのインクルージョンがサポートされていない場合、このプロパティは null を返します。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### 関連項目

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
