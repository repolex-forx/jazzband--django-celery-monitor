# Repolex Knowledge Graph of jazzband/django-celery-monitor

RDF knowledge graph data for [jazzband/django-celery-monitor](https://github.com/jazzband/django-celery-monitor), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-celery-monitor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2b86acddc4cf2e65b63c8c7b2db7ecaa037b4b75
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2b86acddc4cf2e65b63c8c7b2db7ecaa037b4b75
│           └── chunk-001.nq.gz
├── blob
│   ├── 01be9daa7f9cfc218130661aacf891c2cd78f877.nq.gz
│   ├── 068d20b876e28d2c41bba29771d03b758ed887d4.nq.gz
│   ├── 08f3a6c9f1f362e8007aa5150f493e52264f241b.nq.gz
│   ├── 0a8d3da39da77ba53c53b7670594db00a1b1ffa9.nq.gz
│   ├── 1170b2b1007232c00ff6d5773cae2b833cea5647.nq.gz
│   ├── 1969c70e3b92da2005efcd452464aa6ea6389dd5.nq.gz
│   ├── 1de64b7a6172c3817d250d4d4f467711b848edf0.nq.gz
│   ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
│   ├── 2d21d5ae2bfa7b46f83766090bf7947e82986a32.nq.gz
│   ├── 33fca839216450de18c9b499529451a35062e65e.nq.gz
│   ├── 36ecb772b6d1935adbdda8b7fa28126ef37a63c7.nq.gz
│   ├── 40e414dfba692fd45dfd76df96908c262d5ff5e0.nq.gz
│   ├── 5399b69f43c5a04ceec13d924425496731d1fbf6.nq.gz
│   ├── 552af77342a918dd0bd6109b00e1dc960b17dcbd.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5a23899e5c11bf7a4dee12a1297479d68c95560c.nq.gz
│   ├── 644b8ba95d3b7bff1676f8e81f7d7c3632d7539d.nq.gz
│   ├── 649280b6d4da12cf01f61f1caa77ebd05d56c047.nq.gz
│   ├── 652f7516e6a835d125f74598820d076e982e94b8.nq.gz
│   ├── 654c0aeda6afd108fd49a7c1074035916f77d7da.nq.gz
│   ├── 67770b4c0f97271acb56022a65d22cddb1e22271.nq.gz
│   ├── 6795fc6b73deb49f773bc3a3091697b8eba6c11b.nq.gz
│   ├── 6b79c0b4cf329468fc5fdce0daa1b00dc3a6166c.nq.gz
│   ├── 6d6a34ce4ce71239bf1ac94bcbe0fc837b03234b.nq.gz
│   ├── 739912fb7ef92a8fd626e886bec1f6ca49c9d483.nq.gz
│   ├── 75547438f93093e6ebbb9f68295c5500631b04d9.nq.gz
│   ├── 775b6fc6a691a085e3995d03987143cf6fa85156.nq.gz
│   ├── 7ec8e7df2a42f336f9ad3833772f3a385f07f682.nq.gz
│   ├── 8324e6f9d90c6c4d01d308152283d46d1da0e183.nq.gz
│   ├── 89978f0bbaaa50362dc18e4cf8f9db8fed223c9d.nq.gz
│   ├── 8a34779aba8533fedae2ea30128861defffec44e.nq.gz
│   ├── 95e407cb9507a82db90020240f8a0d8d8f769fe7.nq.gz
│   ├── a03809cd4b0809294a1457abc14a9828e774ff07.nq.gz
│   ├── a2674c3686b16d2c97c823d7c24e94a583462f7f.nq.gz
│   ├── a5ae199a1c10b4a7e08b71dcb79115f5a91924f4.nq.gz
│   ├── a6656747226d029cdac1b115c7be29472b49fbcc.nq.gz
│   ├── b2806bb4fdcf5471bfae0d17a5489a43f5cd2dc7.nq.gz
│   ├── b46838f7c081de2cca397d42149ecc75b6ba6eb1.nq.gz
│   ├── b4f4c6aa4475e46ebe1ed55a6f2811e385059703.nq.gz
│   ├── b5605cb50c2764c098b4ca64bc56ee1a2ce5eb2b.nq.gz
│   ├── b7e0aec5beb18d2adbc31edd560f4b63efb8439a.nq.gz
│   ├── c75c448bbd0f8d9076d528dd2b203fa21d35b19e.nq.gz
│   ├── ca6c9e26f2ec8b1c7876465ffd7ef410df3e49c7.nq.gz
│   ├── d07cdd77d01ef4a421d1b02c7963d15cfec34109.nq.gz
│   ├── d35bac495261342980b088e43cb3e24b7d0b1a89.nq.gz
│   ├── d5624b41deb52207ea2e476a07212dbf5a69531e.nq.gz
│   ├── d5be671c39c0b77ee83258658469bee7a1aabb8b.nq.gz
│   ├── da4465e8afadc93d2686beaaff020e1df342eca1.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e92a1251abd5a2692d3c88bf2d2927490a174b91.nq.gz
│   ├── ebe7fe9fb73bb5e5b92871a57357f2dcdcb926f2.nq.gz
│   ├── f16149fc5e59d95aed603e8cd1d1f486c723ef69.nq.gz
│   ├── f50e73db6e4d1fb2d1259aaef09cdffd4a03d07d.nq.gz
│   └── fc3af324a4ec2b5fc548aa6d22de7eb54bfda44a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2b86acddc4cf2e65b63c8c7b2db7ecaa037b4b75.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[jazzband/django-celery-monitor](https://github.com/jazzband/django-celery-monitor)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
