# LumenStory Unity WebGL Beginner Integrated Branch v2 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-13`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `a40b5200`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 439,393,556 | `06d0aed3b93179e3254c7c6e2556fc7bdb2fd75fd610742ebafc4eb31626f9d5` |
| `WebGL.wasm` | 120,018,391 | `b5d9db2422b2c2e74268e6ad354269212952491f1268cf43a83d93f155c1bb46` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `2e3eb1b935b55b96a5b8a126083475e6df54c2689ec513114cf35f2778496aa9` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `77c240094764c42836ebe480920b77095c0de82e58709b697454b385679cc474` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `1bfd0e728e9944829cad4b508d046bf72ef8d014e81babaaa392fe8ef3b43939` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `73d8d8a8209184a507af58165a9e86fab82aec22eb0f8f2040f2b7abffc263f9` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `ae414a616eb8b777837ed10c2183e966d1c0f6720fa15aa8bcbd65741a8a0513` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `591218040e08bcc6aef0e77d9b537b7528611f1100174f2c222e5f0a1893f2db` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `1e3fef171cc11b8ec30d7ea89b16422ff85532e0ba19855adeba3f4a8805b726` |
| `UnityWebGL.data.gz.part-008` | 21,307,245 | `58ee320e2f498b52458b7ef86f7dcbf4aff8f63bd011bc49eb5144a6085209c5` |
| `UnityWebGL.wasm.gz` | 26,853,310 | `fab5e73f77ba6deb3247bd4a505bc9be060caa704f47bdc482a00e2c2f078897` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
