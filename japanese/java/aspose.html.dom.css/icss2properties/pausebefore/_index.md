---
title: "ICSS2Properties.PauseBefore"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。これらのプロパティは、要素の内容を読み上げる前または後に取るべき一時停止を指定します。値は以下の意味を持ちます"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/pausebefore/
---
## ICSS2Properties.PauseBefore property

これらのプロパティは、要素の内容を読み上げる前（または後）に取るべき一時停止を指定します。値は以下の意味を持ちます：

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - 絶対時間単位（秒とミリ秒）で一時停止を表します。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate) プロパティの値の逆数を参照します。例えば、speech-rate が 1 分間に 120 語（すなわち 1 語が 0.5 秒、または 500ms）である場合、['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) が 100% のときは 500 ms の一時停止、['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) が 20% のときは 100ms を意味します。

```java
public String PauseBefore { get; set; }
```

### 戻り値

pause-before プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
