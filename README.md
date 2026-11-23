# Repolex Knowledge Graph of launchbadge/sqlx

RDF knowledge graph data for [launchbadge/sqlx](https://github.com/launchbadge/sqlx), parsed by [repolex](https://repolex.ai).

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
rlex download launchbadge/sqlx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 75bc0487eb661da811bb7a3c5d158f1bd463fef4
│   │   │   └── chunk-001.nq.gz
│   │   ├── bab1b022bd56a64f9a08b46b36b97c5cff19d77e
│   │   │   └── chunk-001.nq.gz
│   │   └── e7236881a1d618835d074481e45306a8ddc5a916
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e7236881a1d618835d074481e45306a8ddc5a916.nq.gz
│   └── repolex
│       └── e7236881a1d618835d074481e45306a8ddc5a916
│           └── chunk-001.nq.gz
└── blob
    ├── 00194cba5797c7e546a8a6c4c7a843873f9235b4.nq.gz
    ├── 002aa4da9626b7c407416f7d25813f225f8c54c3.nq.gz
    ├── 007e202ec97771976849672a1fd8d69bed2f35f7.nq.gz
    ├── 00a4c2999c7cec80042f816efb88c7b62a698b11.nq.gz
    ├── 00b3bc360c67dea64c0f29741f2cf4ba4cf863fe.nq.gz
    ├── 00c8c984464e75933e81970bc5144537255300b9.nq.gz
    ├── 00de302296e53cde42b363e961b08bdd9ac90ffb.nq.gz
    ├── 0120c304e66742b4998bddcc8b59867de2d5fb2b.nq.gz
    ├── 0158870aca993e1ed56e75ba4bc32e593ed0c715.nq.gz
    ├── 01848a3f838e13358c21bd78fe8bb38fc01d7d22.nq.gz
    ├── 019f4c5d4d089f4a9b40977fed48531e9ed216a8.nq.gz
    ├── 01d6073a2f75fe9b9a3a6c084adb69f17bf13268.nq.gz
    ├── 0222ee89a1d808404929057b99109bd0b8f8880b.nq.gz
    ├── 02458ff72d17e3b8600f1d19c4cbde4682b39958.nq.gz
    ├── 0266ad4b69cd2456b5db47474f5964db578a5c98.nq.gz
    ├── 026adfac7793e6c8e101fca051896be1663f3b52.nq.gz
    ├── 029288542277c39606dbc56fed6c0f158221b0a3.nq.gz
    ├── 02b1faa67ab7fc09fccf5bd9db323338afb9d75f.nq.gz
    ├── 0327d5c45dca160e6f8df05328bfae4e3c1e9a6c.nq.gz
    ├── 032f4dda03b5078e4dbe62f6e90fcab846cbda49.nq.gz
    ├── 03c9732d0b8c71f50d7a9e6f0ab1f18fd467edfc.nq.gz
    ├── 046ff5c2fb62d17f92d9a0a66bc72c050dc8e7d4.nq.gz
    ├── 04c5ef837a5c7876e030ca2d8b72956ff3686bb9.nq.gz
    ├── 051353383b08925702246cbb4b94215180033f3e.nq.gz
    ├── 0530f4204cf74def37027ac548ab23dc76c97854.nq.gz
    ├── 05840c65a0e1b491adcbc1e34a5ed641445e624f.nq.gz
    ├── 058a24c52b79d353b4b0476228872266f388137d.nq.gz
    ├── 07ae962018c7a4cc84421daa9be36ee2dc1a40ef.nq.gz
    ├── 07d9d788629484fd753fa58bac693805e03f753d.nq.gz
    ├── 0813ad87675547cb97621de6cd46ae3cf511a8f9.nq.gz
    ├── 085d24f434eb4915606939863ec695d7ee447cba.nq.gz
    ├── 0879b333caf63a36ec8a34756be87aae29b7b930.nq.gz
    ├── 0885b3cca8f60ccacbbc393b2c505760e93b1744.nq.gz
    ├── 08ed7d11a335273a6c7172692b0450b68b01d725.nq.gz
    ├── 08f88a3ad9af6a8232cb405b9e96f971cc57b948.nq.gz
    ├── 0986ef1bbdd658a2472d91264297069150783525.nq.gz
    ├── 0993cbeec6fbac01a611b3929c2053d83e3a8c56.nq.gz
    ├── 09957d764a89faf5d162e14b2e00a38f6c40254e.nq.gz
    ├── 09c2fa44bb452b77aa9c5c2512af544abd41f02f.nq.gz
    ├── 09c886221a39f7dd0f8a19a3ce88541f0eab2daf.nq.gz
    ├── 09ca470cafc70215570a24e8a99972f46b6151f4.nq.gz
    ├── 0a2f5fb839ba9f0a1ecbad93f5f0c5d82f13d56e.nq.gz
    ├── 0a45de26b20472614bcf129f7a108d7310d3fde5.nq.gz
    ├── 0aa95320340037ad5c1585680b256397f80fecb3.nq.gz
    ├── 0ab4dd56bf4d42e50041f9bc32bdf1f743e37e7e.nq.gz
    ├── 0b2309ae60df66b48b1297da484102d05f3f9696.nq.gz
    ├── 0bdc84d8c96f668332ca2f1cfd8a35d36056bb00.nq.gz
    ├── 0c0f4fe99675de8473390504f659c2403c164f24.nq.gz
    ├── 0cafc4d08c4c63c342685fedbcc43222dd38d2f1.nq.gz
    ├── 0d9c14bdfde72d4e6a102c78d1c8b18440cfb7c6.nq.gz
    ├── 0db6f0c2e7ace9d5a1412f029ddc3a802b5ef83d.nq.gz
    ├── 0dd6cc2257f855b8dfd57c62cd13865e68d0f406.nq.gz
    ├── 0dfbcbdf267e936b7b5eb4d6673aad635f0c4825.nq.gz
    ├── 0e0027882d61988d626e9a59e60f8f7faa948c99.nq.gz
    ├── 0e0f6c412509c8436762359d25398338f5a7a489.nq.gz
    ├── 0e4448a9bd3e3b1cfcbd50aeea2dec5ebd361084.nq.gz
    ├── 0e5b16225888201ef843eebb3641b6377e542d14.nq.gz
    ├── 0ea9d4620d0ccb551eb98228f7fc551cdca92c3a.nq.gz
    ├── 0edde05434e3bc70def63743f8d0be0a3043c2e2.nq.gz
    ├── 0f15b59124c9a422b1e222bcfb2878caa6434963.nq.gz
    ├── 0f275f7e897b0e456ef9885377056f08b0b960d4.nq.gz
    ├── 0f39efc46d40e1cb720cea14e076a235018d04f8.nq.gz
    ├── 0f4da33ccc6e7a193102605ae8a807985db24822.nq.gz
    ├── 0f552d005ea18d60c97847326ad1a551b45d13c9.nq.gz
    ├── 0f9aae61b48dba26f834b65330136ea4c953cb5a.nq.gz
    ├── 0faefbb4821fc7f796c2e9882e645120b53d56a0.nq.gz
    ├── 0fb71b14a7917a122a4f61f60e36aa7bd90528d0.nq.gz
    ├── 0fc2b61d8839e052d3944ce15704435896cc867c.nq.gz
    ├── 0fe3809b579f0fd79b049ac4d4540839dc82e528.nq.gz
    ├── 100b750f192265502a66754a19d6cacd4b55c473.nq.gz
    ├── 107cdd246c5c912ee5a466c51c5c0494cc389e48.nq.gz
    ├── 10fc7c7b8ed5542cd266aa8de7a2da25840050d4.nq.gz
    ├── 116a28c2d045e8ce1b3de56c74ca86580f526dcd.nq.gz
    ├── 116a49ccad514e98b1133829a19174dab2db13ab.nq.gz
    ├── 119e5ca95ff8976a5c04dfd75f0a16c2d5b646a9.nq.gz
    ├── 11bca0480606ddae041abd50c57650bdace005dc.nq.gz
    ├── 11bd2da5a23294e6f1d35d93c966fd17adc17673.nq.gz
    ├── 1238a3e86f15169d0e6de2bb6c4b0a76c3f9d58c.nq.gz
    ├── 126771565a8e3250d2124bb3fb77abc2ea4b97be.nq.gz
    ├── 12d92d4b2a82c773da1f826b6c394a603e6a267c.nq.gz
    ├── 1315ea0e200491cbe6d92f88b084d9e820c548c6.nq.gz
    ├── 133ba084f2dc86492420475b3ff058d3e85d0dc9.nq.gz
    ├── 13f9bf1d5dc91d8722523ad3bed1e89e11e10af5.nq.gz
    ├── 14525611a0c07c0ad0df182843a4707da9fe9ece.nq.gz
    ├── 145e46f12b71ed80f7b1b6ec9ddf88270ea96ada.nq.gz
    ├── 1464a730c772ed0d29e881e335c721a3a51219a2.nq.gz
    ├── 157a02f61d970d8b11e9587c9f8c445f013d8d5a.nq.gz
    ├── 157e1214ab295c2a616fe0a85579a5001728f228.nq.gz
    ├── 15892dc1ca3d8e453d5bd4cdc407f141d4964d3d.nq.gz
    ├── 1591d585f8927f95d88c243a82681a1b606a128e.nq.gz
    ├── 15a5b01ab8be90a708bdac0548a46c5efd6955af.nq.gz
    ├── 15c2459c819552a8b356d07fe2fce434564ff7eb.nq.gz
    ├── 166ce39ca8cbaa20c48cbd4d983a19748661fdfd.nq.gz
    ├── 16b7333bf5ea4577df9e289fe149aac36d52004e.nq.gz
    ├── 16cbc14a0705fac95ec8aec912283f70499aa78e.nq.gz
    ├── 16cdd688c89252e6c38bcd1162c24a19b23c594d.nq.gz
    ├── 172f244c1730c616611b12df0abaa987676a5da0.nq.gz
    ├── 173c283e7396b836962218b1e3f33049aff6475f.nq.gz
    ├── 179b8eeaf78d7d2f3ca3d320609ff6b32b360bce.nq.gz
    ├── 17a46a916f537a70fdddf96712b3d6a818204a54.nq.gz
    ├── 17b4bed1ca40f112690011dbc3f38b4585ed1001.nq.gz
    ├── 17dfd6428db7f456b07cd729c0c7baaaa5ecec9c.nq.gz
    ├── 17f67e0fda2bb92ca1606b74a7ce71da4fbf3c63.nq.gz
    ├── 18737f0ec3c7f7f1c95df854a922a2a7b2799bef.nq.gz
    ├── 18db30b183a203814fcd51496c3e8aeee4aa0f32.nq.gz
    ├── 193e379ef7e050dc77c98a5f54eff0ce3e5f8611.nq.gz
    ├── 194d823fd7caedbf7da5d3bccc0cc4fe49a50a5c.nq.gz
    ├── 19b3a6f27c09798cbf466189ee0dec8cd4f69cae.nq.gz
    ├── 19e59028e1424c26a2baf8a239a91db2d2e8d029.nq.gz
    ├── 19e8690f9a428f61851b0a65bd27eb5c4e276016.nq.gz
    ├── 1a4a27dc6a60118f5971b90bb72f558db66928f9.nq.gz
    ├── 1a574038100abe2fa0b377394f4e75f50931c084.nq.gz
    ├── 1a85cf0ff9c10fe0fc33b2354f8779779f146d88.nq.gz
    ├── 1aef121199f506c494cae0aced9efb4c862773c9.nq.gz
    ├── 1bb841b9a130ab8ab2df7ad54a9c1c81cfe8b62d.nq.gz
    ├── 1bc4172fbdbe50bd759e5c8beead1cfc7677c13f.nq.gz
    ├── 1c0ff8729b67ccbac7a7a628434c282aaf83df7e.nq.gz
    ├── 1c40b4b01f4fc02c699fb00c300e84ac83d5c30f.nq.gz
    ├── 1c57d0163f3505dc048be18c5d47bfee4360cf96.nq.gz
    ├── 1c6d735ab79ad4746bb3af646c25cf5202e13210.nq.gz
    ├── 1d4f74df210d08dc320f7e481b7555ac1691b2a8.nq.gz
    ├── 1d5ed7c7dd6a1f19ccbdd5dcda3ee57695e4f78c.nq.gz
    ├── 1dc1b5ad104f8c257a3769691414654fc6d2ab7f.nq.gz
    ├── 1e3513b1ee1dba8bd5f26694eea922ca98d35a19.nq.gz
    ├── 1e8b1c5392113c6e5422430348cabbfcec84baba.nq.gz
    ├── 1ecbbad5194c5afb997a1ffaa796cf8bda3db9b1.nq.gz
    ├── 1ee743a37e7547c778d67dcf70b41b8af5f6a14f.nq.gz
    ├── 1f38779ec40f15b43e1ace2d094e08f0cb33eb1e.nq.gz
    ├── 1f4913b8ef277d93f9fc6e9724f9281627fe5b08.nq.gz
    ├── 1f6ce7726fac22fe6e9159d0bf263a9f5a0bcd33.nq.gz
    ├── 1f93ed11a5bd7e51c88dfa5a3cd476ce919f2bb4.nq.gz
    ├── 1f986174b8ce219c6a3932767961e5dd67c64052.nq.gz
    ├── 1fbb11895c4a3b15326513c50723cde0fc68564e.nq.gz
    ├── 2044d04e8c30239474e445305196f31724e14fa7.nq.gz
    ├── 20468503e05a6ee54b7f5783a1da84d1e56d138d.nq.gz
    ├── 2066364a8eeb709c16b920399214816736254495.nq.gz
    ├── 218c747143fe80b344bca3405d4b0b38da2bd932.nq.gz
    ├── 21e6628caed062bfe54e31f0aeb9142f89a807a5.nq.gz
    ├── 2286ee89030c0bbacea773a60d260e9785705459.nq.gz
    ├── 229e780adfbdb34ac117cf279e11b70a79a491fc.nq.gz
    ├── 23139e857a7bb3f8dc2dfcc6de81649042e2d47d.nq.gz
    ├── 23352a8dcfcde9b59a9445592ce7b0097c6029bf.nq.gz
    ├── 23766e7000cadc2c33b2be1d499bc78a4252aeab.nq.gz
    ├── 237c1d6a352668ccfe57ae89a7384256c31816ce.nq.gz
    ├── 23f9ac5607e5e77d4547544d820e420daded1c26.nq.gz
    ├── 2419b50d974cd40d883a87a5da4534b2e8a24638.nq.gz
    ├── 2446ce61e77b60b7373096cbb4b36fe560db49ae.nq.gz
    ├── 2497e406cc16e7320f9257154bd39435caac65f1.nq.gz
    ├── 249f59b4598dee631e21104e9c1a2b4144fa26cf.nq.gz
    ├── 2585dc1312210d9eb18c15f6df1158656d3c6b2c.nq.gz
    ├── 25aa500aea9063305d8c295e013e86f376be2386.nq.gz
    ├── 25de20b6a5220ec161052acf5161e26ff25e87ac.nq.gz
    ├── 2603105979dfbec6cc2fd34ec866b3862c174bb5.nq.gz
    ├── 273a1bfcd911be956b388fc7e40f0d37dee780bb.nq.gz
    ├── 275958887309325bbe4eebee26f265253dd2b5f5.nq.gz
    ├── 2765abe02fdd1a13e6129763ff27747f6982102d.nq.gz
    ├── 27ad29c33ea7039a17e067d7d9b1608c86e81b4d.nq.gz
    ├── 28016b278676bde91419abd08b6f9d265943dd64.nq.gz
    ├── 2817146bc3b9530c5a9d0a16cab780f004575839.nq.gz
    ├── 28c56758e990595c9928310ddbf1e01ba078db00.nq.gz
    ├── 2959c8d6bce48818e7a83b749b681449fd54cf90.nq.gz
    ├── 2972a8203ccc76d1148434fbbd9a145008e07021.nq.gz
    ├── 29f0b096950c68b89f7ab6bc85eb09cd6c15c3f7.nq.gz
    ├── 2a84ff65551a4c8042bedf1c99402cfa820fee33.nq.gz
    ├── 2a9297cbef34a484c373c4d6f7e23e9b4f7c17e0.nq.gz
    ├── 2acda03410bee13f967ef9d4d07e5d08e124d324.nq.gz
    ├── 2ad2480066e5f8d4833f9f22a60b39b2ece9ecd3.nq.gz
    ├── 2afa57ee0dfaf3ed438aef54e255d140e85c09d1.nq.gz
    ├── 2b6d46718c997671ebafafb7220b566891b068fc.nq.gz
    ├── 2b7f169ae96d23371a0470db29773a72e4214cc9.nq.gz
    ├── 2c57a237eca510d50a24e2c2a9c030d9faec0857.nq.gz
    ├── 2c59ca5339349fd34f34a1801d0aef4b62d9cd25.nq.gz
    ├── 2cdf347472170d30bc6763cba236f7bb5b28e110.nq.gz
    ├── 2cf4209ad6979f244ed0fd8c870e4b1dc68c5776.nq.gz
    ├── 2cfc1907c3f73980a4220b4836fa05e61e048d59.nq.gz
    ├── 2d28641f945cfd4577626d462e3d9ec9c7ef94ac.nq.gz
    ├── 2d504904da346f2e5b45527dc64e9e0232c6f5db.nq.gz
    ├── 2d5342d5b8f976e0f55adbb718bc4927a760da1b.nq.gz
    ├── 2d66d70c76cb4496a9ec6a5aef797ee9cbd5cc9a.nq.gz
    ├── 2da9dddd42f55a63fde1c14c1d1d6b63f40cc7d0.nq.gz
    ├── 2e6fec1c0dbc9da8c9f8142e37d5fd97e4ff8a41.nq.gz
    ├── 2ed8f9449513654f4b42114a3122982fb5a615ab.nq.gz
    ├── 3007884c72523cfa69d43c250c829057896752c5.nq.gz
    ├── 3051f5ff97a57cf3860bbaeae5772bd74f525ce5.nq.gz
    ├── 306431039dd5a7467d7471de79b83998a8cfe9bd.nq.gz
    ├── 309a62b2ecce370f91dd3021b7693f996d6b1972.nq.gz
    ├── 309f2430e02f0365df277e747e36053328e1719a.nq.gz
    ├── 30a24d09d258054f2a56bbc7dfca311eee6dc18a.nq.gz
    ├── 30de8070f605266c5375ab1a969fa8604b421fad.nq.gz
    ├── 310881da144a7ba649c6f80648a008783647837a.nq.gz
    ├── 3130b4f1c65612bc2f368bf071725fe06abf3580.nq.gz
    ├── 317e4a87ce5f2d9f9084f389a1d0e8341d3d4881.nq.gz
    ├── 3192002f578907e261d2c8a3d934149e1c804892.nq.gz
    ├── 31adef0051c6b5796f958e543528926455e12a49.nq.gz
    └── 31c4db2d976a1ed82a8721a08af8cc264f23a2d8.nq.gz

10 directories, 200 files
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

[launchbadge/sqlx](https://github.com/launchbadge/sqlx)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
