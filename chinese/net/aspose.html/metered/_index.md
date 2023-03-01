---
title: Class Metered
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Metered 班级. 提供设置计量密钥的方法
type: docs
weight: 3830
url: /zh/net/aspose.html/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Metered](metered/)() | 初始化此类的新实例。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | 设置计量公钥和私钥。 如果你购买了计量许可证，当启动应用程序时，应该调用这个 API，通常，这就足够了。 但是，如果总是上传消费数据失败，超过24小时，license会被设置为评估状态， 为避免这种情况，您应该定期检查license状态，如果是评估状态，请重新调用此API。 |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | 获得消费积分 |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | 获取消费文件大小 |

### 例子

在此示例中，将尝试设置计量公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件：

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 也可以看看

* 命名空间 [Aspose.Html](../../aspose.html/)
* 部件 [Aspose.HTML](../../)


