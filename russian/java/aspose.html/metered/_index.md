---
title: "Класс Metered"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.Metered. Предоставляет методы для установки метерного ключа"
type: docs

url: /ru/java/com.aspose.html/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

```java
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Устанавливает публичный и приватный метерные ключи. Если вы приобрели метерную лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переключена в статус оценки; чтобы избежать этого, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Получает размер файла потребления |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Проверьте, лицензирована ли metered |

## Примеры

В этом примере будет предпринята попытка установить публичный и приватный ключ metered

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### См. также

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
