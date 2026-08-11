# LumenStory Unity WebGL Pet Grade Motion v3 / Full Card Gacha v2 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-11`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `e7b67f01`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 381,917,769 | `eeb44c184ef6b9219a203629fee95d1b6614bb62013050caf98df1677bf4155f` |
| `WebGL.wasm` | 119,984,388 | `7bee0573a7a71ffa24a44a3c635ed5e818db594b79af727bc2a019ed42daf5f5` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `adabc876fdf808ff4f410e689e395b47983f3e4f6fd44a61d59da42479759898` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `4d50e406367ab7bebf3f37cf8b178b8a02569052f353f1287c01845ebdd6bced` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `13a8c8a99ca6fd609bdfbde1a1c3c80599276c450465a324d58ddd740f27a90e` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `e27278008cceff956ac6948d652ad66fcce7831b4ffb0345705c74d7f336af45` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `346f26401c6aa2cbb9f01e22900367646e4c95da622dfe23dd92c60f73f4f442` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `400dbdc666975e96d0a90ff4faf78257d051bbdd0dee168e7c66c9b4da3ddc69` |
| `UnityWebGL.data.gz.part-007` | 26,241,350 | `0aea9028d69d40eee02e2e9904fb32ab9017bcaa03f87cb2d4836163e56f1def` |
| `UnityWebGL.wasm.gz` | 26,863,471 | `5deac8240e7d26b0eba7002b5f051a36af5ceb37fcf75e3cb87f5ddb1e7e8aa6` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
