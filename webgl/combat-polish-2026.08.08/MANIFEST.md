# LumenStory Unity WebGL — combat-polish-2026.08.08

Unity 6000.3.20f1 Development WebGL payload for the public cross-client QA page.

The browser concatenates the three `data.gz` parts in filename order, then decompresses
the data and wasm payloads with `DecompressionStream("gzip")` before starting Unity.

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `UnityWebGL.data.gz.part-001` | 50,000,000 | `30b7ee79aebac086baa52bd36f8f332237bd61b057362c84a1f2d149f2bee5dd` |
| `UnityWebGL.data.gz.part-002` | 50,000,000 | `3acf9d99055ca9eeea7f488c8603e2c48a448974a4b5a22c6c535c66d3044c79` |
| `UnityWebGL.data.gz.part-003` | 36,337,164 | `de6195e9e6331135db26a9c4e4738c513d5a2e1c2844dde1275934bcc647f349` |
| `UnityWebGL.wasm.gz` | 26,753,150 | `89fd48c49d3f2964178dcc2736558a8b3e3d5c91b6472f0eb6068ac7ca9047ec` |

Reassembled payloads:

| Payload | Compressed bytes | Compressed SHA-256 | Uncompressed bytes | Uncompressed SHA-256 |
| --- | ---: | --- | ---: | --- |
| data | 136,337,164 | `79dd7d1dfee9a4838cf83e23462b82456ccc951d18114aff6453e5c1b9110277` | 167,640,669 | `0d7ac0f1309d992475f25bbf4aacd280fd4090279c72ac99446703072a5dcd78` |
| wasm | 26,753,150 | `89fd48c49d3f2964178dcc2736558a8b3e3d5c91b6472f0eb6068ac7ca9047ec` | 119,321,864 | `59f0cb4fa2af470a20ecc82103df3d4f934d483c105647ddf484666aebda043c` |
