<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@textile/hub](./hub.md) &gt; [ThreadID](./hub.threadid.md) &gt; [fromRandom](./hub.threadid.fromrandom.md)

## ThreadID.fromRandom() method

fromRandom creates a new random ID object.

<b>Signature:</b>

```typescript
static fromRandom(variant?: ThreadID.Variant, size?: number): ThreadID;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  variant | ThreadID.Variant | The Thread variant to use.  Variant |
|  size | number | The size of the random component to use. Defaults to 32 bytes. |

<b>Returns:</b>

ThreadID
