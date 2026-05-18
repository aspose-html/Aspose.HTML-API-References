---
title: "IFile इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.io.IFile इंटरफ़ेस। एक File ऑब्जेक्ट एक Blob ऑब्जेक्ट है जिसमें name विशेषता होती है जो एक String है; इसे वेब एप्लिकेशन में एक कंस्ट्रक्टर के माध्यम से बनाया जा सकता है या यह अंतर्निहित OS फ़ाइल प्रणाली से फ़ाइल की बाइट अनुक्रम का संदर्भ है।"
type: docs

url: /hi/java/com.aspose.html.io/ifile/
---
## IFile interface

एक File ऑब्जेक्ट एक Blob ऑब्जेक्ट है जिसमें name एट्रिब्यूट होता है, जो एक स्ट्रिंग है; इसे वेब एप्लिकेशन के भीतर एक कंस्ट्रक्टर के माध्यम से बनाया जा सकता है, या यह अंतर्निहित (OS) फ़ाइल सिस्टम से फ़ाइल के बाइट अनुक्रम का संदर्भ है।

```java
public interface IFile : IBlob
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) फ़ाइल की अंतिम संशोधित तिथि। प्राप्त करने पर, यदि उपयोगकर्ता एजेंट यह जानकारी उपलब्ध करा सकते हैं, तो यह एक long long मान लौटाना चाहिए जो फ़ाइल के अंतिम संशोधित समय को Unix Epoch से मिलीसेकंड की संख्या के रूप में दर्शाता है। |
| [getName](../../com.aspose.html.io/ifile/name/) फ़ाइल का नाम। प्राप्त करने पर, यह फ़ाइल के नाम को String के रूप में लौटाना चाहिए। |

### संबंधित देखें

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
