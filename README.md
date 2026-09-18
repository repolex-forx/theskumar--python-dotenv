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
│   │   ├── 16e660d384b942b11879b44500afbbe021650448
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│   │   │   └── chunk-001.nq.gz
│   │   └── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 16e660d384b942b11879b44500afbbe021650448.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1.nq.gz
│   │   └── eaf2a9129ccec6febda0f741eb3bb852c3f947bd.nq.gz
│   └── repolex
│       ├── 16e660d384b942b11879b44500afbbe021650448
│       │   └── chunk-001.nq.gz
│       ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│       │   └── chunk-001.nq.gz
│       ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│       │   └── chunk-001.nq.gz
│       └── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d4d5e46b05ea81837fc93b177f51d6eb028ed4.nq.gz
│   ├── 02bdb7649e443807386e4fa0acb16bd38758179e.nq.gz
│   ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
│   ├── 057a1ae93d4d8950b3755a10be3ca7e1513b3d5f.nq.gz
│   ├── 0669eaedcbc8abd1ac83e65289ee989669269894.nq.gz
│   ├── 075a7af175ab5b278229529d1308d62a71d153a0.nq.gz
│   ├── 08b41cd3da975c2b563e1252d73614ac2044a3c4.nq.gz
│   ├── 1753fd89dc4e4b07cda8c482f81b244f4ae59342.nq.gz
│   ├── 1b362fddfbd7204449e47ba814606cd785d4273c.nq.gz
│   ├── 1c073471bbc0f0d8f66d99829f293a9fcaf935e7.nq.gz
│   ├── 1d6bf0b0138d684eaf208f21d4900b7b774e1a0a.nq.gz
│   ├── 227aa6797435a17dbc90a59b0b8160b3dd66d0dc.nq.gz
│   ├── 2aa31779c6b25b958576a06ec81aabdb423d67a9.nq.gz
│   ├── 2d63eec1705132d3250d6947f178c3378d5fa513.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 343fdb2375ac50ab6b859bab35e06f93a5ea1d3c.nq.gz
│   ├── 3977f55a8b1e94e67bab364885e502e6c89e3bc5.nq.gz
│   ├── 3a97119010ac82e15e917a69b7b8f9f59b5a4601.nq.gz
│   ├── 3d55d8994ff5202572ab4223ba148413d20b934f.nq.gz
│   ├── 3ddd13607cd40e65cfef42141b81179c6cad94b1.nq.gz
│   ├── 43386e5a1a12c2c3c278b3b971e7226641c7c912.nq.gz
│   ├── 449611172b4ac1f630f3e15e40d126b20228284c.nq.gz
│   ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
│   ├── 46d3c02e6ce63cb4640d54d6858e3ede472c4f77.nq.gz
│   ├── 47eec047aab59c7f40c8c8e00fd963400d349a41.nq.gz
│   ├── 48e5245a62a1fbbf06541f21b152f6463245872c.nq.gz
│   ├── 4961adce581e3660aa561b69e0a26f3d1afaa845.nq.gz
│   ├── 49840fa761e6681b6486bdc19ac65f8d4f066d43.nq.gz
│   ├── 4a9f28a1fddc4960eab30f80502557511d4779be.nq.gz
│   ├── 4e7edbbfe9d0d4c08659f12c469991a3fcb16b04.nq.gz
│   ├── 50703af0e07631d40351536df78e049d29b01be5.nq.gz
│   ├── 5b58c4c2de21253ef721ba66687e26efdbb41be1.nq.gz
│   ├── 5c0fb88dbeca0a46eed718b0988a81ec030f69c8.nq.gz
│   ├── 608e1b02a514ec49a48f7bd1b4927dd6b3f093a5.nq.gz
│   ├── 60d0365c9ce5e30eda412669a55ded0b8332be88.nq.gz
│   ├── 60effd2b6ee335cbce5314a5009706da629372cd.nq.gz
│   ├── 646b9e7b12fa1de311cbf4abe415061ce054d25a.nq.gz
│   ├── 66056f6cb3f038d9bae19dd17aa4d0e1b43c2e3f.nq.gz
│   ├── 660c5dccc2006d13cb3a794e207c038fbf42386c.nq.gz
│   ├── 667f2f26ff2182ecdfc5b809ba97a6cf1d1be13a.nq.gz
│   ├── 67668d53c8127cf66efe7092cc210ad35f2c3d85.nq.gz
│   ├── 69193de0cedb4fed05af60f3448acb119d5ff035.nq.gz
│   ├── 6a26350272f3c2a9811cf0408b10a4f9ba738a8c.nq.gz
│   ├── 6d1f25f855c820f14f610383d5a3fd7b6685e4d7.nq.gz
│   ├── 6df13fab9e4894fc7c3d516f0761942aed2525ac.nq.gz
│   ├── 6eda086b5e2d3aa85172d0f128d4317dbf2f764f.nq.gz
│   ├── 6f2b220323219450ef89f1031a36b10b0b81ace4.nq.gz
│   ├── 7082d97484e0187169dfffcee06388195c4905a9.nq.gz
│   ├── 735f14a3b425a3ee7d81e6e4aa5a2b04202925c4.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 78866a60615c66bf4a7c5b8900da25120471764b.nq.gz
│   ├── 7df727cd0ba5eb481a9e2568ffdd063bfce90314.nq.gz
│   ├── 7f4c631ba11786bceebd22591f91bd378d8b232c.nq.gz
│   ├── 7f8b71f3907734c148761bc23557882e6b2ee79d.nq.gz
│   ├── 86b0646675bc962dcceaa1bc047539ed9c171c2c.nq.gz
│   ├── 8a3762ad4137717ed5f18719030bd7c32c3debaf.nq.gz
│   ├── 8e6a7cf460f9bad21a2c0c1f1c10ccabbdf4f118.nq.gz
│   ├── 934b07a47fffc7d574b6afe08960522072349622.nq.gz
│   ├── 93b8bae252d6620c5cca5dd7f5a35e93f5517177.nq.gz
│   ├── 9582057abd9f45851d4d171c63fb41adc0319af5.nq.gz
│   ├── 960479bad1fbf0188c67fa9a1fbb1e980d4fe363.nq.gz
│   ├── 9c457e662491cc1de826cc22a733a289198811e2.nq.gz
│   ├── a08d6141d1c8f53c92d13ed2634e7ce953930f0e.nq.gz
│   ├── a2e0feca9caedca4a1d1dfba0c854a6f6eef1237.nq.gz
│   ├── a72da63050240d3e6179d898979c633fd304f961.nq.gz
│   ├── a82b376d2d72e66e1eb1b713f181f287dcea47a1.nq.gz
│   ├── a955fdae12bdf32b79296a3a6dd424aac3843677.nq.gz
│   ├── ab35b253fdd77d44010533454fe0d685a39fd443.nq.gz
│   ├── af7e1bc417979c20e01d55a089acbbf3aa20c491.nq.gz
│   ├── b062117376d6357c4f840e9d1568c59b019f75a3.nq.gz
│   ├── b09a710d48192988e36d014859db9380ada42776.nq.gz
│   ├── b6de171c332c63cc0c8c4b2205304187e63dfd23.nq.gz
│   ├── ba1234ce660ef062f926a443a5ec61f7a0c3c9b8.nq.gz
│   ├── ba77fa7f9afa9d21034a1d78b13ad77152b2153c.nq.gz
│   ├── bc86c944fe22d22f0a5a95996168c827d2876979.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── bf0d47e60d88426e5dbd23b2e0361c03911b755b.nq.gz
│   ├── c548aa396ff9951b1b691ae66431a96f7fc88e29.nq.gz
│   ├── c56ca62137055bf8f278e10942f3c9940625614d.nq.gz
│   ├── c68196d1cb0d5f0c6715cba4414a0b33fe2672c7.nq.gz
│   ├── cc6f0f0767334b816f307268f46662807e497c17.nq.gz
│   ├── d3d0199f3b2656e0437a61db05976c968426c29b.nq.gz
│   ├── d5959e1e58875b02fa50df67f112b2fc1af81aa0.nq.gz
│   ├── d691f0e75eec9115841806f504e27814dcfe2b50.nq.gz
│   ├── dc91d369363cf3f4429027488909d3d46f6e6a03.nq.gz
│   ├── dde24a0138999bd3876dfdfad02d5d93014e481c.nq.gz
│   ├── e27640434d3522dc6378dee0cea2c36f23e40550.nq.gz
│   ├── e3151bb997cc7f17a9325eb5b272a653552cdb86.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e92949ef97c1d36607d54707da62e06eb8284cf4.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── eb100b478cc1383eeaad53c6fbf39b9cf7c6b2be.nq.gz
│   ├── eb9d52042116bd34df05fcf529dd1b1a45a95865.nq.gz
│   ├── f01b3ad7a2d0d8970818032d6fbdffe9a8039cb3.nq.gz
│   ├── f3d43ca1027794a8c7547fd2867242e6e7747589.nq.gz
│   ├── f56378e90c3a7b11c07b8a72c7a20a59c9bb038e.nq.gz
│   ├── f61549ff01abf2359ac9d5e3ea696a35e2dc2b89.nq.gz
│   ├── f8baeac1c695692cdc9b16366fb4c1718ab2347f.nq.gz
│   ├── fac71bffa77a7d135ea02548dbd1fb6f8458924e.nq.gz
│   ├── fc309b48ace7aeeeb37708c30284bf4884f8c12c.nq.gz
│   └── fc86910d80bf2e40693d0764d0cc99e4f4e2f073.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 16e660d384b942b11879b44500afbbe021650448.nq.gz
│   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1.nq.gz
│   └── eaf2a9129ccec6febda0f741eb3bb852c3f947bd.nq.gz
├── filetree
│   ├── 16e660d384b942b11879b44500afbbe021650448.nq.gz
│   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1.nq.gz
│   └── eaf2a9129ccec6febda0f741eb3bb852c3f947bd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

21 directories, 126 files
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
*Parsed on 2026-09-18 by [repolex](https://repolex.ai)*
