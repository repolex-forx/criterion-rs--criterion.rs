# Repolex Knowledge Graph of criterion-rs/criterion.rs

RDF knowledge graph data for [criterion-rs/criterion.rs](https://github.com/criterion-rs/criterion.rs), parsed by [repolex](https://repolex.ai).

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
rlex download criterion-rs/criterion.rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f0d745532e3c7b2e11bbf9de9b911f91790d3b1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7f0d745532e3c7b2e11bbf9de9b911f91790d3b1.nq.gz
│   └── repolex
│       └── 7f0d745532e3c7b2e11bbf9de9b911f91790d3b1
│           └── chunk-001.nq.gz
└── blob
    ├── 007be8ec81b66157d24cfbf959d70099048d8fd4.nq.gz
    ├── 00c1a34aed5d4c8c2dc8d96a480e2b460ce16c8d.nq.gz
    ├── 00ea734b410bad817e4bc6d98127907924259448.nq.gz
    ├── 014474db4d8a7c1da0d1c6d9b35e47b7184495f6.nq.gz
    ├── 02278e33e9fd9c36c5e9eac336195d1675834628.nq.gz
    ├── 02eea79399df7241bb27a75a0cfdf869813335f0.nq.gz
    ├── 03103d3412715b6830a4e388225eed5419d47008.nq.gz
    ├── 03b82fb431715e743f9ad5225f0cc3ab7eba2c4b.nq.gz
    ├── 03e1744652faa38f16ac21f87efc226d59c5dd7d.nq.gz
    ├── 045885d2d0447c1a2607672238b2171d6489e773.nq.gz
    ├── 0543ff315e47eb664d5d0b3195298a6f99713525.nq.gz
    ├── 054e1f37952f0a8d8d6174c5ac7eb1d2b9087fe6.nq.gz
    ├── 07bf1bc8b8e67ec39307ff2ac2b20bd320980e8a.nq.gz
    ├── 09f0b7e6fed8b5eb65fcb2673f2ca4f5978d94cb.nq.gz
    ├── 0b3a931800fb6911e7ccb2141d7f68335a6456e9.nq.gz
    ├── 0bdb836a851b37badc8176cd7ce1dca70944e6fb.nq.gz
    ├── 0c9605a178c9804a303997e064e0d757fa3c8597.nq.gz
    ├── 0cdd94543772a7a329debb7f7234412db6ab6d1b.nq.gz
    ├── 0edc8cab5c7bdfbcb9dcbe6603995783702cb0c0.nq.gz
    ├── 0f46e60ce210d674421ec5e9b9f0b950830cc803.nq.gz
    ├── 0f917d104528fed91907dbd8f6635d5636dfcb68.nq.gz
    ├── 1102f6a55691f610837f73f99ee394f135267d84.nq.gz
    ├── 1230e8f11c51f1a1cf04db2e33b2ea90ed3bc5eb.nq.gz
    ├── 12fc2f07d149fdc3a20bb51340f246f2560d8a69.nq.gz
    ├── 137df256f3935e93ffee1590bb17d5d0e9889dac.nq.gz
    ├── 1382a433c343655302ffd6c992ffc6525d9066c5.nq.gz
    ├── 168a07350c51570bbcefbd26799c8068e759c58d.nq.gz
    ├── 16e93f66e23d4fe04e44bfebf6d44bbc6f4dbd6c.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 18173e061c714e41a656ad4db23e940c0fbcd1e0.nq.gz
    ├── 1a26d3728f89e5229e38037ea6a76067c6c7037f.nq.gz
    ├── 1c075159ed8fa9da2de41ed3f7b75abccf1b0b60.nq.gz
    ├── 1cc1a61b72244237ed79556ffa1f871e633f2937.nq.gz
    ├── 1e47f64ba5c59fd432a497ab425e42fe73c09d64.nq.gz
    ├── 1e8d87cd0d81e2328fce72fbe384e802a15ecf93.nq.gz
    ├── 1ec6ecb90cb977965bbbec055c111ad0acc30008.nq.gz
    ├── 2146e704406244b4ce6e503b12bc42c28af7d7de.nq.gz
    ├── 21c914011e554d178087e4746875a704c7e1a9be.nq.gz
    ├── 22bf10609ed79559eda6c6a1eb0da94f9f1e92e6.nq.gz
    ├── 232137ac236b2ed62732dd532baba23af6ae0ad1.nq.gz
    ├── 24a7fd374d9d457f2cbd5983242e77d74c96e53c.nq.gz
    ├── 25afdefd7f69e9b0fbce9011c699068e5ba35ecf.nq.gz
    ├── 25f98135c3acfed341c05f8ba16ced981f9ae991.nq.gz
    ├── 26203d1da7106e9e2a02f425ffe8860aae7f5660.nq.gz
    ├── 26bca188ae3958c21ccf092c2648dffc33dbea17.nq.gz
    ├── 289b7f38184555b109254b7917b8b4fbb1849b9d.nq.gz
    ├── 29794eb6e5a194c16d5e2daeb8e20f71f8411fad.nq.gz
    ├── 29f4a578ff5e8cf36932b4654ce78d782fbc154f.nq.gz
    ├── 2a5eae724cd8fd1212648a1cb041a42d91bb9353.nq.gz
    ├── 2cd81392c0c88f25c9ac5f8f11b4c944f9cc1611.nq.gz
    ├── 2d854e7c3b6e151b732961dae89d89758f68c56a.nq.gz
    ├── 2d861476353728bb6bc9fb95d47b1b041b167b52.nq.gz
    ├── 2dacb6d1989007162201a3b3cde9868961ac8b80.nq.gz
    ├── 2f885e0f331c447932ce5dbc07c5c10784837827.nq.gz
    ├── 3056b1f3d9277963560bb300e367b38aa9f1b598.nq.gz
    ├── 312f564494d00655779a2b567de5a58e3a8b7e57.nq.gz
    ├── 31308011e015d317c1106ab9d7c2e53c23a2f275.nq.gz
    ├── 32cbd49bca501588ad669e933a916e4566de76f2.nq.gz
    ├── 32f053391a28dd1332f47469267de287207087a7.nq.gz
    ├── 34bcbd8f00ff7a538d4d2bd037b12319238ac11e.nq.gz
    ├── 34ea61d006f161adcbaeb30b86df7d37006d6035.nq.gz
    ├── 3609193628c9b72949bcb5a849106bdd5010f459.nq.gz
    ├── 369c1ce83e28244adc68c1961a880d49dc1a6b46.nq.gz
    ├── 376c4756ba90a3937d18986a2e20b4900cc0ffd2.nq.gz
    ├── 385d7a5dc638a6b1242fcf01a0899a17572250ca.nq.gz
    ├── 39fef4b9c2feb722b6c35021812612e5860be1bf.nq.gz
    ├── 3a1cb001246904ba977f6a3c5f0eb29f8c1b91a9.nq.gz
    ├── 3ac4f1cc7acd1626e54f2a84be9ececc32a62111.nq.gz
    ├── 3b7200ac1a3bf0a9a2384bb9efa130fb5f457b20.nq.gz
    ├── 3b96aced4238250a0fa23a4233a6c4d9de38a421.nq.gz
    ├── 3dc74ad85168b27f1d7bdbd36c4b76550499f91c.nq.gz
    ├── 3f123c6824953d8ba29e8d4874787d2f5211b766.nq.gz
    ├── 41efc27022937b823b9bd11cae17a7dca108fadb.nq.gz
    ├── 43d6e2c817ca0614b8781460580bcfcb8409f54e.nq.gz
    ├── 448caa2f50f32333dd2a379d745bae82e2ce4c2d.nq.gz
    ├── 449d3483ae61ae5a551f667debb96f2be1ca83bb.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 47448ed56a9f5ab4c982ee9d8d2aec4d4c338807.nq.gz
    ├── 494c3e5469c301097d23bc720e2daea5221b6be5.nq.gz
    ├── 4ca5400827410ab844694b60698f9c05747a228a.nq.gz
    ├── 4d3547063e0e76a03ecae4443949bcc554f31e61.nq.gz
    ├── 4d73c888f23abf914eeade9b1c8e681eedd9f6b4.nq.gz
    ├── 4d93ff8cf7ba5d84ff2be17bb78cfffcf3a57459.nq.gz
    ├── 4e42eae7b37b83593aadae57ba83965ef22dde1d.nq.gz
    ├── 4f1ccf239d2e69863c7b129a070e50fc9901ccda.nq.gz
    ├── 51ed567ad19bf5308a9e34940fd64d194c6d3d50.nq.gz
    ├── 52d22332b86a564f5f19bede8460fa10c3116fb4.nq.gz
    ├── 5313277c9421451fca6c4a94c129b67c8183e09e.nq.gz
    ├── 534608d37e7662ca8686948d3ea8c15d9bf76f03.nq.gz
    ├── 5381a671d09a47a5ee102ad95fb65460d25b00b9.nq.gz
    ├── 543c9964b26ed982a62c12cb2918ede1132386ef.nq.gz
    ├── 57c6570a00d9868192ae726dfa7ce837abbba740.nq.gz
    ├── 58269a9db85734328b7355dd13693ca86f6fac10.nq.gz
    ├── 58a8182f9747bfa735be5aaf568281fcecacd5cc.nq.gz
    ├── 58e4eae4774dd934a34e277b01f5bf16d08419e5.nq.gz
    ├── 5a0bf0317d75cdd3dbf2e58cba1cfc99f9085458.nq.gz
    ├── 5a1344dbb830cce2b478bc867a510741a2488060.nq.gz
    ├── 5b1a9546236a15533d319e4bff06e276db98f9ce.nq.gz
    ├── 5b464d382bee2cc34679f0ba18c05133a9a6b977.nq.gz
    ├── 5d4676563de65486d5447487c26a290b59a365e9.nq.gz
    ├── 5ded0afe75ec9760874493818a5abad806be45c4.nq.gz
    ├── 5dee9dc46fb3560eb050fbb5941faeb28d6dc83d.nq.gz
    ├── 6013114c90beab09f87fd98ca1b2513df57c3ff3.nq.gz
    ├── 602ae6f08285b407a73e7a53bb64da3c7bf7fb57.nq.gz
    ├── 6140f9a4222cafd869cd03ef829fdd8f1d1e5e6d.nq.gz
    ├── 61a287db3c853a2ed7813ceef5f87a2ae2f89176.nq.gz
    ├── 623d004af54c12b9c7d9f90182b91657fdd20438.nq.gz
    ├── 63ae8be2a5fb3ade25b264007384ad6a0a80da08.nq.gz
    ├── 645648745aba2883f03a63ea4a48b2d2f261538f.nq.gz
    ├── 66f2e9e60bc6a0f6ced7879b30b5286f8d9bb11d.nq.gz
    ├── 672679778ca7300c3585b691b57794e0b395640b.nq.gz
    ├── 679d725442489238c545847dd253c4aa9ade5850.nq.gz
    ├── 68cbe48e2842d07ef0c2aba63d9ebd3fc55cb828.nq.gz
    ├── 6b04bfe02a1028895d748ec5a7bb660581f6c055.nq.gz
    ├── 6c559c686129880d3fe5470e655e84ec7b320717.nq.gz
    ├── 6cb4f0b7dfd7cbc8a717eb0ddc58e0555b18c504.nq.gz
    ├── 6d2197846d903113dbce78b8f42488690b7ed7df.nq.gz
    ├── 6dcb694a35d0abb7b1c222d5758906c29187aed0.nq.gz
    ├── 6ea9d45f760b3965da03b653f7f1c5a2abceace2.nq.gz
    ├── 6edfe003c7baeb9203eb72c83c8274f934ed0579.nq.gz
    ├── 726c7b62832c1e185a4d322a953ae962e7a48095.nq.gz
    ├── 7320e4cef48ba9b5d105227343ab76efdc20d757.nq.gz
    ├── 740476430c17f94fefcc5a9305088a66e9180e88.nq.gz
    ├── 75b1eb3f28b0967539971dbd11c62fc982705b9d.nq.gz
    ├── 75b61387ca7b75b23ba84df0f2c1f51a5b592a09.nq.gz
    ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
    ├── 76b72861b44690acaa7748affab370206a800d12.nq.gz
    ├── 798c2188466d970eb0f9fd589322342b6cfabebb.nq.gz
    ├── 7bdf5d7b75e1d14c78c94cbfc6f7f06bc8244ea6.nq.gz
    ├── 7c6478435786fb8b8fe6e708bcf2f12c7304380e.nq.gz
    ├── 7e0f8a9c6fac8528be1b31e399d9c3ebc91aad8b.nq.gz
    ├── 7ed555ac3c5f46bf930911a9bc5090e205b78b6a.nq.gz
    ├── 7ee8cf824921379d5633056db53ea5bfe4222726.nq.gz
    ├── 7ee8fc0849ab51ce052aa3463e25be8ec77ff20f.nq.gz
    ├── 7f9009b3c0e57431697063b7533ccc89d323e301.nq.gz
    ├── 80094f3d587c4679ab78fb727b54ef22032dab0b.nq.gz
    ├── 805ec13e319901eda73e4253fec98e7b9f7e55b5.nq.gz
    ├── 80e245181a362372d3a304a93ea5429bc60ee73d.nq.gz
    ├── 84529e3bf05ad99dec73413df4a32d00bf402cc5.nq.gz
    ├── 84c0458b059863846bfe4ef2d8404b0b04861d51.nq.gz
    ├── 8672be074cd360703452a00924e0854f26ab1bcd.nq.gz
    ├── 87524dbd5c7d02fcf6d08598a605332198e6344f.nq.gz
    ├── 8812142ebd0fd82eee8283378a71e02a13f5b4d5.nq.gz
    ├── 8994d737ad6f9a8b4475589f9fe9e23239e1436c.nq.gz
    ├── 8995d40f40d21b17772e62ae608e00a73a39604a.nq.gz
    ├── 8c3648a8ccd8e6946f2f4b88f92bbaa25c11fe44.nq.gz
    ├── 8f6f1e1308e4ad780eafee34029a86377ea04e47.nq.gz
    ├── 8f7f6659910528668ed9f344c533bf36730b78c6.nq.gz
    ├── 92ea3dc46368b0ef88ced2d0ace477718ebe7d09.nq.gz
    ├── 934c33ceabfd906511b4eaba4804d6d8faf56674.nq.gz
    ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
    ├── 98badbc5b9e45ef3f254b7f1074ced4c0ddd03c6.nq.gz
    ├── 99e10962ddc814d1385def236d65e2f7223e4694.nq.gz
    ├── 9a33f50eee461cba39c4343e959be0cd12e0f5f2.nq.gz
    ├── 9a415e6f90047b2e058ac9d672921539f6df54ca.nq.gz
    ├── 9c0a3426694c0d7fa5658a7c1b968c9f37fa6cc7.nq.gz
    ├── 9c7e6335b9e8754e854eab87e8281e9336962ef6.nq.gz
    ├── 9d1bc1835500a7b8dc6c31c3dbc6aa8b72dec86c.nq.gz
    ├── 9db20d1f45e7568235fd0f189c0c9647f53111c0.nq.gz
    ├── 9ddd7e50c1a258b9c44e5b55109a2d2264e2e251.nq.gz
    ├── 9e8d75277832d1a066a5c62d52c38d5883c526e1.nq.gz
    ├── 9eb7fa7b5a46496f27ea713a969139ef6ab00efc.nq.gz
    ├── 9edc8c56a6a46f3574f58688c9657285a9770fcd.nq.gz
    ├── 9f29ead5403e9fa1f3bed11d1f60d3835d3caa2f.nq.gz
    ├── a079d0887f3c20266bc441883c23f10b9564ee3e.nq.gz
    ├── a153b23ec824358a00cff84a6399a96fbb431454.nq.gz
    ├── a38422fbb12c52807bdaed3e326de98cdb21b546.nq.gz
    ├── a38ad9915fe684ad85ebca3546bdf0ac714b095d.nq.gz
    ├── a49e916b0bd664518c5ab3d1b32d993fd71c55fd.nq.gz
    ├── a5b0d18aa83e28c3dee2a9007fab71c25e92e0e0.nq.gz
    ├── a5b55a698c2d0c317bf82af477e5c54534c70daf.nq.gz
    ├── a62af826a20f1bd09aff0a38e765720f0414b2f5.nq.gz
    ├── a68773a688aeff4bd06575baa01aa8dc19185b88.nq.gz
    ├── a6f47aab920feadb2cff6aebf529a2ffeae67876.nq.gz
    ├── a8322303e502961ef9e4f88406fd30e11ef3c936.nq.gz
    ├── a86e077dc53643dee1f13df4329f8efa90bb70e2.nq.gz
    ├── a8910e882439b6ed99924241b4884b27a13c5a90.nq.gz
    ├── ab8c9d406da3fc374ae4a21054143512486c7491.nq.gz
    ├── ac0fda00385af1cd74acd663ea8fc73c56a94fd3.nq.gz
    ├── ad46acd68050ec37e13047446f640957d9dc27e8.nq.gz
    ├── ae2be5b00a9cddd196f4622f7e2559740edbc0bf.nq.gz
    ├── af4696d60b4ee6f65222c1743293fd27ebd2ff11.nq.gz
    ├── b0d81ea0f5cef89216ba66d95553f61ef3506314.nq.gz
    ├── b18a77335470c9ff137eedbc3a669d1b5b5c5400.nq.gz
    ├── b1ef1faffc1632551c8bf78837725eb98f2ae2cb.nq.gz
    ├── b24223e1df3e654950badc2afb5586a77c74d622.nq.gz
    ├── b3eba6e7f255b7057d448f0096547fcebe101fa4.nq.gz
    ├── b532b638f822d65b89f5fe51b983d1b6984e7908.nq.gz
    ├── b5d80683df37c7d96d3788b95cdb2df8d517fcf2.nq.gz
    ├── b7268009b214c338cbf1e53d7baf5ca1f67e6c2a.nq.gz
    ├── b7748ddb5cd9b1552c00cf30ad263e209b54c7bd.nq.gz
    ├── b7d2bd0461069374f13498d04a6cdc8e58676a6c.nq.gz
    ├── b812be9b8824939a09902b2d6593191b8df42b29.nq.gz
    ├── b8ed7c7441396c323fff2902c4f26ab2f4556a70.nq.gz
    ├── ba1ad7ca387dfddd7c581d5d4cddf48d5a765f3e.nq.gz
    ├── ba235a1c83ef854483442765131574c070275ee2.nq.gz
    └── bc36e406461128831336f163acddf468272ca298.nq.gz

8 directories, 200 files
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

[criterion-rs/criterion.rs](https://github.com/criterion-rs/criterion.rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
