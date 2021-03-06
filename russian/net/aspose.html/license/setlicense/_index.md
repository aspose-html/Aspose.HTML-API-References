---
title: SetLicense
second_title: Справочник по Aspose.HTML для .NET API
description: Лицензирует компонент.
type: docs
weight: 20
url: /ru/net/aspose.html/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licenseName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | String | Может быть полным или коротким именем файла&lt;ms&gt; или именем встроенного ресурса &lt;/ мс&gt;. Используйте пустую строку для переключения в режим оценки. |

### Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.

&lt;ms&gt;

2. Папка, содержащая сборку компонента Aspose.

3. Папка, содержащая вызывающую сборку клиента.

4. Папка, содержащая входную (автозагрузочную) сборку.

5. Вложенный ресурс в вызывающую сборку клиента.

**Примечание:** В .NET Compact Framework пытается найти лицензию только в этих местах:

1. Явный путь.

2. Вложенный ресурс в вызывающую сборку клиента.

&lt;/ms&gt;&lt;java&gt;

2. Папка, содержащая JAR-файл компонента Aspose.

3. Папка, содержащая вызывающий JAR-файл клиента.

&lt;/java&gt;

### Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей &lt;ms&gt; компонент, в папке, содержащей вызывающую сборку , в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки. &lt;code&gt; [C#] License license = new License(); license.SetLicense("MyLicense.lic"); &lt;/code&gt;&lt;/ms&gt;&lt;java&gt; jar-файл компонента: &lt;code&gt; License license = новая лицензия(); license.setLicense("MyLicense.lic"); &lt;/code&gt;&lt;/java&gt;

### Смотрите также

* class [License](../../license)
* пространство имен [Aspose.Html](../../license)
* сборка [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, содержащий лицензию. |

### Примечания

Используйте этот метод для загрузки лицензии из потока.

### Примеры

&lt;ms&gt;&lt;code&gt; [C#] Лицензия лицензия = новая лицензия(); license.SetLicense(myStream); &lt;/code&gt;&lt;/ms&gt;

### Смотрите также

* class [License](../../license)
* пространство имен [Aspose.Html](../../license)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
