---
title: Class MutationRecord
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Mutations.MutationRecord कक्ष. एक MutationRecord एक व्यक्तगत DOM उत्परवर्तन क प्रतनधत्व करत है यह वह वस्तु है जसे पस कय जत हैMutationObserver एसMutationCallback .
type: docs
weight: 990
url: /hi/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

एक MutationRecord एक व्यक्तिगत DOM उत्परिवर्तन का प्रतिनिधित्व करता है। यह वह वस्तु है जिसे पास किया जाता है[`MutationObserver`](../mutationobserver/) एस[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | जोड़े गए नोड्स लौटाएं। |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | परिवर्तित विशेषता का स्थानीय नाम लौटाता है, और अन्यथा शून्य करता है। |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | परिवर्तित विशेषता का नाम स्थान देता है, और अन्यथा शून्य करता है। |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | जोड़े गए या हटाए गए नोड्स के अगले सिबलिंग को लौटाएं, या शून्य. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | वापसी मान प्रकार पर निर्भर करता है। "विशेषताओं" के लिए, यह परिवर्तन से पहले परिवर्तित विशेषता का मान है। "चरित्रडेटा" के लिए, यह परिवर्तन से पहले परिवर्तित नोड का डेटा है। |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | जोड़े गए या हटाए गए नोड्स के पिछले सिबलिंग को लौटाता है, या शून्य. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | हटाए गए नोड्स लौटाएं। |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | प्रकार के आधार पर प्रभावित म्यूटेशन को नोड लौटाता है। "गुणों" के लिए, यह वह तत्व है जिसकी विशेषता बदल गई है। "characterData" के लिए, यह CharacterData नोड है। "चाइल्डलिस्ट" के लिए, यह वह नोड है जिसके बच्चे बदल गए हैं। |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | "एट्रिब्यूट्स" देता है अगर यह एक एट्रिब्यूट म्यूटेशन था, "कैरेक्टरडेटा" अगर यह एक कैरेक्टरडेटा नोड के लिए म्यूटेशन था और "चाइल्डलिस्ट" अगर यह नोड्स के ट्री के लिए म्यूटेशन था। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |

### यह सभी देखें

* class [DOMObject](../../aspose.html.dom/domobject/)
* नाम स्थान [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* सभा [Aspose.HTML](../../)


