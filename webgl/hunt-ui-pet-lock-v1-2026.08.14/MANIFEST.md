# LumenStory Unity WebGL hunt-ui-pet-lock-v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-14`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `62d0c681cba8396f7240da191befed8e8bec55e9`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 439,893,599 | `9ef63d3097c900644094af019a340b713b63968dce15bffc231d3cb459a8679b` |
| `WebGL.wasm` | 120,069,883 | `9666f306b1b30df447662164ff7da11a4d50f4766faa8346eb6e5933cf7746e1` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `7bcfb648fb84337ec56e87b9e13b5b56bddbd023739d7a77d21848b0e1f2fd94` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `7727d149a34b9e4b97473cc11d1702f4516ed3b92a3bb1533f686b27c6b1f27b` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `73f433957173143ffaca20ea2f231700f6fb6640facd86da49d085ba347e28a1` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `5e2f65c9807e182ccbb6c57d9fbdf8ccc1b42893e44b8f29757b3b55c07a715b` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `a4628043448cd5ef6c50abb542e31f63b5c59a46592f83c96e5145164a20892b` |
| `UnityWebGL.data.gz.part-006` | 50,000,000 | `361dfc9a8d72d75a54bf811ff63c1dbd2c650c1f9877522fe10a4648514f210b` |
| `UnityWebGL.data.gz.part-007` | 50,000,000 | `86dc7460c64f0c007d804034a50ffedab2e9788a23fa29491df14dbc5ad7392b` |
| `UnityWebGL.data.gz.part-008` | 21,725,966 | `a8546a1178c4f743aef7cd8c2040a53b9bf3e3b7d511c5f7e59a8be4cb805cdf` |
| `UnityWebGL.wasm.gz` | 26,868,317 | `2ac954cfe61050af3e581eb26db467917fcc0e8cb2294fa6af2b363f3d1a9cbe` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
