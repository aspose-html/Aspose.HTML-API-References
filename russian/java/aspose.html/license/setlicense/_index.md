---
title: "License.SetLicense"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод License. Лицензирует компонент"
type: docs

url: /ru/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Лицензирует компонент.

```java
public void SetLicense(String licenseName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

## Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка, содержащая сборку компонента Aspose.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (запускаемую) сборку.

5. Встроенный ресурс в вызывающей сборке клиента.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Явный путь.

2. Встроенный ресурс в вызывающей сборке клиента.

2. Папка, содержащая JAR‑файл компонента Aspose.

3. Папка, содержащая JAR‑файл вызывающего клиента.

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

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```java
public void SetLicense(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | Поток | Поток, содержащий лицензию. |

## Примечания

Используйте этот метод для загрузки лицензии из потока.

## Примеры

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### См. также

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
