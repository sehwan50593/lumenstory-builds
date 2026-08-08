# LumenStory Unity WebGL Career Skills v3 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-09`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `43e3bd774c883be91a1a767f6d275e4dd7012ede`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `webgl.data` | 283,857,837 | `f38d62049f69c580e58166727135697a9e6466950e43b67a71b8ce2ec00a1338` |
| `webgl.wasm` | 119,932,989 | `9efb47c08fbb0ed673c1382d0b83027a7dc657ba14c0d31fc6ece3c5e2aac7bf` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `b794c2211218d6743fcc0a656c0ac2ed96faec5d88222dc7ffa792365c32de54` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `b9c3d914a2fd445c680c82514881d4f872e9f46b3d2fed9b91b49b6f33d01ab1` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `59e3b5d845efaa10c02aa1b592690436ff1391e00088766138bb764dc2ec9b05` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `8b15c0ad1e2c853a6ee8c101c8223108cd1016d651eeaecf2d2944cb305c0d69` |
| `UnityWebGL.data.gz.part-005` | 43,533,674 | `f334dcaa2148dca5fe46c1f26a0cba91a6c3f626db6c31c9ab16468eed542e6a` |
| `UnityWebGL.wasm.gz` | 26,836,659 | `df1fd82d9c1824ff6bf878d1b873fc0dbbcf006fd2a3c85b83b4116cca9c28a4` |

The public loader concatenates the five data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
