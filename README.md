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
│   │   ├── 20db722a8c3329018679f8bbdcd47b64e86834ce
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2a87fc7399ae5bce7bad4c8f7e5747aee801b831
│   │   │   └── chunk-001.nq.gz
│   │   ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3637b3e114b9a3084457594ccfa3cb3e6d3d4ee4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4953de1c154b979d11cb694cd6a972bbf97e4424
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4e76e82e539842d00be0d6d02062a81b8f58675d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53cee8c7fb2fe1252606202ec9e2746651df738c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5e839d4f545d8d8c078e7aa8b3e3369c127251c4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a02ef5a1034d66338811757df07a113a1169af6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 784102284471252f418e797c1874a00063426210
│   │   │   └── chunk-001.nq.gz
│   │   ├── 915f7940e34f3238b504dc2124d81016dbac4f9c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938
│   │   │   └── chunk-001.nq.gz
│   │   ├── a4d39f7cd852c0aabee3b0dc5d9403496406034e
│   │   │   └── chunk-001.nq.gz
│   │   ├── a66b5d1d444718ac220fac28e1a3f962c4773972
│   │   │   └── chunk-001.nq.gz
│   │   ├── ab4e1a0d372b74e9c4eda6682944df6b336a46ac
│   │   │   └── chunk-001.nq.gz
│   │   ├── ae1f1a906feddb23f4fa05c968c52df99c487ead
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
│   │   ├── d143c897d61ba75cf49454b8174aaaf6c5580272
│   │   │   └── chunk-001.nq.gz
│   │   ├── d4b170a15319f81fe6d3493497a2fff9273e50aa
│   │   │   └── chunk-001.nq.gz
│   │   ├── d67735509fb38545be9449201cf26ae9fd10e69a
│   │   │   └── chunk-001.nq.gz
│   │   ├── d6c0b9638349a7dd605d60ee555ff60421c1a594
│   │   │   └── chunk-001.nq.gz
│   │   ├── e13d957bf48224453c5d9d9a7a83a13b999e0196
│   │   │   └── chunk-001.nq.gz
│   │   ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8
│   │   │   └── chunk-001.nq.gz
│   │   ├── e5d68ff94f223b0a1fbee15dfdb6a6b6ff3f809f
│   │   │   └── chunk-001.nq.gz
│   │   ├── e67796720403941538f826463f9fc610a431e899
│   │   │   └── chunk-001.nq.gz
│   │   ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│   │   │   └── chunk-001.nq.gz
│   │   ├── ef800f85d0b0757e31a7f448e2cd21209adbb65a
│   │   │   └── chunk-001.nq.gz
│   │   └── fc138ce8a430b758f4f2c89bc8104f259e2cba38
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 16e660d384b942b11879b44500afbbe021650448.nq.gz
│   │   ├── 20db722a8c3329018679f8bbdcd47b64e86834ce.nq.gz
│   │   ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23.nq.gz
│   │   ├── 2a87fc7399ae5bce7bad4c8f7e5747aee801b831.nq.gz
│   │   ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf.nq.gz
│   │   ├── 36004e0e34be7665ff2b11a8a4005144f76f176d.nq.gz
│   │   ├── 3637b3e114b9a3084457594ccfa3cb3e6d3d4ee4.nq.gz
│   │   ├── 4953de1c154b979d11cb694cd6a972bbf97e4424.nq.gz
│   │   ├── 4e76e82e539842d00be0d6d02062a81b8f58675d.nq.gz
│   │   ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6.nq.gz
│   │   ├── 53cee8c7fb2fe1252606202ec9e2746651df738c.nq.gz
│   │   ├── 5bf882241c607445bf02cf5b241535d62e2b99c1.nq.gz
│   │   ├── 5e839d4f545d8d8c078e7aa8b3e3369c127251c4.nq.gz
│   │   ├── 6a02ef5a1034d66338811757df07a113a1169af6.nq.gz
│   │   ├── 784102284471252f418e797c1874a00063426210.nq.gz
│   │   ├── 915f7940e34f3238b504dc2124d81016dbac4f9c.nq.gz
│   │   ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938.nq.gz
│   │   ├── a4d39f7cd852c0aabee3b0dc5d9403496406034e.nq.gz
│   │   ├── a66b5d1d444718ac220fac28e1a3f962c4773972.nq.gz
│   │   ├── ab4e1a0d372b74e9c4eda6682944df6b336a46ac.nq.gz
│   │   ├── ae1f1a906feddb23f4fa05c968c52df99c487ead.nq.gz
│   │   ├── b043829d810b4bf46ebb4addcf0e8ca97dff3bdd.nq.gz
│   │   ├── b6fe193b4c296a24d1973b741c19ee8b0066bc86.nq.gz
│   │   ├── b96db46dc8b66adba8afcfd3ec3b8ed2b4d6cefe.nq.gz
│   │   ├── cfca79a3cd384710c98651da79d66d964e0a65d1.nq.gz
│   │   ├── d0684d1c092fb6a9a208a09d43f02e4876ee8196.nq.gz
│   │   ├── d143c897d61ba75cf49454b8174aaaf6c5580272.nq.gz
│   │   ├── d4b170a15319f81fe6d3493497a2fff9273e50aa.nq.gz
│   │   ├── d67735509fb38545be9449201cf26ae9fd10e69a.nq.gz
│   │   ├── d6c0b9638349a7dd605d60ee555ff60421c1a594.nq.gz
│   │   ├── e13d957bf48224453c5d9d9a7a83a13b999e0196.nq.gz
│   │   ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8.nq.gz
│   │   ├── e5d68ff94f223b0a1fbee15dfdb6a6b6ff3f809f.nq.gz
│   │   ├── e67796720403941538f826463f9fc610a431e899.nq.gz
│   │   ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd.nq.gz
│   │   ├── ef800f85d0b0757e31a7f448e2cd21209adbb65a.nq.gz
│   │   └── fc138ce8a430b758f4f2c89bc8104f259e2cba38.nq.gz
│   └── repolex
│       ├── 16e660d384b942b11879b44500afbbe021650448
│       │   └── chunk-001.nq.gz
│       ├── 20db722a8c3329018679f8bbdcd47b64e86834ce
│       │   └── chunk-001.nq.gz
│       ├── 2471a5af1027acca27f8d326ddb97b1d43a2ba23
│       │   └── chunk-001.nq.gz
│       ├── 2a87fc7399ae5bce7bad4c8f7e5747aee801b831
│       │   └── chunk-001.nq.gz
│       ├── 303423864ae00f8d5f21cb39d6421a7d775a3daf
│       │   └── chunk-001.nq.gz
│       ├── 36004e0e34be7665ff2b11a8a4005144f76f176d
│       │   └── chunk-001.nq.gz
│       ├── 3637b3e114b9a3084457594ccfa3cb3e6d3d4ee4
│       │   └── chunk-001.nq.gz
│       ├── 4953de1c154b979d11cb694cd6a972bbf97e4424
│       │   └── chunk-001.nq.gz
│       ├── 4e76e82e539842d00be0d6d02062a81b8f58675d
│       │   └── chunk-001.nq.gz
│       ├── 5317a560e0943a7311bbc5bfbd9e4b4c13bc2bb6
│       │   └── chunk-001.nq.gz
│       ├── 53cee8c7fb2fe1252606202ec9e2746651df738c
│       │   └── chunk-001.nq.gz
│       ├── 5bf882241c607445bf02cf5b241535d62e2b99c1
│       │   └── chunk-001.nq.gz
│       ├── 5e839d4f545d8d8c078e7aa8b3e3369c127251c4
│       │   └── chunk-001.nq.gz
│       ├── 6a02ef5a1034d66338811757df07a113a1169af6
│       │   └── chunk-001.nq.gz
│       ├── 784102284471252f418e797c1874a00063426210
│       │   └── chunk-001.nq.gz
│       ├── 915f7940e34f3238b504dc2124d81016dbac4f9c
│       │   └── chunk-001.nq.gz
│       ├── 97615cdcd0b6c6ffcf18b272598e82bfa3a18938
│       │   └── chunk-001.nq.gz
│       ├── a4d39f7cd852c0aabee3b0dc5d9403496406034e
│       │   └── chunk-001.nq.gz
│       ├── a66b5d1d444718ac220fac28e1a3f962c4773972
│       │   └── chunk-001.nq.gz
│       ├── ab4e1a0d372b74e9c4eda6682944df6b336a46ac
│       │   └── chunk-001.nq.gz
│       ├── ae1f1a906feddb23f4fa05c968c52df99c487ead
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
│       ├── d143c897d61ba75cf49454b8174aaaf6c5580272
│       │   └── chunk-001.nq.gz
│       ├── d4b170a15319f81fe6d3493497a2fff9273e50aa
│       │   └── chunk-001.nq.gz
│       ├── d67735509fb38545be9449201cf26ae9fd10e69a
│       │   └── chunk-001.nq.gz
│       ├── d6c0b9638349a7dd605d60ee555ff60421c1a594
│       │   └── chunk-001.nq.gz
│       ├── e13d957bf48224453c5d9d9a7a83a13b999e0196
│       │   └── chunk-001.nq.gz
│       ├── e4bbb8a2aa881409af6fb92933c18e2af6609da8
│       │   └── chunk-001.nq.gz
│       ├── e5d68ff94f223b0a1fbee15dfdb6a6b6ff3f809f
│       │   └── chunk-001.nq.gz
│       ├── e67796720403941538f826463f9fc610a431e899
│       │   └── chunk-001.nq.gz
│       ├── eaf2a9129ccec6febda0f741eb3bb852c3f947bd
│       │   └── chunk-001.nq.gz
│       ├── ef800f85d0b0757e31a7f448e2cd21209adbb65a
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
    ├── 039fcf3af8b6a81ea9d185e50a727866eb5e0fe5.nq.gz
    ├── 03e6644f0b418a2ee6d1d4f755ca063f76eb628f.nq.gz
    ├── 0480593284c5289bbf94965172c6dd36e4094c27.nq.gz
    ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
    ├── 04d2241281c7358420763329df51cf2c19091b30.nq.gz
    ├── 057a1ae93d4d8950b3755a10be3ca7e1513b3d5f.nq.gz
    ├── 05d377a943a1af24ba1c26b6dee5e5bfb5eddbe3.nq.gz
    ├── 06252f1e818aec47e435d10743f53b9abd41a754.nq.gz
    ├── 0625becf44345b517f51d4368ba2d159040a32e9.nq.gz
    ├── 0669eaedcbc8abd1ac83e65289ee989669269894.nq.gz
    ├── 06ad2dd97706d02dd50796f62e52285798a1f186.nq.gz
    ├── 075a7af175ab5b278229529d1308d62a71d153a0.nq.gz
    ├── 077780f4da928fe76c7c088dd0071e7ea8f20180.nq.gz
    ├── 08122825eb29a1e0fb9bb3044f6f88a3f14d5352.nq.gz
    ├── 08b41cd3da975c2b563e1252d73614ac2044a3c4.nq.gz
    ├── 08c523219f8193602c39330dccb89264756a08d3.nq.gz
    ├── 08fd03a5431f4f01acae39d6e296a0e004b3faca.nq.gz
    ├── 09d6103458b20fa028128a15467a9a3df4283f3f.nq.gz
    ├── 09f7c05acb30d7aaa14c51403bd26076edad4493.nq.gz
    ├── 0c7713ca9c145c473868bc4d8d2ef7560bf65eac.nq.gz
    ├── 0cda00f1386b31263f34987f100ae8e97897503e.nq.gz
    ├── 0f168618fe21ff1c35e9e8c1dda67941e8a0933a.nq.gz
    ├── 0f52ac2345693cde229e79d5ccfabc83af3055e6.nq.gz
    ├── 105a32a55cce1bf0cd6d4781a27eba761dc315ce.nq.gz
    ├── 11500a1b443a7f325dd34988463b3b3e047bac37.nq.gz
    ├── 116d97facf917aa055022cef2716abd6f3af16f5.nq.gz
    ├── 11ac8e1a9e33877e76a433e295c838877be17fcb.nq.gz
    ├── 125a0a831e21428d7d4d7f7ff37e9ccfe3220bf6.nq.gz
    ├── 127d46f08d6c652cb2e23a4f7cb37d1528eb1b39.nq.gz
    ├── 1317d7554a122e7cc9d78efe6699a25fb8b7c9bd.nq.gz
    ├── 13e2791c36143fed5dbd36b8910bff593b725c15.nq.gz
    ├── 14f10d378392a34552c268501f3b0802aceb6b32.nq.gz
    ├── 1547e245dcb4e46ae38f1e2c6789fe4af0fa840e.nq.gz
    ├── 16f22d2c4a6accc4ec8cd9b7a89296a06ac74260.nq.gz
    ├── 172047aca727e94fb55d44f6952b2224bbe30601.nq.gz
    ├── 1753fd89dc4e4b07cda8c482f81b244f4ae59342.nq.gz
    ├── 1782ff76adae77d3115e973a235543581492bf37.nq.gz
    ├── 17c1a6260b92314764cb38abcf7fd283cdddba08.nq.gz
    ├── 1848d602bb7f886df48868827679d5f3eba71939.nq.gz
    ├── 1867868f719e0edd17ad0cc144fa680c9e273bf4.nq.gz
    ├── 18c6ca7fae4efd195e26616a951e76ba8be61bdb.nq.gz
    ├── 18e53323f0601fc28080d514b3b854c6e87f6023.nq.gz
    ├── 1a882380ee91f3dd84cefed8f151a70838edca46.nq.gz
    ├── 1b362fddfbd7204449e47ba814606cd785d4273c.nq.gz
    ├── 1c073471bbc0f0d8f66d99829f293a9fcaf935e7.nq.gz
    ├── 1c97b92bf2740ed2eaf8906d9b9f83bdecd967eb.nq.gz
    ├── 1d6bf0b0138d684eaf208f21d4900b7b774e1a0a.nq.gz
    ├── 1f4c4d43b2672dd5d08b5ddcb25edc352ca5705a.nq.gz
    ├── 1ffa855d768320cf83f14daa980402688a6915fa.nq.gz
    ├── 203da4bde7c226f87a74e12ef50523796d46799d.nq.gz
    ├── 209bf19f6a211c1ad5e598ecdf492fe092dcb623.nq.gz
    ├── 20ac61ba6f89fcbef1b5df7c1fff2491e3dd96c3.nq.gz
    ├── 223476fe4093894f66eef47b8835f1311f4a3d00.nq.gz
    ├── 227aa6797435a17dbc90a59b0b8160b3dd66d0dc.nq.gz
    ├── 23404e708016ac5c1aad5b961c3330e95b9a5b3b.nq.gz
    ├── 235f329bd1fbe8cf0f018008cefd27de6f1e3e95.nq.gz
    ├── 24a825287a4f8fad45ce7a9eec0f6c6b238caa1f.nq.gz
    ├── 252a2dd38042e92f440b0f6e1423e96c63effcd4.nq.gz
    ├── 25927fb9db552e200995da40af22270e6e922a32.nq.gz
    ├── 27063ca2f546334904a833dc36880a477756e4da.nq.gz
    ├── 2865cf854ed8a09afaf05d04677c72111589816b.nq.gz
    ├── 2904af86d6d5bb5698bdebf4855d4fc633972022.nq.gz
    ├── 29e38757f2985a545c7c66e80725fe573bc696ee.nq.gz
    ├── 29f0f9a3065a61b8b5c75964900d16d3bac4f519.nq.gz
    ├── 29ff965fed312b03de25fe17f178f0d8193129e0.nq.gz
    ├── 2a32189dc07ff82b33ebd0328187994cc99d6b6e.nq.gz
    ├── 2aa31779c6b25b958576a06ec81aabdb423d67a9.nq.gz
    ├── 2bdc288f7caac4c9d0d033953b274859717249df.nq.gz
    ├── 2be387dfb2a3f3c4b392c4a8d7b5efdbdb2ecac5.nq.gz
    ├── 2c416295221d1a07f0042db14b24ec2cc7a42306.nq.gz
    ├── 2c8dce72d42fca4173bab93f35d8feb0720d0f00.nq.gz
    ├── 2c93cbd015c21be5507c18138003542743ab8939.nq.gz
    ├── 2cd63024fa715a8ddd3c92d855e4396a1f0bec35.nq.gz
    ├── 2d63eec1705132d3250d6947f178c3378d5fa513.nq.gz
    ├── 2dd6186486ac44e0525b6eb9734d86560e226b5f.nq.gz
    ├── 2f78c0d01a9d77971711bed9206a0efe02229652.nq.gz
    ├── 2f7efbeab578c8042531ea7908ee8ffd7589fe46.nq.gz
    ├── 30f0c17faa7055759ccf8b36c11b3f6950b8c416.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 331965df472db0682eca49958245059f9e9e11fd.nq.gz
    ├── 33ae148531288a108d78abeea4532c1663ec7432.nq.gz
    ├── 343fdb2375ac50ab6b859bab35e06f93a5ea1d3c.nq.gz
    └── 349c58b8f705f22dce6f7c939845101b134097f3.nq.gz

80 directories, 200 files
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
