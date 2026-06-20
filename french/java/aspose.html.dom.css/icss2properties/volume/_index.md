---
title: "ICSS2Properties.Volume"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Le volume fait référence au volume médian de la forme d'onde. En d'autres termes, une voix très modulée à un volume de 50 peut dépasser largement ce niveau. Les valeurs globales sont probablement réglables par l'utilisateur pour le confort, par exemple avec un contrôle de volume physique qui augmenterait proportionnellement les valeurs 0 et 100 ; ce que fait cette propriété, c’est ajuster la plage dynamique."
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Le volume fait référence au volume médian de la forme d'onde. En d'autres termes, une voix très modulée à un volume de 50 peut dépasser largement ce niveau. Les valeurs globales sont probablement réglables par l'utilisateur pour le confort, par exemple avec un contrôle de volume physique (qui augmenterait proportionnellement les valeurs 0 et 100) ; ce que fait cette propriété, c’est ajuster la plage dynamique.

Les valeurs ont les significations suivantes :

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - Tout nombre compris entre '0' et '100'. '0' représente le niveau de volume audible minimum et 100 correspond au niveau de confort maximal. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Les valeurs en pourcentage sont calculées par rapport à la valeur héritée, puis limitées à la plage '0' à '100'. silent - Aucun son du tout. La valeur '0' ne signifie pas la même chose que 'silent'. x-soft - Identique à '0'. soft - Identique à '25'. medium - Identique à '50'. loud - Identique à '75'. x-loud - Identique à '100'.

```java
public String Volume { get; set; }
```

### Valeur de retour

propriété volume

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
