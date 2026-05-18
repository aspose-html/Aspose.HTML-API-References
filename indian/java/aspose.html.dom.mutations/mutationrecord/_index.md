---
title: "MutationRecord क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.mutations.MutationRecord क्लास। एक MutationRecord व्यक्तिगत DOM म्यूटेशन का प्रतिनिधित्व करता है। यह वह ऑब्जेक्ट है जो MutationObservers के MutationCallback को पास किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

एक MutationRecord व्यक्तिगत DOM म्यूटेशन का प्रतिनिधित्व करता है। यह वह ऑब्जेक्ट है जो [`MutationObserver`](../mutationobserver/) के [`MutationCallback`](../mutationcallback/) को पास किया जाता है।

```java
public class MutationRecord : DOMObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) जोड़े गए नोड्स को लौटाता है। |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) बदले गए एट्रिब्यूट का स्थानीय नाम लौटाता है, अन्यथा null। |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) बदले गए एट्रिब्यूट का पैकेज लौटाता है, अन्यथा null। |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) जोड़े या हटाए गए नोड्स का अगला सिब्लिंग लौटाता है, या null। |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) लौटाया गया मान प्रकार पर निर्भर करता है। "attributes" के लिए, यह परिवर्तन से पहले बदले गए एट्रिब्यूट का मान होता है। "characterData" के लिए, यह परिवर्तन से पहले बदले गए नोड का डेटा होता है। "childList" के लिए, यह null होता है। |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) जोड़े या हटाए गए नोड्स का पूर्ववर्ती सिब्लिंग लौटाता है, या null। |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) हटाए गए नोड्स को लौटाता है। |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) म्यूटेशन द्वारा प्रभावित नोड को लौटाता है, प्रकार के आधार पर। "attributes" के लिए, यह वह तत्व है जिसका एट्रिब्यूट बदला गया। "characterData" के लिए, यह CharacterData नोड है। "childList" के लिए, यह वह नोड है जिसके बच्चों में परिवर्तन हुआ। |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) यदि यह एट्रिब्यूट म्यूटेशन था तो "attributes" लौटाता है, यदि यह CharacterData नोड में म्यूटेशन था तो "characterData" और यदि यह नोड्स के ट्री में म्यूटेशन था तो "childList" लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
