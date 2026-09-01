---
title: "IUrlSearchParams 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.IUrlSearchParams 接口。提供用于处理 URL 查询字符串的方法"
type: docs

url: /zh/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

提供处理 URL 查询字符串的方法。

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | 在列表中追加一个名称为 `name`、值为 `value` 的新键值对。 |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | 删除所有名称为 `name` 的键值对。 |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | 返回名称为 `name` 的第一个键值对的值。 |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | 返回所有名称为 `name` 的值。 |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | 检查列表中是否存在名称为 `name` 的键值对。 |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | 将找到的第一个名称为指定名称的键值对的值设为指定值，并删除其他键值对。如果未找到具有指定名称的键值对，则会在列表中追加一个新的键值对。 |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | 按名称对所有键值对（如果有）进行排序。 |

### 另请参见

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
