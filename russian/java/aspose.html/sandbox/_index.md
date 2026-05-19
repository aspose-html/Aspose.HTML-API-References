---
title: "Перечисление Sandbox"
second_title: "Справочник API Aspose.HTML для Java"
description: "Перечисление com.aspose.html.Sandbox. Набор флагов песочницы представляет собой набор из нуля или более следующих флагов, которые используются для ограничения возможностей потенциально ненадёжных ресурсов"
type: docs

url: /ru/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Набор флагов песочницы — это набор из нуля или более следующих флагов, которые используются для ограничения возможностей потенциально недоверенных ресурсов.

```java
[Flags]
public enum Sandbox
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Не установлен ни один флаг, все функции песочницы разрешены |
| Navigation | `1` | Этот флаг препятствует контенту переходить к контекстам просмотра, отличным от самого sandboxed browsing context (или контекстов, вложенных в него), auxiliary browsing contexts (которые защищены флагом sandboxed auxiliary navigation browsing context flag, определённым далее), и top-level browsing context (который защищён флагом sandboxed top-level navigation browsing context flag, определённым ниже). Если флаг sandboxed auxiliary navigation browsing context flag не установлен, то в некоторых случаях ограничения всё же позволяют открывать всплывающие окна (новые top-level browsing contexts). Эти browsing contexts всегда имеют один разрешённый sandboxed navigator, задаваемый при создании browsing context, который позволяет создающему их browsing context действительно навигировать их. (В противном случае флаг sandboxed navigation browsing context flag предотвратил бы их навигацию, даже если они были открыты.) |
| AuxiliaryNavigation | `2` | Этот флаг препятствует контенту создавать новые auxiliary browsing contexts, например, используя атрибут target или метод window.open(). |
| TopLevelNavigation | `4` | Этот флаг препятствует контенту навигировать их top-level browsing context и закрывать их top-level browsing context. Когда флаг sandboxed top-level navigation browsing context flag не установлен, контент может навигировать свой top-level browsing context, но другие browsing contexts всё ещё защищены флагом sandboxed navigation browsing context flag и, возможно, флагом sandboxed auxiliary navigation browsing context flag. |
| Plugins | `8` | Этот флаг препятствует контенту создавать плагины, будь то с использованием элемента embed, элемента object, элемента applet или через навигацию вложенного browsing context, если только эти плагины не могут быть защищены. |
| Origin | `10` | Этот флаг принуждает контент к уникальному источнику, тем самым препятствуя доступу к другому контенту того же источника. |
| Forms | `20` | Этот флаг блокирует отправку формы. |
| PointerLock | `40` | Этот флаг отключает API Pointer Lock. |
| Scripts | `80` | Этот флаг блокирует выполнение скриптов. |
| AutomaticFeatures | `100` | Этот флаг блокирует функции, которые срабатывают автоматически, такие как автоматическое воспроизведение видео или автоматический фокус на элементе формы. |
| Fullscreen | `200` | Этот флаг препятствует контенту использовать метод requestFullscreen(). |
| DocumentDomain | `400` | Этот флаг препятствует контенту использовать функцию document.domain для изменения эффективного источника скрипта. |
| Images | `800` | Этот флаг отключает загрузку изображений. |

### См. также

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
