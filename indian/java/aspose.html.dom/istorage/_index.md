---
title: "IStorage इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.IStorage इंटरफ़ेस। Web Storage API का यह इंटरफ़ेस किसी विशिष्ट डोमेन के सत्र या स्थानीय स्टोरेज तक पहुँच प्रदान करता है। Web Storage विनिर्देशन देखें https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /hi/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Web Storage API का यह इंटरफ़ेस किसी विशेष डोमेन के सत्र (session) या स्थानीय (local) स्टोरेज तक पहुँच प्रदान करता है। Web Storage विनिर्देशन देखें: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) कुंजी/मान जोड़ों की संख्या लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | यदि कोई हों, तो सभी कुंजी/मान जोड़े हटाता है। |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | दिए गए कुंजी से संबद्ध वर्तमान मान लौटाता है, या यदि दी गई कुंजी मौजूद नहीं है तो null लौटाता है। |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | nth कुंजी का नाम लौटाता है, या यदि n कुंजी/मान जोड़ों की संख्या के बराबर या उससे अधिक है तो null लौटाता है। |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | यदि दिए गए कुंजी के साथ कोई कुंजी/मान जोड़ा मौजूद है, तो उसे हटाता है। |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | कुंजी द्वारा पहचाने गए जोड़े का मान value पर सेट करता है, यदि पहले उस कुंजी के लिए कोई कुंजी/मान जोड़ा नहीं था तो नया जोड़ा बनाता है। |

### संबंधित देखें

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
