# Repolex Knowledge Graph of plotly/dash-pivottable

RDF knowledge graph data for [plotly/dash-pivottable](https://github.com/plotly/dash-pivottable), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-pivottable
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3440a26ce9fb533c5dc81ea1d6cce7960d625155
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 3440a26ce9fb533c5dc81ea1d6cce7960d625155
│           └── chunk-001.nq.gz
├── blob
│   ├── 0712cd672a471272a3ef10318e6780d4f338faff.nq.gz
│   ├── 0bb1753afa634b98fe05d36c31fdc3425a5e3ff5.nq.gz
│   ├── 0c387bcdcf48bc8c4a40aa9bd11b6737fdc6c545.nq.gz
│   ├── 0c801860ef6ab84a6c3a3a21d028937e2982970d.nq.gz
│   ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
│   ├── 146d2bbe9fbcd5e1f6b1131a0829a5789851f381.nq.gz
│   ├── 1a00953c5c1f20a2c77643f59f02f4f964bbb916.nq.gz
│   ├── 1ffc949eb0b89f0fe5693c296e2d221c1f0b6ae1.nq.gz
│   ├── 2bae4311604b6cdd732bb4624598c144f1557861.nq.gz
│   ├── 2ff2c3db521ddc6b370ab0282ff3ae34fce12e49.nq.gz
│   ├── 36f0e296254fd04ec07409e79a725de2ea3f87b3.nq.gz
│   ├── 465692174192deb2232a32cfe61dfb7b41e968cf.nq.gz
│   ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
│   ├── 4bd7f3f153b17c683a9aac1fbf4355a46cc65844.nq.gz
│   ├── 4ca2c79550e778beb20f7650a3348e5483860815.nq.gz
│   ├── 4dde9a9c488367ab6b94b9681575cc6b2ec0f88c.nq.gz
│   ├── 4ffef06dbfb53d6210bc68ec4218f3b3d74108fc.nq.gz
│   ├── 507c042d89bef9de2e13160771a07649c21058ec.nq.gz
│   ├── 509ed5862144c05c29dcaf88339b1186bb232911.nq.gz
│   ├── 539decb828512da5b64e725c63b515db74697756.nq.gz
│   ├── 5413f5c28b63df1d8630e29a50aad8abd623e85c.nq.gz
│   ├── 655b59a577781b3c8c9e160daaceac509b7f0137.nq.gz
│   ├── 66d9f68de237e71b0207182ce786f82330b6fa93.nq.gz
│   ├── 69227a1441391203ed75813a57d3ba2158eaf647.nq.gz
│   ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
│   ├── 767b7d15238fdabe9f9dc66d7ea752b61e5017ce.nq.gz
│   ├── 7d9c56a096696a2da6237c95111cd14067300a5d.nq.gz
│   ├── 7e5130ae3dc47c7c92d6b38c575e19ae26575413.nq.gz
│   ├── 8394bcfeedc45962e96c0eb6f99d977d1ed82db3.nq.gz
│   ├── 8ac4c555dc28ad5ea31359833f90424edd52fb36.nq.gz
│   ├── 8d6c3dae60a5718c951f1cf9e5057819c5b40802.nq.gz
│   ├── 911d2a126188d4b8725576f3a07725d22e51a50c.nq.gz
│   ├── 991b9130c692e655857aaecef279556189fc2282.nq.gz
│   ├── 9a0a8ba182f14cba1aa037466a1f23074e363e91.nq.gz
│   ├── 9c8c775695402085350e4382a8b0c50c2ed6a868.nq.gz
│   ├── 9eeab92296102430f5e2871947c734a30f471574.nq.gz
│   ├── ad8cd6702c56a532ec0a9b3f6b8cb802f9bb7932.nq.gz
│   ├── b008d637c8fec914f4fc5e4dbf77a33958992bc3.nq.gz
│   ├── b597a44232c2a3b77943c95857fa5c6075cf69d8.nq.gz
│   ├── b651af67176b8626bcac032017b5c996941b4182.nq.gz
│   ├── bc8371522911dae5c57fa15028a9c84eeb316709.nq.gz
│   ├── d1cae1cf203ebb4c132f9f98a087c88cdee7bfb7.nq.gz
│   ├── d45356b4784f5249a5af48a2eb041a1390f4ec64.nq.gz
│   ├── ded8431c0259668bc8762221b00a1b78893a9ee4.nq.gz
│   ├── dfe0770424b2a19faf507a501ebfc23be8f54e7b.nq.gz
│   ├── e5f9ec2644bab4d348104fd9b4363fa41ecefabb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7635bb7ea050ac92913e26c63d6ab01bfae096b.nq.gz
│   ├── eb81a49a94228fc85213e5bd9c8d45722b89887d.nq.gz
│   └── f54d8e1c1846add5705b17360f490c2d83dcd445.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3440a26ce9fb533c5dc81ea1d6cce7960d625155.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[plotly/dash-pivottable](https://github.com/plotly/dash-pivottable)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
