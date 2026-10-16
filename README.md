# Repolex Knowledge Graph of pysal/spreg

RDF knowledge graph data for [pysal/spreg](https://github.com/pysal/spreg), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download pysal/spreg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4dbc809242d9fe8f5fca0257c7dc9c957fc1ce36
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4dbc809242d9fe8f5fca0257c7dc9c957fc1ce36
│           └── chunk-001.nq.gz
├── blob
│   ├── 0037178778579969490bdbaf86a4100cb90aaafe.nq.gz
│   ├── 0358ca905242781d0be981bf75712119bbea76d9.nq.gz
│   ├── 051034bcc37cfd3e4cfdfeea5fd48184b69473f4.nq.gz
│   ├── 060da2c4c58e9e4cde443951c9248a5a5de97655.nq.gz
│   ├── 07d9d0bdc82a60d9e7dfe2e73556905b1aa130a4.nq.gz
│   ├── 094604a618662b2dedca8e157816ccb21ca2c3de.nq.gz
│   ├── 097daceebf03cc1dad68812cb94d9e7865f5b331.nq.gz
│   ├── 09cb42c8654de6a6f78238f38a253f9748117f92.nq.gz
│   ├── 0a1de231bf4f420bcf0d7110b914a11b5d9b5040.nq.gz
│   ├── 0c59bb62e8d9b28c05927eff8dc10af60d50cc53.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 0ea40e8323367c4788f36dba598abb1ea5dee4c6.nq.gz
│   ├── 10d17f9ad07e92ccfaab317d23f3162315045d06.nq.gz
│   ├── 12af71a47a661f686371d4f988fc7f20ef51a8ef.nq.gz
│   ├── 18cc550f3793627c4873119027861e83f6f9749d.nq.gz
│   ├── 191e0d067f5f5264747a52420415a59b7225fbd3.nq.gz
│   ├── 1bef6c40ec96c950707eee19464ac5e264674888.nq.gz
│   ├── 1c0e212709fa4039cde3f68fc14f265c82337313.nq.gz
│   ├── 1fb7416e37158b2621641461f800dd4baf507c38.nq.gz
│   ├── 20ad78ff2727481f720474b1b9360b723b53e343.nq.gz
│   ├── 220d5a1b502afae73be165515ea2f78198a4798c.nq.gz
│   ├── 2811c179e1538d186b71cd6e5b6d6339d956b2fc.nq.gz
│   ├── 2890d45421febc144b3c2823d4891ed35e33a244.nq.gz
│   ├── 2a2df09a7fe06bfc40afac9a71c26dee19926359.nq.gz
│   ├── 2c9e22092b6c12a9689b23e2728dafb4641d6602.nq.gz
│   ├── 2d375d5cf23e93e585d5640c5b214bb42b192b84.nq.gz
│   ├── 2d73f121853e87d097e9bcf995e63d61e422e5e4.nq.gz
│   ├── 2dc910ce5d90fc7b58b8db70e3b4cecf60139bb6.nq.gz
│   ├── 2f1b5306018476930d601cac0fbb54091c2411e6.nq.gz
│   ├── 3041e410ae556a36fda182160396df09bc92e812.nq.gz
│   ├── 33145e801d25753774b336bc8334fcc570de542f.nq.gz
│   ├── 373b7b1782e81a4330ea2f292a0e40d865939a5b.nq.gz
│   ├── 3bcf078dc6c49d8d980218c52bbfbe12088495fb.nq.gz
│   ├── 3d1e683fe3d600fee0d51ffcc1affee2450a8cef.nq.gz
│   ├── 3f2d5ab7e1b01fca900aadc4bb0a64db5fc6abbf.nq.gz
│   ├── 3fbf27a19e228ace7d96d66ace233d73cf0e4957.nq.gz
│   ├── 3fc11cd0cc0b184f13a2da8e3edd7155f6162d71.nq.gz
│   ├── 3fcdd0a446749c26dd277dbf1600d01beffbf084.nq.gz
│   ├── 3ff189047c51b203ab517df803b19d8b791dc05f.nq.gz
│   ├── 40c3edd50cbf211955c3f5591d83b8345bcfc22d.nq.gz
│   ├── 41cbba25ad238ce046e1f9b7661564df68701ffc.nq.gz
│   ├── 428dfad57716092e78658e1401c282c3e0ddbdae.nq.gz
│   ├── 4361d733da94446a4b6813ab9332e395c3eaecf2.nq.gz
│   ├── 44f0989794b068a01990b327e4463f96d6888a09.nq.gz
│   ├── 46262e5a38c02236aafc1f33f94cf3edeb8c6335.nq.gz
│   ├── 4786bc4ea49f9c977ee9ea8ced0ad7af0ebe9b17.nq.gz
│   ├── 4789e1b431df2ad73cd67d263bd22c856e031af7.nq.gz
│   ├── 4ac6fdf71c46637784da4f6cc18a2c363d0f8df6.nq.gz
│   ├── 4da4604f166db428ae27a80c42711dc0b8b8a665.nq.gz
│   ├── 4ebfd1bd8424a50c4a1bb7ebce5419571865ef7f.nq.gz
│   ├── 4fad34ccdde6175dcc93a603291634b01fabbd4a.nq.gz
│   ├── 4ff36e3f55b8c5b2d2bc09c3d535ec16c297726c.nq.gz
│   ├── 51318c0e4b77a82a1e2247cd51172c0d59192ef1.nq.gz
│   ├── 51ea66b53a5795c9d0f12eda2abb46450b279ae9.nq.gz
│   ├── 56e906a64c338ade8f0863817996fc8fdc2502cd.nq.gz
│   ├── 5710d20ea680c427999f1178cbdfdb42bd5430d5.nq.gz
│   ├── 644d63a4a4d9e377cd3e9572564929f373aee37b.nq.gz
│   ├── 657a49886cb6a0f9fc1218ee497afef9d5dc6b73.nq.gz
│   ├── 65d57371678df996167fa6d9f4509f3c45eebf47.nq.gz
│   ├── 6dec74be7873d52cd4cdea1abbc802f2e4d83513.nq.gz
│   ├── 6ea8dc004e36ef0335b55394d6ce3423c26d0034.nq.gz
│   ├── 6eab0ac08b006f870564e0e1a0b4485f4a6b07cd.nq.gz
│   ├── 703d351014e9949e43cd3e844d6eaf274edaaf83.nq.gz
│   ├── 727c295169b9ef9ee3c17ceeabe91e43a82e8394.nq.gz
│   ├── 74760dd84fdfdb260e0395da1c88fa1d1b3ecfe0.nq.gz
│   ├── 770507b53fcd14c570928a742e9964064be65def.nq.gz
│   ├── 777dfaa58cb60397eb096278d0655c7d5838475b.nq.gz
│   ├── 77f755d8e382670719ba3d972cc08f6e4a94339d.nq.gz
│   ├── 78c112434c51e71ca67eaa9053fedd4477719453.nq.gz
│   ├── 78d3e6da58cc3beb4d1560430411e7d3a72f5652.nq.gz
│   ├── 7a27a5ec1a1ea5426539f85d734d333ad6c5219d.nq.gz
│   ├── 7b786d5079061a132b90ed30c557fba347f59616.nq.gz
│   ├── 80239f32d206bd433f29088d20a47e3ffbfbb1d6.nq.gz
│   ├── 8222809f9620edd500b6e2640c80c2c0ed0125bf.nq.gz
│   ├── 8351d653e8a41b0d6b68cf3223b3a5cfb3cf36e6.nq.gz
│   ├── 854ee3fe141dc4add8c27249c1397d96bdfaa393.nq.gz
│   ├── 8606fe8bce6f3da93093d0729466fb1acd20f494.nq.gz
│   ├── 8c322bc1091ea59096908b9f340690b5387c74d2.nq.gz
│   ├── 8efc6e6c29cdbe2b52dd0f38d0abb375391c7016.nq.gz
│   ├── 9161d19500eb791e3bf3e8e65d57e7f188f4f335.nq.gz
│   ├── 95e171f57390e9c1cf5d4daa3a21e8372d87b5c0.nq.gz
│   ├── 993ff9af02ad87c9df18691dc08e57385ccafcd1.nq.gz
│   ├── 9996c1635594b2a01b310e84d3ea298789a9dbe8.nq.gz
│   ├── 9a1585c2834dd2df35531c50616b406d6ce9181b.nq.gz
│   ├── 9b1da1de234909348f936d4ced655234d15654fa.nq.gz
│   ├── 9e65d2e96863bdffda23368dd9fefb6ee6e2e201.nq.gz
│   ├── 9f408bc959308f879dd957a23de8cc68c5d24780.nq.gz
│   ├── a03d423b10d96a4d61877299b977bb0001ae9dd9.nq.gz
│   ├── a24e43a89dfb79aaf7c076053179e0a49c6863e8.nq.gz
│   ├── a55e9b9aa6d6e17c5c647f31cc97ea7255f43af4.nq.gz
│   ├── a61b7f7d7c6f2b2f01c872e6e203126f083a50a4.nq.gz
│   ├── a80d66843b743554efa0d9d22f22b46a1f04a6e4.nq.gz
│   ├── a99b5b436524da238168a27561a1ebd2d34ed716.nq.gz
│   ├── ada225b7703f0f5aef849264d1711266853e8e0e.nq.gz
│   ├── ae6a468ef1a2e1576ab6bc62ce0b3c337c0dc44a.nq.gz
│   ├── b2aa5d71cf68c6e6a488ce0f9619e03496d307a1.nq.gz
│   ├── b2fc2c79b055fb762bd13eb4b480e39bddbf3d09.nq.gz
│   ├── b35d688721e99edd635d0d4785c1ad4c12d63743.nq.gz
│   ├── b38f8079a562136015e48b664294b0cfe58c6a14.nq.gz
│   ├── b4ceb236a1d3294149041c8e4fe5f216ae17f75b.nq.gz
│   ├── b6989675ad813cd7cf3a077c22b3b4f717a345ae.nq.gz
│   ├── b6ecef7c8ab42f87a8b41e8a0e3877b4d82647d5.nq.gz
│   ├── b77e0bd7500e05c77e0c9d335392fbae8e6c16f1.nq.gz
│   ├── b9edd548699614289cfd0bde33bd18a9f4d30589.nq.gz
│   ├── bae0f4e40970991e7dd5b80c1e06414a9077d756.nq.gz
│   ├── bba1d69c98f38cbfa8b814d09fc016c3429ee350.nq.gz
│   ├── bdacaafb28fcff17dcb3159ba750d9165d0398a7.nq.gz
│   ├── be597291b3576391ca1bf20147f3d499cf479dfe.nq.gz
│   ├── beb231e973e5f0b68ff7acbbcc28ff04773e9b72.nq.gz
│   ├── bf3095aa211b1b8b0282d8ba8bca445523dd5650.nq.gz
│   ├── bfabf52449a62ae1dddf9bdd4c54bdd332819b40.nq.gz
│   ├── bfbcf91ce5a5294738b8d3d13dd748237d6a47c4.nq.gz
│   ├── c0fd412e04ef5e013fd825fd5c7c8925111e1fe0.nq.gz
│   ├── c1c6fe18736a31c3a58295687670f5e15170054e.nq.gz
│   ├── c439528a4e434db22c59304e6e982666e9c7ebc1.nq.gz
│   ├── c5635972a34b3f3c9a7334a94a867e61f0553aa1.nq.gz
│   ├── c64c322f0f307362d6eac4422f2d56bb12e0b949.nq.gz
│   ├── caf589103fc9dd08c2f359844513949bcce18335.nq.gz
│   ├── cc6a032490d7d50328f17dfbc673a47e93cae2c0.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── cf3a860594a1ae380a3c1d7a28b53b5db6e18d00.nq.gz
│   ├── d149d9e3b29d8ea86260b25875d83a55c27f3a59.nq.gz
│   ├── d1765b058edece2292d042ff79a0ee2b7db65c23.nq.gz
│   ├── d2f6b9a950df0552837857888a2d803ffc6442a6.nq.gz
│   ├── d7c7d51300e70e71c1b3a600c0f256aa8573f89c.nq.gz
│   ├── d7cba4b6c7b19436fd59940f3712bb9453526f92.nq.gz
│   ├── dfcc02d1e52a06df9b4374cdae0617d784dbd10a.nq.gz
│   ├── e0290af1c3f5a8f5df1af9989a6e43362981d3e7.nq.gz
│   ├── e07530a9dd93b85ab276161bb7910f54f47739b1.nq.gz
│   ├── e10aa7ab478b7b928aa916f58cced96dc62ce015.nq.gz
│   ├── e12fe7f6db124337d35b9ce7f169f73f8961f661.nq.gz
│   ├── e23b7aae89aacd868ab5472cc2ce94d0f3defa31.nq.gz
│   ├── e5c1a2f6bc59d19348e5bace7c546835ea613b4e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70d1fc2bfe7abb300baf647862c529468ad7888.nq.gz
│   ├── e7210fff2d9c65bddef5695226fd5bcf3c15a6a7.nq.gz
│   ├── e81bea34ffe4568b5ac9d63d4373c2865bea456e.nq.gz
│   ├── e8e15436df4ec5a992f76f8e1324afd262adc1c1.nq.gz
│   ├── ecc0fa1209b48a39619d59e76b8caef0dc166e21.nq.gz
│   ├── f1ea659bada5c7ba3c6ce541b368ff85895cc12c.nq.gz
│   ├── f323d6a0e6f78c7ec0de54f52dc21dc9b59db142.nq.gz
│   ├── f4e0e33ff4b4c069152bf1689da7a5c8a85b89a1.nq.gz
│   ├── f54354496e0c4488ad7b8721987907d94374858f.nq.gz
│   ├── f9675822600f20f3101c298d175561c55ab9a5f5.nq.gz
│   ├── fbe435279033f3f4ba78df15c59f85d887d4da5c.nq.gz
│   └── fe8876d7ad80e87da4b6d9c61d7c937e29dcab27.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4dbc809242d9fe8f5fca0257c7dc9c957fc1ce36.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 154 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[pysal/spreg](https://github.com/pysal/spreg)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
