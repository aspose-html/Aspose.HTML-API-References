---
title: "ICSSKeyframesRule インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSKeyframesRule インターフェイス。CSSKeyframeRule インターフェイスの name プロパティは、animation-name プロパティで使用されるアニメーションの名前を取得および設定します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframeRule インターフェイスの name プロパティは、animation-name プロパティで使用されるアニメーションの名前を取得および設定します。

```java
public interface ICSSKeyframesRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) [`CSSKeyframeRule`](../icsskeyframerule/) インターフェイスの読み取り専用 cssRules プロパティは、キー フレーム at-rule のルールを含む [`CSSRuleList`](../icssrulelist/) を返します。 |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) [`CSSKeyframeRule`](../icsskeyframerule/) インターフェイスの name プロパティは、animation-name プロパティで使用されるアニメーションの名前を取得および設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | appendRule メソッドは、渡された [`CSSKeyframeRule`](../icsskeyframerule/) をキー フレーム ルール コレクションの末尾に追加します。 |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | deleteRule メソッドは、渡されたキーを持つ [`CSSKeyframeRule`](../icsskeyframerule/) を削除します。そのキーのルールが存在しない場合、メソッドは何もしません。 |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | findRule メソッドは、渡されたキーと一致するキーを持つルールを返します。そのようなルールが存在しない場合、null が返されます。 |

### 関連項目

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
