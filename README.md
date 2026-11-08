# Repolex Knowledge Graph of scverse/scverse-tutorials

RDF knowledge graph data for [scverse/scverse-tutorials](https://github.com/scverse/scverse-tutorials), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scverse-tutorials
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e95d8db7039608aa52dd3cc13bb9e25cf6d1586
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e95d8db7039608aa52dd3cc13bb9e25cf6d1586
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 02e0879856fc4844183473b3b69d1ebfe0d539c2.nq.gz
│   ├── 0b5d365624cf38d7f2b1d2c3b4fcea87524b3bb5.nq.gz
│   ├── 0ca3d5339f4f2946244fe2da8d13328ce8693be5.nq.gz
│   ├── 101d2717def938ed4939f6efe57d2f5f8f2a66fc.nq.gz
│   ├── 113e6c4b0b37d1d58a25abe3edc3efccc70f2d76.nq.gz
│   ├── 11957ee1c0ee9e590ae4c3e8b64e7aa926379bc9.nq.gz
│   ├── 12a50852969da56780283b21c4ae4fd372f90585.nq.gz
│   ├── 17193f1dcd59d77aea93fc8f971cef50a924fd17.nq.gz
│   ├── 18eab13120859f6c5aac61882ec6530704575ec9.nq.gz
│   ├── 1c57ada4e9f66372cd173a26f29c7ea257089f7a.nq.gz
│   ├── 1ed7945ae9ec3b2aa5ea5e1cfc32edff4e2326c0.nq.gz
│   ├── 22b5980e5d0dbca531b2bedce9bc8bde7370e608.nq.gz
│   ├── 2626b4a9fde06058f94422bfbc36a25479de319f.nq.gz
│   ├── 2c7abbded05629af1dda25a79f5a6ffa890328c6.nq.gz
│   ├── 30dbb581364160b83109f50e90d3821ccc0dc85d.nq.gz
│   ├── 3152927cab0e800f1aedfe3b7c8156034a4dd91d.nq.gz
│   ├── 323cc8aed7f4070b009dcdea5b78097560a8be87.nq.gz
│   ├── 334521521585a4a6bead4b7215e727e32750c985.nq.gz
│   ├── 37519e7afa2c72b6c72708a17041d5772f786719.nq.gz
│   ├── 382f275d058a3bdb02871b7ff23ce3981ed63e2c.nq.gz
│   ├── 3ae426fa7f1bea8832dea52b6ee14f988a1227f0.nq.gz
│   ├── 3b74b650334859a001594844abd2fcfc916285f3.nq.gz
│   ├── 3cb2f623aff856a652420e0224ce475867289b65.nq.gz
│   ├── 3f3ed393786d0448ca8e06ff5900379ffe511d74.nq.gz
│   ├── 474c52ae5d40341d5703a7bcab726613d83f078d.nq.gz
│   ├── 49d0d8f99beb93ad075b9986f50f4d405675cadc.nq.gz
│   ├── 4acb793c9e3408ec01b141509ed683a7dc1faaff.nq.gz
│   ├── 4bb47318597159af68a777003cfbab636c6d475a.nq.gz
│   ├── 4e6e7146fc05ee7a320dfeaa3fce857afd8cfc8f.nq.gz
│   ├── 5417e0c00d87fe083eb0a3c54f731a7fd2f7c674.nq.gz
│   ├── 595b2fa56ab3c65c4fc5f088a542fd0f4bdae461.nq.gz
│   ├── 5b0c3d7c939ec094ec1252eb9e7738ecb2132027.nq.gz
│   ├── 5ca07e9629f63b2c3bc60840933a12a946f4771f.nq.gz
│   ├── 6b05be1cb4a2b80f940101651e490aa11764c050.nq.gz
│   ├── 6bd807ccb91c8865d2a679df432f2803380868fd.nq.gz
│   ├── 6be1f2f34f351cfee033d4a72ddf1d7a31ea9432.nq.gz
│   ├── 728efc5767bed72ad81a097bb07739c85257f187.nq.gz
│   ├── 73e442ab2cf276b9326591de834bbc35a3dd1a2d.nq.gz
│   ├── 771dad17a56b45ba9cb3ff2dd9aadeac6291962f.nq.gz
│   ├── 775315aaa04d3ce4eb90bcd54db60c5bcd2dfd4b.nq.gz
│   ├── 7b4a0cf87d73bbe25166dd0330e358876a2f0756.nq.gz
│   ├── 7d73d6e6b264b77196ae452aa36ac49836d1d818.nq.gz
│   ├── 7d86961595d3da34d3a6bef9c1fb1fa36062bc14.nq.gz
│   ├── 83089ce56fe4fc05c4e655786e2bd33a41af31fa.nq.gz
│   ├── 8a4aa4e766b38014d7a7b99ea820cf59859adb92.nq.gz
│   ├── 8fce603003c1e5857013afec915ace9fc8bcdb8d.nq.gz
│   ├── 92fe74edb60c2fb20d673b680db5026416f8124f.nq.gz
│   ├── 9579e9bbe660e6f532366d19b0383e3b3939d521.nq.gz
│   ├── 98392b375eb4f3fba6ee698e562b7d9ce0851b96.nq.gz
│   ├── 9a2459fcc6bed91a92e18a795adb1c6c6ecfc893.nq.gz
│   ├── 9c0bf99b7d1c5d0a37694b7da6e3fb2c1b2bd2c2.nq.gz
│   ├── 9d0ef6ecb708b8d1d8b7c94d0b4bdfe6bc46736d.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a1d50655bfde82f937b3a1e4d097de205f5b84ff.nq.gz
│   ├── a203df0a281f5e6788132941ee1d07091b48941e.nq.gz
│   ├── a3515dac02bc6c227b44cf4f8a05af00209d48f0.nq.gz
│   ├── a90362c90abf52b35b9038b4d38949b2df1df78d.nq.gz
│   ├── ae523098da9a9ace3ee906d9a57d390a1da1d63e.nq.gz
│   ├── b27f964a3a8c69517fd02efc788458c023596cc0.nq.gz
│   ├── b42fa2075faca0366318f94eb1eee137c8813fc0.nq.gz
│   ├── b6c0a8655a675255cab8593cc1c7a876a9d733cf.nq.gz
│   ├── b6e3fa9f3782cf06050d6f19c0d9e82f3f027855.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── b8cede0c6bd86cb8c79dd206ec8e554bc2d264d6.nq.gz
│   ├── bb5b1dc36c9827d3dc82fd4d5aa0cb7f9a05f005.nq.gz
│   ├── bd56cc9c464f04d53c957aeb759c33064c50aaec.nq.gz
│   ├── bd7758a264b5aef268b53f3b8a9c02f8af0a57a3.nq.gz
│   ├── c2c697e405b514fcc23668d1732e6d7c56d3c08a.nq.gz
│   ├── cbb63d747b1f8fc1cf5fcab80bd305a82b2f46d0.nq.gz
│   ├── cd294cdb8356150241a099f2e645607df0af7580.nq.gz
│   ├── cfc27b8a95370705af5c6f71d0a8e1fd5341d2d0.nq.gz
│   ├── d05a89755dfb117b6b157ff81db12f1864f222a8.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d2adbd87f7c6f3a4f0d6fb6c46856de98119537c.nq.gz
│   ├── dc517e55f74947e737bd26d20ace1b6cefc33b97.nq.gz
│   ├── dea2de9df56ed2c38c376203d1e2f71547c6d5e0.nq.gz
│   ├── e1e6398aeaee3c88907f8aa6b815007cf0671b8d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec5339dac3f8eb481788269a9fa646b828ddf86e.nq.gz
│   ├── f2ab9d37509e2f8cbc2af6b1e0c6a65dd91b7435.nq.gz
│   ├── f77673eafdc97ce6759349bfbd5c020d00e42d14.nq.gz
│   ├── f9032ef7b776c4038c385746402df63ee767cb9a.nq.gz
│   └── faeb0a4ad7347c0cd57acce46c620e26b7dd7ded.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e95d8db7039608aa52dd3cc13bb9e25cf6d1586.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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

[scverse/scverse-tutorials](https://github.com/scverse/scverse-tutorials)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
