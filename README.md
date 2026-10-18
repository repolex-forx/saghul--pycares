# Repolex Knowledge Graph of saghul/pycares

RDF knowledge graph data for [saghul/pycares](https://github.com/saghul/pycares), parsed by [repolex](https://repolex.ai).

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
rlex download saghul/pycares
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ceda977f5543af81152c6b730fb6bbc1f83b14b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6ceda977f5543af81152c6b730fb6bbc1f83b14b
│           └── chunk-001.nq.gz
├── blob
│   ├── 086f279666b2614e1c03661517b66d24f442899d.nq.gz
│   ├── 0c5df08d63a0736fb2dc474b91afeefb0eba9c7b.nq.gz
│   ├── 0f979dc85287339a72d2598582e1fb2a6f79abbe.nq.gz
│   ├── 10f1d219f3e8b6061ad1498a95cde8fd06daa5f7.nq.gz
│   ├── 12ef2a68923b0e39b0f0406693291be35626ec20.nq.gz
│   ├── 1b2112c89c5100cf38fdf8de38660c90626099c8.nq.gz
│   ├── 201f3a1edd193385f892604c109a9bf65fdad247.nq.gz
│   ├── 20ae73e5ce6f4d734a013f6802b56fae82e693f0.nq.gz
│   ├── 24a05a5e767c26eb110e0ac0485c8e053c3f6f73.nq.gz
│   ├── 27c835895e441db98623e60394ce802a293c1f24.nq.gz
│   ├── 2a62ea08ea573fdae4d86a72ad9714c79484f0d8.nq.gz
│   ├── 4298505dd95a3da7c3f21bf93974a7768f3e2fb3.nq.gz
│   ├── 437d222dce64d306bd225b1807f125c9c32850b4.nq.gz
│   ├── 584943e4f6dd81645474eab62039f5b58afcbd33.nq.gz
│   ├── 5ce0c628ba4e7553bb55452751be99693d80f16b.nq.gz
│   ├── 7460e64ce7595e91dec4222e384407c42584317f.nq.gz
│   ├── 84b5e25beea372d3aca87980d9987142ffaec481.nq.gz
│   ├── 859d70b3fe836df309aaa16e16386e5fd9e965df.nq.gz
│   ├── 86683771937e1beb4885e9bcdb0fbd14d87e4e62.nq.gz
│   ├── 87058a0cda309b2fc863ac60047b4ef3c88fac86.nq.gz
│   ├── 8796785687522c97ce533e41de82000e9f32344d.nq.gz
│   ├── 8afc8a38aba657502cc6f22841c168914869154f.nq.gz
│   ├── 979a317abb751eaea78b148ee7fda1e5d16ad369.nq.gz
│   ├── a8804f9d407dfe59b4d2d370bf3b2e9821602d6f.nq.gz
│   ├── aaf0367fccb32d4dca9e2a9582d079f98eddcf0c.nq.gz
│   ├── aed5f15b14f67cd1b07402dc6795694677884be2.nq.gz
│   ├── afec5ad6a0ce7771b86d82f26d23bc7bf6b34b63.nq.gz
│   ├── b2aaa9068ed5d7e215e6db2b92a7bddaea4ff919.nq.gz
│   ├── b843bb60fdf8bd5524d233255c1acaaecb1d2e9a.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── c1054d77b4e59e55f0bfcd47b34889e75a2f72ee.nq.gz
│   ├── c4d881a390db495943c3e5fd7d265dadf750e187.nq.gz
│   ├── cbdb622511b915864577bd8422ecd34e820893bc.nq.gz
│   ├── ceffc085163c6ad810a08615482fc0a17fe164ab.nq.gz
│   ├── cf62f4a49eb92951df24bf68e83567b48f50ffbd.nq.gz
│   ├── dbb10d5821c0a5d019544a960e66b89408843503.nq.gz
│   ├── de510155ce0e3149f97fe262751c82ad6b732e8c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eec8c871b33c6fe0032c655b031f61a42d4e0230.nq.gz
│   ├── ef99d1129ae914c6e9df182bb0c5f4f3f5585d5a.nq.gz
│   ├── f08209e474b7a8ba9b8cdd6140c8206dd5aefee2.nq.gz
│   ├── fafb97a3be0d95f2637bb1507f34db9b4bbed7c8.nq.gz
│   └── fd4e3dee0acbe4549580c83cb06b25ceb3349f58.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6ceda977f5543af81152c6b730fb6bbc1f83b14b.nq.gz
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

[saghul/pycares](https://github.com/saghul/pycares)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
