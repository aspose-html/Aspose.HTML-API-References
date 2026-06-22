---
title: "ITrueTypeFont интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.drawing.ITrueTypeFont интерфейс. Объявляет методы для работы с шрифтом TrueType"
type: docs

url: /ru/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Объявляет методы работы с шрифтом TrueType.

```java
public interface ITrueTypeFont
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Возвращает размер данных шрифта в байтах |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Получить имя семейства шрифта. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Это должно быть сочетание "FamilyName" и "SubFamilyName". Исключение: если шрифт имеет значение "Regular", как указано в "SubFamilyName", использовать только имя семейства, содержащееся в "FamilyName". Исключение из вышеописанного определения полного имени шрифта относится к строкам платформы Microsoft для шрифтов CFF OpenType: в этом случае строка полного имени шрифта должна быть идентична PostScript FontName в CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Имя подсемейства шрифта отличает шрифт в группе с тем же именем семейства шрифта. Предполагается, что это относится к стилю (italic, oblique) и толщине (light, bold, black и т.д.). Шрифт без особых различий в толщине или стиле (например, средняя толщина, не italic и установлен бит fsSelection 6) должен иметь строку "Regular" в этом поле. |

## Методы

| Имя | Описание |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Возвращает ascent в пунктах. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Откройте поток с данными шрифта. Вызывающий код отвечает за освобождение потока. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Возвращает descent в пунктах. |

### См. также

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
