---
title: "ICSSKeyframesRule.FindRule"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSKeyframesRule メソッド。findRule メソッドは、渡されたキーと一致するキーを持つ規則を返します。該当する規則が存在しない場合は null 値が返されます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icsskeyframesrule/findrule/
---
## ICSSKeyframesRule.FindRule method

findRule メソッドは、渡されたキーと一致するキーを持つルールを返します。そのようなルールが存在しない場合、null が返されます。

```java
public ICSSKeyframeRule FindRule(String key)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| キー | 文字列 | 検索する規則を記述するキーです。キーは 0 から 1 の間の数値に解決できなければならず、そうでない場合は規則は無視されます。 |

### 戻り値

指定されたキーフレームセレクタに一致する最後に宣言された [`CSSKeyframeRule`](../../icsskeyframerule/) を返します。該当する規則が存在しない場合、メソッドは何もしません。

### 関連項目

* interface [ICSSKeyframeRule](../../icsskeyframerule/)
* interface [ICSSKeyframesRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
