<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/rspeedy](./rspeedy.md) &gt; [Performance](./rspeedy.performance.md)

## Performance interface

The [Performance](./rspeedy.performance.md) option is used to

**Signature:**

```typescript
export interface Performance 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [chunkSplit?](./rspeedy.performance.chunksplit.md) |  | [ChunkSplit](./rspeedy.chunksplit.md) \| [ChunkSplitBySize](./rspeedy.chunksplitbysize.md) \| [ChunkSplitCustom](./rspeedy.chunksplitcustom.md) \| undefined | _(Optional)_ [Performance.chunkSplit](./rspeedy.performance.chunksplit.md) is used to configure the chunk splitting strategy. |
|  [printFileSize?](./rspeedy.performance.printfilesize.md) |  | PerformanceConfig\['printFileSize'\] \| undefined | <p>_(Optional)_ Whether to print the file sizes after production build.</p><p>[Performance.printFileSize](./rspeedy.performance.printfilesize.md)</p><p>See [Rsbuild - performance.printFileSize](https://rsbuild.dev/config/performance/print-file-size) for details.</p> |
|  [profile?](./rspeedy.performance.profile.md) |  | boolean \| undefined | _(Optional)_ Whether capture timing information in the build time and the runtime, the same as the [profile](https://rspack.dev/config/other-options#profile) config of Rspack. |
|  [removeConsole?](./rspeedy.performance.removeconsole.md) |  | boolean \| [ConsoleType](./rspeedy.consoletype.md)<!-- -->\[\] \| undefined | _(Optional)_ Whether to remove <code>console.[methodName]</code> in production build. |

