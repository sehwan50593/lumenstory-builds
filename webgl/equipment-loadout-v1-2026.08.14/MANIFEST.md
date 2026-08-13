# LumenStory Unity WebGL Equipment Loadout Clarity v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-14`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `b839c43bdacd4f9b5a9f279402f73f60f19a6c5e`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 439,889,625 | `af5713a621d9741cf9f422d133b085be8e4a8fee9995fce7cf4c08f63795418b` |
| `WebGL.wasm` | 120,039,536 | `51167c64052c0ce79a38a154dd3edff531f6b7056ebcf8ec31fe34542aed539e` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `631fa98260fcc4a850e91001306e5679885d6ab4379aee2cfe53c1935223f988` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `c6c7d55a51de4879360d0726ee0ca7dfbcface68751b281f87d62173f0ead8b2` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `ea4b85da20f8e9e29d56e6848a753496ea17a7ce4c75b0f1eaf28c45cc3c0100` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `319ee3ec3aacca5200ffdc29626537e9262b8592e8f291102eaa5e2b31013480` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `812813737cbcf74954eec296eb2e0c6c6d5a57f626b96b6c181d2aa354d39c15` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `d17f7745d781c84760e1755b024bd25fac69bb4e5e34ae2d9d97efab13275cdf` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `8c17b6bb13394f79678d94007cafb31d96c09149d2388175b028d41865355a0f` |
| `UnityWebGL.data.gz.part-008` | 21,720,908 | `4dcba63f243927395c4a6c8158c374e0f6ff1332f34941800b2d4e3a99127bcf` |
| `UnityWebGL.wasm.gz` | 26,864,954 | `0e009901a74cc9c20ca0aae887b2c7b418fa89a56f5e25ca53ecb934746710c1` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
