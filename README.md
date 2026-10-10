# Repolex Knowledge Graph of tiangolo/uvicorn-gunicorn-docker

RDF knowledge graph data for [tiangolo/uvicorn-gunicorn-docker](https://github.com/tiangolo/uvicorn-gunicorn-docker), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/uvicorn-gunicorn-docker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8858d49c5fd60c2662783c0b6b30481e0fa3b8ed
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8858d49c5fd60c2662783c0b6b30481e0fa3b8ed
│           └── chunk-001.nq.gz
├── blob
│   ├── 03eadd01d009652c2901fd41fa0c338845f74411.nq.gz
│   ├── 07b8a7fb2af8d8b22c76c38c515b07d065538c2d.nq.gz
│   ├── 0abccfdd0f67e17f18cb45c3347917e579e47d9a.nq.gz
│   ├── 0f23d28ebec229599dfb787a94bb36d6f6f8c6f1.nq.gz
│   ├── 15e6582ecd57b91099101c3ae514610850111c09.nq.gz
│   ├── 17c31a026a169e46e51499c1b669e4044771f78c.nq.gz
│   ├── 1a6c01d76ac8f4488a9b21767bba85a49e920fb3.nq.gz
│   ├── 22b136e0559e8a8a75fa1987c0937ed074fe2f9b.nq.gz
│   ├── 233747f8107611459344bd44a0a519bf699ac11c.nq.gz
│   ├── 2811ded3331f0482bdee78628f167c7668741729.nq.gz
│   ├── 3332013b6daf01c44c44a137ca2a13f2df035e75.nq.gz
│   ├── 3feedde6f99bcdcb4453492fa79e34959baed7d8.nq.gz
│   ├── 42eefe1f675ac08e99731335d6c9993dd23249b5.nq.gz
│   ├── 4cec5d35fb3b4b3871ab278a6fee5e9421267b63.nq.gz
│   ├── 4d11126cad79f11176470c5a0582640165285916.nq.gz
│   ├── 4d4a462bac2c1a6ba9324b6294bd3c9dcc28d465.nq.gz
│   ├── 55eec6eb458d17b0a36c90625488d8fafbda90d5.nq.gz
│   ├── 6793b9a0780433d06d15ef1f8c64bff3cadde9a7.nq.gz
│   ├── 6843d1a2176ba1f64a51e7663b3881a26fada3c1.nq.gz
│   ├── 7dd141dfc55f98de00b07daffea9a898677e9df4.nq.gz
│   ├── 820f133dec0d7f56adaf33120cd9b092f7cb5207.nq.gz
│   ├── 852d2adea9b9f3e578f606f3d99f1e8e540c7e16.nq.gz
│   ├── 85d76befa0d2d422a98ad73ce9ac558ad4d6ed6d.nq.gz
│   ├── 87547d4ca39e644d292f5a8692341d4184275673.nq.gz
│   ├── 8a5d36fc0173a6224a73f13fa26d33aeb7d668df.nq.gz
│   ├── 8b98c416aa7e1e7d77610bd7ded0989352040218.nq.gz
│   ├── 94143827ed065ca0d7d5be1b765d255c5c32cd9a.nq.gz
│   ├── 9ccb1dabcbaf7082ebc12fdefdb7c061d05983e2.nq.gz
│   ├── 9d8e1a27ccf835a743c1766afe14d81684d4a169.nq.gz
│   ├── a52243cf1e5c3a39287269a4566b58cdf5b8165e.nq.gz
│   ├── b8b6318275161bda5c930f822b0e747201bdfc9e.nq.gz
│   ├── bd194aae420d98f53128633a823ac745bbbd6599.nq.gz
│   ├── bf5014071bdc9fccc6f519d900d0159f2267dfab.nq.gz
│   ├── c27d231a76f21d09a3b2e5d5ddbf03d27f05b9ac.nq.gz
│   ├── c94d562277a586c63f96f5e08e85cef15d9b1a4f.nq.gz
│   ├── cc03d08588c877c917e51080a3ba74dd8091f6ed.nq.gz
│   ├── e590a0e2d6651eb7f9ddf14c5559315b08b1c5fa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed64a320320e35800fb41d6ede3c43b95e3205da.nq.gz
│   ├── ee6081daa71ee46bd0726e72d23197dfc5596f78.nq.gz
│   ├── eec27c2f07b8aed90ede7b46386ef8a63e3a878f.nq.gz
│   ├── f3fe11923d768ce355d90dabb47ae428ac1c0f66.nq.gz
│   └── feec529f1e6a2c68172ce4c39dca6419764cdbfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8858d49c5fd60c2662783c0b6b30481e0fa3b8ed.nq.gz
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

[tiangolo/uvicorn-gunicorn-docker](https://github.com/tiangolo/uvicorn-gunicorn-docker)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
