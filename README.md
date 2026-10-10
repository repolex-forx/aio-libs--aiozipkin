# Repolex Knowledge Graph of aio-libs/aiozipkin

RDF knowledge graph data for [aio-libs/aiozipkin](https://github.com/aio-libs/aiozipkin), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiozipkin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 978e7cde37a838340ad2c4aae1b6a72735fa8414
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 978e7cde37a838340ad2c4aae1b6a72735fa8414
│           └── chunk-001.nq.gz
├── blob
│   ├── 05367ec51ac3df59ea5075f52a41486ec58171e9.nq.gz
│   ├── 06af1f81c99d8f434b6dca7520b2479c4aec7ea9.nq.gz
│   ├── 0ab06ff925413ea0d877924425170ef0746a5b3a.nq.gz
│   ├── 0bc6d4c081ee8159a2a1a202fbf70b93a3de3480.nq.gz
│   ├── 0bc82865c72f855c14ad17d26dac48bd46c4a7d2.nq.gz
│   ├── 0f7f8121fba51a3a642845467b97e55510e556d8.nq.gz
│   ├── 106a507e544a7eb4d80a690f2c4bd8a676d0e91b.nq.gz
│   ├── 13a7a4d8de86bb0250048e05d4f198858b1ebce5.nq.gz
│   ├── 156488ad7cb3a6b486453b2f7fc0d4d99804d34a.nq.gz
│   ├── 18884b99a8ce49fbab097589bb50127b4e06acf6.nq.gz
│   ├── 214be9afa9f2902abe4261a84aa96c73818bf6b5.nq.gz
│   ├── 23a7074afb0a53aa114341bdbf060ea68f543603.nq.gz
│   ├── 25c103beb47289b687513ddcc001f60f2d152c03.nq.gz
│   ├── 2caf8c4187e5136137a8f7e2a9e42795eef21e8a.nq.gz
│   ├── 2cc94b7cd3429988650de6cbdb60a207d39107d6.nq.gz
│   ├── 31bd661b6c708bc95a8ba87f90521da551062700.nq.gz
│   ├── 322094cd6024c64ef9a5d29234133b31eb840c76.nq.gz
│   ├── 3a793747796d5e8443cde22689e771a2c6e9a746.nq.gz
│   ├── 3ca6a62be12afc19b32b8b8537897297232553c8.nq.gz
│   ├── 48e32bf4b525337465cd2377598d63456b00e3dc.nq.gz
│   ├── 49722a621e43beb175886054950bb7304f54972e.nq.gz
│   ├── 54193ae6198202282c0e8956cca30f06ee7558f8.nq.gz
│   ├── 5b1315110f6809c68297eb8099c99a45402f4a69.nq.gz
│   ├── 5b5f14589c38cdbf064ba89dceca7f896b93da01.nq.gz
│   ├── 5cad9bf462d0218b901ece2b42e87386de4c4102.nq.gz
│   ├── 5de16fb67361d29a82e91401611483bc5dca4da9.nq.gz
│   ├── 636b3abef5175b0c66b44acd3d18ad6fc7c1f491.nq.gz
│   ├── 69157c72cb9d60a95098112abb45fb0753341fe7.nq.gz
│   ├── 7062c637ce4c861fb6ef8038a10e177a16645222.nq.gz
│   ├── 73b88d2f83cf09fb6bb50b5fcd28d9ce6b036df3.nq.gz
│   ├── 75bc84bf9252c42bf0e71cebc58b52c103d010d3.nq.gz
│   ├── 75d550c32193c233b78ca0a2f33e54344497a814.nq.gz
│   ├── 77f598ccb5ca4b236ce8b2d8dc0da4994d8e4270.nq.gz
│   ├── 7937791371b864a9bac7cefe7b28929d18769aca.nq.gz
│   ├── 7bf5a164653e357f8f3f3ef57d2e9fb6f0fdc299.nq.gz
│   ├── 8b25969a5462b330dab154ccb826215ffb57aa6d.nq.gz
│   ├── 8bd3f355029b95468f76bb09da92124024f5a9a2.nq.gz
│   ├── 8f9da04a9bbc6c72e6472b8bb19d2debb28ea232.nq.gz
│   ├── 91bef238bf01356a550d416d14bb464c576ac6f4.nq.gz
│   ├── 93b1ce3a1cdcbd5db041fad6ed048c0eb436778d.nq.gz
│   ├── 93d4aadf11120979eb94cb4fa0b6cc7a4a96bfd2.nq.gz
│   ├── 93e18b558b3e8bb112ff9d14c67fa8c5f03cb096.nq.gz
│   ├── 95a306ab420249104897c7cafc5afc03a4592a06.nq.gz
│   ├── 9793e921af2ec9a10e3551f727f360a90ad078e7.nq.gz
│   ├── 9829645e3de5e8999f385bbcad94b72f6385f84f.nq.gz
│   ├── 9ca1b0bf5674889f313f27104234421c9effef22.nq.gz
│   ├── 9f3e63a4d0d083e1c02ac9e687a5102ac08978aa.nq.gz
│   ├── 9ffe5ee8825e1ac4a562e3c522149e54bf2189fb.nq.gz
│   ├── a32960bdc83bfe111520e40052e84c2246d86b83.nq.gz
│   ├── a5452509e98b1b203c1a04b18058a0c8c6184297.nq.gz
│   ├── a710bde405c9ad9796a5faf3aaad4f6b8c72a9b6.nq.gz
│   ├── a7617891c6c5d59421768d13f86c75002eae8265.nq.gz
│   ├── b0496495e0c3ecfa685d3e5ffbfcbb4ca1616095.nq.gz
│   ├── b23b9e5250f8a6a930fee8a52a2449a8347a5da1.nq.gz
│   ├── b8141f76a358ab8e8c7faad0d48cd548c6468819.nq.gz
│   ├── bbf36222c449c31a3e14b3d0d114c7094336c985.nq.gz
│   ├── bc6016baf5c9dfaccf327a5bbb586161a431bf5d.nq.gz
│   ├── bd053e930a85a5155ded03d9d1e5e8df85578716.nq.gz
│   ├── be966bc0db429285535bab860a338074afb3ae50.nq.gz
│   ├── c213833b91269efc995e1c9679eaafe8d9027d9c.nq.gz
│   ├── c6b7d8b26238e9f15a01871bdae3a76a76d6e533.nq.gz
│   ├── c898873aa08024e485af4b39f9bfd5f0f1100751.nq.gz
│   ├── d3a1092c8b2bd119a7eff588aa508f819448b61e.nq.gz
│   ├── d6903524902897d211a5ff483996b935381509ce.nq.gz
│   ├── d7bbf830be8c3e6ca30fcc9c6ea3f27613ba8806.nq.gz
│   ├── d9f283262a8d3b3a883dd8e15d0b3099f1311e30.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e83ca7a870af119db5f0ec69a6c0450aee904648.nq.gz
│   ├── e874f04fe3e973ec8322d26a5cd270fbb15c9ec6.nq.gz
│   ├── f2f47db7ffc93b35f2c70ed389f9f82d47b8f31a.nq.gz
│   ├── f4025dcad7d029b4a7b2ac2e9865f7d33e5377b1.nq.gz
│   ├── f71f734cec94ccac38bfaa9316840330605692d7.nq.gz
│   ├── fca62ef32c16120a09e0ad7a6544ab692e892eab.nq.gz
│   ├── fdf2d1ca7d91be98a255b6a90c6042d79043d28b.nq.gz
│   └── fdffa2a0fd7bfbca016990e698d6ea642934bb55.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 978e7cde37a838340ad2c4aae1b6a72735fa8414.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[aio-libs/aiozipkin](https://github.com/aio-libs/aiozipkin)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
