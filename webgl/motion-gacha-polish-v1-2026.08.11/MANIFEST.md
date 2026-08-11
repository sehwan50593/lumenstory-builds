# LumenStory Unity WebGL Motion/Gacha Polish v1 payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-11`
- Source branch: `codex/full-cross-client-sync`
- Source commit: `5ddcece0`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 348,009,086 | `7af1b518f76155f5391b2a905fde05782d8cf0f540e193910ddf035c295bbe96` |
| `WebGL.wasm` | 119,982,666 | `7d72a72b2c62a06d035ad152d385ca887116ce19726b200b37e4fca8178a5f4c` |

## Hosted deterministic gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `2d3f7ef7c567c0dd0039dff076d9956b1a5b3508e8dd7e980c08b7da41736933` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `8cb55cdafde31ca2632c8d2be3f9fcddbbc33d63e2f0740a0c5292320cfef917` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `b1504eba78cb0a4cb394b43fdccdbd918e84bd7387d799d769e1f735281a2ef5` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `0237753c9c623232c5a092cbeb2798fcbe574dc7cab8c263ccdfbf5c8d0c1ae1` |
| `UnityWebGL.data.gz.part-005` | 50,000,000 | `b55c43fa61ea6a2333a7d01bd0336831402475a2c6dc686bb1f8803d4190c5b7` |
| `UnityWebGL.data.gz.part-006` | 49,530,922 | `22128459c9795420387eb285da887bbb8745459ea686dffb51cd85206a2ac589` |
| `UnityWebGL.wasm.gz` | 26,862,385 | `d63f506b1532089a9d8ca923648ddc8b897b3e1761e8af215982a4370fe12126` |

The public loader concatenates the data chunks, decompresses both gzip payloads,
verifies the decompressed byte counts, and passes blob URLs to the Unity loader.
