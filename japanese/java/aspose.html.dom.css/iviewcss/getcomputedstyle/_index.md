---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IViewCSS メソッド。IViewCSS.getComputedStyle メソッドは、アクティブなスタイルシートを適用し、値に含まれる基本的な計算を解決した後の要素のすべての CSS プロパティ値を含むオブジェクトを返します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

IViewCSS.getComputedStyle() メソッドは、アクティブなスタイルシートを適用し、これらの値が含む可能性のある基本的な計算を解決した後、要素のすべての CSS プロパティの値を含むオブジェクトを返します。

個々の CSS プロパティ値は、オブジェクトが提供する API を通じて、または CSS プロパティ名でインデックス付けしてアクセスできます。

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| element | Element | 計算スタイルを取得する対象の [`Element`](../../../com.aspose.html.dom/element/) です。このパラメータは null にできません。 |

### 戻り値

返されるスタイルはライブ [`CSSStyleDeclaration`](../../icssstyledeclaration/) オブジェクトで、要素のスタイルが変更されると自動的に更新されます。

### 例外

| 例外 | 条件 |
| --- | --- |
| TypeError | 渡されたオブジェクトが Element でない、または pseudoElt が有効な疑似要素セレクタでない場合。 |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 関連項目

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

IViewCSS.getComputedStyle() メソッドは、アクティブなスタイルシートを適用し、これらの値が含む可能性のある基本的な計算を解決した後、要素のすべての CSS プロパティの値を含むオブジェクトを返します。

個々の CSS プロパティ値は、オブジェクトが提供する API を通じて、または CSS プロパティ名でインデックス付けしてアクセスできます。

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| element | Element | 計算スタイルを取得する対象の [`Element`](../../../com.aspose.html.dom/element/) です。このパラメータは null にできません。 |
| pseudoElement | 文字列 | マッチさせる疑似要素を指定する文字列。実際の要素の場合は省略（または null）。 |

### 戻り値

返されるスタイルはライブ [`CSSStyleDeclaration`](../../icssstyledeclaration/) オブジェクトで、要素のスタイルが変更されると自動的に更新されます。

### 例外

| 例外 | 条件 |
| --- | --- |
| TypeError | 渡されたオブジェクトが Element でない、または pseudoElt が有効な疑似要素セレクタでない場合。 |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 関連項目

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
