# Repolex Knowledge Graph of dbcli/pgcli

RDF knowledge graph data for [dbcli/pgcli](https://github.com/dbcli/pgcli), parsed by [repolex](https://repolex.ai).

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
rlex download dbcli/pgcli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c3776cf221a0877be52d6ff9d8bda29d0b146e7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c3776cf221a0877be52d6ff9d8bda29d0b146e7
│           └── chunk-001.nq.gz
├── blob
│   ├── 028d02524766f6ac5b7b0aae9f5bd1e577584153.nq.gz
│   ├── 02bd434718b0d953eb4c643cf157520d2313ad43.nq.gz
│   ├── 08fe74e658502b9dff4bb7385eefadf45bdba9ed.nq.gz
│   ├── 1013eb4f73eb4b376b41f8e35094f1b8de9a1e9d.nq.gz
│   ├── 114e3edf526935245879b8c5d782bc897b042869.nq.gz
│   ├── 11855df74bba27c3e98e5de95dbcea3623394aa0.nq.gz
│   ├── 13eed58db2ad1641c57c1547662cb62a3e84e4b8.nq.gz
│   ├── 1437096ab978349d3825842d311b405c1d86a212.nq.gz
│   ├── 14cc5ad8a17789ea336d3be668873ffacde4e10a.nq.gz
│   ├── 15f952f238c7c15d7afe3a7a71b087023a8be1cf.nq.gz
│   ├── 15f98113902ee5c17e043d2d47b9fe8795eadf88.nq.gz
│   ├── 1954a8ddcdaa80aa04c643d28360a502a08fadd0.nq.gz
│   ├── 1c5f697caca9fec74ba01e7f7f301b30269288c1.nq.gz
│   ├── 1cac82eb4b84aeb497b52f8b962b8b123824c195.nq.gz
│   ├── 1f21e60ea2557b5a02d1305ce4b1b4877e0f9ce5.nq.gz
│   ├── 20abb99a9e49e0e6ceea14c993b2137c6886a65a.nq.gz
│   ├── 2162b8b96419ef11ed4c65139cf1ae79402512cd.nq.gz
│   ├── 21735457b4af3a774208a14b1f8c9cdf5438f38b.nq.gz
│   ├── 24c7e1e2fdd7741d1efc2671d7ca5d95f2bacbc7.nq.gz
│   ├── 2553c922e5343062672bcab5603bfa0167243213.nq.gz
│   ├── 284c6da48302a8e72600d2cfd601b7c4fa2c2a12.nq.gz
│   ├── 2b44a7bb7337b74a58e194452c43ebf699744418.nq.gz
│   ├── 2bb57e3d29cdbb0206c98cab2721ca0f0265755e.nq.gz
│   ├── 2edbee9e467594f3fb2ec203f74ee990637866c6.nq.gz
│   ├── 302cab94926456c94bd5e1ba811404719132b5c8.nq.gz
│   ├── 322060fa64ea16b134b09c36b87827b43931b85a.nq.gz
│   ├── 34771b8a2bfac179ee7a6aec939fc2c8c3b17a43.nq.gz
│   ├── 3708ed88fe737ddcaf7ddd9f63f729972bf08ed7.nq.gz
│   ├── 38f5fef5136b4224651b9c51a3697fb91d81c001.nq.gz
│   ├── 3a989f8b3cc6a632fab5fbddd9e7017519631314.nq.gz
│   ├── 3ab88a719e9355708408e9d5e627c8ed588cb654.nq.gz
│   ├── 3c1f89afbcc136b0bbfe8f93ab6a8d37f15fea08.nq.gz
│   ├── 3e89ccafeef33b8c25cd0b52d4370ca5137c8c3d.nq.gz
│   ├── 3f52859b03cb17eb1949fb5f9a99aafb67c40dac.nq.gz
│   ├── 450f2c8b9829c8590c5948f98702dec952ad22ad.nq.gz
│   ├── 4533c7c11c35f0ebf9aa237df9d4515e1761d6c5.nq.gz
│   ├── 46065d0d5fbbbd184d0316a0c9fc126b3ebf5b6d.nq.gz
│   ├── 4aa448df95caec2ffb7a90c58775add15f4654ca.nq.gz
│   ├── 4c1c71a1f721a6193c5dd2e181d852b19b54b74b.nq.gz
│   ├── 4d21c09d4f1b9fb6239790d7fafd01bee633caed.nq.gz
│   ├── 4f9578390bc09e3765c8636fa7467755f4e222da.nq.gz
│   ├── 513097a31d521c7bec139531af5b60817e929102.nq.gz
│   ├── 51d490956530f95d619ff8767cf411e3eac139e2.nq.gz
│   ├── 5466bd684b86fe214e2f911bc0b874986229e956.nq.gz
│   ├── 58520c5faababaa7f64adb1e1fdec719e70a3b15.nq.gz
│   ├── 5c39296d4750218db64dcc3928914fda56d50e48.nq.gz
│   ├── 620563d2777ca290111659b558573edd20457921.nq.gz
│   ├── 63c5cdc989979bbb1b0f80039a8ab3afb0d357de.nq.gz
│   ├── 65e50ee4ccd7796cfbd7c2e391c43002871df251.nq.gz
│   ├── 6c4973db7377a36477222edfb03a0c7c1fb77b77.nq.gz
│   ├── 706e5a475728b7afb77ac96144c56800613a3a0b.nq.gz
│   ├── 70b603d82f75e6818cde0dbca0e8feea6c31d4a8.nq.gz
│   ├── 72b11f3bd02e0e750873cdca0823b8eff01eab65.nq.gz
│   ├── 74201b92a39be30cc03548027c212a0454975d9b.nq.gz
│   ├── 78ff5dc9549aa5b0fe34d3e9f58b1827ece9bd81.nq.gz
│   ├── 7c0d047c540c4cb2524acf7e3c404853ddcc6c23.nq.gz
│   ├── 7e975dcc8d1ca6b727d9c0fd4987f809467d7939.nq.gz
│   ├── 81fbefe78d19dd83a21ddbd8719aec0b447da808.nq.gz
│   ├── 83226b7753e2ede193b15b3a47d6f6f0feb10b47.nq.gz
│   ├── 87da4e392be42357f7e8b343cbb3321449fbc72c.nq.gz
│   ├── 8a43c5c0a0f5ee0e0e5456f99212f05c78f23f40.nq.gz
│   ├── 8f8f2cd0191e12be2f7f1d71319e6322816090d5.nq.gz
│   ├── 91abe374a11ab54f7ecc5d5808e06fce61d5ecf2.nq.gz
│   ├── 92045428ce595aced1e5b8c0d5a41ad97a91cbd6.nq.gz
│   ├── 9284586b1d01b12966b45d110b241381ca368299.nq.gz
│   ├── 9507d461aa5fc80999d985d729dc943a9ba6237c.nq.gz
│   ├── 978a3211f5b94ccae6d916899a06ea9475eea295.nq.gz
│   ├── 98feb02db9b63a9423376a2bcea04c14b5bc2881.nq.gz
│   ├── 994f116e56b07e9011a4644ec14e0845d0e96ea0.nq.gz
│   ├── 9bad5790a5799b96f2e164d825c0b1f8ec0c2dfb.nq.gz
│   ├── 9c8e66d75a53c5e70bb40da395b48e9ee526c69d.nq.gz
│   ├── 9fe46ce06e4d5a4c92a80e3437746790da53bbec.nq.gz
│   ├── a5529d6b30414b307b0db863f487d9ab8be5a297.nq.gz
│   ├── a6cde7021487090306949a343345c133718983b2.nq.gz
│   ├── a85f37104628dc766041e57cb947e9206f8db8e3.nq.gz
│   ├── aa95718662479661092b42e748486fa2d9caf392.nq.gz
│   ├── acd7e99607e2f47073d72ac5661919d4e8fe805c.nq.gz
│   ├── ae8bc67c960ee7b5eab9f54811e000000b7cc9af.nq.gz
│   ├── b3f3cf4b892a204f4e1b2481c2b73ec62d510150.nq.gz
│   ├── b5cdbecebca1efc7fd4d8fed054cfa2311d8c0b2.nq.gz
│   ├── b783dc7a7586dabb9f8cf39b62f7bca637874078.nq.gz
│   ├── bacb65cf50622280a598f19314797655aa305e3e.nq.gz
│   ├── bb9ca0678fa0d1d7b628ea14601db6eb51c1fa70.nq.gz
│   ├── bebb9766f17fe8095040f4940fd608ee4dc31867.nq.gz
│   ├── c321c861b8247e7b09f754e46c7ccca397850052.nq.gz
│   ├── c4000ab1cc349b28a35b0605828525b78ea41c25.nq.gz
│   ├── c5fcaa2cdeeb9d727cb8d76cfdfbee2e57937809.nq.gz
│   ├── c9232c71190171603b2765e64e43af5e05b73a4b.nq.gz
│   ├── cc72154c1bb5139420184dd1be04f489d9a06638.nq.gz
│   ├── cd99e321b0b2fb419db533c9e818cc19da40d763.nq.gz
│   ├── ce45b4f8d0e8ebe4393e6278b1bf28e899c68187.nq.gz
│   ├── d1094d2aab6ba3925be32e3864a7b87d731b7e53.nq.gz
│   ├── d1221f86e372ca7830ab097676fc0e7c7a0a417a.nq.gz
│   ├── d516a3f6eb6ff223fa83227335dcab9769893e21.nq.gz
│   ├── d607dfae0f5519b0bd7d7497898b0ab0092d8105.nq.gz
│   ├── d6b5096d1b7d0e9f156bf37116a9af44c2fc1373.nq.gz
│   ├── d7cdccd4330c17669db2e26a8a6f29c68e9b56fe.nq.gz
│   ├── d8a48985c760eb05489042e34bbf3c0a58a069d4.nq.gz
│   ├── dad7d10e472dac0a4e11c8ac464b33539d487b5f.nq.gz
│   ├── daecc189ab20a6e157f75b6a5046de9f535b867e.nq.gz
│   ├── db7f017f1956b769e28031c4a3c50d3d7696aba0.nq.gz
│   ├── dd053c81245cbaf1e13a12e3790c178da277c68e.nq.gz
│   ├── ddf1662d86d619032a8b007c0919389f33eab898.nq.gz
│   ├── decae97b158e6e146ba331d01cdd50236f175419.nq.gz
│   ├── df41cf4ee76aa01c02728d61c59639ab7b8eb358.nq.gz
│   ├── e0766617308ecf15b18b27bf1004034ec8eb929d.nq.gz
│   ├── e0ae56f51790b9e2f8074ccdd06bd58aef7f3d5c.nq.gz
│   ├── e2ccc2caedab909d80041ff3bff5d0370cdd30f3.nq.gz
│   ├── e4860486a9b7cdc427c039eb3e64f1e99d31c575.nq.gz
│   ├── e50e397a5c329cba6614978d785ee8e95e56680f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dad62a7972525802233afff480de3348ce48b5.nq.gz
│   ├── ee0cdc81ba212d20528719489d9dad694dc70687.nq.gz
│   ├── ef79e43d5da50409c404185748a71739f605cb83.nq.gz
│   ├── f1569823107747c510344851ef357a9c686e95b0.nq.gz
│   ├── f5b67006d0f0e662c3464da0ca96d6d773e1de65.nq.gz
│   ├── f78774051e8b3a2199ef6c9dffd8786ce160d98c.nq.gz
│   ├── f853c371dd93963454ae5dc4691d1fd3b769aa33.nq.gz
│   └── fffc1a387ec5aa929e0be6ff4a56a01ff549ca63.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c3776cf221a0877be52d6ff9d8bda29d0b146e7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 127 files
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

[dbcli/pgcli](https://github.com/dbcli/pgcli)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
