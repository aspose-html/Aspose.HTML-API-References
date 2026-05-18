---
title: "License.SetLicense"
second_title: "Aspose.HTML for Java API 参考"
description: "License 方法。为组件授权"
type: docs

url: /zh/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

对组件进行授权。

```java
public void SetLicense(String licenseName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | String | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串可切换到评估模式。 |

## 备注

尝试在以下位置查找许可证：

1. 明确路径。

2. 包含 Aspose 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明确路径。

2. 客户端调用程序集中的嵌入资源。

2. 包含 Aspose 组件 JAR 文件的文件夹。

3. 包含客户端调用 JAR 文件的文件夹。

## 示例

在本示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

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

### 另请参阅

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

对组件进行授权。

```java
public void SetLicense(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 包含许可证的流。 |

## 备注

使用此方法从流中加载许可证。

## 示例

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### 另请参阅

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
