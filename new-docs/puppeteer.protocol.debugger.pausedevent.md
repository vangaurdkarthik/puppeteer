<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Debugger](./puppeteer.protocol.debugger.md) &gt; [PausedEvent](./puppeteer.protocol.debugger.pausedevent.md)

## Protocol.Debugger.PausedEvent interface

Fired when the virtual machine stopped on breakpoint or exception or any other stop criteria.

<b>Signature:</b>

```typescript
export interface PausedEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [asyncCallStackTraceId](./puppeteer.protocol.debugger.pausedevent.asynccallstacktraceid.md) | [Runtime.StackTraceId](./puppeteer.protocol.runtime.stacktraceid.md) | Never present, will be removed. |
|  [asyncStackTrace](./puppeteer.protocol.debugger.pausedevent.asyncstacktrace.md) | [Runtime.StackTrace](./puppeteer.protocol.runtime.stacktrace.md) | Async stack trace, if any. |
|  [asyncStackTraceId](./puppeteer.protocol.debugger.pausedevent.asyncstacktraceid.md) | [Runtime.StackTraceId](./puppeteer.protocol.runtime.stacktraceid.md) | Async stack trace, if any. |
|  [callFrames](./puppeteer.protocol.debugger.pausedevent.callframes.md) | [CallFrame](./puppeteer.protocol.debugger.callframe.md)<!-- -->\[\] | Call stack the virtual machine stopped on. |
|  [data](./puppeteer.protocol.debugger.pausedevent.data.md) | any | Object containing break-specific auxiliary properties. |
|  [hitBreakpoints](./puppeteer.protocol.debugger.pausedevent.hitbreakpoints.md) | string\[\] | Hit breakpoints IDs |
|  [reason](./puppeteer.protocol.debugger.pausedevent.reason.md) | ('ambiguous' \| 'assert' \| 'debugCommand' \| 'DOM' \| 'EventListener' \| 'exception' \| 'instrumentation' \| 'OOM' \| 'other' \| 'promiseRejection' \| 'XHR') | Pause reason. (PausedEventReason enum) |

