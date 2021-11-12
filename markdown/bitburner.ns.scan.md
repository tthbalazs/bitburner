<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [scan](./bitburner.ns.scan.md)

## NS.scan() method

Get the list servers connected to a server.

<b>Signature:</b>

```typescript
scan(host: string, hostnames?: boolean): string[];
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  host | string | Hostname of the server to scan. |
|  hostnames | boolean | Optional boolean specifying whether the function should output hostnames (if true) or IP addresses (if false). |

<b>Returns:</b>

string\[\]

Returns an string of hostnames or IP.

## Remarks

RAM cost: 0.2 GB

Returns an array containing the hostnames or IPs of all servers that are one node way from the specified target server. The hostnames/IPs in the returned array are strings.
