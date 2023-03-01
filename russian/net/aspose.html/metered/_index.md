---
title: Class Metered
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Metered сорт. Предоставляет методы для установки измеренного ключа.
type: docs
weight: 3830
url: /ru/net/aspose.html/metered/
---
## Metered class

Предоставляет методы для установки измеренного ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Устанавливает лимитный открытый и закрытый ключ. Если вы покупаете лимитную лицензию, при запуске приложения должен вызываться этот API, обычно этого достаточно. Однако, если всегда не удается загрузить данные о потреблении и время превышает 24 часа, лицензия будет установлена в ознакомительный статус, во избежание такого случая, вы должны регулярно проверять статус лицензии, если это ознакомительный статус, снова вызывать этот API. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Получает потребительский кредит |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Получает размер файла потребления |

### Примеры

В этом примере будет предпринята попытка установить лимитированный открытый и закрытый ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Смотрите также

* пространство имен [Aspose.Html](../../aspose.html/)
* сборка [Aspose.HTML](../../)


