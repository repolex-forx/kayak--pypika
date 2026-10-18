# Repolex Knowledge Graph of kayak/pypika

RDF knowledge graph data for [kayak/pypika](https://github.com/kayak/pypika), parsed by [repolex](https://repolex.ai).

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
rlex download kayak/pypika
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5e800d83a0f0ae14210410c02fd97e51e2e3f1d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5e800d83a0f0ae14210410c02fd97e51e2e3f1d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 00028c243bfa9cf1a96c116fcb311598111d6449.nq.gz
│   ├── 009256f48d183e7e57bd14233d60449b5f085572.nq.gz
│   ├── 02c204eab2e714035c3684bdc56031ff77acfea9.nq.gz
│   ├── 0c10e70a13d4df3ca83f388de8ae25b23dc407de.nq.gz
│   ├── 0c975902ce5e2145dc4f7ed9b5ae10ad8cf9cfe5.nq.gz
│   ├── 104a7235b6ea2d46fd365989f68c5d081eb20076.nq.gz
│   ├── 1274e0a898a912df7f2988cc8f1f447d0e392121.nq.gz
│   ├── 135dd7f112131776d76748e15eead1eb81752b59.nq.gz
│   ├── 145baeb7753dd9cbefbd6f272bd672ae5730b0c0.nq.gz
│   ├── 15984e042e4c924717b58ad9af63f7f5a257d0c4.nq.gz
│   ├── 15a7b93fdcf91838b6ceac5fc62657aa8e45662a.nq.gz
│   ├── 15e08c2731461dd7f7caea78c29b25c26d958f1d.nq.gz
│   ├── 1631f63257e5852571e297d99bd9709a4219ef47.nq.gz
│   ├── 177def32c291e859e95c8931f9f006db4e761457.nq.gz
│   ├── 1884b739504b510c56d18f1d4b7072be93e8e340.nq.gz
│   ├── 1c627d8e9c2d65410c67cf2c39974949b0720a0e.nq.gz
│   ├── 1f45607fe8d2f176bc2a008ad5c747c57b859185.nq.gz
│   ├── 1ff04aea4d951be78aa01ccc0ba0384c682c570e.nq.gz
│   ├── 21b54f16fd5d3518b5c767d3605068637898a73f.nq.gz
│   ├── 21f602065d1f64c87dd848e5dca1f38548f85416.nq.gz
│   ├── 25038ce5482c9ae0adb95d703810ec3054db3a5e.nq.gz
│   ├── 26282846d611e7565779a479a8f0f761c2738cc7.nq.gz
│   ├── 265ae7350d2054549731f9a8c4379fdac95dc580.nq.gz
│   ├── 2a2aa4e29d7f0c9543fed2f405ced7e9cfc9d313.nq.gz
│   ├── 2bb4eb2a1e26a4e214fe5094aa165514fbf27747.nq.gz
│   ├── 2c6250f601605b29b0fae11ac0a50c4ab97a5312.nq.gz
│   ├── 2d3b5528faf75b332baaa42e69360b48e0b7a8fb.nq.gz
│   ├── 33bc13ebaf57ae5e7cb1b0fdd93a63655214280b.nq.gz
│   ├── 35b2925332253b82ee81d188e34a050ab7d1131a.nq.gz
│   ├── 36ae82ed47694cfca5f75634677b5c9509d1b869.nq.gz
│   ├── 3bdd7dc21ab8a25854b5fd89f2eeae8a3af657d6.nq.gz
│   ├── 3c6c86207a4d0206b5c0ba80b77fac4cc257fa17.nq.gz
│   ├── 3d523642f65ae9d625a9d4545494adfe5da8a9ff.nq.gz
│   ├── 4042af6e969a98c89a1133dd125fd039ceac4f17.nq.gz
│   ├── 40ce275bdb60b30cca52fc447b32ba75c0098f8a.nq.gz
│   ├── 431f598fc2b1bf87a059d8f3c997e21762b580d4.nq.gz
│   ├── 469705a9ff3c8fe9cc7f02c44a9812521eeb67f4.nq.gz
│   ├── 482b687f3cf99e184a027dae974a95a3308bc26b.nq.gz
│   ├── 48d1b22f13ccf0f189a9d1691106bd456d4a2764.nq.gz
│   ├── 4c07346d1cc895e9da8a6131f2d628f4be7758ec.nq.gz
│   ├── 4dc649c40e8252be92c91ae87cd257bf9749dc52.nq.gz
│   ├── 4dfb1ec06b4c1182454b8bc508b50410efc2c79a.nq.gz
│   ├── 52fb4487fe7be3ae28a4e9eb08628fba89dc0f79.nq.gz
│   ├── 572baf8b04a4d4927e376fb25fd37f46e3ce5e9a.nq.gz
│   ├── 578f36931b7d3d9d70341195f5c2c7e56b78352d.nq.gz
│   ├── 57f8d39d63caa1726781849db73b29df78d05dec.nq.gz
│   ├── 5820e15223839e3a1cdfebd89f22dd65d03b7a1a.nq.gz
│   ├── 5bda7a5c087e109435bfc66bc8499980d2a87197.nq.gz
│   ├── 5e28dc925f75b2c2cdda9028e612a93badbe30e2.nq.gz
│   ├── 60ffd3cd8e6191e3fc782dac003c41bfb7a78528.nq.gz
│   ├── 61985bfc244fcd663e7d8a904b4645901f3abdfc.nq.gz
│   ├── 69cedb6dd523d2a01b7327efe505387a5dc554d4.nq.gz
│   ├── 6a7b3c34323e6d8fbbfb2dc8f5b31a143fb4ca7a.nq.gz
│   ├── 6aeb47c0e5045d3a2bc477a71a79f170e36caa11.nq.gz
│   ├── 6afaba9b7ee8560fc468a858ac604f94ad92ce63.nq.gz
│   ├── 6bff198592030529d6937846e69cee29b78b0044.nq.gz
│   ├── 72e39ea18ad7cee30785ee9a0a209f729936bbe6.nq.gz
│   ├── 74a51c936e70caf63fd70608161496351a3c6db2.nq.gz
│   ├── 78589aef5075f6c63d222ff148fade6a1bdde47f.nq.gz
│   ├── 7941961e924c2e39ec0f15f9a43cfe59a5dee2eb.nq.gz
│   ├── 7cf53b228f413a8c7cd3e414fef5522a82f99b29.nq.gz
│   ├── 7e8cab56e220d752e566fce46657ed98ceb7d358.nq.gz
│   ├── 8085803251e9a87d2636b85b20aaa511200614e9.nq.gz
│   ├── 8455dd6e83d8aaeb39c2a15b684e95d3ccfd6d0e.nq.gz
│   ├── 86d8a68101915c27b95484243dd81d55f7dba356.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c8747b97613ae156f5c558c71620f6a7c620f43.nq.gz
│   ├── 921e381ba8613d4a83cc53bd60d111d9547e2c1f.nq.gz
│   ├── 93bc84d7b312721c4ef3b136705f12154e973429.nq.gz
│   ├── 9c8f3ea0871e0bfe81da0fa6e7c1d7d156dc380e.nq.gz
│   ├── a17cd02d133199bf1477cfda78d218c20af74270.nq.gz
│   ├── a3f23fe53af3174a33b002f6965e2d1ca06d2790.nq.gz
│   ├── ad81895225d67877ef4ba5e4c2c2c1364b638fa0.nq.gz
│   ├── b58a170c3e82d4289efe034a732d32c97f52e973.nq.gz
│   ├── bb9a9b1c68fe8671989f7c49f9db90e389d06f59.nq.gz
│   ├── c11e9afcd9624abb0a7313306eda34ebcf4c99ba.nq.gz
│   ├── c60ed8e49207957fc5c2e15688529686053592db.nq.gz
│   ├── c6da29a05cad4a83975a2b7991b890b0f5800a69.nq.gz
│   ├── c713a686417e9653b60dfe03c2c39b90e5a70c90.nq.gz
│   ├── cb1716672995c372e81c8d7eab5a289521b3ae83.nq.gz
│   ├── d085f1c8f27e3f7bba51e4eafedbe59c83a0f3f5.nq.gz
│   ├── d1c80adca24fe0d67c5d8519f91fe55e94df8fbf.nq.gz
│   ├── d5d00323bf8715a9b9425326b9bb38c95b1bfb23.nq.gz
│   ├── dc5783335f3064b7cd685be8b84cf1898d8e44f6.nq.gz
│   ├── dcc56baede23e3571b336625e695c466ab833a56.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed08224e22fb27eb18876595a542dcd3ad14bffc.nq.gz
│   ├── ee539bfa1e9c4509b929e7a86a03f098dd923515.nq.gz
│   ├── eef8d4538ffc8bd527805a09981cc6e0128d453b.nq.gz
│   ├── efbb4724c567bd5e0f524c8eb085854c0069ffc1.nq.gz
│   ├── f319c4627bd25d7004894181906a284b8b1c64cf.nq.gz
│   ├── fdfad9e3b5e7f706705bd850a3cf7d06ef6d8014.nq.gz
│   ├── feed3c838feea8d488abd0525d56b8522776625b.nq.gz
│   ├── ff05e63e0fc7f4b0fe0e3af6f12fa2f58ac2244c.nq.gz
│   └── ff23ab460b5c6c5de890e4f29145f1c762caa5dc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5e800d83a0f0ae14210410c02fd97e51e2e3f1d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[kayak/pypika](https://github.com/kayak/pypika)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
