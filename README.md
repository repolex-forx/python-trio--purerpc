# Repolex Knowledge Graph of python-trio/purerpc

RDF knowledge graph data for [python-trio/purerpc](https://github.com/python-trio/purerpc), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/purerpc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3c17dd885d8f36bcf3a78c7506e35f7bc33cccc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3c17dd885d8f36bcf3a78c7506e35f7bc33cccc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0349b31cd47e68561b141cc2944516ad909287d7.nq.gz
│   ├── 03de33640d64289afa479aec0459990ece341475.nq.gz
│   ├── 069ed6e65160cb3565c6d2b95f90e1d5bc8876be.nq.gz
│   ├── 072a76bc6c1f3ae4f6b7d7485449740f4616ffa2.nq.gz
│   ├── 0affe866cc92d85d18581b9229378d86cac8d9d6.nq.gz
│   ├── 104c402ebf17ef55f9cdca2114f0a4449f6dd039.nq.gz
│   ├── 10d7daf0b079f1a6bb923bbb18221969d85084ac.nq.gz
│   ├── 19c645c00ce0d566ed01ca2759f83c73f8f1d6c8.nq.gz
│   ├── 1ed9f167d334aa987c23ec9d636be357a847dd1d.nq.gz
│   ├── 22d06c29c3173cd000d365ca5493a919b508df79.nq.gz
│   ├── 24d22c1aa847489b76f995ce331fb34147c98cbd.nq.gz
│   ├── 28b3f8d319f527cfe3337e739db397c88b605fdc.nq.gz
│   ├── 2909c8b4229afad4708fd432829ae2643d1a3dbf.nq.gz
│   ├── 4293937c052fbff3b0a91487526e8ce88e6317e4.nq.gz
│   ├── 43b69d0510f38f51cdd616b6b865ba6bb6464b81.nq.gz
│   ├── 51bd1d4679ac44332b7bb71cd9d64c7d17554829.nq.gz
│   ├── 52612755d60d0fe558c784d26338599ba691f643.nq.gz
│   ├── 53a35184823a8826bb7b64f81f302d2ecb00e277.nq.gz
│   ├── 55a0651a62f4f540181028db91cdb529311e37c6.nq.gz
│   ├── 589356d6226debf2c011435d6a63a7bb63ae1bec.nq.gz
│   ├── 58e462103bc84fafa6ab772a08eed0c6e8a3b415.nq.gz
│   ├── 5aac48588cab6b86cf40fe3205c372c5c1833e87.nq.gz
│   ├── 5c209a23c317f782d63e7212d7152d5ca57faea8.nq.gz
│   ├── 5d52164f00670e9a6dc33489d9d76ff2f4215181.nq.gz
│   ├── 6837db53a513ed4fcdb5f1de70c0bec0377b4f39.nq.gz
│   ├── 7394fa4727576ccefc34090e2892a2b53b7f3010.nq.gz
│   ├── 776d7fb456216ad9adb20672a56b336e0ec97432.nq.gz
│   ├── 7ab9dc137f4b1f1c43dd8c303cba4ce99224917d.nq.gz
│   ├── 7e3f86babd3d97131a03d959b948c294dce060b1.nq.gz
│   ├── 7e5c81c735d49ad74080343f74ae0a5760c101ae.nq.gz
│   ├── 7fe2de5d19614444ecbc620334a238685d1e7a9d.nq.gz
│   ├── 834dcba55d58b26d9bf5b21279a6aa24d11c6f87.nq.gz
│   ├── 84581ea66c22021adb49c05c35668671f573b626.nq.gz
│   ├── 86f51b8c2ebae923db10c3c6ef2141bba319eb55.nq.gz
│   ├── 8ce28d552c7f27a6a7a97ebd893df10eee4c6a55.nq.gz
│   ├── 8d82ad64feca97e409b98d6e4aeedfad6c0afe5d.nq.gz
│   ├── 94018288028ddbde7929606e77b6c686d97776b4.nq.gz
│   ├── 95490db239317d26a73a29cbe26c7b2f502e576f.nq.gz
│   ├── 957066b1b409985e9f558a95d4a6288603836251.nq.gz
│   ├── 9d6a9b62ade226d805097b71b18017b060639f43.nq.gz
│   ├── 9f80c4cbe79797a720db6d87af3dd2e715b00a4f.nq.gz
│   ├── a2543e00f2085119a461f1b514ffb8568538dc1b.nq.gz
│   ├── b29329ff6db712544f9b9ee97066a8427245a94d.nq.gz
│   ├── b582ffd829cbb23ddf79babf4a76c92773814a84.nq.gz
│   ├── b9663fd71de5c719f524772a903c856ffc6e655d.nq.gz
│   ├── bdc2351244e9eb2f20248dbc1eebfc326d468e8d.nq.gz
│   ├── c6442e8f853e7a2ae47f09a38a2134eeab1d3953.nq.gz
│   ├── ca1e93230bb5e3bdf91ec25101381d648a1ecb7d.nq.gz
│   ├── cb43f16b7a45a496bae4a3fed0ed4de8bb67fff4.nq.gz
│   ├── cb47c10ee9bf04204940d1048e52c9e432e25e05.nq.gz
│   ├── d066f586252be80913ccece45326919ff72b2a7c.nq.gz
│   ├── d25d9c453e82f5e15932b64c939430294cd0c49f.nq.gz
│   ├── d313b32c95b51622bb7e24950427521725e06989.nq.gz
│   ├── d47b75e8628282935c32c4cf934dbed2b3dce4ba.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6a8c279b8cc65e4b757a91e434783cd28eb210a.nq.gz
│   ├── d821efc8a0b1da95381cd89162fc0061970b0b22.nq.gz
│   ├── e341ab7b3525652f499a9898c2460f4fde0c4378.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8908300b96cb0182fec685c66012c7ed71005c7.nq.gz
│   ├── e900582d024d2fdcb5a749c340df700ebe078f3a.nq.gz
│   ├── eb0c1cbe38353640beab4cd0b8ac5a0fd0881359.nq.gz
│   ├── ee1d708fdb94bc425b72c9090cc689c309888812.nq.gz
│   ├── efaa35b6044ddbf6d6896338d7b622f3942c9fd6.nq.gz
│   ├── eff9c59058c348fb258ffcf2d572760dc1cc86c6.nq.gz
│   ├── f221d0c72233663c3fe2a5bb50b923ff8ff0608a.nq.gz
│   ├── f5a2339d4ae23e48380970a027be72102719c2dd.nq.gz
│   ├── f767871c783b870dc9693062f94ee672732d0a86.nq.gz
│   ├── fbcc590a4d84f16ae48e435e174e7ad9d2e83315.nq.gz
│   └── fc76c5a18f1692a6a19156256203cc169c3f4e10.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a3c17dd885d8f36bcf3a78c7506e35f7bc33cccc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[python-trio/purerpc](https://github.com/python-trio/purerpc)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
