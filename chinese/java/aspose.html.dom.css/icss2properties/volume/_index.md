---
title: "ICSS2Properties.Volume"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。Volume 指波形的中位音量。换句话说，音量为 50 的高度起伏的声音可能会远高于该值。整体数值可能会为了舒适而由人类调节，例如使用物理音量控制器，这会按比例同时提升 0 和 100 的数值。此属性的作用是调整动态范围。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Volume 指波形的中位音量。换句话说，音量为 50 的高度起伏的声音可能会远高于该值。整体数值可能会为了舒适而由人类调节，例如使用物理音量控制器（这会按比例同时提升 0 和 100 的数值）；此属性的作用是调整动态范围。

取值具有以下含义：

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - 任意介于 '0' 到 '100' 之间的数字。'0' 表示最小可听音量水平，100 对应最大舒适水平。'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 百分比值相对于继承值计算，然后被限制在 '0' 到 '100' 的范围内。silent - 完全没有声音。值 '0' 并不等同于 'silent'。x-soft - 等同于 '0'。soft - 等同于 '25'。medium - 等同于 '50'。loud - 等同于 '75'。x-loud - 等同于 '100'。

```java
public String Volume { get; set; }
```

### 返回值

volume 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
