# Repolex Knowledge Graph of theskumar/python-dotenv

RDF knowledge graph data for [theskumar/python-dotenv](https://github.com/theskumar/python-dotenv), parsed by [repolex](https://repolex.ai).

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
lexq download theskumar/python-dotenv
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36004e0e34be7665ff2b11a8a4005144f76f176d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   └── repolex
│       └── 36004e0e34be7665ff2b11a8a4005144f76f176d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d4d5e46b05ea81837fc93b177f51d6eb028ed4.nq.gz
│   ├── 02bdb7649e443807386e4fa0acb16bd38758179e.nq.gz
│   ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
│   ├── 1753fd89dc4e4b07cda8c482f81b244f4ae59342.nq.gz
│   ├── 1c073471bbc0f0d8f66d99829f293a9fcaf935e7.nq.gz
│   ├── 2aa31779c6b25b958576a06ec81aabdb423d67a9.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 3977f55a8b1e94e67bab364885e502e6c89e3bc5.nq.gz
│   ├── 3a97119010ac82e15e917a69b7b8f9f59b5a4601.nq.gz
│   ├── 3d55d8994ff5202572ab4223ba148413d20b934f.nq.gz
│   ├── 43386e5a1a12c2c3c278b3b971e7226641c7c912.nq.gz
│   ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
│   ├── 47eec047aab59c7f40c8c8e00fd963400d349a41.nq.gz
│   ├── 48e5245a62a1fbbf06541f21b152f6463245872c.nq.gz
│   ├── 49840fa761e6681b6486bdc19ac65f8d4f066d43.nq.gz
│   ├── 4a9f28a1fddc4960eab30f80502557511d4779be.nq.gz
│   ├── 4e7edbbfe9d0d4c08659f12c469991a3fcb16b04.nq.gz
│   ├── 50703af0e07631d40351536df78e049d29b01be5.nq.gz
│   ├── 60d0365c9ce5e30eda412669a55ded0b8332be88.nq.gz
│   ├── 646b9e7b12fa1de311cbf4abe415061ce054d25a.nq.gz
│   ├── 66056f6cb3f038d9bae19dd17aa4d0e1b43c2e3f.nq.gz
│   ├── 667f2f26ff2182ecdfc5b809ba97a6cf1d1be13a.nq.gz
│   ├── 6a26350272f3c2a9811cf0408b10a4f9ba738a8c.nq.gz
│   ├── 6d1f25f855c820f14f610383d5a3fd7b6685e4d7.nq.gz
│   ├── 6eda086b5e2d3aa85172d0f128d4317dbf2f764f.nq.gz
│   ├── 6f2b220323219450ef89f1031a36b10b0b81ace4.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 78866a60615c66bf4a7c5b8900da25120471764b.nq.gz
│   ├── 8a3762ad4137717ed5f18719030bd7c32c3debaf.nq.gz
│   ├── 93b8bae252d6620c5cca5dd7f5a35e93f5517177.nq.gz
│   ├── a08d6141d1c8f53c92d13ed2634e7ce953930f0e.nq.gz
│   ├── a2e0feca9caedca4a1d1dfba0c854a6f6eef1237.nq.gz
│   ├── ab35b253fdd77d44010533454fe0d685a39fd443.nq.gz
│   ├── b09a710d48192988e36d014859db9380ada42776.nq.gz
│   ├── ba1234ce660ef062f926a443a5ec61f7a0c3c9b8.nq.gz
│   ├── bc86c944fe22d22f0a5a95996168c827d2876979.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── bf0d47e60d88426e5dbd23b2e0361c03911b755b.nq.gz
│   ├── cc6f0f0767334b816f307268f46662807e497c17.nq.gz
│   ├── dc91d369363cf3f4429027488909d3d46f6e6a03.nq.gz
│   ├── dde24a0138999bd3876dfdfad02d5d93014e481c.nq.gz
│   ├── e27640434d3522dc6378dee0cea2c36f23e40550.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── eb100b478cc1383eeaad53c6fbf39b9cf7c6b2be.nq.gz
│   └── eb9d52042116bd34df05fcf529dd1b1a45a95865.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
├── filetree
│   └── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 56 files
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

[theskumar/python-dotenv](https://github.com/theskumar/python-dotenv)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
