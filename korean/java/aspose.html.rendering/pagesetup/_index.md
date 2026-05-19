---
title: "PageSetup 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.rendering.PageSetup 클래스. 페이지 설정 객체를 나타내며 출력 페이지 세트 구성을 위해 사용됩니다."
type: docs

url: /ko/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

출력 페이지 설정 구성을 위해 사용되는 페이지 설정 객체를 나타냅니다.

```java
public class PageSetup
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) 홀수 페이지 구성을 가져옵니다. |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) 짝수 페이지 구성을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | 좌/우 페이지 구성을 설정합니다. |

### 또 보기

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
