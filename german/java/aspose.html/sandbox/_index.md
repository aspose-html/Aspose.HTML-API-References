---
title: "Sandbox Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.Sandbox Aufzählung. Ein Sandbox‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken"
type: docs

url: /de/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Ein Sandbox‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken.

```java
[Flags]
public enum Sandbox
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Kein Flag ist gesetzt, jedes Sandbox‑Feature wird akzeptiert |
| Navigation | `1` | Dieses Flag verhindert, dass Inhalte andere Browsing‑Kontexte als den sandboxed Browsing‑Kontext selbst (oder weiter darin verschachtelte Browsing‑Kontexte) navigieren, Hilfs‑Browsing‑Kontexte (die durch das unten definierte sandboxed auxiliary navigation browsing context‑Flag geschützt sind) und den Top‑Level‑Browsing‑Kontext (der durch das weiter unten definierte sandboxed top-level navigation browsing context‑Flag geschützt ist). Wenn das sandboxed auxiliary navigation browsing context‑Flag nicht gesetzt ist, erlauben die Einschränkungen in bestimmten Fällen dennoch das Öffnen von Pop‑ups (neuen Top‑Level‑Browsing‑Kontexten). Diese Browsing‑Kontexte besitzen stets einen zulässigen sandboxed Navigator, der beim Erzeugen des Browsing‑Kontexts festgelegt wird und es dem erzeugenden Kontext ermöglicht, sie tatsächlich zu navigieren. (Andernfalls würde das sandboxed navigation browsing context‑Flag sie selbst dann daran hindern, navigiert zu werden, wenn sie geöffnet wurden.) |
| AuxiliaryNavigation | `2` | Dieses Flag verhindert, dass Inhalte neue Hilfs‑Browsing‑Kontexte erstellen, z. B. über das target‑Attribut oder die window.open()-Methode. |
| TopLevelNavigation | `4` | Dieses Flag verhindert, dass Inhalte ihren Top‑Level‑Browsing‑Kontext navigieren und verhindert, dass Inhalte ihren Top‑Level‑Browsing‑Kontext schließen. Wenn das sandboxed top-level navigation browsing context‑Flag nicht gesetzt ist, kann Inhalt seinen Top‑Level‑Browsing‑Kontext navigieren, während andere Browsing‑Kontexte weiterhin durch das sandboxed navigation browsing context‑Flag und ggf. das sandboxed auxiliary navigation browsing context‑Flag geschützt sind. |
| Plugins | `8` | Dieses Flag verhindert, dass Inhalte Plugins instanziieren, sei es über das embed‑Element, das object‑Element, das applet‑Element oder durch Navigation eines verschachtelten Browsing‑Kontexts, es sei denn, diese Plugins können gesichert werden. |
| Origin | `10` | Dieses Flag zwingt Inhalte zu einem eindeutigen Ursprung und verhindert so, dass sie auf andere Inhalte desselben Ursprungs zugreifen. |
| Forms | `20` | Dieses Flag blockiert das Absenden von Formularen. |
| PointerLock | `40` | Dieses Flag deaktiviert die Pointer‑Lock‑API. |
| Scripts | `80` | Dieses Flag blockiert die Skriptausführung. |
| AutomaticFeatures | `100` | Dieses Flag blockiert Funktionen, die automatisch ausgelöst werden, wie das automatische Abspielen eines Videos oder das automatische Fokussieren einer Formulareingabe. |
| Fullscreen | `200` | Dieses Flag verhindert, dass Inhalte die requestFullscreen()-Methode verwenden. |
| DocumentDomain | `400` | Dieses Flag verhindert, dass Inhalte die document.domain‑Funktion nutzen, um den effektiven Skript‑Ursprung zu ändern. |
| Images | `800` | Dieses Flag deaktiviert das Laden von Bildern. |

### Siehe auch

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
