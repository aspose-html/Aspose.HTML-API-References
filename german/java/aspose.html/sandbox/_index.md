---
title: "Sandbox Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.Sandbox enum. Ein Sandbox‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken"
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
| Navigation | `1` | Dieses Flag verhindert, dass Inhalte Browsing‑Kontexte navigieren, die nicht der sandboxed browsing context selbst sind (oder weiter in ihm verschachtelte Browsing‑Kontexte), Hilfs‑Browsing‑Kontexte (die durch das als nächstes definierte sandboxed auxiliary navigation browsing context Flag geschützt sind) und der Top‑Level‑Browsing‑Context (der durch das unten definierte sandboxed top-level navigation browsing context Flag geschützt ist). Wenn das sandboxed auxiliary navigation browsing context Flag nicht gesetzt ist, erlauben die Einschränkungen in bestimmten Fällen dennoch Pop‑ups (neue Top‑Level‑Browsing‑Kontexte) zu öffnen. Diese Browsing‑Kontexte haben immer einen zulässigen sandboxed navigator, der beim Erstellen des Browsing‑Kontexts festgelegt wird und dem erstellenden Browsing‑Kontext ermöglicht, sie tatsächlich zu navigieren. (Andernfalls würde das sandboxed navigation browsing context Flag sie selbst dann daran hindern, navigiert zu werden, wenn sie geöffnet wurden.) |
| AuxiliaryNavigation | `2` | Dieses Flag verhindert, dass Inhalte neue auxiliary browsing contexts erstellen, z. B. durch das target‑Attribut oder die window.open()-Methode. |
| TopLevelNavigation | `4` | Dieses Flag verhindert, dass Inhalte ihren top-level browsing context navigieren und verhindert, dass Inhalte ihren top-level browsing context schließen. Wenn das sandboxed top-level navigation browsing context Flag nicht gesetzt ist, kann Inhalt seinen top-level browsing context navigieren, jedoch bleiben andere Browsing‑Kontexte weiterhin durch das sandboxed navigation browsing context Flag und ggf. das sandboxed auxiliary navigation browsing context Flag geschützt. |
| Plugins | `8` | Dieses Flag verhindert, dass Inhalte Plugins instanziieren, sei es über das embed‑Element, das object‑Element, das applet‑Element oder durch Navigation eines verschachtelten Browsing‑Kontexts, es sei denn, diese Plugins können gesichert werden. |
| Origin | `10` | Dieses Flag zwingt Inhalte in einen eindeutigen Ursprung und verhindert so den Zugriff auf andere Inhalte desselben Ursprungs. |
| Forms | `20` | Dieses Flag blockiert das Absenden von Formularen. |
| PointerLock | `40` | Dieses Flag deaktiviert die Pointer‑Lock‑API. |
| Scripts | `80` | Dieses Flag blockiert die Skriptausführung. |
| AutomaticFeatures | `100` | Dieses Flag blockiert Funktionen, die automatisch ausgelöst werden, wie das automatische Abspielen eines Videos oder das automatische Fokussieren einer Formularkontrolle. |
| Fullscreen | `200` | Dieses Flag verhindert, dass Inhalte die requestFullscreen()-Methode verwenden. |
| DocumentDomain | `400` | Dieses Flag verhindert, dass Inhalte die document.domain‑Funktion nutzen, um den effektiven Skript‑Ursprung zu ändern. |
| Images | `800` | Dieses Flag deaktiviert das Laden von Bildern. |

### Siehe auch

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
