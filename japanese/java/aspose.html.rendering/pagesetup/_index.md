---
title: "PageSetup クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.PageSetup クラス。 ページ設定オブジェクトを表し、出力ページセットの構成に使用されます。"
type: docs

url: /ja/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

ページ設定オブジェクトを表し、出力ページセットの構成に使用されます。

```java
public class PageSetup
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) 奇数ページの構成を取得します。 |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) 偶数ページの構成を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | 左/右ページの構成を設定します。 |

### 関連項目

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
