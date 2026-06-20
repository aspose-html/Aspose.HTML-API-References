---
title: "Énumération Sandbox"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "énumération com.aspose.html.Sandbox. Un ensemble de drapeaux de sandboxing est un ensemble de zéro ou plusieurs des drapeaux suivants qui sont utilisés pour restreindre les capacités des ressources potentiellement non fiables"
type: docs

url: /fr/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Un ensemble de drapeaux de sandboxing est un ensemble de zéro ou plusieurs des drapeaux suivants, utilisés pour restreindre les capacités des ressources potentiellement non fiables.

```java
[Flags]
public enum Sandbox
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucun drapeau n'est défini, chaque fonctionnalité de sandbox est acceptée |
| Navigation | `1` | Ce drapeau empêche le contenu de naviguer vers des contextes de navigation autres que le contexte de navigation sandboxé lui‑même (ou des contextes de navigation imbriqués davantage à l'intérieur), les contextes de navigation auxiliaires (qui sont protégés par le drapeau de navigation auxiliaire sandboxé défini ci‑après), et le contexte de navigation de niveau supérieur (qui est protégé par le drapeau de navigation de niveau supérieur sandboxé défini plus bas). Si le drapeau de navigation auxiliaire sandboxé n'est pas défini, alors, dans certains cas, les restrictions permettent néanmoins l'ouverture de fenêtres pop‑up (nouveaux contextes de navigation de niveau supérieur). Ces contextes de navigation ont toujours un navigateur sandboxé autorisé, défini lors de la création du contexte de navigation, qui permet au contexte de navigation qui les a créés de les naviguer réellement. (Sinon, le drapeau de navigation sandboxé empêcherait leur navigation même s'ils étaient ouverts. |
| AuxiliaryNavigation | `2` | Ce drapeau empêche le contenu de créer de nouveaux contextes de navigation auxiliaires, par ex. en utilisant l'attribut target ou la méthode window.open(). |
| TopLevelNavigation | `4` | Ce drapeau empêche le contenu de naviguer dans son contexte de navigation de niveau supérieur et empêche le contenu de fermer son contexte de navigation de niveau supérieur. Lorsque le drapeau de navigation de niveau supérieur sandboxé n'est pas défini, le contenu peut naviguer son contexte de navigation de niveau supérieur, mais les autres contextes de navigation restent protégés par le drapeau de navigation sandboxé et éventuellement par le drapeau de navigation auxiliaire sandboxé. |
| Plugins | `8` | Ce drapeau empêche le contenu d'instancier des plugins, que ce soit en utilisant l'élément embed, l'élément object, l'élément applet, ou via la navigation d'un contexte de navigation imbriqué, à moins que ces plugins puissent être sécurisés. |
| Origin | `10` | Ce drapeau force le contenu à adopter une origine unique, empêchant ainsi l'accès à d'autres contenus provenant de la même origine. |
| Forms | `20` | Ce drapeau bloque la soumission de formulaires. |
| PointerLock | `40` | Ce drapeau désactive l'API Pointer Lock. |
| Scripts | `80` | Ce drapeau bloque l'exécution de scripts. |
| AutomaticFeatures | `100` | Ce drapeau bloque les fonctionnalités qui se déclenchent automatiquement, comme la lecture automatique d'une vidéo ou le focus automatique d'un contrôle de formulaire. |
| Fullscreen | `200` | Ce drapeau empêche le contenu d'utiliser la méthode requestFullscreen(). |
| DocumentDomain | `400` | Ce drapeau empêche le contenu d'utiliser la fonctionnalité document.domain pour modifier l'origine effective du script. |
| Images | `800` | Ce drapeau désactive le chargement d'images. |

### Voir aussi

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
