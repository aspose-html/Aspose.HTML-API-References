---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Metered-Methode. Legt den gemessenen öffentlichen und privaten Schlüssel fest. Wenn Sie eine gemessene Lizenz beim Start der Anwendung erwerben, sollte diese API normalerweise aufgerufen werden, das ist ausreichend. Sollte jedoch immer das Hochladen der Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf."
type: docs

url: /de/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz in den Evaluierungs‑Status gesetzt. Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungs‑Status, rufen Sie diese API erneut auf.

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

### Siehe auch

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
