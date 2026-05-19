---
title: "ICSSRule.ParentRule"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSRule プロパティ。このルールが別のルール（例: メディアブロック内のスタイルルール）に含まれている場合、これは包含するルールです。このルールが他のルールにネストされていない場合は null を返します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

このルールが別のルール（例: @media ブロック内のスタイルルール）に含まれている場合、これは包含するルールです。このルールが他のルールにネストされていない場合は null を返します。

```java
public ICSSRule ParentRule { get; }
```

### Property Value

包含するルールの型である [`CSSRule`](../) です。現在のルールがメディアクエリ内にある場合、[`CSSMediaRule`](../../icssmediarule/) を返します。そうでなければ null を返します。

### 関連項目

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
