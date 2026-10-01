# Repolex Knowledge Graph of block/elasticgraph

RDF knowledge graph data for [block/elasticgraph](https://github.com/block/elasticgraph), parsed by [repolex](https://repolex.ai).

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
rlex download block/elasticgraph
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57bc8aec8c12564b3363fd00e6406f467342697e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 57bc8aec8c12564b3363fd00e6406f467342697e.nq.gz
│   └── repolex
│       └── 57bc8aec8c12564b3363fd00e6406f467342697e
│           └── chunk-001.nq.gz
└── blob
    ├── 0012bb26625773f42fc472deccb8f93a78b216c1.nq.gz
    ├── 0023e877b1b1c064a3cdf77ca0b77625d3fb6e24.nq.gz
    ├── 00450c7b3451cf743d513848eef20c73c893f584.nq.gz
    ├── 0070e5b3095f1209689b77c4ed591f37c93952eb.nq.gz
    ├── 0135b263b35d08c1cc80459ce04d83f52ba3ab51.nq.gz
    ├── 01b28348cfd50514a14e5ef5c19389904f8d0485.nq.gz
    ├── 01be07598bab4f662245fe287daf5c8e38cefaf0.nq.gz
    ├── 02227c974f6e9568f6432068866d611376e38d23.nq.gz
    ├── 024e59f94ec75545f1ef29c446644a04d7309943.nq.gz
    ├── 02891c08aa3e6a9d59095bee652c9409cfc5492b.nq.gz
    ├── 02f78f246d1da5a71fc8ce76bc75a081f4fad186.nq.gz
    ├── 02fe0cc5861dea34ac5be1d5137e1e5464abb4df.nq.gz
    ├── 057d27394f3f622a8c6a460dd010b1657f6f133f.nq.gz
    ├── 05b4a14fe80683ce545ee74a66b19c8dfe43fdfc.nq.gz
    ├── 0752aa66ee2f6a39981a2076d3631b73b977dc0b.nq.gz
    ├── 07d40cb1dcecdbc71f73206facc96f29eccfe735.nq.gz
    ├── 08af8fb576a23316cd05243d1f7ae40da589b4a2.nq.gz
    ├── 08d95e009ed79492a8746b6a3b9d0c4ba16938b7.nq.gz
    ├── 09a643da9c5528abbeb245d938944453742c1676.nq.gz
    ├── 0ab06358ce9b328857aad087a5a1b99743276ddb.nq.gz
    ├── 0ad3b253037426ecd33df40010b45d0a3cb2a1ad.nq.gz
    ├── 0c752d4e423c5215349a3ab013e394b31b891ca1.nq.gz
    ├── 0ca1c66a9d38a035dbb092ed8d593205ab9821a8.nq.gz
    ├── 0d780ffc53307e5965c6ebb092e90b59cdb35f0a.nq.gz
    ├── 0dc3ff6190ac977d7f7a6ae1e9ed3cb3fcdea90a.nq.gz
    ├── 0ec8b8a0ead577d281fafce1de6b038051feff57.nq.gz
    ├── 0ecdae84a7afadd0c8638eeff411e9a37bc5e9ad.nq.gz
    ├── 0f60f3e9828d39b17a00126f9b8457970872c633.nq.gz
    ├── 0fa5d6d2ca167e071aa956d87155ac28735704aa.nq.gz
    ├── 105b8b025ecf206d42c1d575be7d5429491ad57a.nq.gz
    ├── 1118686f426e058cca3276fb87b9bddebb2652b6.nq.gz
    ├── 1264777f79347db018a3706da7ee4d02efb30030.nq.gz
    ├── 1290927466c14c3df48f5ad1f679506c3d2f91f9.nq.gz
    ├── 142e31c0a11c9432ea6745bef4f1bff7eec9ee2b.nq.gz
    ├── 14c844e57c9a6a551c88250dd8c8b9be3b00ed85.nq.gz
    ├── 1572a1803d0f3ad9d77eee574fb1e30e88d746a7.nq.gz
    ├── 1625b6fcc58c28385f2fd4d15b989f629cf2a573.nq.gz
    ├── 16ad592cb53a2401783ae75a7f27879eb76a7f5d.nq.gz
    ├── 16c616a648d98706020773ece9b318e58c420f92.nq.gz
    ├── 1751d4ef2296cb4f8c58b2dd75f6bc56e860639b.nq.gz
    ├── 17e8bc9d355437634253884b5a9d5656442d7a47.nq.gz
    ├── 17f609204b44e9bda3f9ec7baf0c1ca5771abafc.nq.gz
    ├── 17fc1fa9dcfacab9ef802c204a18b82dab4e039b.nq.gz
    ├── 18603141d10ab558b25b30cfac0431e79009b9ca.nq.gz
    ├── 1a5c7d63405a4ca3e40f52a5195a6316c84bac77.nq.gz
    ├── 1b33577cd7fd7c00b3e84ab2ba387e91438c8ee5.nq.gz
    ├── 1c1a9a7c0170b0311f28d6a6323a816ec6d2d592.nq.gz
    ├── 1c2dd5f0e4366c96cb2801ecfbc3fb335e314dc1.nq.gz
    ├── 1c79f751213f982c203f4b53c696e1a65a6d438c.nq.gz
    ├── 1cc6aebf40b7645c227c215e03dff69f4624c798.nq.gz
    ├── 1cfd2a1be813ac219a204fdf32a9397e406ee171.nq.gz
    ├── 1d285dcdd3796589dd0d5079fb4cf88cf749dd6c.nq.gz
    ├── 1d7aa43b3535ccae7a5f45127a4770bf24e65eba.nq.gz
    ├── 1d7c3e85928fd4c3cc9c3f3363795f2452858f7a.nq.gz
    ├── 1d85bc501ff3b6aecf1512dcd14d0aae7930e6a1.nq.gz
    ├── 1f445fc354c1ba78d877aa187a0fee9fe8e44540.nq.gz
    ├── 1f6dc6fc81ad6a42d89ada6c4d09ade5a8341fb0.nq.gz
    ├── 1ff6e77b990333324f809117a0fe5f61e8dc4ccb.nq.gz
    ├── 204d822eabaaba172e598f1bbd6806208dfaa1f1.nq.gz
    ├── 20c640bb1556edb11c2c148c7d1e88595753aaa6.nq.gz
    ├── 21775bc846478ee804a770c6764a72cda0964013.nq.gz
    ├── 21e153654fd637f3633196bbd99b2b2c0b5a4411.nq.gz
    ├── 220fac20af5a378236dc573054c7796874912f64.nq.gz
    ├── 232827afc17a2d08d653143a945a31f5d532afc4.nq.gz
    ├── 239ac5adc65b23b318a9e3ae9fd3319696bc24cd.nq.gz
    ├── 23a676a0832eb6c2b084eb8c1618916764fd69e6.nq.gz
    ├── 24f27fa8d5ecc4bb2e38c4fa5c6e4b6f0c2dbc25.nq.gz
    ├── 252f31ae52a7046b9d47455194f8ca8375b70431.nq.gz
    ├── 260135a119ea56189453bbe9021d6f89a3bbb9f8.nq.gz
    ├── 26026a7b81c09ceec5554cca08ae491c42c3c80a.nq.gz
    ├── 26c2450788bb37ce268bfa994b13da0a9184d491.nq.gz
    ├── 26cb2ad91289415a1808550d7de9cc879599c7be.nq.gz
    ├── 278586a1c7246af67ed35401a09349d709f6124d.nq.gz
    ├── 28e56f60d6b77c64fa9f7e7495090e4893d23ece.nq.gz
    ├── 293ac8a7f76c774da822f7f33b28c7c9057d4c7c.nq.gz
    ├── 29874f563ca5eff8ec00b6ca96cba07d22883a9a.nq.gz
    ├── 2a00d4cccb9ad24506973a6dfdca47b155e7d4b9.nq.gz
    ├── 2a5a089b4e1f43091e39cdcfe3afbb1ad308e132.nq.gz
    ├── 2a667be2b0df7e81ed676f9826c08596c55b79a0.nq.gz
    ├── 2af6069012245028afe57a1f876227a51a12113d.nq.gz
    ├── 2b0289fe85a15945b3c8fc66b05350db5dd4ed4e.nq.gz
    ├── 2b4ae97504617d900f9b4988dbd512786b92779b.nq.gz
    ├── 2bdec1e2e2a11722f429bbd767e6121e8d063299.nq.gz
    ├── 2bdef64b3a7570eff340e8d0bee0e06324585637.nq.gz
    ├── 2c35c88b089ea014ce07e76e2d97830da9c790d9.nq.gz
    ├── 2c393cafc2c935db66cf403bbf2cb0bc04176801.nq.gz
    ├── 2c4cfa890193ec351b8b9407af7274339d4c0932.nq.gz
    ├── 2d1b8e057db900f545dca31c007edb4182ea8c0d.nq.gz
    ├── 2dd96d0dee605363cfd8e7b5658d07513e3778c0.nq.gz
    ├── 2e82f0c1d86b4f13123eed752e6250eac2ce246c.nq.gz
    ├── 2eef625904fa1ca08461a731777d4b4bd013070f.nq.gz
    ├── 2ef32a398c144f6ce9ad4efed13114ed84e71fe2.nq.gz
    ├── 2f000ecac6c9e392d8709fcc8bace14331cd78eb.nq.gz
    ├── 2f5062978af50345c547f32fecd4d5bf76da1791.nq.gz
    ├── 2fa5e42d8e4ef825b12f3bd00c45c9e87120128f.nq.gz
    ├── 318c6f1a2983c6e9dc9d33b65e816dca5a91e7dc.nq.gz
    ├── 31d50d1a374291ca182e8ead6e27c04ffec665e2.nq.gz
    ├── 320dbec53c1fe17a11336eec68c43fff1b3b8fe1.nq.gz
    ├── 35132b87af73ed429790c523846ceb17ec0d9fc9.nq.gz
    ├── 36859da688bbc82cf54a4d1965d57e129a6e032a.nq.gz
    ├── 3685dd2607b20b2cf369e766685431d9298261de.nq.gz
    ├── 3686337044e94ad1352c8f1ae218eb5fb83b6635.nq.gz
    ├── 36f52ecdea1eb06db522f80eceaa6d4e1967d56a.nq.gz
    ├── 37389605f2b5c5369c9abcae4c89bcc2ed8ba4f4.nq.gz
    ├── 379b02d3bc365c8ddc1a83457ffe3450f09386c3.nq.gz
    ├── 38636a7dd1d0bb194b995afe6d834a7568fddc43.nq.gz
    ├── 388c9382f6c138cfc2be9d53f3a09354562eb485.nq.gz
    ├── 38feb5ff2ca4a641e189ceb1550ffde603fb2f43.nq.gz
    ├── 3a1da0909b09c741f8162f4e6e2031a783251d2e.nq.gz
    ├── 3ac8308b142e14a2ba6090de7f55c7f09778684a.nq.gz
    ├── 3b28ff6f899f1764814cd1581d252f806cb077b1.nq.gz
    ├── 3b8ac8b4c6839373b68504e094e250f5e1520588.nq.gz
    ├── 3bda1dab037de08e7cf2e8cb0836b469c46714b0.nq.gz
    ├── 3c489a070e3d576861a8979d9583ec78f2eb3118.nq.gz
    ├── 3e58d469ad64a5d781b0affa6d8205be7cfc4fa6.nq.gz
    ├── 3e79f80800eb0f67697a1f0125f4cfaaf32c1e0c.nq.gz
    ├── 3e93a0aaed172856de12c7f1b77a8cd51ad67dab.nq.gz
    ├── 3ece647fbe349750c7b0bc8b756dbb46b8db92bc.nq.gz
    ├── 3fa8b7381c8ebb9dc09fa4cd0a1724fe1b78d8e5.nq.gz
    ├── 3fe2f1d83e235ee2053144165d11b60266d849cf.nq.gz
    ├── 400076411a6ce0bd9796969f1287fbfbe973ad22.nq.gz
    ├── 401642705daa565024a6216e16e6b958bbb5d3f5.nq.gz
    ├── 4029ce14c57b62e45b792f45482397700e896a58.nq.gz
    ├── 403d997bd95a80548b6fa3dbb166fe0f0da3857c.nq.gz
    ├── 40c1c57b0d4f22f3bc0f5d8f4e08ea5274bd1314.nq.gz
    ├── 40e9f1e1df50dc40092f5eb1f721de8dc75622c3.nq.gz
    ├── 40eb61906cf379f617d47b505f2f9db23c9712b7.nq.gz
    ├── 424df0a2767144c8ce0ac57789f738602c6b0859.nq.gz
    ├── 43c929650aab8bb58bbc5ac7a4d693f85c1f60f0.nq.gz
    ├── 43e9165c007f45990f86833e9ff49bd1fa31ecc9.nq.gz
    ├── 4484831d35c114c7aa65d5e63a030781f1e03d03.nq.gz
    ├── 462ebb1886740d9fa2465952d5990b2159229b19.nq.gz
    ├── 47664969949325693912aa09c1c8ec5090e6d9d8.nq.gz
    ├── 47b192ec93602df80556000597f2d2098e480781.nq.gz
    ├── 47cb75435aad3afe24c9a2364d5a4c97f639e5e5.nq.gz
    ├── 4897aca98a6e458af32f91a2f3ac60bf51145e69.nq.gz
    ├── 4969446bc530905b37af467ed2ede271e46baffc.nq.gz
    ├── 49bd7a1e8f362f78fb93c9867bd502df4ca5a822.nq.gz
    ├── 49cb5a0c92932dc2ae61f3c48086da328b7b6a31.nq.gz
    ├── 4b4f6f0f6694b5cb2099ead1de3af9a15c00f5c6.nq.gz
    ├── 4b5bdca9edff49eec1e5d3358acfcb751fd73858.nq.gz
    ├── 4b5bf318e044b6900811f53619a3dbb1b1b7c656.nq.gz
    ├── 4c36a1a7655ebc0b981d571e6a39cfe7dc240896.nq.gz
    ├── 4c38deba3e9eaac0bcb5acea60d302fb6a987930.nq.gz
    ├── 4c768d5dd80b5dcf9c1ae7c7dc3e76359897ce55.nq.gz
    ├── 4d02795fdc46001ca4643a0b5fbf282d4566a53d.nq.gz
    ├── 4d8de4317199b3cb52592962d47341da803e4106.nq.gz
    ├── 4f699a35d5e0d12460464c800b93d1422ba8bf4f.nq.gz
    ├── 5028f9fbcd0536a9e54f7325b417eafe1e41ad8a.nq.gz
    ├── 508cfd9aaac7eddde8690ab3d35e930776bf87ee.nq.gz
    ├── 50b27936fe8c74d75241be239d37d51b66dfe83d.nq.gz
    ├── 50d1badb7ffe840b897941179cff3ed53eb91327.nq.gz
    ├── 50eca30628ad0b0fc240880a002f344aa8c66927.nq.gz
    ├── 51000704a5de15b275c10cf092b6ec6783f3efaa.nq.gz
    ├── 51788538108d0d1f1d55543c7f100a73218c0d63.nq.gz
    ├── 51c3c12cd730ea331104fd1276bced31ba452d11.nq.gz
    ├── 522fe1b918d7651fcb64e53c17fa3fd16816cb79.nq.gz
    ├── 5246fae4d08d30c23ddbaa52c9b0912ae5029cd3.nq.gz
    ├── 524e151daf05eabb7994c35bb608f1ffa78258b4.nq.gz
    ├── 53c56a8ec8ba727848585a44636e9bfad6a30cb6.nq.gz
    ├── 54d6b51c7639399b89948e98e064484a0d122077.nq.gz
    ├── 55729ee37d8734d628b1a6949383d21225f1ce2e.nq.gz
    ├── 559c8417298f90a7b107bf6db4cb8e3fb583550b.nq.gz
    ├── 55c65094bac4809226824d0e20deb71f48dc5690.nq.gz
    ├── 56024a2a549afeb61afcaa99eb9db459f93541fb.nq.gz
    ├── 5673ec5e132bd6b2335170ad964cf7a802e209e2.nq.gz
    ├── 572de6686439f841e949d0f8b031f6f46f7bfbab.nq.gz
    ├── 5755117a06d05191772b449e75099d869a748f40.nq.gz
    ├── 587f8592fe9209b24fff900ab67f8bac9e233e10.nq.gz
    ├── 588e495faa426e512bf7c4fd6c0acfee8bd43b1f.nq.gz
    ├── 59cf583a6bcd4705a6081359fb2bb41c2c3f7529.nq.gz
    ├── 59d37981fd864a0f75909c56fd2cd58371338497.nq.gz
    ├── 5a2367815f390b72dc7d161c8ea04bedde17a376.nq.gz
    ├── 5b56d9536e78bede7e743b4ee96ffc1e8d8e5add.nq.gz
    ├── 5b97a0368e939fd64be18450c5f1b1568fa788e2.nq.gz
    ├── 5bdff70e812957cd9da43930066b72eb1af387e0.nq.gz
    ├── 5bf7abef6b2c47fa91487bc154cbd8ea6444b3f2.nq.gz
    ├── 5c64e7896f92b24b6623fae1f6d5c4a54fac4086.nq.gz
    ├── 5d21e5336f5cd4511c0f08b50d636b429eb950f5.nq.gz
    ├── 5d5f5289b6cb48387bfd665893fc1adefd55e2cb.nq.gz
    ├── 5ee1cd201c0e26f67ccec67900487af171c33081.nq.gz
    ├── 5eeb6a1a26bff1f36ceba68b98ea3defe6beeb84.nq.gz
    ├── 5f078d16839571ccaeca2a1a378859d660d4f176.nq.gz
    ├── 600594d84e4afbf4e437cda93d86b236a87fa70c.nq.gz
    ├── 60dca722ff0e9a5c75470be307a7defbd851e0e0.nq.gz
    ├── 61d7e76ea44db3f4732405cccd518637fda9ad08.nq.gz
    ├── 627418fc5970ff22442fdc7453f3185894051f86.nq.gz
    ├── 629141a41cf6ed57995a01817d06fbf1fbb81a83.nq.gz
    ├── 62bf3d8c81e3e17dbf28f79580f3d8a6e7e9cee5.nq.gz
    ├── 632a63391e7d8d2453f836cdaf3ac6db322a0079.nq.gz
    ├── 63badc13854787d78b2a97dad1ca0f4a86f72534.nq.gz
    ├── 63c59039f9d3675acbb623caf1ed14a55ae8b6fd.nq.gz
    ├── 645309b9d6416a5046e2c5ceb13b5529e9417c43.nq.gz
    ├── 64f9e1c7b82cec89aaf585681f6fb8e33f6f6cd5.nq.gz
    ├── 667c5039650a21a4b81cd7427fbf365bfa692b32.nq.gz
    ├── 66cfe0561b92eda7e01985752c86c806b0e4eb5b.nq.gz
    └── 66d1874c3b10b5e3beec29575ea8043f2d0f5fc3.nq.gz

8 directories, 200 files
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

[block/elasticgraph](https://github.com/block/elasticgraph)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
