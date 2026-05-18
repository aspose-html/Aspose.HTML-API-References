---
title: "IMediaList 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.IMediaList 接口。MediaList 接口提供了有序媒体集合的抽象，而不定义或约束该集合的实现方式。空列表等同于包含所有媒体的列表。"
type: docs

url: /zh/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList 接口提供媒体有序集合的抽象，而不定义或约束该集合的实现方式。空列表等同于包含媒体 "all" 的列表。

另请参阅 [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface)。

```java
public interface IMediaList : IEnumerable<String>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) item(index) 方法必须返回由索引指定的媒体查询集合中的媒体查询的序列化字符串，如果索引大于或等于媒体查询集合的数量，则返回 null。 |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) length 属性必须返回媒体查询集合中的媒体查询数量。有效的索引范围为 0 到 length-1（含）。 |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) 一个字符串化器，返回表示 MediaList 为文本的 DOMString，并且允许您设置一个新的 MediaList。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | 将媒体 newMedium 添加到列表末尾。如果 newMedium 已经存在，则先将其移除。 |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | 从列表中删除由 oldMedium 指示的媒体。 |

## 备注

注意：MediaList 是实时列表；使用下面列出的属性或方法更新列表会立即影响文档的行为。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## 示例

以下代码将在控制台输出当前文档应用的第一个样式表的 MediaList 的文本表示。

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### 另请参阅

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
