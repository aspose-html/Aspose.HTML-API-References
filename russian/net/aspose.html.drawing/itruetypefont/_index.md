---
title: Interface ITrueTypeFont
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Drawing.ITrueTypeFont интерфейс. Объявляет методы работы со шрифтом TrueType.
type: docs
weight: 2760
url: /ru/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Объявляет методы работы со шрифтом TrueType.

```csharp
public interface ITrueTypeFont
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Возвращает размер данных шрифта в байтах |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Получить название семейства шрифтов. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Это должно быть сочетание "FamilyName" и "SubFamilyName". Исключение: если шрифт «Обычный», как указано в «SubFamilyName», используйте только имя семейства, содержащееся в «FamilyName». Исключением из приведенного выше определения полного имени шрифта являются строки платформы Microsoft. для шрифтов CFF OpenType: в этом случае строка полного имени шрифта должна быть идентична PostScript FontName в имени CFF INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | Имя подсемейства шрифтов отличает шрифт в группе с таким же именем семейства шрифтов. Предполагается, что это стиль адреса (курсив, наклон) и насыщенность (светлый, полужирный, черный и т. д.). Шрифт без особых различий в жирности или стиле (например, средний жирность, не курсив и установлен бит 6 fsSelection) должен иметь строку «Обычный», сохраненную в этой позиции. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Возвращает подъем в пунктах. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Открыть поток с данными шрифта. Вызывающий отвечает за удаление потока. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Возвращает спуск в пунктах. |

### Смотрите также

* пространство имен [Aspose.Html.Drawing](../../aspose.html.drawing/)
* сборка [Aspose.HTML](../../)


