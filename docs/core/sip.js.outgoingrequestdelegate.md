<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [OutgoingRequestDelegate](./sip.js.outgoingrequestdelegate.md)

## OutgoingRequestDelegate interface

Delegate providing custom handling of outgoing requests.

<b>Signature:</b>

```typescript
export interface OutgoingRequestDelegate 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [onAccept(response)](./sip.js.outgoingrequestdelegate.onaccept.md) | Received a 2xx positive final response to this request. |
|  [onProgress(response)](./sip.js.outgoingrequestdelegate.onprogress.md) | Received a 1xx provisional response to this request. Excluding 100 responses. |
|  [onRedirect(response)](./sip.js.outgoingrequestdelegate.onredirect.md) | Received a 3xx negative final response to this request. |
|  [onReject(response)](./sip.js.outgoingrequestdelegate.onreject.md) | Received a 4xx, 5xx, or 6xx negative final response to this request. |
|  [onTrying(response)](./sip.js.outgoingrequestdelegate.ontrying.md) | Received a 100 provisional response. |

