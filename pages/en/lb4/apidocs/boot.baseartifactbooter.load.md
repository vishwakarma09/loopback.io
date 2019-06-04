---
lang: en
title: 'API docs: boot.baseartifactbooter.load'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.boot.baseartifactbooter.load.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/boot](./boot.md) &gt; [BaseArtifactBooter](./boot.baseartifactbooter.md) &gt; [load](./boot.baseartifactbooter.load.md)

## BaseArtifactBooter.load() method

Filters the exports of 'discovered' files to only be Classes (in case function / types are exported) as an artifact is a Class. The filtered artifact Classes are saved in the 'classes' property.

NOTE: Booters extending this class should call this method (await super.load()) and then process the artifact classes as appropriate.

<b>Signature:</b>

```typescript
load(): Promise<void>;
```
<b>Returns:</b>

`Promise<void>`

