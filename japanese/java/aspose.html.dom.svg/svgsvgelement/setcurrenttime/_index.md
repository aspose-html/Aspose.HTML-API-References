---
title: "SVGSVGElement.SetCurrentTime"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement メソッド。この SVG ドキュメントフラグメントの時計を調整し、新しい現在時刻を設定します。たとえば、ドキュメントのタイムラインが開始される前に、スクリプト要素内で実行されるスクリプトによって setCurrentTime が呼び出された場合、メソッドの最後の呼び出しで渡された秒数の値は、ドキュメントのタイムラインが開始されたときにドキュメントがシークする時刻を示します。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

この SVG ドキュメントフラグメントの時計を調整し、新しい現在時刻を設定します。setCurrentTime がドキュメントのタイムラインが開始される前（例として、ドキュメントの SVGLoad イベントがディスパッチされる前に ‘script’ 要素内で実行されるスクリプトによって）に呼び出された場合、メソッドの最後の呼び出しでの seconds の値は、ドキュメントのタイムラインが開始されたときにドキュメントがシークする時刻を示します。

```java
public void SetCurrentTime(float seconds)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 秒 | Single | 現在の SVG ドキュメントフラグメントの開始時刻からの相対秒数で表した新しい現在時刻。 |

### 関連項目

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
