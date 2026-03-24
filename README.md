# Repolex Knowledge Graph of pallets-eco/blinker

RDF knowledge graph data for [pallets-eco/blinker](https://github.com/pallets-eco/blinker), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets-eco/blinker
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 01aaea5c518104c8b9a83cf2af589e932b55f1ad.nq.gz
│   ├── 0517fe56af8fb03f702cfa4e86ffa9aa538cb27c.nq.gz
│   ├── 07ddd989fe3b5ed2bf34b77227dad0dd94014ccd.nq.gz
│   ├── 081173df1d682063fb6b88097d9f9454baf6aeae.nq.gz
│   ├── 133c57a0642e997e52ad5235c00930cf94919b3e.nq.gz
│   ├── 1ca9c161cc3256e249267afb72666580148eea02.nq.gz
│   ├── 2853115cae7cf8facedbd8073c92c0c9e1a4f533.nq.gz
│   ├── 462ccd31926e3a8e0cbb320c2c0acbaae2bdd516.nq.gz
│   ├── 4f802f4057fbb38f7270ca1c349329962c2b4774.nq.gz
│   ├── 521431d90cb4c1a6d97478fa6a2faaf35e041ae6.nq.gz
│   ├── 5bbd2005f045a17b9b95c3c7445ec3ad73be667e.nq.gz
│   ├── 6bb1491e8ba9f2a9f26a21d31cfee5df05e418ae.nq.gz
│   ├── 72fdd8e01ba981e8694071eefcaaa22d16636e21.nq.gz
│   ├── 7521ac3c5432d602d86dbac5ade7f408662667f1.nq.gz
│   ├── 79c9825adbacb5d8c6eaee51863b8a40051d97c8.nq.gz
│   ├── 883dded1c8298e8cd11f9fabd26eccd393fc7006.nq.gz
│   ├── 88e18188ab9de35802d700de2400598c582b9a8e.nq.gz
│   ├── 8a3e4f95b97eba3dc8005b87432a322beedf5eda.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── ab73fb81d6feac57591eec7c4bf09662f583ef8e.nq.gz
│   ├── bed55ca9d83c80d886b19d7ca7dfe69a378a5a5a.nq.gz
│   ├── cab56636c2eed4f47f3d8e18c1590ff3fb50c8eb.nq.gz
│   ├── d278ca08e39bb5054ef039200cf30e9c1bff0e7f.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── db1749db31620631c4462cf192c2c235f67b4300.nq.gz
│   ├── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz
│   └── e74db47723fd69129b55d0b8cce8cf12dcf524d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 33 files
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

## Source repository

[pallets-eco/blinker](https://github.com/pallets-eco/blinker)

---
*Parsed on 2026-03-24 by [repolex](https://repolex.ai)*
