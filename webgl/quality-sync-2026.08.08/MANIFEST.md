# LumenStory Unity WebGL quality sync payload

- Unity: `6000.3.20f1`
- Build: Development WebGL
- Built: `2026-08-08`
- Source branch: `codex/full-cross-client-sync`

## Decompressed payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `WebGL.data` | 232,894,894 | `9008bd72bf92be01d21ef66c6f3863d4e20a7175cb648c67effbe51fb7907b03` |
| `WebGL.wasm` | 119,911,451 | `93c33f7d36bac93b84e7490acfa128fcfcde2fbd34a10c5b9f4af290faa1f8ab` |

## Hosted gzip payload

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `a12cf8ed78b772fbd78194ee988922f2acbb31ecd8bc23a24e7c272ae11bc74b` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `0001457229d7253ee73e256790eb1bc1134361a5c289bcecc345447d4a5fed52` |
| `UnityWebGL.data.gz.part-003` | 50,000,000 | `f5ae1613252828550a9542e59095768e9a387b230237f035dc19038019aabd85` |
| `UnityWebGL.data.gz.part-004` | 50,000,000 | `f52a20a3c1e03b77b52978fc7141a55554744f21c58a8a027699a1f8210585e7` |
| `UnityWebGL.data.gz.part-005` | 292,204 | `2b25fe578cc7a41becb9c0d8deb4372fc36aade66c90ef07efebe4a3f0806274` |
| `UnityWebGL.wasm.gz` | 26,939,896 | `1fe59ac89ca3543fa51683d717bb66739bc355189be57ced5c4b41d9055b90d2` |

The public loader concatenates the five data chunks, decompresses both gzip
payloads in the browser, verifies the decompressed byte counts, and passes blob
URLs to the Unity loader.
