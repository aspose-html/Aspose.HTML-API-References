---
title: "ICSSRule インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSRule インターフェイス。CSSRule インターフェイスは、すべての種類の CSS 文の抽象基底インターフェイスです。これにはルールセットと at-rule の両方が含まれます。実装は、パーサーが認識しないルールであっても、CSS スタイルシートに指定されたすべてのルールを保持することが期待されます。認識されないルールはこのインターフェイスで表現されます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule インターフェイスは、あらゆる種類の CSS 文の抽象基底インターフェイスです。これにはルールセットと at-rule の両方が含まれます。実装は、パーサーが認識しない場合でも、CSS スタイルシートで指定されたすべてのルールを保持することが期待されます。認識されないルールはこのインターフェイスで表現されます。

```java
public interface ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) このルールが別のルール内に含まれている場合（例: @media ブロック内のスタイルルール）、それが包含するルールです。ルールが他のルールにネストされていない場合は null を返します。 |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) `CSSRule` インターフェイスの parentStyleSheet プロパティは、現在のルールが定義されている [`StyleSheet`](../istylesheet/) オブジェクトを返します。 |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) ルールのタイプは、[CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type) で定義されています。バインディング固有のキャストメソッドを使用して、CSSRule インターフェイスのインスタンスからタイプが示す特定の派生インターフェイスへダウンキャストできることが期待されています。 |

### 関連項目

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
