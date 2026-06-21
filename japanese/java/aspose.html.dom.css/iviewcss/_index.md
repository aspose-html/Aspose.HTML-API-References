---
title: "IViewCSS インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.IViewCSS インターフェイス。IViewCSS インターフェイスは、Window オブジェクトへの拡張を表し、要素のすべての CSS プロパティ値へのアクセスを提供します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

IViewCSS インターフェイスは、Window オブジェクトへの拡張を表し、要素のすべての CSS プロパティの値へのアクセスを提供します。

特定の要素の CSS スタイルは、IViewCSS.GetComputedStyle() メソッドを使用して取得できます。

```java
public interface IViewCSS : IAbstractView
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | IViewCSS.getComputedStyle() メソッドは、アクティブなスタイルシートを適用し、これらの値に含まれる基本的な計算を解決した後、要素のすべての CSS プロパティ値を含むオブジェクトを返します。 |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | IViewCSS.getComputedStyle() メソッドは、アクティブなスタイルシートを適用し、これらの値に含まれる基本的な計算を解決した後、要素のすべての CSS プロパティ値を含むオブジェクトを返します。 |

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 関連項目

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
