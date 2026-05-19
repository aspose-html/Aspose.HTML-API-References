---
title: "SVGSVGElement.GetCurrentTime"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement のメソッドです。現在の SVG ドキュメントフラグメントの開始時刻からの相対秒数で現在時刻を返します。たとえば、ドキュメントのタイムラインが開始される前に、スクリプト要素内で実行されるスクリプトによって getCurrentTime が呼び出された場合、0 が返されます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/getcurrenttime/
---
## SVGSVGElement.GetCurrentTime method

現在の SVG ドキュメントフラグメントの開始時刻からの経過秒数を返します。ドキュメントのタイムラインが開始される前に getCurrentTime が呼び出された場合（例として、ドキュメントの SVGLoad イベントが発火する前に ‘script’ 要素内のスクリプトが実行された場合）、0 が返されます。

```java
public float GetCurrentTime()
```

### 戻り値

現在の時刻（秒）。ドキュメントのタイムラインがまだ開始されていない場合は 0 が返されます。

### 関連項目

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
