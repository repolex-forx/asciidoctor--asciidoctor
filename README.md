# Repolex Knowledge Graph of asciidoctor/asciidoctor

RDF knowledge graph data for [asciidoctor/asciidoctor](https://github.com/asciidoctor/asciidoctor), parsed by [repolex](https://repolex.ai).

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
rlex download asciidoctor/asciidoctor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 356f79cd21b00bba15fbfa3f4f7a3059abe6a4d3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 356f79cd21b00bba15fbfa3f4f7a3059abe6a4d3
│           └── chunk-001.nq.gz
└── blob
    ├── 0103e2df24d17dfa59a61c009649371126cee843.nq.gz
    ├── 0138d1e8b982869c81b27110126b42471937df88.nq.gz
    ├── 0196289e28ed870a9ac245219c742241fe885fe5.nq.gz
    ├── 01ed1d3172894dee2c6f25b20e7fe9c5cabf34f4.nq.gz
    ├── 02292a630047d0b7ecca4a7829ec823356c28924.nq.gz
    ├── 022ebdbc30af663fcbf07ebb94b2ce83d2e9018a.nq.gz
    ├── 029b7d97298ca9886fd2bfba03273055d691e895.nq.gz
    ├── 0349b4c30e570543edc5f8670d56205f7275caf5.nq.gz
    ├── 05015e3a74020acdea23964d0e4682c65c0fedf9.nq.gz
    ├── 0669e5a20ebccddfea8681e8d015964ddbf1e306.nq.gz
    ├── 0669fb43a91b5051cf8f87b239ccd6abde44c481.nq.gz
    ├── 077c80b55b516e21d41bb1d89210870f6bd8d3d6.nq.gz
    ├── 07fdd7949d78d91ec10effee8aa62bcde6bd6842.nq.gz
    ├── 08b41ccbfab81702bb455eaf527ad165621b7bbf.nq.gz
    ├── 0ab1a6751fa88d9facb8e8bdc3880e8e4f8a9bb0.nq.gz
    ├── 0b5dcaa8011b5ff09f509f666ffecdd7b4aca854.nq.gz
    ├── 0d22f46b072c65572a07d5872989bbe5e64f0e64.nq.gz
    ├── 0d729810e672f445e5217b886cc6f883100b04c9.nq.gz
    ├── 0e8b232340dae9cc6abcf15971972a2938e2e901.nq.gz
    ├── 0f4e464178e92950204747063acf4b2c4bf4589b.nq.gz
    ├── 0f8f0066c546298b128a9a26a45d4405353a5b9e.nq.gz
    ├── 0fd2c8f7cd8595064b90983a0a13c4ab2a41b670.nq.gz
    ├── 106eca5ae53dd874562c5b5a56067f869c085f8e.nq.gz
    ├── 1180b1441344a328c8940f813fdd05eba03be2ee.nq.gz
    ├── 1199d13656ca4638a894a5619f4f0d536d6a8b05.nq.gz
    ├── 11a039164e1b9c7a320c9c19ca15ac497fd41e17.nq.gz
    ├── 12f97cece2401bcb49b4fef6d91a9b2b00d20c63.nq.gz
    ├── 130c8e363aff9cb948f6341c4e87b0a1259685a7.nq.gz
    ├── 13b28e9fe1587630bc55c1f0039fd56fb62fc7dc.nq.gz
    ├── 16c28ebf645fc88c8f13b7fb850a844c48d13bc6.nq.gz
    ├── 17638913f0ee52dc9a1cbd394fbfdb42daf55c77.nq.gz
    ├── 18467ebaa76c3bf4a435800243fab76b56c8b89b.nq.gz
    ├── 18ca048111835ed0d241b3e2640293015764615b.nq.gz
    ├── 18f042c802dc804996fb800a08355cb04d8a434a.nq.gz
    ├── 1bf7957b7704a8d4d94fa1dfed7b00a3d9e46362.nq.gz
    ├── 1cd7c97a213bd16d2e60b79acf96ddc4f9e27d0b.nq.gz
    ├── 1d3896de4932f422d0df05af11f13c89f0c85579.nq.gz
    ├── 1de65ff6119169bd819e2758cdad47550ba24744.nq.gz
    ├── 1ea161c857a9b2d040cbe1a729eaeda56475c297.nq.gz
    ├── 1ecf4b354907f244e90390060c61f082752c2793.nq.gz
    ├── 1f63b8e0a7b09b673804941971fd6871cd72d77b.nq.gz
    ├── 20054684dd757b363aab0ef9b76149e9506c5f04.nq.gz
    ├── 206e3a639a6cff29e9b237bf0cf2d005d20f3b9a.nq.gz
    ├── 2078483bde55655f336e772db36079a4fe737a42.nq.gz
    ├── 226aaab5dee63a65474e5f2c27569820a1e8a4b7.nq.gz
    ├── 227bb80019b0125aaf563968a883864363820b4d.nq.gz
    ├── 23049a04a8e840807ac22bfa0ad698650caeee04.nq.gz
    ├── 238dc1fc1db98e27c42f2c3971c832354ca97caf.nq.gz
    ├── 23add3bf97046542970365331f3cfbca2614020d.nq.gz
    ├── 245c7873abf8d4e2a115c9fe15d3d6399d9406fd.nq.gz
    ├── 2523501f75512aef3c66bad6a3167dbce8f75e04.nq.gz
    ├── 2639a13142d96b2c11e0ab40575f8a828788eedd.nq.gz
    ├── 26f15d0b3bb47abfee56b2582d6c80963286d260.nq.gz
    ├── 28065d9e068794c27e67627b1aac8e7ab8a1b9a8.nq.gz
    ├── 29b124eeee2a03926b3f64fc83b60245a2091e94.nq.gz
    ├── 2a56c91b132c13edac17e3bc5bb0c1f0f8902f29.nq.gz
    ├── 2c35826a51256e8d75b438f5dad97b972c2206f5.nq.gz
    ├── 2d052b101d703ed65ee6d3f0c03c9c0fb4047237.nq.gz
    ├── 2d362d52ba75dbb466c63f62e7a460f7536d3d4e.nq.gz
    ├── 2d3912c0b0204c2bc12fb6ff842b6185e3762165.nq.gz
    ├── 2e36789fa4286b5cfe38b03d87cd098f89e654aa.nq.gz
    ├── 2e9c131f2332f81be8c61189396e981d475e8961.nq.gz
    ├── 2ed51c8eee3fc84fbda076a5a9941563cfa82232.nq.gz
    ├── 2f49193f1ecf8bc4a90a053d5d06f6327a58cc5c.nq.gz
    ├── 2fc854582c1cd7da1d5de4b82ef0176d6e4a8354.nq.gz
    ├── 31016999016d7c3c595666079b1438a1e6f93711.nq.gz
    ├── 312e2d16806e6ff71b4bbe3e789568e46263faa6.nq.gz
    ├── 31bb754f46ec853369e90c02861cfed6369dec94.nq.gz
    ├── 31f850eebfdb5eb77e4cfd2bff783529c079b9bf.nq.gz
    ├── 322999e775720fa6549d2147bad6651613cb2b85.nq.gz
    ├── 341d05fd516375859daeb76d02c95c2818e8a9b0.nq.gz
    ├── 34be7185708457e3c085e5f25835e968353ea3dd.nq.gz
    ├── 35be2559ef0890dd68978a58dbc8d77347adee2a.nq.gz
    ├── 3785392e5765602a3a12a7ddcb74654a5bb0094f.nq.gz
    ├── 37b34fc091cecfc794c1a861caaa52ef826a660e.nq.gz
    ├── 390365f639bbeef175e4065443bbc9f51a439ea9.nq.gz
    ├── 391e1cb82e6aa225ebf81140d6b57c1890a640ed.nq.gz
    ├── 398c67a1984742b4b50250ccda74634ab17b4261.nq.gz
    ├── 39d118113d3de29ea6f550433075bbffdb21ed33.nq.gz
    ├── 3a841f5b6adb79016ff880261a02b03ea9ee3400.nq.gz
    ├── 3b930a2fb484611b002600364db13e1a56cff2c2.nq.gz
    ├── 3caf6f66590f7b9d4a95063ef5d5fabf9612969a.nq.gz
    ├── 3e5fea1529abe73cec51dda8f6a5afd5ebe3d133.nq.gz
    ├── 3eb675c8fd3e1056829d2b867a44ffafe8ff7bb3.nq.gz
    ├── 3ebf264100d3772a4d87859dd9ca03aea681077d.nq.gz
    ├── 401df5c803a756049f5ff09354074a42f048c5df.nq.gz
    ├── 40dd7dc9c32d35628de6065411ec1afff08f8b3f.nq.gz
    ├── 40ebca6f379abeaff1877918cd1aa8c1be29e2ab.nq.gz
    ├── 4267c846185679ccd3ce621f778d1073862dfa9c.nq.gz
    ├── 42bd904812debfcd1f654bb0fd518290ebac4083.nq.gz
    ├── 42be5b31b727c264cb05ec83efd9e7cd58113efd.nq.gz
    ├── 42bf5bf717ba9859662f06bd9f12359260593e29.nq.gz
    ├── 4385cd522aea851f1d4bb77d5c4cb6897f409888.nq.gz
    ├── 4492b07d71e79d917442220c02f85e9dee9f9634.nq.gz
    ├── 45321fb8bd437f51275203b26e76daffd5a00889.nq.gz
    ├── 4560af88d5c44016484ce64ee32795ac08c7dc07.nq.gz
    ├── 4584a510dd138a7e3a150773f409a50ff694004c.nq.gz
    ├── 45aa82dc0933cc2da9c75828c5f13d53a1334cea.nq.gz
    ├── 45bdd81cc465f9f61e7f42c8fb5e5845955feefe.nq.gz
    ├── 46f2527a46b75c92cc3ef6e25806b7f808187f60.nq.gz
    ├── 4750d4631ec9883ac3447a508b5722f22eed5aec.nq.gz
    ├── 48375b66872ebfc8b9e4ba13c33a461e49c7d28a.nq.gz
    ├── 487bb1ac7039867a143a964ba0de2b9af80e22df.nq.gz
    ├── 4a0f087e0936038b991e365d6aa78da2653f7364.nq.gz
    ├── 4a6f864249bfef32bd92927ccf3da5597f50e285.nq.gz
    ├── 4a9c1af6a66211f8bd328c5233377adf658bb824.nq.gz
    ├── 4c02cb303d3b2b3eed50271c4d1de4f667b25aef.nq.gz
    ├── 4c129e401597d0b7e8677bc9a97377a745348ad5.nq.gz
    ├── 4c7eb5054eba522eabcce0dff0c65993ba9f64e2.nq.gz
    ├── 4c7ed13d44310d281d50a79aa4a092f2b1515bf1.nq.gz
    ├── 4d2480f7c72adf974e65e44a1e0f79b9dd9dedd5.nq.gz
    ├── 4e3e9f22870cc313b2cca4f1603c84ac28f397e9.nq.gz
    ├── 4ed18c58ba32db23c14d5c7fa56fc2b03392c4b8.nq.gz
    ├── 4f0493ae705381ff05538b964a3e1b320b369be1.nq.gz
    ├── 4fdfbc40732892f03d4b1083e3cd064b94a3abe8.nq.gz
    ├── 5218f9553fe11096303fe0498eff0e473a67501f.nq.gz
    ├── 52bd3e6322be7b2fee4a93226368d832a7bcc667.nq.gz
    ├── 52c14c414cf2463b0fb26056f80f250c5f6abc7c.nq.gz
    ├── 52f6ac139cb6ccff9c76ba82539868621f87c3f1.nq.gz
    ├── 534ca3741917b8b0bdae4d52400582ddae10c27d.nq.gz
    ├── 541128fca30f370ddd2f6971199a478e1994650a.nq.gz
    ├── 54ed1708e0edca01cc8d28a19b9c535829596188.nq.gz
    ├── 5537a60cc92b697961c27c26e4d6113557ae1499.nq.gz
    ├── 566fc6ebf365a256bec3f7199d79df3fd84709ee.nq.gz
    ├── 5867a20117d4df1ddaf221bb787e3842c2c4e746.nq.gz
    ├── 591491109e6f28cb7bdf7536593bbfc451782944.nq.gz
    ├── 5a7fb7855936cfaa2893b7733968fbf6c550a235.nq.gz
    ├── 5b10c0904ee41ab7092c0baea13b5416cdb1daec.nq.gz
    ├── 5b5437c74d23ee3802616929a358ae3e5e9d8641.nq.gz
    ├── 5c15a19472de4f8442c5213337b9c8dc7c883b02.nq.gz
    ├── 5d6305efa2c9ba713594705043761ffdd21d7035.nq.gz
    ├── 5edb4d7a5ca9956e14ce377e1287b2618333d723.nq.gz
    ├── 60f1eab97137f7dc51fc53c8e4f3e49f63342c38.nq.gz
    ├── 611fd66a5c838eee98a6421a75b800160a98b6a0.nq.gz
    ├── 613bfc0d2cf4bde0ab1279211ed7f636b672242a.nq.gz
    ├── 614d306ea2b579fe6d7e0ef61a99e2f2ed262304.nq.gz
    ├── 6206bf408acb399660b8b45d547eb2d2583d5209.nq.gz
    ├── 62629abda7e3daa49b4829dd55273622a7c29d6a.nq.gz
    ├── 6396975d7925dc426f32170e356f44bf824e733b.nq.gz
    ├── 63ac8da8b789eaaed3d26b82c1268aae9f340def.nq.gz
    ├── 654efbbcada844dacab51a16001bf14313d76e5c.nq.gz
    ├── 6571c0ce8ce06cadc65e65f83718f928ce61cc14.nq.gz
    ├── 667827e91d07a645e6df7d7ac41a41514e7c33c0.nq.gz
    ├── 66a55323fae0dbcd7507813b63cecf32fbc2f9f2.nq.gz
    ├── 66b4c9f5b4ae8b3e6700ef00f704ae3c9b77dd0f.nq.gz
    ├── 66db3565b60a9bb8fdf5107db398af837500576f.nq.gz
    ├── 6796137a93ebfa26e2b47b1bd8b5d8fe8fb18e81.nq.gz
    ├── 68ba14783b8c8e3f1411236708101bb886a40d33.nq.gz
    ├── 68c788ae55dd29e8f6abe2318ea39e6ce2838a25.nq.gz
    ├── 6908b4310bc8638cb3e1bcb8f0be9b71aa392828.nq.gz
    ├── 691aab5288d95ab49749d08fa71bb63f4ad85dcf.nq.gz
    ├── 69b1bfa1fc0bad492b29b19e18a6b0987875eb8b.nq.gz
    ├── 6a2709792dd6048a81835d7bc2ce6074a75f9a65.nq.gz
    ├── 6a8376969ef6fa9b613f0012289dd2edd668f17c.nq.gz
    ├── 6c48ff7933d8a307ef5ce821720d643cc3557cbe.nq.gz
    ├── 6d95c9c5b4ee843d6e670acf639e64a9c8baffaa.nq.gz
    ├── 70f72bdbccadbd5ce41d831bf1a473404d6ef725.nq.gz
    ├── 7125c22c78d24adfb552bbeab8b060d6f4187008.nq.gz
    ├── 718bd26a27484d31078c60536864f08f236bc720.nq.gz
    ├── 71a8d6b6c84909ad4608e609d310d95fd3dd077b.nq.gz
    ├── 72223976b5e10dd2e70d865d11972a97b1c1eff6.nq.gz
    ├── 72dd67d2c8807c3b54f5de1940b73c7c282075df.nq.gz
    ├── 73f06bd7736b4b06d9ca64d088ec8d9ec706bd2f.nq.gz
    ├── 74337e54894a7d6bdd99bc10ac01ad6ead0dd866.nq.gz
    ├── 75307812831a19b6d59ccbaaab6c4cdeca4f0f69.nq.gz
    ├── 76b9296f68631288db847e5eb2f61dfec9824beb.nq.gz
    ├── 77c18c1d1ce388f9839818f0a7703f31c5747a82.nq.gz
    ├── 77d4f8a847b2fc0bf5617ce46a49085c015d6806.nq.gz
    ├── 784f36e93392aa4d42023d3e489228793cbc1fb9.nq.gz
    ├── 7871358cc5e3db25b3f795b014a76899b44b88fe.nq.gz
    ├── 79418da4f420206fe65d4602cd10fe7fee0a56ee.nq.gz
    ├── 7aa44627d09220efd862e6c6059f97cdd9e9856c.nq.gz
    ├── 7af0e3ed94234b3f63335cbefc12c0dbdac58acc.nq.gz
    ├── 7af1b72472611dd4c6c1e2a0f4c41a22b63ba8e7.nq.gz
    ├── 7ba5a89a75ed928ec20e0875f03dcedd929ff195.nq.gz
    ├── 7bf3b8c47061b3e23916445c6209adf576bdb490.nq.gz
    ├── 7c7847af813c07fe48dd4883cfda4016b7609e02.nq.gz
    ├── 7d12bdc3b96e34bb498370358785cb05f8ba4136.nq.gz
    ├── 803f5bbe58e4a0964fa834c9261480b46b8b439f.nq.gz
    ├── 810737a521fb1d91f7517416c70e2927975402bb.nq.gz
    ├── 8233c83e62ab2c3e6b79a7995af76cd57d3f60dc.nq.gz
    ├── 825c6bf351b26aab5345bb56bddb25ac3dbfd7ff.nq.gz
    ├── 84b81b2cbcf1133ca5a1be5c8c089f784b57947e.nq.gz
    ├── 84d8152e2a800b5b3938c663f4cc817154a12526.nq.gz
    ├── 86776c4d42fb1d9f3b0e8d61b8bb8f8f61a4bccc.nq.gz
    ├── 873db56c7448a957d524a2596dc4707663ada1e9.nq.gz
    ├── 8860f7ed8c8bbba3796af21dce6c58638c82ecff.nq.gz
    ├── 893feef31d7b607b7a3bb689855758f68f0161a8.nq.gz
    ├── 8aeea2b5ee681c86b49a76b3176872f23ebf7fc6.nq.gz
    ├── 8c0c786d485e2e3d4fc408705843426a811c39a4.nq.gz
    ├── 8f862bb251fd38611811ae05ae9cc7ffbd9b9fee.nq.gz
    ├── 9054cfc22c68c5da6d77e1c9d40398df37274758.nq.gz
    ├── 9060f4d4eb402a970fdf66495bb85673b1cc85c6.nq.gz
    ├── 90832716dfef6d94964fc3e39fef55a3c71e01a3.nq.gz
    ├── 90c92a038b301972532222f3aaca0eb50c1c913b.nq.gz
    ├── 92ae40db948988d278e1a8a714fc6fb52a0d5a80.nq.gz
    ├── 936e5c57af94787780c78cc0aae6e870a4b957a5.nq.gz
    └── 93f5cabb339cda049e914da10fd63457ea445e98.nq.gz

7 directories, 200 files
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

[asciidoctor/asciidoctor](https://github.com/asciidoctor/asciidoctor)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
