---
title: "SelectElement クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.forms.SelectElement クラス。SelectElement は HTMLSelectElement に関連付けられたラッパーを表します。"
type: docs

url: /ja/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement は HTMLSelectElement に関連付けられたラッパーを表します

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) 要素のタイプを取得します。 |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | 入力要素の Id 属性を表します。 |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | 入力要素の name 属性を表します。 |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) オプションのリストを返します |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) 選択されたオプションのリストを返します |
| [getType](../../com.aspose.html.forms/selectelement/type/) このフォームコントロールのタイプです。multiple 属性が `true` の場合は文字列 "select-multiple"、`false` の場合は文字列 "select-one" になります。 |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | 取得時には、オプションのリストをツリー順に走査し、selected が true に設定されている最初の option 要素の値を返す必要があります（該当がある場合）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | このメソッドはインデックスで複数のオプションを選択できるようにします。 |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | このメソッドは値で複数のオプションを選択できるようにします。 |

### 関連項目

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
