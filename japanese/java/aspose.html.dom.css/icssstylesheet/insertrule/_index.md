---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSStyleSheet メソッド。CSSStyleSheet.insertRule メソッドは、現在のスタイルシートに新しい CSS ルールをいくつかの制限付きで挿入します"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule() メソッドは、いくつかの制限付きで現在のスタイルシートに新しい CSS ルールを挿入します。

注: insertRule() は [`CSSStyleSheet`](../) の専用メソッドですが、実際には CSSStyleSheet.cssRules — その内部の [`CSSRuleList`](../../icssrulelist/) にルールを挿入します。

```java
public long InsertRule(String rule, int index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルール | 文字列 | 挿入されるルールを含む文字列。挿入されたルールが何を含むべきかは、そのタイプによって異なります： |
| index | Int32 | stylesheet.cssRules.length 以下の正の整数で、新しく挿入されたルールが CSSStyleSheet.cssRules 内で占める位置を表します。デフォルトは 0 です。 |

### 戻り値

スタイルシートのルールリスト内における新しく挿入されたルールのインデックス。

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### 関連項目

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
