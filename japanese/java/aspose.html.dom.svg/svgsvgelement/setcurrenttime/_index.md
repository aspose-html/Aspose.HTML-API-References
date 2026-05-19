---
title: "SVGSVGElement.SetCurrentTime"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement のメソッドです。この SVG ドキュメントフラグメントの時計を調整し、新しい現在時刻を設定します。たとえば、ドキュメントのタイムラインが開始される前に、スクリプト要素内で実行されるスクリプトによって setCurrentTime が呼び出された場合、メソッドの最後の呼び出しで渡された秒数の値が、ドキュメントのタイムラインが開始されたときにシークされる時刻となります。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

この SVG ドキュメント フラグメントのクロックを調整し、新しい現在時刻を設定します。setCurrentTime がドキュメントのタイムラインが開始される前に呼び出された場合（たとえば、ドキュメントの SVGLoad イベントがディスパッチされる前に ‘script’ 要素内で実行されるスクリプトによる場合）、メソッドの最後の呼び出しでの秒数の値は、ドキュメントのタイムラインが開始されたときにドキュメントがシークする時刻を示します。

```java
public void SetCurrentTime(float seconds)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 秒 | Single | 現在の SVG ドキュメントフラグメントの開始時刻からの相対秒数で示す新しい現在時刻。 |

### 関連項目

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
