---
title: "License.SetLicense"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة License. ترخص المكوّن"
type: docs

url: /ar/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

يرخص المكوّن.

```java
public void SetLicense(String licenseName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مضمن في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمن في تجميع استدعاء العميل.

2. المجلد الذي يحتوي على ملف JAR لمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

## الأمثلة

في هذا المثال، سيُجرى محاولة للعثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

ملف jar الخاص بالمكوّن:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```java
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل الترخيص من تدفق.

## الأمثلة

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### انظر أيضًا

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
