---
title: "DOMException वर्ग"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.DOMException वर्ग। DOMException इंटरफ़ेस एक असामान्य घटना को दर्शाता है जिसे अपवाद कहा जाता है, जो किसी मेथड को कॉल करने या वेब API की प्रॉपर्टी तक पहुँचने के परिणामस्वरूप होती है। यह मूलतः वेब API में त्रुटि स्थितियों को वर्णित करने का तरीका है।"
type: docs

url: /hi/java/com.aspose.html.dom/domexception/
---
## DOMException class

DOMException इंटरफ़ेस एक असामान्य घटना (जिसे एक्सेप्शन कहा जाता है) का प्रतिनिधित्व करता है जो वेब API की किसी मेथड को कॉल करने या प्रॉपर्टी तक पहुँचने के परिणामस्वरूप होती है। यह मूलतः वेब APIs में त्रुटि स्थितियों का वर्णन करने का तरीका है।

```java
public class DOMException : PlatformException
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | `DOMException` वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [DOMException](domexception/#constructor_1)(String, String) | `DOMException` वर्ग का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) एक मान लौटाता है जिसमें त्रुटि कोड स्थिरांक में से एक होता है, या यदि कोई मेल नहीं खाता तो 0। यह फ़ील्ड ऐतिहासिक कारणों से उपयोग किया जाता है। |
| [getMessage](../../com.aspose.html.dom/domexception/message/) एक स्ट्रिंग लौटाता है जो दिए गए त्रुटि नाम से संबंधित संदेश या विवरण दर्शाती है। |
| [getName](../../com.aspose.html.dom/domexception/name/) एक स्ट्रिंग लौटाता है जिसमें त्रुटि नाम से जुड़ी स्ट्रिंग्स में से एक होती है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | ऑपरेशन को रोक दिया गया था। |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | ऑब्जेक्ट को क्लोन नहीं किया जा सकता। |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | यदि निर्दिष्ट टेक्स्ट रेंज DOMString में फिट नहीं होती। |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | यदि कोई नोड कहीं ऐसे स्थान पर डाला जाता है जहाँ वह नहीं होना चाहिए। |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | यदि इंडेक्स या आकार नकारात्मक है, या अनुमत मान से अधिक है। |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | यदि किसी विशेषता को जोड़ने का प्रयास किया जाता है जो पहले से कहीं और उपयोग में है। |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | यदि कोई पैरामीटर या ऑपरेशन अधोस्त वस्तु द्वारा समर्थित नहीं है। |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | यदि कोई अमान्य या अवैध अक्षर निर्दिष्ट किया गया है, जैसे XML नाम में। |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | व्यंजक में सिंटैक्स त्रुटि है या यह विशिष्ट XPathEvaluator के नियमों के अनुसार वैध व्यंजक नहीं है, या इसमें ऐसी विशेष एक्सटेंशन फ़ंक्शन या वेरिएबल्स हैं जो इस कार्यान्वयन द्वारा समर्थित नहीं हैं। |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | यदि अधोस्त वस्तु के प्रकार को बदलने का प्रयास किया जाता है। |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | प्रदान किया गया नोड गलत है या इस ऑपरेशन के लिए इसका पूर्वज गलत है। |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | यदि किसी वस्तु का उपयोग करने का प्रयास किया जाता है जो उपलब्ध नहीं है, या अब उपयोग योग्य नहीं है। |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | यदि पैकेजों के संदर्भ में गलत तरीके से किसी वस्तु को बनाने या बदलने का प्रयास किया जाता है। |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | एक नेटवर्क त्रुटि हुई। |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | यदि किसी संदर्भ में जहाँ वह मौजूद नहीं है, एक नोड को संदर्भित करने का प्रयास किया जाता है। |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | यदि कार्यान्वयन अनुरोधित वस्तु या ऑपरेशन के प्रकार का समर्थन नहीं करता है। |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | यदि डेटा उन नोड के लिए निर्दिष्ट किया जाता है जो डेटा का समर्थन नहीं करता। |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | यदि उन वस्तुओं को संशोधित करने का प्रयास किया जाता है जहाँ संशोधन की अनुमति नहीं है। |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | कोटा पार हो गया है। |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | ऑपरेशन असुरक्षित है। |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | यदि एक अमान्य या अवैध स्ट्रिंग निर्दिष्ट की गई है। |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | ऑपरेशन का समय समाप्त हो गया। |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | व्यंजक को निर्दिष्ट प्रकार लौटाने के लिए परिवर्तित नहीं किया जा सकता। |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | यदि वस्तु का प्रकार उस वस्तु से जुड़े पैरामीटर के अपेक्षित प्रकार के साथ असंगत है। |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | दिए गए URL का अन्य URL से मिलान नहीं होता। |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | यदि insertBefore या removeChild जैसे मेथड को कॉल करने से नोड "आंशिक वैधता" के संदर्भ में अमान्य हो जाता है, तो यह अपवाद उठाया जाएगा और ऑपरेशन नहीं किया जाएगा। यह कोड [DOM Level 3 Validation] में उपयोग किया जाता है। आगे की जानकारी के लिए इस विनिर्देशन को देखें। |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | यदि किसी नोड का उपयोग उस दस्तावेज़ में किया जाता है जो उसे बनाता है, उससे अलग दस्तावेज़ में (जो इसका समर्थन नहीं करता)। |

### संबंधित देखें

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
