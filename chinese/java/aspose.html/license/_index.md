---
title: "License 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.License 类。提供对组件授权的方法。"
type: docs

url: /zh/java/com.aspose.html/license/
---
## License class

提供对组件进行授权的方法。

```java
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license/)() | 初始化此类的一个新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | 对组件进行授权。 |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | 对组件进行授权。 |

## 示例

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

组件 jar 文件：

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另请参见

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
