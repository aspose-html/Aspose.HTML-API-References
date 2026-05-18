---
title: "Event.PreventDefault"
second_title: "Aspose.HTML for Java API 参考"
description: "事件方法。如果事件是可取消的，则使用 PreventDefault 方法表示该事件将被取消，这意味着实现通常因该事件而采取的任何默认操作都不会发生。"
type: docs

url: /zh/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

如果事件是可取消的，`PreventDefault` 方法用于表示该事件将被取消，这意味着实现通常因该事件而采取的任何默认操作都不会发生。

```java
public void PreventDefault()
```

## 备注

如果在事件流的任何阶段调用 `PreventDefault` 方法，则事件被取消。与该事件关联的任何默认操作都不会发生。对不可取消的事件调用此方法没有任何效果。一旦调用了 `PreventDefault`，它将在事件传播的剩余阶段保持生效。此方法可在事件流的任何阶段使用。

### 另请参阅

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
