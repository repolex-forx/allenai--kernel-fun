# Repolex Knowledge Graph of allenai/kernel-fun

RDF knowledge graph data for [allenai/kernel-fun](https://github.com/allenai/kernel-fun), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/kernel-fun
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 662db70bf9b54e1e2ed77479ff495c9bee489bae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 662db70bf9b54e1e2ed77479ff495c9bee489bae
│           └── chunk-001.nq.gz
├── blob
│   ├── 059ceb39096c6a4d71402df026480e82a6b12b9b.nq.gz
│   ├── 088eab9f5a0f7e59aa2951a0b78dbae7ee3b122d.nq.gz
│   ├── 0dcb8ddb292eb0f7da1acdde23ed3bc50d4e77f6.nq.gz
│   ├── 0e2bacd70511319b8644ea9744e3480b54755767.nq.gz
│   ├── 119e53aab126d02c54a335a26217b47d0610d417.nq.gz
│   ├── 121ff642ed2246944c2cc7662354c2af0561e5a5.nq.gz
│   ├── 18b31c8f3be019bac359533fe424eca08243284b.nq.gz
│   ├── 1db327ea5f5a636459f62f602a2c2c59628d1a01.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2673a30908b9d9b419bfd57ade9f433d48f8fed0.nq.gz
│   ├── 2e63cff5b9dd0cea9a6cb7583928bdd0b2ee2a95.nq.gz
│   ├── 301e1d1f505ef66ac15f9ffa4a31fb81e3130741.nq.gz
│   ├── 30a401398f688837015292bf9fe1cb17d0684168.nq.gz
│   ├── 31c76004fdbaadb25369c56d3498116fe65a17ee.nq.gz
│   ├── 321f4911c3ca608396afa41931bcfb7f32a185c0.nq.gz
│   ├── 341acaca04d8ab1bbbf0ce024ff71997f069a9ef.nq.gz
│   ├── 3845e91fc0ef6e35b5bfe3bad717df444109cf52.nq.gz
│   ├── 42f8bee969df64a233052e8f700c25c57f15d302.nq.gz
│   ├── 4506c94476254db7dee36efdda0937c67705676a.nq.gz
│   ├── 4fc324aa4650cbff6fd0924d31630607fb1567a2.nq.gz
│   ├── 542bf57b608a3cd2419b200b641cd5b97d50e03f.nq.gz
│   ├── 54fea82242af3ee7dcce3f14b21658a928168da0.nq.gz
│   ├── 59ef5a7951d6b08c836dc42ef7647939404be466.nq.gz
│   ├── 62e17f1ffefed4a165c2acc91fb75015a486799e.nq.gz
│   ├── 63305b6b52136012c508212258d666ad896b8b3d.nq.gz
│   ├── 64d132bc20075e7809b3b343204e3422a71713ca.nq.gz
│   ├── 7183e85bf4afaab5f1883eaa9319af59cf3f273c.nq.gz
│   ├── 8336de4e77bdf30cc3407d09a2bdcf60960ee7b5.nq.gz
│   ├── 94b37257dd886638d2dda8561031128164945721.nq.gz
│   ├── 94fdd996345c4c2eae78e7eaffc821df00c29c0a.nq.gz
│   ├── a75541847b731abc38560628f0b7bf02feccaa49.nq.gz
│   ├── ac552d506bed8096554627bbc0dccb450a6781f9.nq.gz
│   ├── acbb7891ec9357002f67ab7ac6ec5e71ad042007.nq.gz
│   ├── af894de3b6345d3f19c09713f99dfd30d6fc7fcd.nq.gz
│   ├── b711a186904e15b57bf32829fd135c22ff076fbd.nq.gz
│   ├── b76a67a3c3138124334901075a5119fb7dddaeca.nq.gz
│   ├── ba046132822100a9bdfed154863c2081ade15d98.nq.gz
│   ├── bd4a938f6e79607e8039da0f9cbc6916eb53c076.nq.gz
│   ├── c7e1bbf75b0f6d10f16d3b33b4900df4ebb17cf8.nq.gz
│   ├── c9360c4930c5d44fb3d26ba2af269dd2e9510861.nq.gz
│   ├── d7a94d7004373118ce6c15d07c5d92de8e20a1ed.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0f867ad9c1f66f2787e3d4323ce1802d509de68.nq.gz
│   ├── f93d5b12e400a1f3e9a08210d660c0c8c1307a8e.nq.gz
│   └── fb4131d16715c3a537a9fa4afc8842ae729786a4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 662db70bf9b54e1e2ed77479ff495c9bee489bae.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[allenai/kernel-fun](https://github.com/allenai/kernel-fun)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
