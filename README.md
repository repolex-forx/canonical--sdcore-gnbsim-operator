# Repolex Knowledge Graph of canonical/sdcore-gnbsim-operator

RDF knowledge graph data for [canonical/sdcore-gnbsim-operator](https://github.com/canonical/sdcore-gnbsim-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-gnbsim-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 954093392564bba2b321d5ab2a20040bcdb3d16b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 954093392564bba2b321d5ab2a20040bcdb3d16b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cce1b9c349ed220bc793e21528772363f85cc3.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0e5fe3fdacdbd55b206a5a1cd92bba1aed14ac76.nq.gz
│   ├── 0f511301a7366159548f80b34d9cc0de304082e0.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 3aea313d9ee67506824476146335716b9e3ccb80.nq.gz
│   ├── 3bc78fd0e1fd0458d5988d1ba8c5f54b5a50776a.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 428a25018346a16aade1836af3ec33e85e0b1d4c.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4c91480cd4ecba023f1c7eb31c738e45d8e34af5.nq.gz
│   ├── 4d37a38d9f2212098c8908b60fbed55d9e671cfd.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 4f66ec88752b8d9e571da94a9c5be38645e44fe6.nq.gz
│   ├── 5cd84018627523aee6afdbfe1d63eeb7a4ce2bb5.nq.gz
│   ├── 5f73e94f589db2c71c6c5ea7dac58a10abfd4fa0.nq.gz
│   ├── 6321ac6b4016287bdda9dcb6a09597321ef21d07.nq.gz
│   ├── 691405bfa19f89107888639c665fdacaf9013726.nq.gz
│   ├── 6bfc88e26fcfcc2f714b7ea7767ff987b0c5869a.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 8c2dda62d4d5c1c4a386003421c5592e1ab8312d.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 8f7e2e277d1ac9d47fa77732d88241824d1ae2fe.nq.gz
│   ├── 93dd2632ddfa007447653053a48b52a13c0cb2a1.nq.gz
│   ├── 961fb7a242d2ad5fee4feb2471b06fb73758036d.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a76c30812e29e30a7ff7140a0a433586d10a50a6.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── a82d04cae29a2a02375e68482690538a73dccfd2.nq.gz
│   ├── a9a6ae552853dc38c2e6b13568a8f80e4e5b659b.nq.gz
│   ├── af4b1c516d6177355e517177dda1f31c94b277dc.nq.gz
│   ├── b49ed0a2f75a2850c081a69e87686e3549f492f9.nq.gz
│   ├── bb5a7242f58d59d1bef0c9c31ea59d512cfa966a.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── c694bb144edabd25b3bda3824bf80e68f0d67b8e.nq.gz
│   ├── c8d2c199961b1ae2d07c62000f3f92fbe0d35ed7.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── e40feda4db1f05512a075872599238c331881bc2.nq.gz
│   ├── ece834ebefaac7d3e5063a5fbcd9aac9ec68b067.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   ├── efbeb558e070dd32a589d61b950fab052fe889b5.nq.gz
│   └── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 954093392564bba2b321d5ab2a20040bcdb3d16b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[canonical/sdcore-gnbsim-operator](https://github.com/canonical/sdcore-gnbsim-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
