---
title: "IWindowTimers 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.window.IWindowTimers 接口。允许作者安排基于计时器的回调。"
type: docs

url: /zh/java/com.aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

允许作者安排基于计时器的回调。

```java
public interface IWindowTimers
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [clearInterval](../../com.aspose.html.window/iwindowtimers/clearinterval/)(int) | 取消由 handle 标识的 setInterval() 设置的超时。 |
| [clearTimeout](../../com.aspose.html.window/iwindowtimers/cleartimeout/)(int) | 取消由 handle 标识的 setTimeout() 设置的超时。 |
| [setInterval](../../com.aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | 安排一个超时，以每隔 timeout 毫秒运行处理程序。任何参数都会直接传递给处理程序。 |
| [setTimeout](../../com.aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | 安排一个超时，以在 timeout 毫秒后运行处理程序。任何参数都会直接传递给处理程序。 |

### 另请参阅

* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
