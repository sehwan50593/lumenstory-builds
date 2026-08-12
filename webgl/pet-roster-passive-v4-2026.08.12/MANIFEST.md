# LumenStory Unity WebGL Pet Roster Passive v4 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-12`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `03540ea02940fd880dad8a076ee05fff228696d4`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 436,647,960 | `ca16b5800912d5be1948e8f2995cfea441f62df02fcbc586772bacf708bb9549` |
| `WebGL.wasm` | 120,006,001 | `15d18350fda4e75fdf4d6d2fc772201ae38990de6225a992269050cbc3b83137` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `300d98a449beea5e63c7ea020edd8cf9984330d32eb26ba1977b7b205b760f29` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `ca60522630670657f5184171190e0799cf2ee94f3927f810347941d825f48f20` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `f253c680ea234ce947c3e29b4c2c3f6bbdb148b3101ff6444e2eabfdd6dd5105` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `20e04d236674c8e0586060f425d0a21f8d7fd9046f0115301451a29ce985d3a5` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `7e368e3a4032c6cddc9748e1aac1801f6c53c02558dbc2d8b51230e5c253220c` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `6981838119fa5a001e57113eabd8d08d6ccb003d6ad80bb631a864f637aa46b8` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `2ac469773893328a8825326cf8c610d8777bcaaa7811075a1b3c6b0af42ad7d7` |
| `UnityWebGL.data.gz.part-008` | 19,271,121 | `7887f6f16163d013ec8792b1759a17bb1e1fd29addbedbc826f4f44dda53466c` |
| `UnityWebGL.wasm.gz` | 26,963,008 | `486d27b9c19ff69a30ba24f95e3a3f409b5eeabfe519d0c35c503288c9ecd083` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
