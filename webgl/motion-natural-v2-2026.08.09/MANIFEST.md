# LumenStory Unity WebGL Natural Motion v2 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-09`
- Source branch: `codex/full-cross-client-sync`
- Source base commit: `8355ea27`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `webgl.data` | 351,934,741 | `6021d21079d7cc0e4bad183a44b87f91ad5917a1539db72537a54f2d10cf9e86` |
| `webgl.wasm` | 119,942,152 | `9f6196d37fdb8ab8af61116793db8d54b24526438dc11b7a8e3f0827fc5647ad` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `3cc019831d47925a80cc6bf37ea83356e62d5d82d9b9bc7cb86cf4b305fed27c` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `b5c404af6d4d45ca21250e7bc7b33cd391738744c5a33f5ef79c88d1bb81228f` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `3216966b19d3af2ee3af032c8c688da5973bd3c5c079f9a1f96c8876c1949877` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `3d63bf7dbb5e4c2512a0c9d73ab8f3c00587192faff45b1f4f74fe52962b15d6` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `5e30eaf00c82004a10219866b43192d6e2dfd0f908d2484976e281df63e1e04a` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `cf65304885ebf8a6042db02716861434cc5a088fa5494e9166bbfd7d7d3d02c7` |
| `UnityWebGL.data.gz.part-007` | 3,450,683 | `b7e7123da54c6aaa6c539cb3531efd9112a7b847833a0f8ed9d30b2c4eccbfff` |
| `UnityWebGL.wasm.gz` | 26,840,258 | `b5338b631886b22978057954e71be66315da2050872286d25b08b0c440a55a92` |

The public loader concatenates the seven data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
