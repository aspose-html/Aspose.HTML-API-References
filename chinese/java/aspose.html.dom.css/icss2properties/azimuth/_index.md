---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。空间音频是听觉呈现的重要风格属性。它提供了一种自然的方式来区分多个声音，就像在现实生活中人们很少全部站在房间的同一个位置。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

空间音频是听觉呈现的重要风格属性。它提供了一种自然的方式来区分多个声音，就像在现实生活中（人们很少全部站在房间的同一位置）。

```java
public String Azimuth { get; set; }
```

### 返回值

azimuth 属性

### Property Value

以下值的含义如下：

angle - 位置以角度描述，范围为 '-360deg' 到 '360deg'。数值 '0deg' 表示正前方，位于声场中心。'90deg' 表示向右，'180deg' 表示在后方，'270deg'（或等价且更方便的 '-90deg'）表示向左。

left-side - 等同于 '270deg'。在 'behind' 时为 '270deg'。

far-left - 等同于 '300deg'。在 'behind' 时为 '240deg'。

left - 等同于 '320deg'。在 'behind' 时为 '220deg'。

center-left - 等同于 '340deg'。在 'behind' 时为 '200deg'。

center - 等同于 '0deg'。在 'behind' 时为 '180deg'。

center-right - 等同于 '20deg'。在 'behind' 时为 '160deg'。

right - 等同于 '40deg'。在 'behind' 时为 '140deg'。

far-right - 等同于 '60deg'。在 'behind' 时为 '120deg'。

right-side - 等同于 '90deg'。在 'behind' 时为 '90deg'。

leftwards - 将声音向左移动，相对于当前角度。更精确地说，减去 20 度。运算采用模 360 度进行。注意，'leftwards' 更准确的描述是 "逆时针旋转"，因为它始终减去 20 度，即使继承的 azimuth 已经在听者后方（此时声音实际上会向右移动）。

rightwards - 将声音向右移动，相对于当前角度。更精确地说，增加 20 度。算术细节请参见 'leftwards'。

### 另请参阅

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
