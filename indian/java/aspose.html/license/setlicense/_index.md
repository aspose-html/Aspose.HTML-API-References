---
title: "License.SetLicense"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "License मेथड। घटक को लाइसेंस देता है।"
type: docs

url: /hi/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

घटक को लाइसेंस करता है।

```java
public void SetLicense(String licenseName)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| licenseName | String | यह पूर्ण या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |

## टिप्पणियाँ

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. वह फ़ोल्डर जिसमें Aspose कंपोनेंट असेंबली मौजूद है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली मौजूद है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली मौजूद है।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

2. वह फ़ोल्डर जिसमें Aspose कंपोनेंट JAR फ़ाइल मौजूद है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग JAR फ़ाइल मौजूद है।

## उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर में MyLicense.lic नामक लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा, और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में।

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

घटक jar फ़ाइल:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### संबंधित देखें

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस करता है।

```java
public void SetLicense(Stream stream)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | स्ट्रीम | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

## टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

## उदाहरण

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### संबंधित देखें

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
