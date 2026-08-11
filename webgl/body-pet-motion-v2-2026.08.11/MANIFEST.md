# LumenStory Unity WebGL Body-driven combat and pet stride v2 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-11`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `785d5106e57aa12df3609f89892b19cb845b673b`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 348,008,746 | `0b018678f2a81c26cd6f88fa5fd11ab1e0cd0313575eca310e98cc1a27f04726` |
| `WebGL.wasm` | 119,980,016 | `f2c8ce71bf43f4d6944a09a935346a8319a59968672a607ec424075b18d05321` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `f53ee284effd1f9e8188d60e85d9cb62aa820d5980ad544f40468cf4dd7ec701` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `682208321e3de6c51f8dfb99dfe678014c4d1a407deca2e72e981a73831a51c7` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `0dd7aa80ef685e73f2bacf46bc761e5d977b38e277c35f14e61ad79c6275093f` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `4249903631218618327f6771bdc984b98fd75c9e7695f22e327688d1359c0d5c` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `fc900f58df08f4e2092d8a7ea40981f8b08f136dc241336bab7594dd018c28c5` |
| `UnityWebGL.data.gz.part-006` | 49,532,506 | `5a85a72f2a2abb692f491376569930b5c85e6f257c7a4bca6dcd27b9b0b135c6` |
| `UnityWebGL.wasm.gz` | 26,854,559 | `b0fdcbc095b3980b63e9efadb6f1b3df8e14fff9cf9be13a1ae89c79263893ac` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
