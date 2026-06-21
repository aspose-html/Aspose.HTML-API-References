---
title: "ITreeWalker Interface"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.traversal.ITreeWalker इंटरफ़ेस। TreeWalker ऑब्जेक्ट का उपयोग दस्तावेज़ वृक्ष या उपवृक्ष को नेविगेट करने के लिए किया जाता है, जो उनके whatToShow फ़्लैग्स और किसी भी फ़िल्टर द्वारा परिभाषित दस्तावेज़ दृश्य का उपयोग करता है। TreeWalker का उपयोग करके नेविगेशन करने वाला कोई भी फ़ंक्शन स्वचालित रूप से TreeWalker द्वारा परिभाषित किसी भी दृश्य का समर्थन करेगा।"
type: docs

url: /hi/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker ऑब्जेक्ट्स का उपयोग दस्तावेज़ ट्री या सबट्री को नेविगेट करने के लिए किया जाता है, जिसमें दस्तावेज़ का दृश्य उनके whatToShow फ़्लैग्स और फ़िल्टर (यदि कोई हो) द्वारा परिभाषित होता है। कोई भी फ़ंक्शन जो TreeWalker का उपयोग करके नेविगेशन करता है, स्वचालित रूप से TreeWalker द्वारा परिभाषित किसी भी दृश्य का समर्थन करेगा।

उपवृक्ष के तर्कसंगत दृश्य से नोड्स को हटाने से ऐसी संरचना बन सकती है जो पूर्ण, बिना फ़िल्टर किए दस्तावेज़ में उसी उपवृक्ष से काफी अलग हो। TreeWalker दृश्य में जो नोड्स भाई-बहन होते हैं, वे मूल दृश्य में विभिन्न, दूरस्थ नोड्स के बच्चे हो सकते हैं। उदाहरण के लिए, एक NodeFilter पर विचार करें जो सभी नोड्स को छोड़ देता है सिवाय टेक्स्ट नोड्स और दस्तावेज़ के रूट नोड के। परिणामस्वरूप तर्कसंगत दृश्य में, सभी टेक्स्ट नोड्स भाई-बहन बन जाएंगे और रूट नोड के सीधे बच्चे के रूप में दिखाई देंगे, चाहे मूल दस्तावेज़ की संरचना कितनी भी गहराई में हो।

साथ ही देखें [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker को वर्तमान नोड के पहले दृश्यमान बच्चे पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड के कोई दृश्यमान बच्चे नहीं हैं, तो null लौटाता है और वर्तमान नोड को बरकरार रखता है। |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker को वर्तमान नोड के अंतिम दृश्यमान बच्चे पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड के कोई दृश्यमान बच्चे नहीं हैं, तो null लौटाता है और वर्तमान नोड को बरकरार रखता है। |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | TreeWalker को वर्तमान नोड के सापेक्ष दस्तावेज़ क्रम में अगले दृश्यमान नोड पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड का कोई अगला नोड नहीं है, या यदि nextNode की खोज TreeWalker के रूट नोड से ऊपर जाने का प्रयास करती है, तो null लौटाता है और वर्तमान नोड को बरकरार रखता है। |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker को वर्तमान नोड के अगले भाई-बहन पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड का कोई दृश्यमान अगला भाई-बहन नहीं है, तो null लौटाता है और वर्तमान नोड को बरकरार रखता है। |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | वर्तमान नोड के सबसे निकटतम दृश्यमान पूर्वज नोड पर जाता है और उसे लौटाता है। यदि parentNode की खोज TreeWalker के रूट नोड से ऊपर जाने का प्रयास करती है, या यदि वह दृश्यमान पूर्वज नोड नहीं पा पाती, तो यह विधि वर्तमान स्थिति को बरकरार रखती है और null लौटाती है। |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | TreeWalker को वर्तमान नोड के सापेक्ष दस्तावेज़ क्रम में पिछले दृश्यमान नोड पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड का कोई पिछला नोड नहीं है, या TreeWalker की रूट नोड से ऊपर जाने का प्रयास किया जाता है, तो null लौटाता है, और वर्तमान नोड को बरकरार रखता है। |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker को वर्तमान नोड के पिछले भाई‑बहन नोड पर ले जाता है और नया नोड लौटाता है। यदि वर्तमान नोड का कोई दृश्यमान पिछला भाई‑बहन नोड नहीं है, तो null लौटाता है, और वर्तमान नोड को बरकरार रखता है। |

### संबंधित देखें

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
