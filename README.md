# Repolex Knowledge Graph of choffmeister/roboto-fontface-bower

RDF knowledge graph data for [choffmeister/roboto-fontface-bower](https://github.com/choffmeister/roboto-fontface-bower), parsed by [repolex](https://repolex.ai).

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
lexq download choffmeister/roboto-fontface-bower
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d2e5bf806cc43db44e0bdd1a4261c311c0c7e0f7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d2e5bf806cc43db44e0bdd1a4261c311c0c7e0f7.nq.gz
│   └── repolex
│       └── d2e5bf806cc43db44e0bdd1a4261c311c0c7e0f7
│           └── chunk-001.nq.gz
├── blob
│   ├── 005e9281a8e68bae3b991132389b55348443ff77.nq.gz
│   ├── 01eba140a96750bc16add12d523b40b08bbde51c.nq.gz
│   ├── 0cb65ba2200f59d67762a613f86449ab10852161.nq.gz
│   ├── 0d4c1b3ce1340c7df5b74e3c80f6999a093617ad.nq.gz
│   ├── 1019f3e9f2310bc7e034f877c70e21371a597020.nq.gz
│   ├── 11ef167fca243a3fbb121e72de121c5089593aa5.nq.gz
│   ├── 12f971c4fa6b55dc206fbe26386c6a081c56bf9e.nq.gz
│   ├── 16e8583b7eaa555ca2c1757202447ca4d6a7e2d3.nq.gz
│   ├── 18a3c41b173bdb0a0ee95718421142e0efb9354e.nq.gz
│   ├── 1c1a3c87f0d5d5dcf05c4b8351c2ab3c7765a377.nq.gz
│   ├── 20398aff31abb093abaafcc1d9bf5418ac437139.nq.gz
│   ├── 2d97f7276a21377f8c6da913b3f4e6282956cafe.nq.gz
│   ├── 2fb9b5f68c8ab60f7e1a069a718e82da15dad766.nq.gz
│   ├── 328f5bb042838089a40d0125728f9f47747d6c27.nq.gz
│   ├── 329ec9b5ce0e78341cca4b386d25e8a4db5ed91a.nq.gz
│   ├── 337d287116cd6540ec54f51b039a1c962dbcca7b.nq.gz
│   ├── 3603c5a46582ae6a8612e93271441e580ecc27f4.nq.gz
│   ├── 393b0c951f5b8e0a2706429f0b8eb71e542282f1.nq.gz
│   ├── 3d09e6c4123ec69a4aa698c3811b686e25bcde98.nq.gz
│   ├── 3fea88faeb68d07d80ec16e9806b81986c0b53d0.nq.gz
│   ├── 41186d078e1335226556d65203d80448077e97a1.nq.gz
│   ├── 45c9ef7328fb32ca5e2f22dce9f5c892e776f4d4.nq.gz
│   ├── 4e27813fed41c44a7882d4774494d73e5c184a7e.nq.gz
│   ├── 50d0a62be7db577d334f52843f8029a188f534f8.nq.gz
│   ├── 549d688d7d3916267054227f01de68bea77a0b18.nq.gz
│   ├── 549fb8acb26e345886199afa5d4f4e4356a68ad8.nq.gz
│   ├── 5865243a15c0ef845b1c1eec085f396c7b3f87b5.nq.gz
│   ├── 59f6eb4f944444e91a70122714c8ebe96ca73283.nq.gz
│   ├── 5cc51526a173ce0f28d99689e5b2a78c37c79cbf.nq.gz
│   ├── 5cf44001f3cd32e4bd5d1f7f306e0395dcaa2198.nq.gz
│   ├── 63559425ec2fbd21c534a0fb2368cfda8e1730f5.nq.gz
│   ├── 64caaa1201ed648047023093ae2e14bea55daa44.nq.gz
│   ├── 64ef2b6aa70b6805992968d4ce15b6ca9d85480d.nq.gz
│   ├── 67c4240666240b0ca04361deae309ea8d93de8e3.nq.gz
│   ├── 6a88805fedd13146d2c0c24ebda3170ce3c59ed5.nq.gz
│   ├── 6b30ea630d5259514afaaa6cad000336226c2fd8.nq.gz
│   ├── 6cb60000181dbd348963953ac8ac54afb46c63d5.nq.gz
│   ├── 6e0f56267035c2321ca6b590adcfc0fc93b7dc51.nq.gz
│   ├── 700c39629ebe192cfd9452fc9f7031914563175c.nq.gz
│   ├── 7059e23142aae3d8bad6067fc734a6cffec779c9.nq.gz
│   ├── 751e283bfe003c7d8ae604a7f575927bbc90a24e.nq.gz
│   ├── 76817cc76130c307947f116525b48a6afb870abc.nq.gz
│   ├── 7a0530c552b7eb21ce8b1e1ca7e96eaf5583ad90.nq.gz
│   ├── 7d1beda6d72f90666d85343906c2939144f18cc1.nq.gz
│   ├── 7db3855d56dca84c3af14fd51d8ec0d1132dadd2.nq.gz
│   ├── 7e131e082eb3ab514fdbabb856c7fdb5b816ceb9.nq.gz
│   ├── 7e2b90310f535f730dda913ea38873971926a46e.nq.gz
│   ├── 818233dbd6c804b5626c2f0ec5320cb58cbec178.nq.gz
│   ├── 82ca54b1c946d4dd9ca8e73bfb113b753d32f637.nq.gz
│   ├── 8870503f1a2cb92b84427684a6e44c0ba76fd2e2.nq.gz
│   ├── 8ae5e205dddb5c46100c4c2fac92e611b9dca85c.nq.gz
│   ├── 8c44987128ae80b03c4475447b407d1aa32b15fe.nq.gz
│   ├── 8e50ed079d8c37a3250959073053833fb9088324.nq.gz
│   ├── 8ef84bdbc510dbe0a4c6aa3b737ec96cdecf87e0.nq.gz
│   ├── 96b86a0dd7a43f1f23ff8ff8f079595f5bbacc48.nq.gz
│   ├── 96c1986f01459bc3b7ca8e18fc06785e5e35dc45.nq.gz
│   ├── 982b7db13396741b54cfbf4641a34f0f5c8a6229.nq.gz
│   ├── 9834cc8ce0515640602d4d07f76f9f778e101d0d.nq.gz
│   ├── 98809758868e4abd6b2fccfd51255770ee06c966.nq.gz
│   ├── 9a0064ec27e069931227a628e8ed899f3dda2c73.nq.gz
│   ├── a6de40bc4319f0a1c9c9f254ee16dce1344a1813.nq.gz
│   ├── aca27e9d13da1102b5566bb06335dbf9b973a011.nq.gz
│   ├── afe8f4a11daa623ffcd2a50f1f4878522a50861f.nq.gz
│   ├── b11c823ccfac5c40bb19b0d5b78f44ebe2613737.nq.gz
│   ├── b1ddac3fb57a0ae26f75f2928cb22831635c3121.nq.gz
│   ├── b677fc82434c53c6d82f0bb8abd562af639f9ee6.nq.gz
│   ├── b88053700aa2ef73c79e2fed405f9b4255c43297.nq.gz
│   ├── b97efeaf5b7906822166ce442a9497e02a680e48.nq.gz
│   ├── b9e99185c8300c786fa77a0490fefdd26ab2e99e.nq.gz
│   ├── ba70c2a39626eb507130fcdf8e6ec244b8db95b5.nq.gz
│   ├── bc1d7326270d70b58cfdf5e9855716495d338198.nq.gz
│   ├── be9f6965b637310bfb6b58154c53f1ef77c8e8ff.nq.gz
│   ├── bf6ebbaf4ae0aa40656129477c773c91b50f781b.nq.gz
│   ├── bf9965204f08c10bcc201fff108b85b75ff552f1.nq.gz
│   ├── c68feed201746aa880bec7cff92e918bb57616bc.nq.gz
│   ├── c8f170b37b55992d237cc7b7b9420baff7d4fd85.nq.gz
│   ├── ca904144d49fd26fd3f5b52ed7130a343008c4f5.nq.gz
│   ├── ca9ae9a4f4b503e00a0fb035780241945d67e0e1.nq.gz
│   ├── cf21729c6b35c358fae677bc20d76f3e388bd450.nq.gz
│   ├── d148dd4ba9bc522b8c5cd160aa0edca4504232b5.nq.gz
│   ├── d3373781a93d7acd3f3f175b48a67d207cac3bcd.nq.gz
│   ├── d52828cc0132980297393b0b4ab9798365233a1b.nq.gz
│   ├── d869162d303b2e5836c775aa62c02584bd535acf.nq.gz
│   ├── ddbf4a9250eac16256d72eabf8db24448d36be66.nq.gz
│   ├── de4a4e7b6b3ce77b07b382c59da4992e32b101b0.nq.gz
│   ├── df3c3f4472aee1f12d289f0a69945ec4bbb974a4.nq.gz
│   ├── e04c79303961e548c63e2f4e64166e13dd642845.nq.gz
│   ├── e11870bc45e7639d2112f9f57900c0368b8cefb9.nq.gz
│   ├── e1cee8f4a78f14a410e06815d60e0ab27d63f06a.nq.gz
│   ├── e3a3f63fe097579b976d6d0c32ec1a15624c7afb.nq.gz
│   ├── e75fa793bcfea869d97b6ab558c119658e1408a4.nq.gz
│   ├── e7f173b7edd23250aa98f5dbe26753c070ee0e70.nq.gz
│   ├── e9257a93f1270150fdd4ff45f48880b045428514.nq.gz
│   ├── ea90d717144c054a36953d52c7458fc1edbffee3.nq.gz
│   ├── ed2948ba7920c5bf6cbcaa52484eb8cac8dc2b34.nq.gz
│   ├── ef47a4f7aae8e2af22f59319feb91d4325b17a9a.nq.gz
│   ├── f2a9e06c0c165ac92474ef3436965d79e9c7fcbe.nq.gz
│   ├── f2c76e5bda18a9842e24cd60d8787257da215ca7.nq.gz
│   ├── f2fd7d2d2331ab03d5bb1dd08f68298d13a9946c.nq.gz
│   ├── f815f63f99da80ad2be69e4021023ec2981eaea0.nq.gz
│   ├── f831abd0ced312b9b1b78dd5f77579cda86adbf8.nq.gz
│   ├── f9cc2bd5cea3e795ce12f23780f4e52a41a04e43.nq.gz
│   └── fa48f40358a4c71b60eec970654e926133306295.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d2e5bf806cc43db44e0bdd1a4261c311c0c7e0f7.nq.gz
├── filetree
│   └── d2e5bf806cc43db44e0bdd1a4261c311c0c7e0f7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 113 files
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

[choffmeister/roboto-fontface-bower](https://github.com/choffmeister/roboto-fontface-bower)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
