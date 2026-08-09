# LumenStory Unity WebGL Ambient Motion v3 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-09`
- Source branch: `codex/full-cross-client-sync`
- Source base commit: `8355ea27`
- Motion contract: `motion-01-v7`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 353,403,911 | `1506060b0aae03f1b0734fbc08a2da41768ae0eadef5f4288cf2f1c862ff8e2b` |
| `WebGL.wasm` | 119,951,275 | `3e3af78a401d59980811870ad145376fa8d0f017accfce71998ee5efe98159c2` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `48bf817e1fd099f9ef87cc73aa66621e5b758143f955a5c2c3cd017b8cd18eb4` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `f37a2f98e3d692e914b7acd7aac7bd3cc96781ae6a65727cf2953af8967f8e68` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `3d9d5f1aae9db2a5c6739c1bb7ccae0b6fef6348b3e67b2aab94b66a0a057221` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `8b9eb8b6ddc869fc6dc9080ba41ba07d283c61d262ed452a0471bcd8c3e13acb` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `5c6604616da46c7a2f6d8eb0b83044616a492cd3eee22874d95a2cd714323f97` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `07d7d70213cd3621f9aae309e330b5fe6902e3524404620e8396980c94ac0deb` |
| `UnityWebGL.data.gz.part-007` | 4,688,434 | `321a0c33631f4224bc0be700d7f47ec234f4473ae2d2cb86058ae0acb2cfbf35` |
| `UnityWebGL.wasm.gz` | 26,840,251 | `c9e82a38ae6ac199f77fe3843b9aac6a633b5010ab41439e8daac33a958e7007` |

The public loader concatenates the seven data chunks, decompresses both gzip
payloads, verifies their decompressed byte counts, and passes blob URLs to the
Unity loader.
