---
title: "IStyleSheet.Media"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IStyleSheet プロパティ。StyleSheet インターフェイスの media プロパティは、スタイル情報の対象となるメディアを指定します。これは読み取り専用の配列のような MediaList オブジェクトで、deleteMedium で削除し、appendMedium で追加できます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheet/media/
---
## IStyleSheet.Media property

[`StyleSheet`](../) インターフェイスの media プロパティは、スタイル情報の対象となるメディアを指定します。これは読み取り専用で配列のような [`MediaList`](../../imedialist/) オブジェクトで、deleteMedium() で削除し、appendMedium() で追加できます。

```java
public IMediaList Media { get; }
```

### Property Value

media属性は、CSSスタイルシートに関連付けられた [`MediaList`](../../imedialist/) オブジェクトを返す必要があります。

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-media](https://drafts.csswg.org/cssom/#dom-stylesheet-media) – The CSSOM definition.

### 関連項目

* interface [IMediaList](../../imedialist/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
