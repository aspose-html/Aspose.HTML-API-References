---
title: "ICSS2Properties.WhiteSpace"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété indique comment les espaces blancs à l'intérieur de l'élément sont gérés. Les valeurs ont les significations suivantes"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

Cette propriété indique comment le [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) à l'intérieur de l'élément est géré. Les valeurs ont les significations suivantes :

normal - Cette valeur indique aux agents utilisateurs de réduire les séquences d'espaces blancs et de couper les lignes au besoin pour remplir les boîtes de ligne. Des sauts de ligne supplémentaires peuvent être créés par des occurrences de "\A" dans le contenu généré (par ex., pour l'élément BR en HTML).pre - Cette valeur empêche les agents utilisateurs de réduire les séquences d'espaces blancs. Les lignes ne sont coupées qu'aux sauts de ligne dans la source, ou aux occurrences de "\A" dans le contenu généré.nowrap - Cette valeur réduit les espaces blancs comme pour 'normal', mais supprime les sauts de ligne dans le texte sauf ceux créés par "\A" dans le contenu généré (par ex., pour l'élément BR en HTML).

```java
public String WhiteSpace { get; set; }
```

### Valeur de retour

propriété white-space

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
