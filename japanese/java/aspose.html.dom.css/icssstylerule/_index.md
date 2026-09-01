---
title: "ICSSStyleRule インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSStyleRule インターフェイス。CSSStyleRule インターフェイスは単一の CSS スタイルルールを表します。取得時の selectorText 属性は、関連付けられたセレクタ群をシリアライズした結果を返す必要があります。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstylerule/
---
## ICSSStyleRule interface

CSSStyleRule インターフェイスは単一の CSS スタイルルールを表します。selectorText 属性は取得時に、関連付けられたセレクタのグループをシリアライズした結果を返す必要があります。

```java
public interface ICSSStyleRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getSelectorText](../../com.aspose.html.dom.css/icssstylerule/selectortext/) ルールセットのセレクタのテキスト表現です。実装はセレクタを解析する際に、重要でない空白を除去している可能性があります。 |
| [getStyle](../../com.aspose.html.dom.css/icssstylerule/style/) 読み取り専用の style プロパティは、`CSSStyleRule` の宣言ブロック用の [`CSSStyleDeclaration`](../icssstyledeclaration/) インターフェイスです。 |

### 関連項目

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
