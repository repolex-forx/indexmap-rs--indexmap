# Repolex Knowledge Graph of indexmap-rs/indexmap

RDF knowledge graph data for [indexmap-rs/indexmap](https://github.com/indexmap-rs/indexmap), parsed by [repolex](https://repolex.ai).

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
rlex download indexmap-rs/indexmap
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41a870887c4c77adf665886e63df08f406bfe37a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 41a870887c4c77adf665886e63df08f406bfe37a
│           └── chunk-001.nq.gz
├── blob
│   ├── 08c2baef1dc7fb8297e4783959c2af484082e3d4.nq.gz
│   ├── 090012c828fc449c939f8a58a65a59ab35ea79d2.nq.gz
│   ├── 0a3eebdd93cc7a3c1a448082328d084047de5944.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 27bfe608213433a57c82dd1eb4eebf16b4aa550f.nq.gz
│   ├── 28b97e3bdf0513e279f365055cc6afcdb02ad456.nq.gz
│   ├── 39301c3b98381fc9d4436cb12a1b5a67713493cb.nq.gz
│   ├── 4434cb78bd052d4c75db526077f4531ab770012c.nq.gz
│   ├── 4b5dbc9552a0d2628154da28eff13bd4be24e43b.nq.gz
│   ├── 4fa84f8151fb8e602ea39cbbdf3f30c121770479.nq.gz
│   ├── 52232e67b5d5f099409c51be04e66491f33ead04.nq.gz
│   ├── 563fb1dcf921e8a502f98567a3423af098fc2e95.nq.gz
│   ├── 5b7a174c6e8b1add772580f469e246977f0966e0.nq.gz
│   ├── 5e6c05e1c352d9d35ede376a620b7202cae271a4.nq.gz
│   ├── 60e66a28f2a927309e8f0dd9bec5924cf8e01c99.nq.gz
│   ├── 682b8e17fe790e10e2ebe2cd18f60409b693c69e.nq.gz
│   ├── 73e7fa0e438e9846515d1edd19f0f96841bb1c92.nq.gz
│   ├── 73f096cf815eafb851a5cea378bc0d0cf2a35d6e.nq.gz
│   ├── 7798438c1567722f9b5c5dc21602e748a1b20bd5.nq.gz
│   ├── 78abbb5d6071ef5175f8f91cce9f8435f0f0f32a.nq.gz
│   ├── 7acae4022144cfd00b26dfbcf7ecf362b88180fc.nq.gz
│   ├── 7d522f1c970808b9a10418e7fdb12afbed41d33c.nq.gz
│   ├── 86e1f7ba9ee48fa2bd1b857c56e46a2bdbfcaec1.nq.gz
│   ├── 8b8181068b3cb531b8d9d75bf7a825d9a5dfad2f.nq.gz
│   ├── 90a0702f1b4a4332a4b3cff80171db5359cf424c.nq.gz
│   ├── 95feebd2a552eee600715d93acfe844c28a5b062.nq.gz
│   ├── 982e6fbbd403f503a7de47c7cfebb605ea38fb76.nq.gz
│   ├── 9bef6492e2560d2e46cc0f9cd20184a864d662c4.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── afcd7bba65c5071030068f84d833c16afb4ac4cc.nq.gz
│   ├── b0ecf344f41b2c68a7d7f620e1a731b6ae1c581c.nq.gz
│   ├── b0fda99854371fec9a7162c1c932b07cf2df230c.nq.gz
│   ├── b104920848e68cf66bb86746ea442e58c766691f.nq.gz
│   ├── b4c64876b43fb8506af2d5c4c95c24b52dfff01d.nq.gz
│   ├── b555f9ae96d8661d93c2c62922911e183d491174.nq.gz
│   ├── b6dd4ce3b63706e676012f6a9b32f71e8748d6fc.nq.gz
│   ├── b85c22ebcccc72facf58fbeae6d0074627391ff5.nq.gz
│   ├── bb4c77ea8767ff670f378606eea5149d15c2d450.nq.gz
│   ├── c3665d2b0600f5f24f876162435a3cef35dc88eb.nq.gz
│   ├── e0835f619707833596347b5e9eb91b62807b064c.nq.gz
│   ├── e12c768f0aad7a51ac6db9658377c4c9638216d0.nq.gz
│   ├── e2309c59859abcd3ab12fa0c6f000551e6c98f10.nq.gz
│   ├── f4e5b13bebefa7b87132ebe3405cc01a41f35bf5.nq.gz
│   ├── f9394e20590349bca8101bd455692ce8daa6e2ea.nq.gz
│   ├── fb3a5c8943da208a01f4f37513e47631cdb3a898.nq.gz
│   └── fe1886659e32b218a7c603f838470563081766c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 41a870887c4c77adf665886e63df08f406bfe37a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[indexmap-rs/indexmap](https://github.com/indexmap-rs/indexmap)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
