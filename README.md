# Repolex Knowledge Graph of zenml-io/agent-benchmarks

RDF knowledge graph data for [zenml-io/agent-benchmarks](https://github.com/zenml-io/agent-benchmarks), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/agent-benchmarks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d971fbe6b82643107ae91a4aea27f47e76acb9b6
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── d971fbe6b82643107ae91a4aea27f47e76acb9b6
│           └── chunk-001.nq.gz
└── blob
    ├── 002b3673b30bb61da4c0c08031b4d539f99fcdaa.nq.gz
    ├── 00e7a5a5c2e5ae35e6b40cae49d865d1ce62d769.nq.gz
    ├── 0125ce4a9df63da41b8ffded4d58e3c71592c62b.nq.gz
    ├── 0148cc0f90c6a7dfc6c07c54f79deb0294fe1a40.nq.gz
    ├── 018c19ee858f869f15945d0759f3efa09d0fe9bc.nq.gz
    ├── 01db45a31c2250f9ea5e5cd5596bf520fe66c4d1.nq.gz
    ├── 02f7a557dff9da5e90cf5d6eb258ffa8fb1c13ea.nq.gz
    ├── 03495e0b155d137ea31d6c0e99e48cc060ee1318.nq.gz
    ├── 0350484703d58213a9bd7b470f18144d3c7639d9.nq.gz
    ├── 03c3fe7095acdeec61062c3bbc57b348ac671adf.nq.gz
    ├── 046b6b904d73b93642c05304812092bbe76643fa.nq.gz
    ├── 049a043365d0d9396b6a21ba113e3d3c7f4ef415.nq.gz
    ├── 049a84d4c885f07925c6f3b0f79d99a909aad6a6.nq.gz
    ├── 04c50e192cc481aba26dc40878f79f8c8243703f.nq.gz
    ├── 055d4c9c40f07aca91225a4f79a726df9b24147d.nq.gz
    ├── 0646cfd5db2e3c13637dd49a1d2e02596a971f4d.nq.gz
    ├── 072d1ae7a7732e5ef27ab9a162b0b4812e3b8dd6.nq.gz
    ├── 07667de3afb216dd06a2b1b931e5363e6fbb3904.nq.gz
    ├── 085e1ac6c616f2a92bfa092861334e692761c93a.nq.gz
    ├── 0911ade9738fdeca75e2122c8d9066dd1a4562ff.nq.gz
    ├── 0c8b57adcc51565322ec81dfabd17640dd064c91.nq.gz
    ├── 0c8c362996b36621d382a1497f8d96e55610248a.nq.gz
    ├── 0cc016bc80b3a9da8f9bac59ee59e7659755f8ea.nq.gz
    ├── 0cdd635392681523445e6215c168eb0cb37add98.nq.gz
    ├── 0ce375cd74280b8840d9a7357d7770dcff3162b9.nq.gz
    ├── 0d9c1dddbaf3288eb6e1881e64e14d3f667305b7.nq.gz
    ├── 0ef19e77794c4faf8eb5310d99bd5c38dc0b3a68.nq.gz
    ├── 0f22ca53655a72c60a09a390267c8ed1a48d0e44.nq.gz
    ├── 105ddfa5f5afc0e3c876cffc796794b5f9d1d8a4.nq.gz
    ├── 10aec055a801fa8d5f7f38db494999246a4569c8.nq.gz
    ├── 110a3fc561d01c67ebc24ec670ae02eda722992c.nq.gz
    ├── 11677d711eb75f4472a7f21c772b7b8740bd8fd8.nq.gz
    ├── 12a5a6f73d3dd6339fb49a64cc0fad9dd7f6616d.nq.gz
    ├── 137c5003801e22a50a710ee5655be8cd7d0bb4ce.nq.gz
    ├── 14777d6cfeeec7fe2d2d46663a3f246f5896a988.nq.gz
    ├── 14793dca237dfdc399f844cc9473c218715260b7.nq.gz
    ├── 14a5e876ce0c3a75c395aa8a13c9ddc8630ecb8b.nq.gz
    ├── 1615674e05b1f22ac142161badc2b98df3c203c4.nq.gz
    ├── 163fe55f215e9681de4ac6a386d5dfdd257173d1.nq.gz
    ├── 16cee499bc243a1041821fca0e20438e40e47d4e.nq.gz
    ├── 1722d0c0b9f2fb91a0ebbdb5e2c6be9d6df79c65.nq.gz
    ├── 190f7265086a860595ed4df14d07c48dba12f517.nq.gz
    ├── 19d20853801f3bb65bc92bf7bbd928a5ba448e77.nq.gz
    ├── 1a295e6cc54a44f5bb137e67f6b84728d26a43be.nq.gz
    ├── 1a4fc8a59ebc5aa4a2418540297f4b335308b1f4.nq.gz
    ├── 1b7539c841c423bcb14e505ba453b735bf9e519c.nq.gz
    ├── 1b936b7a6dd6b4687fbac235ac51ab891f6cbd53.nq.gz
    ├── 1cfb16f45f991783c5372769d7c30b1ef58027df.nq.gz
    ├── 1d41f5eb2badcd7140226640a78878d4368d9013.nq.gz
    ├── 1d637c03d4f7e24dc8bc00d5ef334da17d035200.nq.gz
    ├── 1e98110d504b4787a5625c02d83a05bfe63c0e84.nq.gz
    ├── 1ebfa24ac3a410b150903cbaac575d10056aca83.nq.gz
    ├── 1f0e8ed53d98878b5318fe5541e296fd1beab7f9.nq.gz
    ├── 1f61e62191bb35c3844b7a31463e5480538bc325.nq.gz
    ├── 1f90658416de7888b258581c35c14c1703b8cbcc.nq.gz
    ├── 1fcdba25993253844109643b91d9e8227495e80e.nq.gz
    ├── 200a8b3b73ba79c95c49f1d02cc663e83edda522.nq.gz
    ├── 20765a6bbc6a45c3ab07c86ee02fcc94f3eef2cd.nq.gz
    ├── 208340971648359d7659672fbe3ac2d4df028ee5.nq.gz
    ├── 20caba23bc3d6de436b49f8093157140a6400761.nq.gz
    ├── 20ddb88dc80b75fb32eadb8e525c9026ad90a017.nq.gz
    ├── 210042072995b5c185bfafbce1b682e72336465d.nq.gz
    ├── 211c0feb4cc967b8b5bf98776ef6a9fa32e8770f.nq.gz
    ├── 2242da158047c623a39c5e6f78abcf4b6be4fc13.nq.gz
    ├── 22fcc240f37c487de508c0a78cb2cce23f83f544.nq.gz
    ├── 235f7eef2b75835bddc211479bea83eed15c2f1d.nq.gz
    ├── 23a911d7f69518d0acfb92a2d991622f2aca0aec.nq.gz
    ├── 2414d58cdab54552c9df82aacbb3b1d489073086.nq.gz
    ├── 24a892303d05cd844e31d8f0c7acc2486489f858.nq.gz
    ├── 24fb6174130a36837a47d32efcbfbe39d91d93e0.nq.gz
    ├── 25409eb05d6093c25915fe02a6ceca2ddd366fc4.nq.gz
    ├── 25d576770aa4557a07d6aff0a0e150c871923316.nq.gz
    ├── 25df9b881e58ab879cf2f56b9f0884f13653d063.nq.gz
    ├── 2608f9b5555d80bb72563e11a0a3b55655b7d24f.nq.gz
    ├── 26e0aa07482b35364e0e9f1f094d83ce987b6b7a.nq.gz
    ├── 26f670483dee4049c830f0028b164262e1422674.nq.gz
    ├── 26fe2d98b1e764bbf99d529dca2ad1629fc6f255.nq.gz
    ├── 27e52cdc5888ddb3269691ac88531ff25802faa9.nq.gz
    ├── 28d26400f0f723bf37d2bf86cbbb85494f0b49c9.nq.gz
    ├── 28e5a3e085afeae8eb244b14a15afb587bdb8557.nq.gz
    ├── 28f428f8cb28d09d83ec0360cef199d3920c0958.nq.gz
    ├── 2926b86869762667df2621be94114c496974a837.nq.gz
    ├── 29d3ab36b24ff93b96e4f963c92d7bb8f519091a.nq.gz
    ├── 2aa9502dec25f1879be9e0d754439c99f019833d.nq.gz
    ├── 2ac349989049db17471595df46a7cb4dd13ff216.nq.gz
    ├── 2ad388e6f4b7582bb078a2385d0585d50c951c28.nq.gz
    ├── 2adafe3cdaf25603a3c2672eb715573b16e91a55.nq.gz
    ├── 2b7366f41d3b92d089e430eaa5ce7a27b6c6ecaa.nq.gz
    ├── 2b79535fc51bf5bed70edc0e3d8166613adc5e6d.nq.gz
    ├── 2ba49680ee35a7788cfb04ba9645e68f5eb2a197.nq.gz
    ├── 2bb408c3df09aea40a77b35861f2d9690677ea1d.nq.gz
    ├── 2bcacaa87d643067c617900a900df98403d4f8ac.nq.gz
    ├── 2c35e9399ef049973ac64ef885848a5d392e7659.nq.gz
    ├── 2de2cd3aa99cfe9620e472362a088464b7657993.nq.gz
    ├── 2ff87fa071ab9e30439b0004cf39f57248d8a395.nq.gz
    ├── 302d817f1b45204e4522a1f44a498563c8f1ad4e.nq.gz
    ├── 307110d8800486082095a9171617d2872f8ea0ff.nq.gz
    ├── 3387059b4263a1dcb84d3e36bed152e678fa0354.nq.gz
    ├── 33f69496a566429f7f0918668b8545745fa16133.nq.gz
    ├── 3403c8ac855ba34dacd17790d8b64381ff605cde.nq.gz
    ├── 343fb05460af168efaa85f2e22fe8970629718af.nq.gz
    ├── 348b4ace012f9097c243fd43fc09725591de7fbe.nq.gz
    ├── 353cd20c33e0f3014fff70219043981540463d03.nq.gz
    ├── 3574a30202470bd3996f874a5c606d1304032dec.nq.gz
    ├── 3589f2d14d93ea61a639278a4d33da5f0e834f00.nq.gz
    ├── 35d99d712425c50122d22cc105ad9a00d3e50e42.nq.gz
    ├── 35f05bcc5f348661c0fdb2dfffee712805bc2b03.nq.gz
    ├── 36049a0fd3de85b1cbc5a052d7d3433fbaaf6800.nq.gz
    ├── 3612fcf5f5d0abc7f8e6dbdf95619e0a77c664ec.nq.gz
    ├── 37b265cc1f37b9cdac7e89e7c56d543bc63c3bf9.nq.gz
    ├── 37b5bf5493b4ce8c2de6d5f00c0e76c803d6b544.nq.gz
    ├── 38be6c03b27907d52e89aa67b871d8a52c1ef76f.nq.gz
    ├── 3929ef9c4815aa93e8a147b1614d49bb21f48e43.nq.gz
    ├── 39b4e85bc41ba566f15f45a90b961ce79f01015e.nq.gz
    ├── 3a96bfcaedcf51737e3e860daa33a88674756792.nq.gz
    ├── 3b93498573f24f67b4bf4fcf5bc6e7e01c1aac06.nq.gz
    ├── 3be9455f84fe58dddb2cf46eff8b9c3ca999629f.nq.gz
    ├── 3c142e2598aff6be93cf8a1a3dc70fc7e765cb34.nq.gz
    ├── 3c6fc6297c3bcccc06fa157b29c161299c677d64.nq.gz
    ├── 3c7d6f84cc1dacf7ba67893dac2a89a6dfd3f427.nq.gz
    ├── 3ca4bd36d01fd610cb98cc1fd4b27f24eebbb997.nq.gz
    ├── 3cf426854dd4ffca257728e12f3c44615122268a.nq.gz
    ├── 3d294b733f5cd7d6ad0838d10b72219100d284c2.nq.gz
    ├── 3e78e2e79bc996895660dec7144e1b7986d33b6d.nq.gz
    ├── 3e830c4d843d3368cb6383b64f1608ed34269c73.nq.gz
    ├── 3f19a246652ee590c735350b7cf0efd1c96e5c3c.nq.gz
    ├── 3f90f61655344536634ceac693f6c067e8940a57.nq.gz
    ├── 4073833af95b728804659eb69f60ee8bd6d336a1.nq.gz
    ├── 40b706e15da0e3443bd5cbeb090bc356f55c0666.nq.gz
    ├── 4121a74582c0cc566c9c30adfa9288d6f7d9a965.nq.gz
    ├── 41f4a43f69b518ded1c4e6cdbda5e9ee97b612c3.nq.gz
    ├── 436377ba2db0974e9a76cf634152aa9cf61f7f5c.nq.gz
    ├── 4366b0dc12ed69a23b516bdfc8031456519d0d5a.nq.gz
    ├── 43c99372b366b0af35db7f9aad697e3338131e48.nq.gz
    ├── 443872be2b432cd0ba9265b0316b6c80eb801ab3.nq.gz
    ├── 456ef83e337dd6c19e3c09222bf223f0cfe2229d.nq.gz
    ├── 459385c34133f483cd196e0f4ab9f3f40bff1e58.nq.gz
    ├── 45c79a596899b1914fe3c92afd48170b9fc7583a.nq.gz
    ├── 467e15f3005f5c46f250dcc24dcb37d53b6e9e6b.nq.gz
    ├── 476c8ff2dbd2fe5ce0b5f275354f55911a30ffff.nq.gz
    ├── 4791c3d6c872576f0569c2fbed8cca2fac2cb981.nq.gz
    ├── 48067ae7d9a044ef11e460029a4e959256b4070c.nq.gz
    ├── 48891a667c5d07e0ed47829199ba33393099262e.nq.gz
    ├── 48f65c48e4c4bd06e066f84e6e0c11849c708ddb.nq.gz
    ├── 49560b62ec6e6ae074c8dd1dac808122471bbe6f.nq.gz
    ├── 497526c94cd801d7c147868e7e261560f5e03407.nq.gz
    ├── 49d4f2004379d7fe62a766068870ba4bd7b7df9e.nq.gz
    ├── 4a1abf013536d816320d1c507e7d98b945fd3e79.nq.gz
    ├── 4a3cd7368a89f0a9b735f92e07bc25e70a07373b.nq.gz
    ├── 4a8987cfd9991c7e743dd032d590cb498aa2c5f4.nq.gz
    ├── 4ac335bc95131196a2bae098ea2180df3e54bb36.nq.gz
    ├── 4b0f17087091759a31d43421e37b12e0a78e13c3.nq.gz
    ├── 4bb3f956e4cbfcd182e5c1e3d76ef19626eb9b4c.nq.gz
    ├── 4c13ec6377ba6200d4a0141d696c500d60418102.nq.gz
    ├── 4ccb5a892197372b275ef635087fb1c40d534884.nq.gz
    ├── 4d5581646e03d5f4a705ec404c6d768a5ef31590.nq.gz
    ├── 4d63989249cdb09dcac6bfacfbe20c45b70ea89e.nq.gz
    ├── 4d72ad1f976a6b5d4b6c3ca4b4425c9bc9d6123a.nq.gz
    ├── 4e39d0a2eeaf678e90d1607b9c7415bd1cd034ae.nq.gz
    ├── 4f5e8066420cb5927d9d5a42c351c468a47ee3c9.nq.gz
    ├── 4f90b33d9e80b1e554ba1d32f44993a3395de839.nq.gz
    ├── 50200c059423898fd38b0e405988b48df2be967d.nq.gz
    ├── 50216d35fb171b9787611f91a4b508eb6c862645.nq.gz
    ├── 50d888544e6ee94fd0168a098a454f7f3d51bfdf.nq.gz
    ├── 5111b6129dbaed2cab1623491813e32c3c70da7d.nq.gz
    ├── 52b15ea3321b5f85ea78d5dae1bc36915a2ea93b.nq.gz
    ├── 52c1e5a3c40e9c277caedb3e029cd19f29307f52.nq.gz
    ├── 53c1de75e5773bf72b9a908387728172a2bf2e87.nq.gz
    ├── 543f6326f85482252974d0d0ae0727258f1216cd.nq.gz
    ├── 546333f28a157cf239d8227dda871e5b7962286d.nq.gz
    ├── 54e2a37933125f48195efe657b4a53276ff10cf3.nq.gz
    ├── 553cb55509c1f4bace041ffc8643a273d4ee3c0d.nq.gz
    ├── 572dc1d6739934c31f711e139db230811e94e9dc.nq.gz
    ├── 57c86ed3a587bb63be330de0462a090278a9bd91.nq.gz
    ├── 5823466d3c671e12320d360d2801cf2d1ad2c574.nq.gz
    ├── 58c47b5b8731867eb1c46867a93a7a2cad1e5bda.nq.gz
    ├── 58c4a31a4ec24ad5ad8fde6be3d2406c0ad556b2.nq.gz
    ├── 58f326efe510a07ed7947299eb512876eb8cfc7e.nq.gz
    ├── 59213f3f7d70bab43de3be732e9b19f251c4efa9.nq.gz
    ├── 5926193441526aec73862f31b133bb8de917b882.nq.gz
    ├── 5a446a85f4a60d854793b0f5b7d3d86ff50b6df1.nq.gz
    ├── 5b344e590cfa3eb96604a552775111b1e1cb21c1.nq.gz
    ├── 5ba12f0a058031b362456f727291ec9c5c4472ee.nq.gz
    ├── 5baf74d1f93afc9fe296d499d626ed410642c8fc.nq.gz
    ├── 5bb5af58f1028f283c2fbcd3f6d4e3877e0e735d.nq.gz
    ├── 5ce7d398d7ce08d71839d8f70845d4b35dfd6747.nq.gz
    ├── 5d11211c7f165e82c97258e2b2d684ac0bac8c5d.nq.gz
    ├── 5d6611f1a533dfa298ec5eee20e93d72604a61fb.nq.gz
    ├── 5d7b064f0e5188dbfb4ea6de83e95836ff161a17.nq.gz
    ├── 5d7ce8ded737ddaf2fca2c82ced75d759be1560a.nq.gz
    ├── 5e76f5ce6d58ef1ffa3b6151e737196ad9836e60.nq.gz
    ├── 5e97554513980377b758c17c517224d93b94bf58.nq.gz
    ├── 6097d35b5d004e52c996959ffa2417100c97391f.nq.gz
    ├── 60f0c91689159e7efaca9ab26e15ee22275724b7.nq.gz
    ├── 61235fc1d571d5c6ead16fe7822f0dc58d1c8897.nq.gz
    ├── 6177b5ca3b244f71df90186237c6a7370b4dc57b.nq.gz
    └── 6186b1799ae564212267b3719470c99d23df6325.nq.gz

7 directories, 200 files
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

[zenml-io/agent-benchmarks](https://github.com/zenml-io/agent-benchmarks)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
