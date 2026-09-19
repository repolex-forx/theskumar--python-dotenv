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
│   │   ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23
│   │   │   └── chunk-001.nq.gz
│   │   ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53cee8c7fb2fe1252606202ec9e2746651df738c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a02ef5a1034d66338811757df07a113a1169af6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 784102284471252f418e797c1874a00063426210
│   │   │   └── chunk-001.nq.gz
│   │   ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938
│   │   │   └── chunk-001.nq.gz
│   │   ├── b043829d810b4bf46ebb4addcf0e8ca97dff3bdd
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6fe193b4c296a24d1973b741c19ee8b0066bc86
│   │   │   └── chunk-001.nq.gz
│   │   ├── b96db46dc8b66adba8afcfd3ec3b8ed2b4d6cefe
│   │   │   └── chunk-001.nq.gz
│   │   ├── cfca79a3cd384710c98651da79d66d964e0a65d1
│   │   │   └── chunk-001.nq.gz
│   │   ├── d0684d1c092fb6a9a208a09d43f02e4876ee8196
│   │   │   └── chunk-001.nq.gz
│   │   ├── d6c0b9638349a7dd605d60ee555ff60421c1a594
│   │   │   └── chunk-001.nq.gz
│   │   ├── e13d957bf48224453c5d9d9a7a83a13b999e0196
│   │   │   └── chunk-001.nq.gz
│   │   ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8
│   │   │   └── chunk-001.nq.gz
│   │   ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│   │   │   └── chunk-001.nq.gz
│   │   └── fc138ce8a430b758f4f2c89bc8104f259e2cba38
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 16e660d384b942b11879b44500afbbe021650448.nq.gz
│   │   ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23.nq.gz
│   │   ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   │   ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6.nq.gz
│   │   ├── 53cee8c7fb2fe1252606202ec9e2746651df738c.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1.nq.gz
│   │   ├── 6a02ef5a1034d66338811757df07a113a1169af6.nq.gz
│   │   ├── 784102284471252f418e797c1874a00063426210.nq.gz
│   │   ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938.nq.gz
│   │   ├── b043829d810b4bf46ebb4addcf0e8ca97dff3bdd.nq.gz
│   │   ├── b6fe193b4c296a24d1973b741c19ee8b0066bc86.nq.gz
│   │   ├── b96db46dc8b66adba8afcfd3ec3b8ed2b4d6cefe.nq.gz
│   │   ├── cfca79a3cd384710c98651da79d66d964e0a65d1.nq.gz
│   │   ├── d0684d1c092fb6a9a208a09d43f02e4876ee8196.nq.gz
│   │   ├── d6c0b9638349a7dd605d60ee555ff60421c1a594.nq.gz
│   │   ├── e13d957bf48224453c5d9d9a7a83a13b999e0196.nq.gz
│   │   ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8.nq.gz
│   │   ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd.nq.gz
│   │   └── fc138ce8a430b758f4f2c89bc8104f259e2cba38.nq.gz
│   └── repolex
│       ├── 16e660d384b942b11879b44500afbbe021650448
│       │   └── chunk-001.nq.gz
│       ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23
│       │   └── chunk-001.nq.gz
│       ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf
│       │   └── chunk-001.nq.gz
│       ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│       │   └── chunk-001.nq.gz
│       ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6
│       │   └── chunk-001.nq.gz
│       ├── 53cee8c7fb2fe1252606202ec9e2746651df738c
│       │   └── chunk-001.nq.gz
│       ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│       │   └── chunk-001.nq.gz
│       ├── 6a02ef5a1034d66338811757df07a113a1169af6
│       │   └── chunk-001.nq.gz
│       ├── 784102284471252f418e797c1874a00063426210
│       │   └── chunk-001.nq.gz
│       ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938
│       │   └── chunk-001.nq.gz
│       ├── b043829d810b4bf46ebb4addcf0e8ca97dff3bdd
│       │   └── chunk-001.nq.gz
│       ├── b6fe193b4c296a24d1973b741c19ee8b0066bc86
│       │   └── chunk-001.nq.gz
│       ├── b96db46dc8b66adba8afcfd3ec3b8ed2b4d6cefe
│       │   └── chunk-001.nq.gz
│       ├── cfca79a3cd384710c98651da79d66d964e0a65d1
│       │   └── chunk-001.nq.gz
│       ├── d0684d1c092fb6a9a208a09d43f02e4876ee8196
│       │   └── chunk-001.nq.gz
│       ├── d6c0b9638349a7dd605d60ee555ff60421c1a594
│       │   └── chunk-001.nq.gz
│       ├── e13d957bf48224453c5d9d9a7a83a13b999e0196
│       │   └── chunk-001.nq.gz
│       ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8
│       │   └── chunk-001.nq.gz
│       ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│       │   └── chunk-001.nq.gz
│       └── fc138ce8a430b758f4f2c89bc8104f259e2cba38
│           └── chunk-001.nq.gz
└── blob
    ├── 0025c946293d288a79a4464d22a0c4cf38d6138d.nq.gz
    ├── 00d4d5e46b05ea81837fc93b177f51d6eb028ed4.nq.gz
    ├── 0206316fb48a20828186150e2632405560950a4d.nq.gz
    ├── 02bdb7649e443807386e4fa0acb16bd38758179e.nq.gz
    ├── 02dc0695afda6bd24c3fc139557ea4a51c7659ee.nq.gz
    ├── 02dc9d96149b89424d03ed13b58a02cd94f3630d.nq.gz
    ├── 03e6644f0b418a2ee6d1d4f755ca063f76eb628f.nq.gz
    ├── 0480593284c5289bbf94965172c6dd36e4094c27.nq.gz
    ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
    ├── 057a1ae93d4d8950b3755a10be3ca7e1513b3d5f.nq.gz
    ├── 05d377a943a1af24ba1c26b6dee5e5bfb5eddbe3.nq.gz
    ├── 0669eaedcbc8abd1ac83e65289ee989669269894.nq.gz
    ├── 06ad2dd97706d02dd50796f62e52285798a1f186.nq.gz
    ├── 075a7af175ab5b278229529d1308d62a71d153a0.nq.gz
    ├── 08b41cd3da975c2b563e1252d73614ac2044a3c4.nq.gz
    ├── 09d6103458b20fa028128a15467a9a3df4283f3f.nq.gz
    ├── 0f168618fe21ff1c35e9e8c1dda67941e8a0933a.nq.gz
    ├── 0f52ac2345693cde229e79d5ccfabc83af3055e6.nq.gz
    ├── 116d97facf917aa055022cef2716abd6f3af16f5.nq.gz
    ├── 11ac8e1a9e33877e76a433e295c838877be17fcb.nq.gz
    ├── 127d46f08d6c652cb2e23a4f7cb37d1528eb1b39.nq.gz
    ├── 1317d7554a122e7cc9d78efe6699a25fb8b7c9bd.nq.gz
    ├── 13e2791c36143fed5dbd36b8910bff593b725c15.nq.gz
    ├── 14f10d378392a34552c268501f3b0802aceb6b32.nq.gz
    ├── 16f22d2c4a6accc4ec8cd9b7a89296a06ac74260.nq.gz
    ├── 172047aca727e94fb55d44f6952b2224bbe30601.nq.gz
    ├── 1753fd89dc4e4b07cda8c482f81b244f4ae59342.nq.gz
    ├── 1848d602bb7f886df48868827679d5f3eba71939.nq.gz
    ├── 1b362fddfbd7204449e47ba814606cd785d4273c.nq.gz
    ├── 1c073471bbc0f0d8f66d99829f293a9fcaf935e7.nq.gz
    ├── 1d6bf0b0138d684eaf208f21d4900b7b774e1a0a.nq.gz
    ├── 20ac61ba6f89fcbef1b5df7c1fff2491e3dd96c3.nq.gz
    ├── 223476fe4093894f66eef47b8835f1311f4a3d00.nq.gz
    ├── 227aa6797435a17dbc90a59b0b8160b3dd66d0dc.nq.gz
    ├── 23404e708016ac5c1aad5b961c3330e95b9a5b3b.nq.gz
    ├── 24a825287a4f8fad45ce7a9eec0f6c6b238caa1f.nq.gz
    ├── 27063ca2f546334904a833dc36880a477756e4da.nq.gz
    ├── 2865cf854ed8a09afaf05d04677c72111589816b.nq.gz
    ├── 29e38757f2985a545c7c66e80725fe573bc696ee.nq.gz
    ├── 2aa31779c6b25b958576a06ec81aabdb423d67a9.nq.gz
    ├── 2c93cbd015c21be5507c18138003542743ab8939.nq.gz
    ├── 2cd63024fa715a8ddd3c92d855e4396a1f0bec35.nq.gz
    ├── 2d63eec1705132d3250d6947f178c3378d5fa513.nq.gz
    ├── 2dd6186486ac44e0525b6eb9734d86560e226b5f.nq.gz
    ├── 2f78c0d01a9d77971711bed9206a0efe02229652.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 331965df472db0682eca49958245059f9e9e11fd.nq.gz
    ├── 33ae148531288a108d78abeea4532c1663ec7432.nq.gz
    ├── 343fdb2375ac50ab6b859bab35e06f93a5ea1d3c.nq.gz
    ├── 3512d10118af91691780750180d268c1f6ecccb8.nq.gz
    ├── 364fc24d605faf439277cdad1d81b4c44bb4be13.nq.gz
    ├── 39302b21e2bc313a767c814ae1fa1cc7f2a5b642.nq.gz
    ├── 39372feec020715a19e52cb689b4a1ee7a37fe19.nq.gz
    ├── 396cdf61271f89f6d54207849bf6b65b7b804758.nq.gz
    ├── 3977f55a8b1e94e67bab364885e502e6c89e3bc5.nq.gz
    ├── 398bd49ac6abb40e15219736ce983d8c754eded6.nq.gz
    ├── 3a3d059b36169ce7ee09a67a435be11663d9b58f.nq.gz
    ├── 3a97119010ac82e15e917a69b7b8f9f59b5a4601.nq.gz
    ├── 3d55d8994ff5202572ab4223ba148413d20b934f.nq.gz
    ├── 3ddd13607cd40e65cfef42141b81179c6cad94b1.nq.gz
    ├── 3fc452c55b1ada0cee3e219e64ac531973304957.nq.gz
    ├── 3fefd1f082444973149616f8271892b2f89431a3.nq.gz
    ├── 43386e5a1a12c2c3c278b3b971e7226641c7c912.nq.gz
    ├── 449611172b4ac1f630f3e15e40d126b20228284c.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 46d3c02e6ce63cb4640d54d6858e3ede472c4f77.nq.gz
    ├── 47eec047aab59c7f40c8c8e00fd963400d349a41.nq.gz
    ├── 4828dfc291c4871e749a8879dd14bfb78aa85312.nq.gz
    ├── 483f6d404f4bd267de876d28ac07925783cc1d44.nq.gz
    ├── 48cecdce9c20b7311840ffc5ad331afd6f303e7b.nq.gz
    ├── 48e5245a62a1fbbf06541f21b152f6463245872c.nq.gz
    ├── 4961adce581e3660aa561b69e0a26f3d1afaa845.nq.gz
    ├── 49840fa761e6681b6486bdc19ac65f8d4f066d43.nq.gz
    ├── 49e1399f4d69990ca85fc09277925202e071fa99.nq.gz
    ├── 4a9f28a1fddc4960eab30f80502557511d4779be.nq.gz
    ├── 4c1ca3c80986ea8ec44ff096e50770c7e4f06ab8.nq.gz
    ├── 4d49c291347b358834d9fe1f7d37c100e217e0dc.nq.gz
    ├── 4e7edbbfe9d0d4c08659f12c469991a3fcb16b04.nq.gz
    ├── 50703af0e07631d40351536df78e049d29b01be5.nq.gz
    ├── 5135ae4f34aa011b16166987bae636c0d5ea972c.nq.gz
    ├── 530ab129059c363134e0a14b3c5b03031ed16455.nq.gz
    ├── 53ba5a074916579e8e144f93418bf0ee5e040929.nq.gz
    ├── 541ac5ee486558203779ad8233b3dab0b3d3b025.nq.gz
    ├── 56a7a94c4763128c2ab357397996c3bbdf1f4dbb.nq.gz
    ├── 580540719597481c52a984d1de2cac80780f4877.nq.gz
    ├── 58a23f3dfdf5fbb5b4bdda97a20d0a99541ed8ad.nq.gz
    ├── 5a313cc7ef4af1ec1829732ee059788808655b76.nq.gz
    ├── 5b58c4c2de21253ef721ba66687e26efdbb41be1.nq.gz
    ├── 5becc17c04a9e3ad1c2a15f53252b7bb5a7517e7.nq.gz
    ├── 5c0fb88dbeca0a46eed718b0988a81ec030f69c8.nq.gz
    ├── 5c4105cd39cc4181c773f21fc007b4d120968c8b.nq.gz
    ├── 5c9aeaf92eaca2afd6cfdd9a288195eb718e96be.nq.gz
    ├── 5cb1cdfa65b8684c4e39dcbfc4684ed062c10388.nq.gz
    ├── 5da48f0a097b376694aa089211851ced977056ce.nq.gz
    ├── 5f4bb0b3459b4ba19a73bd0b96373c042934868e.nq.gz
    ├── 608e1b02a514ec49a48f7bd1b4927dd6b3f093a5.nq.gz
    ├── 60d0365c9ce5e30eda412669a55ded0b8332be88.nq.gz
    ├── 60effd2b6ee335cbce5314a5009706da629372cd.nq.gz
    ├── 646b9e7b12fa1de311cbf4abe415061ce054d25a.nq.gz
    ├── 64b4431fbb2e9dbcc577a812a940b46a995047d9.nq.gz
    ├── 65ead46155f568a197a16b64c6335f1f28cda9a6.nq.gz
    ├── 66056f6cb3f038d9bae19dd17aa4d0e1b43c2e3f.nq.gz
    ├── 660c5dccc2006d13cb3a794e207c038fbf42386c.nq.gz
    ├── 667f2f26ff2182ecdfc5b809ba97a6cf1d1be13a.nq.gz
    ├── 67668d53c8127cf66efe7092cc210ad35f2c3d85.nq.gz
    ├── 6849410aae0a8010e76d5f0a44ced13d750b0989.nq.gz
    ├── 68503d452c7331976d375fb5b796f03f5d36df92.nq.gz
    ├── 69193de0cedb4fed05af60f3448acb119d5ff035.nq.gz
    ├── 6a26350272f3c2a9811cf0408b10a4f9ba738a8c.nq.gz
    ├── 6a726d853bc5b05a092d56af6a9ff05cfe4a7b7a.nq.gz
    ├── 6b2b2bbb2e0f3ac043e74f2b7425d0b69b8f2b50.nq.gz
    ├── 6b9458d273588b9bc54e4ba22bcb4e965adc8ac7.nq.gz
    ├── 6d1f25f855c820f14f610383d5a3fd7b6685e4d7.nq.gz
    ├── 6df13fab9e4894fc7c3d516f0761942aed2525ac.nq.gz
    ├── 6eda086b5e2d3aa85172d0f128d4317dbf2f764f.nq.gz
    ├── 6f2b220323219450ef89f1031a36b10b0b81ace4.nq.gz
    ├── 7082d97484e0187169dfffcee06388195c4905a9.nq.gz
    ├── 735f14a3b425a3ee7d81e6e4aa5a2b04202925c4.nq.gz
    ├── 7374d05ca53fa443d43aad06813e0f041ee66c8a.nq.gz
    ├── 758fbb46e8b52bf454de466f86c4b2458512c6a3.nq.gz
    ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
    ├── 7666da098c2f28e0b0853dd48c054d6986102cec.nq.gz
    ├── 76f24586d40f7093f689ab23fefce32961cb78be.nq.gz
    ├── 78866a60615c66bf4a7c5b8900da25120471764b.nq.gz
    ├── 78e43e9b10b7e7fd539e86444a1dc6326cfa3c42.nq.gz
    ├── 7a9ed7e5e794171a9e31835b32971a38df4e92dc.nq.gz
    ├── 7aa4cfd9e06ec0c80e4ff77a54d244670d321477.nq.gz
    ├── 7bc5428572d9e0ca221146484b42cd321d930fe5.nq.gz
    ├── 7df727cd0ba5eb481a9e2568ffdd063bfce90314.nq.gz
    ├── 7f1b13d6c4adbf5cff1adb04a985af34fad965de.nq.gz
    ├── 7f4c631ba11786bceebd22591f91bd378d8b232c.nq.gz
    ├── 7f8b71f3907734c148761bc23557882e6b2ee79d.nq.gz
    ├── 7fbd24f895a3fb7331c685e5a9b64c5eba00783c.nq.gz
    ├── 82c73ba1feb6e822ea13e9a1ca42571937270d06.nq.gz
    ├── 85076147995464f3e77e0c156928c0aa8fe43df3.nq.gz
    ├── 86b0646675bc962dcceaa1bc047539ed9c171c2c.nq.gz
    ├── 8983bf134660bbaff999ba49e06a11da6e340033.nq.gz
    ├── 89b5d30e8c41b8e3b5ee1b42cc2409d2aa48f946.nq.gz
    ├── 89fc6434aba6a6e95bd5511d08f79a51835c7148.nq.gz
    └── 8a3762ad4137717ed5f18719030bd7c32c3debaf.nq.gz

46 directories, 200 files
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
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
