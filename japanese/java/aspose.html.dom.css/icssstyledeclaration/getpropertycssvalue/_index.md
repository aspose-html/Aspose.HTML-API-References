---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSStyleDeclaration メソッド。この宣言ブロック内で明示的に設定された CSS プロパティの値のオブジェクト表現を取得するために使用します。プロパティがショートハンドの場合、このメソッドは null を返します。ショートハンドプロパティの値は、getPropertyValue および setProperty メソッドを使用して文字列としてのみアクセスおよび変更できます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

この宣言ブロック内で明示的に設定された場合、CSS プロパティの値のオブジェクト表現を取得するために使用されます。プロパティがショートハンドの場合、このメソッドは null を返します。ショートハンドプロパティの値は、getPropertyValue および setProperty メソッドを使用して文字列としてのみアクセスおよび変更できます。

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyName | 文字列 | propertyName は、取得するプロパティ名を表す文字列です。 |

### 戻り値

value は、プロパティの CSS 値を含む CSSValue です。存在しない場合は null を返します。

### 関連項目

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
