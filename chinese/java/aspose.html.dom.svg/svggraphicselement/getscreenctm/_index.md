---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGGraphicsElement 方法。返回从当前用户单位（即在对 transform 属性（如果有）应用后）到父级用户代理感知的像素的变换矩阵。对于显示设备，这理想情况下代表物理屏幕像素。对于其他设备或未知物理像素大小的环境，可以使用类似 CSS2 像素定义的算法。注意，如果该元素未挂载到文档树中，则返回 null。该方法本可以更恰当地命名为 getClientCTM，但出于历史原因仍保留为 getScreenCTM。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

返回从当前用户单位（即在应用了 ‘transform’ 属性（如果有）之后）到父用户代理所感知的 \"pixel\" 的变换矩阵。对于显示设备，理想情况下这代表物理屏幕像素。对于其他设备或物理像素大小未知的环境，则可以使用类似 CSS2 对 \"pixel\" 定义的算法。注意，如果该元素未挂载到文档树中，则返回 null。该方法本可以更恰当地命名为 getClientCTM，但出于历史原因仍保留名称 getScreenCTM。

```java
public SVGMatrix GetScreenCTM()
```

### 返回值

一个定义给定变换矩阵的 SVGMatrix 对象。

### 另请参见

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
