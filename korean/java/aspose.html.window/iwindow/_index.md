---
title: "IWindow 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.window.IWindow 인터페이스. window 객체는 DOM 문서를 포함하는 창을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.window/iwindow/
---
## IWindow interface

window 객체는 DOM 문서를 포함하는 창을 나타냅니다.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) document 속성은 Window 객체의 최신 Document 객체를 반환해야 합니다. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Document의 frameElement 객체. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) 키/값 쌍을 사용자 에이전트에 저장할 수 있는 Storage 객체를 반환합니다. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Window 인터페이스의 location 속성은 해당 Window 객체의 Document에 대한 Location 객체를 반환해야 합니다. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) opener IDL 속성은 Window 객체에서 가져올 때, 현재 browsing context가 생성된 browsing context(그의 opener browsing context)의 WindowProxy 객체를 반환해야 합니다(존재하고 아직 사용 가능하며 현재 browsing context가 opener를 포기하지 않은 경우). 그렇지 않으면 null을 반환합니다. 설정할 때, 새 값이 null이면 현재 browsing context는 자신의 opener를 포기해야 합니다; 새 값이 다른 경우 사용자 에이전트는 Window 객체의 [[DefineOwnProperty]] 내부 메서드를 호출하여 속성 이름 "opener"를 속성 키로 전달하고, Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true }를 속성 기술자로 사용해야 하며, 여기서 value는 새 값입니다. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) parent IDL 속성은 browsing context b에 있는 Document의 Window 객체에서, 부모 browsing context가 존재하면 그 부모의 WindowProxy 객체를 반환하고(즉, b가 자식 browsing context인 경우), 그렇지 않으면 browsing context b 자체의 WindowProxy 객체를 반환해야 합니다(즉, 최상위 browsing context이거나 분리된 중첩 browsing context인 경우). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Window 객체의 browsing context에 대한 WindowProxy 객체를 반환합니다. |
| [getTop](../../com.aspose.html.window/iwindow/top/) top IDL 속성은 browsing context b에 있는 Document의 Window 객체에서, 최상위 browsing context가 존재하면 그 최상위 browsing context의 WindowProxy 객체를 반환해야 합니다(만약 b 자체가 최상위 browsing context라면 자신의 WindowProxy 객체가 됩니다). 최상위 browsing context가 없으면 자신의 WindowProxy 객체를 반환합니다(예: 분리된 중첩 browsing context인 경우). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Window 객체의 browsing context에 대한 WindowProxy 객체를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | 주어진 메시지를 포함한 모달 경고창을 표시하고 사용자가 닫을 때까지 기다립니다. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | 입력 데이터를 base64로 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 형태로 받아 디코딩하고, 각 문자가 U+0000부터 U+00FF까지의 범위에 해당하며 각각 0x00부터 0xFF까지의 바이너리 바이트 값을 나타내는 문자열을 반환합니다. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | 입력 데이터를 U+0000부터 U+00FF까지 범위의 문자만 포함하는 Unicode 문자열 형태로 받아, 각 문자가 0x00부터 0xFF까지의 바이너리 바이트 값을 나타내며, 이를 base64 표현으로 변환하여 반환합니다. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | 주어진 메시지를 포함한 모달 OK/Cancel 프롬프트를 표시하고 사용자가 닫을 때까지 기다린 뒤, 사용자가 OK를 클릭하면 true, Cancel을 클릭하면 false를 반환합니다. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | 새 MediaQueryList 객체를 반환하며, 이를 사용하여 문서가 미디어 쿼리 문자열과 일치하는지 판단하고, 일치 여부가 변할 때(일치하거나 일치하지 않게 될 때) 문서를 모니터링할 수 있습니다. CSSOM View Module 사양을 참조하십시오: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | 주어진 메시지를 포함한 모달 텍스트 입력 프롬프트를 표시하고 사용자가 닫을 때까지 기다린 뒤, 사용자가 입력한 값을 반환합니다. 사용자가 프롬프트를 취소하면 null을 반환합니다. 두 번째 인수가 제공된 경우, 해당 값이 기본값으로 사용됩니다. |

### 또 보기

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
