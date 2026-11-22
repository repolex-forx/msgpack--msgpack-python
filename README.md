# Repolex Knowledge Graph of msgpack/msgpack-python

RDF knowledge graph data for [msgpack/msgpack-python](https://github.com/msgpack/msgpack-python), parsed by [repolex](https://repolex.ai).

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
rlex download msgpack/msgpack-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 19b5d33ded09d5a563a677c1a3d75b6246181259
│   │   │   └── chunk-001.nq.gz
│   │   └── 874b828d9bfed863e0603cc462b550813cc92f15
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 19b5d33ded09d5a563a677c1a3d75b6246181259.nq.gz
│   └── repolex
│       ├── 19b5d33ded09d5a563a677c1a3d75b6246181259
│       │   └── chunk-001.nq.gz
│       └── 874b828d9bfed863e0603cc462b550813cc92f15
│           └── chunk-001.nq.gz
├── blob
│   ├── 0103fbf7ec21db7f1e1a35c9c1ea1c20aea737ab.nq.gz
│   ├── 015e8b5eb46f2f17d1995d0f8e9b553bb6c0397a.nq.gz
│   ├── 0947863f59a47f26eb5b5117da488b27e163b326.nq.gz
│   ├── 0a2a6f5397da6f98a0aa7ac42ddc3ea88cfb1c26.nq.gz
│   ├── 0cbd87332a41de11bc89a01d76ae17ebbc2d39e9.nq.gz
│   ├── 0dd708d17c3d4d47bf388a9a6f3e19394244789d.nq.gz
│   ├── 0f6c1b503c60ff6e50f2f2747a5a1eab7626a6e6.nq.gz
│   ├── 0f895d7dcb5261eddf6bf318647fc64212b4394c.nq.gz
│   ├── 1866bc673c59575f2002b195eb08f55b40a19d7a.nq.gz
│   ├── 198cf7b5223faf947712cb96096edccd6de14f95.nq.gz
│   ├── 1c70594f5966b8218c60c9538c492a4638dfd978.nq.gz
│   ├── 1e9c0045020113b9a54982cb66746d2f600148e6.nq.gz
│   ├── 1f0632422fd59deb92d310ce1e9e82fbab430b2d.nq.gz
│   ├── 1faaac3aa6217cfed7a75928d82b760b587a1492.nq.gz
│   ├── 2099b916a6149872ee354ca266c65a54b4ed985b.nq.gz
│   ├── 23be06d50715f7e7497db8b38b1c4744faec033d.nq.gz
│   ├── 26002de441aaec108834d9654f76e04d88abb5d6.nq.gz
│   ├── 26b4ce68ce2360998e9836e702d474d06597a779.nq.gz
│   ├── 27adf8c07952d8b110541aad6d330f93780edcf4.nq.gz
│   ├── 28116cd672660ed506c80a4ebba69bd057f2bbd5.nq.gz
│   ├── 2e778dd27d86e5c3c1638dbc344e54ef2b2c4fda.nq.gz
│   ├── 31d7d6e195bcd23eea383cf17c6715aff490b340.nq.gz
│   ├── 323543c910afd7b7e2c721b66791a75489b1dead.nq.gz
│   ├── 341be631076e5db9469a99f4e80ea77276f77cc9.nq.gz
│   ├── 344eedd19503e4a4967398d2c28d916f7be38971.nq.gz
│   ├── 34ff330476a467f65b52eb7dcb7870e4f9b7dee9.nq.gz
│   ├── 374d1549a1fbf83f710ba9a7d9a210d3543fbe32.nq.gz
│   ├── 38370088ab8c87b828535aa366db04fbcc0311ae.nq.gz
│   ├── 3976adc7133af19e3fd095be3fb6c4e2f8d468a1.nq.gz
│   ├── 3e753e118263a91f3fd77a479fa3f88b4f41f072.nq.gz
│   ├── 4029e9ed2df9b3034d9187cf90ba0340a68357e2.nq.gz
│   ├── 402b69469bf996db45cd40f45a90466290662614.nq.gz
│   ├── 51f3e0efbdd3312bd62f5fd170e04137111129cd.nq.gz
│   ├── 569c751feaae31f6ff3e0a24928df4250a6b4d00.nq.gz
│   ├── 57d84a4c3298da57104bf8ddb9c3a8fe20b1d873.nq.gz
│   ├── 5811c27f983d92bfd8f3e03b8222dc233065bff1.nq.gz
│   ├── 58a2f4f500af221dd29f244667fde03f99d2693d.nq.gz
│   ├── 5e3122f65290737307bc87c843943114b2dfaf8e.nq.gz
│   ├── 5f0709a4910b6cd35740d0062553afa3515c5ea0.nq.gz
│   ├── 5fbf185ef957a3febb64a8eb75fa4ffaf87128be.nq.gz
│   ├── 61852f1545e3a50ec96963d4f34571885867e330.nq.gz
│   ├── 6317706e92668acb1159edacdb29f5ba5cc7c6e1.nq.gz
│   ├── 6694fdc63a3ef164df3c026702c69575ce1bb24b.nq.gz
│   ├── 6e9c8c1478d1dad9803e54715f1f94fe3a2b2486.nq.gz
│   ├── 6e9d9ba40e2aa9a6401913df0337ae6ff8f97ca2.nq.gz
│   ├── 70673004acd10e4c11a4ac57c9eaebe092618c12.nq.gz
│   ├── 72776a2c0242b84db18dc3028f1269c5153a1a09.nq.gz
│   ├── 75f0c54144ccbc08d6f538b1ee8fb1355fedace4.nq.gz
│   ├── 80274ac6e86ef8285345d888d16273a578b12f68.nq.gz
│   ├── 831141a1959b17b3e4a608849729b6791e96a273.nq.gz
│   ├── 831a6a7f77795d5a4e7b26a7f5eb29d1841e6108.nq.gz
│   ├── 88d871825e5180cfcb4c567ad8bdecdd77c4c0cc.nq.gz
│   ├── 8dee4620fde3c6c542396e10729c23e36a6aceef.nq.gz
│   ├── 904be42fa8a8300bfeeb5220d40e51a482a53e33.nq.gz
│   ├── 9680b31eee9cc8499003d5ed2bfe6f49b57c6687.nq.gz
│   ├── 9694819a7df1570ccbb41de065cb7052f9af8e79.nq.gz
│   ├── 9b92b4d9d474ab26d1dc81ae60641529f9997a8c.nq.gz
│   ├── 9ca6e182814d356d3929527529e5537be06272b3.nq.gz
│   ├── 9e2f9be5aa4f3815f63a4ffa5ac60c3ae9801844.nq.gz
│   ├── a7acc16c081c142c6d487b090b1c7081130099b2.nq.gz
│   ├── a911578c3b8960a67fef37c996ef1e1f2eec4e3c.nq.gz
│   ├── aaf0fd92d8f059c7380699906c8aba45cb7bf290.nq.gz
│   ├── abaaad900fb9585031080d556c6b6998112b7447.nq.gz
│   ├── aee0d5ed4498cdedd3861ef48920bf95235eae5e.nq.gz
│   ├── b02e47cfb91a54a7205881ee87a5db2ea8d049a7.nq.gz
│   ├── b17c3c53da72998f063390aa13639c76c7a22c6b.nq.gz
│   ├── b544ccac81e5a30013e11dba4dcb0e95f4ff0d40.nq.gz
│   ├── b696b926ef9bd94b1c5a6a9a5295339cca4dc072.nq.gz
│   ├── b77ac800cc57c80ed980ed90c6b0ecd0a8f7eb95.nq.gz
│   ├── b8959f022828c042657e178b4344a8842e259ca1.nq.gz
│   ├── beeab15c5f10097f0b1f82d4fc12966412165740.nq.gz
│   ├── c06c87dc7d331c3c31258b6d4be2d4ae8351eab2.nq.gz
│   ├── c14a3c2b5b0fdbb17176d780c3d8b28148cbe12b.nq.gz
│   ├── c2e9b9c956e1390d6aaf21874aa9456a287fe649.nq.gz
│   ├── c44c63660f1cb80753a892dcdbcda6ebb5b750b3.nq.gz
│   ├── c4c615e39a4b5b7655b49865183e9ec3ab8534ed.nq.gz
│   ├── ca0972228cc01eae9244d90b1c02d37c03c6ab00.nq.gz
│   ├── cce29e7a8c29030a2b2c6aa9d580e6709627c73d.nq.gz
│   ├── d696ad6a82c8efcc655c2f259b42a4b2b6345685.nq.gz
│   ├── d6d2615cfdd0b914d064cdf7eecd45761e4bcaf6.nq.gz
│   ├── d7215a94cc4ba78684a10eb564b8282a2d16e0c0.nq.gz
│   ├── e66d4549c1dc8585318c1ad3d7b526bca420a196.nq.gz
│   ├── e9c2ce83d20a795cde33b7eaac1f52fb06e439f2.nq.gz
│   ├── edf3a3feb14506f4e15252d61b338c29a218810c.nq.gz
│   ├── f067af3aae15a5b494f0eeb15a7064c176e30fd5.nq.gz
│   ├── f3266b701fb408b481a686845bb4d0d5335c51be.nq.gz
│   ├── f4b89d43c61ca65bd4aeb38f861a922e98ea2745.nq.gz
│   ├── f5dfbbd2d97f4277156b0534ce31b5fd6aca29a7.nq.gz
│   ├── fa7e979ba260819d09dd728e9ea5e0b5ede28c6e.nq.gz
│   ├── fca321afe6fbc480f4a140168dec337c23b9f6d8.nq.gz
│   ├── fd124dcef3b7ee4ffed3d79f2d143530ec41ceec.nq.gz
│   └── ff34139dc519a67f99e1eb3f9eda1bebf1ae9770.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 19b5d33ded09d5a563a677c1a3d75b6246181259.nq.gz
├── filetree
│   ├── 19b5d33ded09d5a563a677c1a3d75b6246181259.nq.gz
│   └── 874b828d9bfed863e0603cc462b550813cc92f15.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 105 files
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

[msgpack/msgpack-python](https://github.com/msgpack/msgpack-python)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
