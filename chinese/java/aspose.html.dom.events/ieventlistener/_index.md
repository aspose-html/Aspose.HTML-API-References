---
title: "IEventListener 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.events.IEventListener 接口。该接口是处理事件的主要方式。用户实现该接口并使用该方法注册其监听器。用户在完成使用监听器后，还应从其上移除。"
type: docs

url: /zh/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

该接口是处理事件的主要方式。用户实现该接口并使用该方法在对象上注册其监听器。用户在完成监听后还应从中移除监听器。

```java
public interface IEventListener
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | 每当发生接口已注册类型的事件时，调用此方法。 |

## 备注

当使用 cloneNode 方法复制节点时，附加到源节点的事件监听器不会附加到复制的节点上。如果用户希望将相同的事件监听器添加到新创建的副本中，必须手动添加它们。

### 另请参阅

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
