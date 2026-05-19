---
title: "Интерфейс ITrueTypeFont"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.drawing.ITrueTypeFont. Объявляет методы для работы с шрифтом TrueType"
type: docs

url: /ru/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Объявляет методы для работы с шрифтом TrueType.

```java
public interface ITrueTypeFont
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Возвращает размер данных шрифта в байтах |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Получает название семейства шрифта. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Это должно быть сочетание "FamilyName" и "SubFamilyName". Исключение: если шрифт имеет значение "Regular", указанное в "SubFamilyName", использовать только название семейства из "FamilyName". Исключение из вышеописанного определения полного имени шрифта относится к строкам Microsoft для шрифтов CFF OpenType: в этом случае строка полного имени шрифта должна быть идентична PostScript FontName в индексе CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Имя подсемейства шрифта различает шрифт в группе с одинаковым названием семейства шрифта. Предполагается, что оно отражает стиль (italic, oblique) и насыщенность (light, bold, black и т.д.). Шрифт без особых различий в весе или стиле (например, средний вес, без наклона и установленный бит fsSelection 6) должен иметь строку "Regular" в этом поле. |

## Методы

| Имя | Описание |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Возвращает значение ascent в пунктах. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Открывает поток с данными шрифта. Вызывающая сторона отвечает за освобождение потока. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Возвращает значение descent в пунктах. |

### См. также

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
