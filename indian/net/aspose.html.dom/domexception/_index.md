---
title: Class DOMException
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.DOMException कक्ष. DOMException इंटरफ़ेस एक असमन्य घटन जसे अपवद कह जत है क प्रतनधत्व करत है ज कस वध क कल करने य वेब एपआई क संपत्त तक पहुँचने के परणमस्वरूप हत है यह मूल रूप से वेब एपआई में त्रुट स्थतयं क वर्णन कय गय है
type: docs
weight: 640
url: /hi/net/aspose.html.dom/domexception/
---
## DOMException class

DOMException इंटरफ़ेस एक असामान्य घटना (जिसे अपवाद कहा जाता है) का प्रतिनिधित्व करता है जो किसी विधि को कॉल करने या वेब एपीआई की संपत्ति तक पहुँचने के परिणामस्वरूप होता है। यह मूल रूप से वेब एपीआई में त्रुटि स्थितियों का वर्णन किया गया है।

```csharp
public class DOMException : PlatformException
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`DOMException` वर्ग. |
| [DOMException](domexception/#constructor_1)(string, string) | का एक नया उदाहरण प्रारंभ करता है`DOMException` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | एक मान देता है जिसमें त्रुटि कोड स्थिरांक में से एक होता है, या 0 यदि कोई मेल नहीं खाता है। इस फ़ील्ड का उपयोग ऐतिहासिक कारणों से किया जाता है. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | दिए गए त्रुटि नाम से जुड़े संदेश या विवरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग देता है। |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | एक स्ट्रिंग लौटाता है जिसमें एक त्रुटि नाम से जुड़े तार होते हैं। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | ऑपरेशन निरस्त कर दिया गया था। |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | ऑब्जेक्ट का क्लोन नहीं बनाया जा सकता. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | यदि पाठ की निर्दिष्ट सीमा किसी DOMString. में फ़िट नहीं होती है |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | यदि कोई नोड कहीं डाला गया है तो यह संबंधित नहीं है। |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | यदि अनुक्रमणिका या आकार ऋणात्मक है, या अनुमत मान से अधिक है. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | यदि किसी ऐसी विशेषता को जोड़ने का प्रयास किया जाता है जो पहले से कहीं और उपयोग में है। |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | यदि कोई पैरामीटर या ऑपरेशन अंतर्निहित वस्तु द्वारा समर्थित नहीं है। |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | यदि कोई अमान्य या अवैध वर्ण निर्दिष्ट किया गया है, जैसे कि XML नाम में. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | अभिव्यक्ति में एक सिंटैक्स त्रुटि है या अन्यथा विशिष्ट XPathEvaluator के नियमों के अनुसार एक कानूनी अभिव्यक्ति नहीं है या इसमें विशेष एक्सटेंशन फ़ंक्शन या वेरिएबल्स शामिल हैं जो इस कार्यान्वयन द्वारा समर्थित नहीं हैं। |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | यदि अंतर्निहित वस्तु के प्रकार को संशोधित करने का प्रयास किया जाता है। |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | आपूर्ति किया गया नोड गलत है या इस ऑपरेशन के लिए गलत पूर्वज है। |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | यदि किसी ऐसे ऑब्जेक्ट का उपयोग करने का प्रयास किया जाता है जो प्रयोग करने योग्य नहीं है, या अब नहीं है। |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | यदि किसी वस्तु को इस तरह से बनाने या बदलने का प्रयास किया जाता है जो नामस्थानों के संबंध में गलत है। |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | एक नेटवर्क त्रुटि हुई। |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | यदि किसी संदर्भ में नोड को संदर्भित करने का प्रयास किया जाता है जहां यह मौजूद नहीं है। |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | यदि कार्यान्वयन अनुरोधित प्रकार के ऑब्जेक्ट या ऑपरेशन का समर्थन नहीं करता है। |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | यदि डेटा एक नोड के लिए निर्दिष्ट है जो डेटा का समर्थन नहीं करता है। |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | यदि किसी वस्तु को संशोधित करने का प्रयास किया जाता है जहां संशोधनों की अनुमति नहीं है। |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | कोटा पार हो गया है। |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | ऑपरेशन असुरक्षित है। |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | यदि कोई अमान्य या अवैध स्ट्रिंग निर्दिष्ट है। |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | ऑपरेशन का समय समाप्त हो गया। |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | निर्दिष्ट प्रकार को वापस करने के लिए अभिव्यक्ति को परिवर्तित नहीं किया जा सकता है। |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | यदि ऑब्जेक्ट का प्रकार ऑब्जेक्ट से जुड़े अपेक्षित प्रकार के पैरामीटर के साथ असंगत है। |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | दिया गया URL किसी अन्य URL से मेल नहीं खाता. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | यदि इन्सर्टबियर या रिमूवचाइल्ड जैसी किसी विधि को कॉल करने से "आंशिक वैधता" के संबंध में नोड अमान्य हो जाएगा, तो यह अपवाद उठाया जाएगा और ऑपरेशन नहीं किया जाएगा। इस कोड का उपयोग [DOM लेवल 3 वैलिडेशन] में किया जाता है। अधिक जानकारी के लिए इस विनिर्देश का संदर्भ लें। |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | यदि किसी नोड का उपयोग किसी भिन्न दस्तावेज़ में किया जाता है, जिसने इसे बनाया है (जो इसका समर्थन नहीं करता है)। |

### यह सभी देखें

* class [PlatformException](../../aspose.html/platformexception/)
* नाम स्थान [Aspose.Html.Dom](../../aspose.html.dom/)
* सभा [Aspose.HTML](../../)


