# LumenStory Unity WebGL growth-stat-walk-v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-14`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `aee344b4`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 439,890,292 | `7a3a395bd8e44cc7befcd5cc3204f8b5af8f4bc902f49a1d63dd62f1443494a6` |
| `WebGL.wasm` | 120,044,981 | `dd5148ced31dee9115151bce6dea7a6396ca35b094d4de000229bfac005a83cd` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `6cd652b2488d18903184d980b5217dcf7e8ca03e939607a61e4904dfabb6f4be` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `f26e656c86f55810d42dae39a7f194596b7b176f0995528183cbd073f1c5382c` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `fecbc22362b853f82e20ebc83ad015435c8b50a1859cc86b531bf536060aaf1e` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `59a88e2e001db3cccd5f2ab7ec126404cf573c85abbdc36fd76d7e0362d99f7e` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `521a5743698394e1118f0e9e4ce0f6c0d28e3905907286dec3bfbfc403a9f019` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `2fc1ed0943d502ebe6fd75e91cd4b6f6db34922ed8eace7f075d20889fd962aa` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `a1e2c890d86bf080943f33a5d848cb189007d4acd2bb4419e548f39799923e40` |
| `UnityWebGL.data.gz.part-008` | 21,721,193 | `8f75d67ea21f59126014093c581473ec8ba581280998eb8432485ba112901ecb` |
| `UnityWebGL.wasm.gz` | 26,865,615 | `f876bc4bc553f5f6d667704c2cfb864d11e5974a9e94b37bb0ef09c4c6d1c91c` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
