---
title: "ICSS2Properties.FontWeight"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。font-weight 属性指定字体的粗细。其取值含义如下"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

‘font-weight’ 属性指定字体的粗细。其取值含义如下：

100 到 900 - 这些值形成一个有序序列，每个数字表示至少与前一个相同或更粗的粗细。normal - 等同于 '400'。bold - 等同于 '700'。bolder - 指定比继承的粗细更粗的下一个粗细。如果不存在这样的粗细，则直接使用下一个更粗的数值（字体保持不变），除非继承值为 '900'，此时结果粗细仍为 '900'。lighter - 指定比继承的粗细更细的下一个粗细。如果不存在这样的粗细，则直接使用下一个更细的数值（字体保持不变），除非继承值为 '100'，此时结果粗细仍为 '100'。

```java
public String FontWeight { get; set; }
```

### 返回值

font-weight 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
