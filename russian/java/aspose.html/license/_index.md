---
title: "License класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.License класс. Предоставляет методы для лицензирования компонента"
type: docs

url: /ru/java/com.aspose.html/license/
---
## License class

Предоставляет методы для лицензирования компонента.

```java
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Лицензирует компонент. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Лицензирует компонент. |

## Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке основной сборки, а затем во встроенных ресурсах вызывающей сборки.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

файл jar компонента:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### См. также

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
