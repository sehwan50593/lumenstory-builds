# LumenStory Unity WebGL Beginner Journey v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-13`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `38c4f19e`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 439,395,783 | `0f8caf0d3a9855b9750b333e612fd330b06de9dcbc69f137c2a562018ff60d0b` |
| `WebGL.wasm` | 120,032,696 | `74b87d8c0701124719cc41d0e41aa776ab4bd4e42545b7759bb2e5c42c1e2f21` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `ec446ef3f75418bf11946fb2afeb6a5d451a3cec8a6504348e824e7cb24352a5` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `34d05a1e9593da7dbd63c0029c15796462ce707e75ddd9d9f74364d978d27a66` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `fb2a5de24c247f531feb3c3cf1f2290b30809aa2270117bf18f54d16a00493b2` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `8378fd14b45ecbbc8e9c7b50b60a170650f6ea10cbc74f89e52c74a662abb5ea` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `a8d453959e7f6dd47ce962084c893e6449b0cb97250b8e6d08b1445bd604c1f6` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `76bff5404ab77e65e682d90ebeb3577b7187322b7be36ece370dd083dd1f4d26` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `3e087ef3c94f224469fca0be31d2e220ebd1ede915875825fc58d910fe507d12` |
| `UnityWebGL.data.gz.part-008` | 23,546,096 | `1cc9c22f0559dc4d15dc79b522d37301073af028efc6c8547b9baaaefe2d9b71` |
| `UnityWebGL.wasm.gz` | 27,295,074 | `45b66a74005a40423684a2df4582e19804c0798e0f9ac4e4ee1f59575c3744a1` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
