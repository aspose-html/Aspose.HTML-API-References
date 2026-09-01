---
title: "ICSSRuleList インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSRuleList インターフェイス。CSSRuleList は読み取り専用の CSSRule オブジェクトの順序付けられたコレクションを表します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList は読み取り専用の [`CSSRule`](../icssrule/) オブジェクトの順序付けられたコレクションを表します。

CSSRuleList オブジェクトは読み取り専用で直接変更できませんが、内容が時間とともに変化するためライブオブジェクトとみなされます。

[`CSSRule`](../icssrule/) オブジェクトが返す基礎的なルールを編集するには、[`CSSStyleSheet`](../icssstylesheet/) のメソッドである CSSStyleSheet.insertRule() と CSSStyleSheet.deleteRule() を使用します。

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) メソッド item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList) を使用して CSS ルールを取得します。このコレクション内の順序は CSS スタイルシート内のルールの順序を表します。インデックスがリスト内のルール数以上の場合、null を返します。 |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) `CSSRuleList` インターフェイスの length プロパティはリスト内の [`CSSRule`](../icssrule/) オブジェクトの数を返します。 |

### 関連項目

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
