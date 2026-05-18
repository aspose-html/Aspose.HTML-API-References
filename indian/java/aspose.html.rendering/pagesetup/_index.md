---
title: "PageSetup क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.PageSetup क्लास। एक पेज सेटअप ऑब्जेक्ट का प्रतिनिधित्व करता है जिसका उपयोग आउटपुट पेज-सेट को कॉन्फ़िगर करने के लिए किया जाता है"
type: docs

url: /hi/java/com.aspose.html.rendering/pagesetup/
---
## PageSetup class

पेज सेटअप ऑब्जेक्ट का प्रतिनिधित्व करता है जो आउटपुट पेज-सेट को कॉन्फ़िगर करने के लिए उपयोग किया जाता है।

```java
public class PageSetup
```

## गुण

| नाम | विवरण |
| --- | --- |
[getAdjustToWidestPage]
[setAdjustToWidestPage] Gets or sets flag that determines case when page size will be adjusted to widest page in document. This options is time-consuming so time of document processing can be increased in two times. Adjustment will take place only if widest page in document is wider than page size determined in `PageSetup`. Adjusted page size will be used for all pages in document. |
[getAnyPage]
[setAnyPage] Gets or sets all pages configuration in the the page-sequence. |
[getAtPagePriority]
[setAtPagePriority] Gets or sets [`AtPagePriority`](../atpagepriority/) which will determine order of applying page size declarations. By default options will override css `@page` rules . |
[getFirstPage]
[setFirstPage] Gets or sets the first page configuration. |
| [getLeftPage](../../com.aspose.html.rendering/pagesetup/leftpage/) ऑड पेज कॉन्फ़िगरेशन प्राप्त करता है। |
[getPageLayoutOptions]
[setPageLayoutOptions] Gets or sets the [`PageLayoutOptions`](../pagelayoutoptions/). Default value is None, any other value will override the [`AdjustToWidestPage`](./adjusttowidestpage/) behaviour. Works only with HTML documents. |
| [getRightPage](../../com.aspose.html.rendering/pagesetup/rightpage/) इवन पेज कॉन्फ़िगरेशन प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [setLeftRightPage](../../com.aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | लेफ़्ट/राइट पेज कॉन्फ़िगरेशन सेट करता है। |

### संबंधित देखें

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
