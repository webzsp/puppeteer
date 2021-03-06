<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Media](./puppeteer.protocol.media.md) &gt; [PlayerError](./puppeteer.protocol.media.playererror.md)

## Protocol.Media.PlayerError interface

Corresponds to kMediaError

<b>Signature:</b>

```typescript
export interface PlayerError 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [errorCode](./puppeteer.protocol.media.playererror.errorcode.md) | string | When this switches to using media::Status instead of PipelineStatus we can remove "errorCode" and replace it with the fields from a Status instance. This also seems like a duplicate of the error level enum - there is a todo bug to have that level removed and use this instead. (crbug.com/1068454) |
|  [type](./puppeteer.protocol.media.playererror.type.md) | ('pipeline\_error' \| 'media\_error') | (PlayerErrorType enum) |

