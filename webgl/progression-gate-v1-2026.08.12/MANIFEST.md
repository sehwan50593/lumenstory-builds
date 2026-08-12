# LumenStory Unity WebGL Progression-Gate-v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-11`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `2949f60a`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 436,649,552 | `73b93401b3db21c1aa4ac1b0bf5e15a767d539b3a2448a83e58033163da7a0a0` |
| `WebGL.wasm` | 120,018,044 | `a59572a1cd957cc8352150415fe2158f16f7b94118ab2ce7687d561ce449d2ee` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `223a6974041cec290367fdde9e993ef12b1e1b13fa26101a7db9d004cb4ee2fa` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `eafb16c8010492a10a17cd9aaac35ee0b5119185cb818f0984a12b91ab2ab9e0` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `719ca7dfb0906827fb46a23dc14099613cc9b90d06c8b444d9c1832aa1e17c70` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `8c0f093278722ced3c194eb7b7ce07353a87a46bea7dd0c297e6f484c8a946d6` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `7f6e54208f2a28601856dc435136c8e2be980aa661c71c5ab3f1de624396bada` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `4019a7bf47bd9c19cdd75a280d3ca80114a17bda042a45f320a771c7db88aa2b` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `ff6da5f547e10c612f59b927351fb7259c679d03ef41989dd647e30ddae434a6` |
| `UnityWebGL.data.gz.part-008` | 19,225,645 | `72f477fa1085eb6979d08be4d230a066bb053312067978f0bc092cf06f3233f2` |
| `UnityWebGL.wasm.gz` | 26,852,252 | `e1a6db9249651d395defc31db1051b113cd160ffbdaf092865a5e0e611159536` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
