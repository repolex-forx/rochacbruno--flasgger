# Repolex Knowledge Graph of rochacbruno/flasgger

RDF knowledge graph data for [rochacbruno/flasgger](https://github.com/rochacbruno/flasgger), parsed by [repolex](https://repolex.ai).

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
rlex download rochacbruno/flasgger
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb1a86b2d71ed0bdd3e8183570a9ce9d1f5abac1
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── bb1a86b2d71ed0bdd3e8183570a9ce9d1f5abac1
│           └── chunk-001.nq.gz
├── blob
│   ├── 036c4d135bf954ef3c2b15bc6493f72a01909aee.nq.gz
│   ├── 03c7626d7f97066362bcd4091efe624525313260.nq.gz
│   ├── 05052feb34361e2a801a6683e932a176b10a0dd5.nq.gz
│   ├── 05314b634340ede210ac1ef2677315261d1755f9.nq.gz
│   ├── 06393889242fb3ea9e0205fa84369ec7bb66d15a.nq.gz
│   ├── 07bc617e9084f44aebcf92096a4a52633a398371.nq.gz
│   ├── 09043cbfeeb47a6380d48dcbd022bbad209547be.nq.gz
│   ├── 0996601d760817e56a7ba63a2d31e03a51bc704f.nq.gz
│   ├── 0a5672d7502ce42897506bb4853664b6ff31f6a8.nq.gz
│   ├── 0b71d7db0cfbd03e2c12f554ee5658bbb8f2f89f.nq.gz
│   ├── 0c0dc83f1e94637d21e01dcb83c36adffebbeae2.nq.gz
│   ├── 0cb6a7125ff13ef7eba6bf3a6e6fa9f6004523f0.nq.gz
│   ├── 0d54c6e6d74ecf8edc13a2bf0e4676ab8412df3b.nq.gz
│   ├── 0d9da13644b1d3948c8739b79fe954fd70719285.nq.gz
│   ├── 0e75437c0899fe98f55311e302c7c41b3a14ed78.nq.gz
│   ├── 0f0a922ac724916c9e62327b82015fa9cf481a41.nq.gz
│   ├── 0f7e13b0d9903d27a9129950b1dad362361504e4.nq.gz
│   ├── 102d817d52d1bc1c0dfc7f35751fdd49ec7152b0.nq.gz
│   ├── 108082363a2333f3b3c50764eab9b8b3475bb1ea.nq.gz
│   ├── 11623c7c3986169d5f30902a3fb84aab5033d66d.nq.gz
│   ├── 1192ad8cd6a715fb011b90239abb2ab39c18e508.nq.gz
│   ├── 13fa015e6df8ae7d20edabda9eb42bcaa71a7a2c.nq.gz
│   ├── 15896c441fd59e5c2e9bdab90816661de06cdcba.nq.gz
│   ├── 162a224ddd604f92692819f20ed275391285f103.nq.gz
│   ├── 16426a9c34b13bd4a65d18bab206a562b9477b4f.nq.gz
│   ├── 16caf0738d8a65f48f48c22edd4559dfce09b37b.nq.gz
│   ├── 176fa545db239edef69d753a90e91461e0b97c9c.nq.gz
│   ├── 17dc93603968a93fd7f084c4012609c31df85af0.nq.gz
│   ├── 19adba3e15715c2b3b2f787d252edd759a623fb8.nq.gz
│   ├── 1a85e7582eaaa2086b2afc2bdf786d671a17074c.nq.gz
│   ├── 1cbeb374ac17d20e750daf0a6498f3a2f68c9020.nq.gz
│   ├── 1d401933aa5992b3012cbc063e5339b32e6689a9.nq.gz
│   ├── 1e726a7cfce4130243a3de4bb2bd412000658896.nq.gz
│   ├── 1f5bcc48dceae4c1722836b32e5bfdc11fd007f6.nq.gz
│   ├── 249737fe44558e679f0b67134e274461d988fa98.nq.gz
│   ├── 260e66d5148b0b938bd2b9643adaa470ba2c57d6.nq.gz
│   ├── 27b0c1cebac610bc74175f4c43533765e5645697.nq.gz
│   ├── 280de821c09abb01eaeaa361454a8a93132ced58.nq.gz
│   ├── 2ddd8a2588e0617b22db749ec9daa3a2a847adad.nq.gz
│   ├── 2f435f961d7e7687b6dc6bc655177a0572d6ea5e.nq.gz
│   ├── 2f9a7cb64c2a24592a79cce010bace9bd29c0b99.nq.gz
│   ├── 318da19bb25d390b9d2bbfdcc0bfdbdc249ae66d.nq.gz
│   ├── 322a3f1b7458413d91a43c7a11b91da91b6e7293.nq.gz
│   ├── 388dff14bac6ce8cdb530badf1108115e4eb297b.nq.gz
│   ├── 399ad1c00ed075080b48d6528d3e48b7e1ef6b02.nq.gz
│   ├── 39edd9e9698f8f549fd5291b7348706bd8bd9758.nq.gz
│   ├── 39f7caaadec838e3c792c2833c7969ea652b15b9.nq.gz
│   ├── 3af61ad6e4cf74c31fafdb0e22de5cb98904c4aa.nq.gz
│   ├── 3efb2c4ce4d33ce715761a611025759b4a96d9cc.nq.gz
│   ├── 44d1c12a8722c0615c45c207d0c84489407c3137.nq.gz
│   ├── 45f8dd5a36db98416b39d0afe2a2c819c3bc9694.nq.gz
│   ├── 475845957c5ee1124a6e127a5d0ba394ca766b9d.nq.gz
│   ├── 477bf13718dc56928f313ef6eeb1c2b1a47db69a.nq.gz
│   ├── 477f19ead6357cd47dd51adadbe29cfed8fae643.nq.gz
│   ├── 49bf5eef80a6c8ed8170e52b399260d2ee3790bb.nq.gz
│   ├── 4c0fcab044418eb97bf17bb2ed83fa28426802dd.nq.gz
│   ├── 4c331a07a792f1b004b1c6822d873af9cc4a44a5.nq.gz
│   ├── 4cc576b22581f6dfd3e799c39072761587ae407e.nq.gz
│   ├── 50482ed9746501b05539e6c18119aacb69680cb4.nq.gz
│   ├── 52907e463657c4b46acf17e7140ef49f75542d88.nq.gz
│   ├── 57025bc9b4a590a5030bfced458e2816590c9a33.nq.gz
│   ├── 592744e957f77750ef69b4e90a4fb31b30f795c0.nq.gz
│   ├── 5a70cefed6a24fb327fb661b55d7638464ed3ff9.nq.gz
│   ├── 5a9cd515e5d1350df2209181f8885d0f81f19594.nq.gz
│   ├── 5bd53494aae230ee25556b3f791232b31863d153.nq.gz
│   ├── 5c3ee3ba93d8a5b424676ed24551c4356f00ea4c.nq.gz
│   ├── 5fab50bcd0549592969330ad5412f34ab2bfdbc2.nq.gz
│   ├── 602731acea01f924ef0c6c3abb1568e48c317230.nq.gz
│   ├── 609c20d9c86e4dfa7dc8fd58b90672aeac5328e3.nq.gz
│   ├── 622bfb2ca43a0d99de092c08b7ad9231f31c88a5.nq.gz
│   ├── 6635370f510bb9e97218f4dbe104663f9f8ec355.nq.gz
│   ├── 66b3508ec6f148821f770e8aaf9aedb2cfad942f.nq.gz
│   ├── 67e3e25f8362c71003430d52894260cd4c69413a.nq.gz
│   ├── 6b0649b3cc5d762f56148888417b45863ead560c.nq.gz
│   ├── 6b71c0926509ff0c9d16eda993bda190e79f97be.nq.gz
│   ├── 71fd7231f0d53fd5c4fc0f2d05d43ac9f5df2df5.nq.gz
│   ├── 73a5ff69353b1a79a9d627fd9dfa42f87b74d50f.nq.gz
│   ├── 7545ab142e5b0354f463dcdf9183d0ba003d71cd.nq.gz
│   ├── 771b6ec90b37650da238ccb76dc65fd586c28545.nq.gz
│   ├── 7747e0fa4aaa0582ad80f4d5171f1c62a9d30575.nq.gz
│   ├── 77f55a1548a9a06ab801b6840a112225a0d4f6b9.nq.gz
│   ├── 785c3428e25c86ec809657976b1242b1b6964ebb.nq.gz
│   ├── 796ab96df16c10524139dfe3a875c77211b1ca77.nq.gz
│   ├── 7b00c68d3656161a979ad0dbba9177dfa6d57de2.nq.gz
│   ├── 7c2b2874c477c0a0d7ee2245b5d776da35f61de1.nq.gz
│   ├── 8157577db0f0a7099535ac3806340f298cf01132.nq.gz
│   ├── 844f9bd2dba83d02a6adf85e69ea23d4856f138e.nq.gz
│   ├── 8470bf4a031c46d03e17d78e45d36514f31f45a4.nq.gz
│   ├── 8529c2a90bc2f381b6349871815d4ce2a4362948.nq.gz
│   ├── 868b2d3b11b597365d4a471462309640a696e009.nq.gz
│   ├── 86fce056541657e8164df3bc53cb9d698e3e6b32.nq.gz
│   ├── 881936f5d65cf9cf339557240190427b71fb7ffa.nq.gz
│   ├── 8843e8ce5a46781defd33d5304a0cb4191e72546.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b194e617af1c135e6b37939591d24ac3a5efa18.nq.gz
│   ├── 8b60bcf06a7685b9ea53983c125e7058906fbcbd.nq.gz
│   ├── 8eff02e9842da1c771e40aa1fe2913388658c780.nq.gz
│   ├── 8f05fa84f2196232662137149a1dbd4918f80a50.nq.gz
│   ├── 8f7460ec5a74483c4c43562659dd1f748c07ad34.nq.gz
│   ├── 918313665db2b6d92e639a0ecd412f9267c28b7c.nq.gz
│   ├── 92701951a054c448bcc561944490ceae50c7622a.nq.gz
│   ├── 933d8cb222aa18865e02e6078c81c8886fab244b.nq.gz
│   ├── 9469d743c75bbeeb92361e6635b2fd3a30ac452a.nq.gz
│   ├── 956273f132504099ab61c9ca43fac2f9e5d13a85.nq.gz
│   ├── 9575d51bad249b78b01fa517932882eb917cb750.nq.gz
│   ├── 95da73319d8dedee0101cf99e865742d23c3e435.nq.gz
│   ├── 964cb2f73f6433427bc8ba66ab0514ef2a6fc5bd.nq.gz
│   ├── 96f81bce745e779e85f578c769ff11707ba6eb0d.nq.gz
│   ├── 9c3b901beddbfd8f1863e2a48a7702a2ede1fa5c.nq.gz
│   ├── 9d57defadd4906b962158bf0d50107c012597f6e.nq.gz
│   ├── 9ecda7e9cd7b3fae5140a16af374b47af7c841d6.nq.gz
│   ├── 9ef2f954d679a96b3dd3e58b26181a4b3c869f3b.nq.gz
│   ├── 9f93f74c3bede4b96290650f7a21c98eb1e01351.nq.gz
│   ├── a0aa5a3fedf7f2c7f7b5ac3d4418be5e55703176.nq.gz
│   ├── a4c5c9d1bacf3248a568f440a33d2f67c2fba194.nq.gz
│   ├── a54bbbbf258aad7b1fe25e4773671e36ff72bfcc.nq.gz
│   ├── a572570593ff2e66c13eecc375d74b3c9cf19c2c.nq.gz
│   ├── a73432b571febcc9e111e00ee2dcbb9d0c3ccee9.nq.gz
│   ├── a757b23bfd23cb4a1bc41c7d0b6792aa5abb31e2.nq.gz
│   ├── aadc532980d3a44eb226cca99d1cbe3d97bb5d7a.nq.gz
│   ├── abf19899f75a0e8ab8e2d41caeecd8d764d3f08c.nq.gz
│   ├── abfdd63749b16f4e254323399130695a48c26b1f.nq.gz
│   ├── ac0d3cc3a3b8951d43b3ffe4c1dcf84c8c70af08.nq.gz
│   ├── ac2698e85aee584b0f47c0cccff8a8b9b16a5c66.nq.gz
│   ├── b016451b3865a06f5d2fe1a75122d0725b358913.nq.gz
│   ├── b0a3352ffd3fec6f2afb4cfcc34ec3a2976f45e3.nq.gz
│   ├── b31129663410b4e3d761663277b93e728be54cf5.nq.gz
│   ├── b34d63c859d9982013a0ba51231c5fabc2c2c3fc.nq.gz
│   ├── b3c5774dc544de24c6385ae3a84c55cfbf92bc04.nq.gz
│   ├── b4a8fdf518788026ea6685ffa69b56bd9cf5d926.nq.gz
│   ├── b52866affb46d9e52c36f729b3079184a3ea5067.nq.gz
│   ├── b6ca4be10e7c7c9dd9eb623380892e82d07790d1.nq.gz
│   ├── bb83d682b603febc65ea27241ab420d4e0e04765.nq.gz
│   ├── bd5a309782ff569fa83eda0c17c905fb012d1de0.nq.gz
│   ├── bde14dc742d42ced23d56d890427574265f350a2.nq.gz
│   ├── be43b27394052f1808eccb2758c6d0911a777f6b.nq.gz
│   ├── c1413324e9d811fab7bc4a76258a79a0f2792e01.nq.gz
│   ├── c334bffeac702d300d07ff2333174977d84c485c.nq.gz
│   ├── c3f3232c0da948a7a254a6000f47f69226694e31.nq.gz
│   ├── c553d1342506196ad218bcc9f626bdb5187ddf72.nq.gz
│   ├── c76ffb75fdfd606cec37b1053999e006ff8794cf.nq.gz
│   ├── cb74ced59848d8862f806ef0024ea00475b5c040.nq.gz
│   ├── ce3908e3f275ee790b38b28bdd03084cdf46bfe8.nq.gz
│   ├── ce41e91799dc7f12c653d98ac72a1c2eb08c5095.nq.gz
│   ├── d0f43f9ac1e9885f17ec5cd72583e16554eec1b7.nq.gz
│   ├── d29ca2010d5327313c3f1671a92d20180fb5dd08.nq.gz
│   ├── d547de4ae413a9f6c2ec4f94ea2b56bf85715118.nq.gz
│   ├── d65ca1a137b8d1e0bb6c55cb896ba37adc89b19a.nq.gz
│   ├── d7427b90b6890e8ba742f4448b39bd8da240b532.nq.gz
│   ├── d8524983ad8d296be95cb5b469efd1987d6e04e3.nq.gz
│   ├── d937e892d8761d1f70fa545193c6631596bb3fe8.nq.gz
│   ├── d9f2a214f9629c6e75b90bf503a21d0e622cb05c.nq.gz
│   ├── dc0ddab138f12d90a530d7bb5f460da6dc6472ad.nq.gz
│   ├── ddbd93ed4f4cd604077d986a4ad6efc7853ee947.nq.gz
│   ├── ddea83ccfec8425a0d92c68136d6e0b6c6a71ef5.nq.gz
│   ├── de6111ee02bd2924fb684ce0db0722f71e836a36.nq.gz
│   ├── e0a52405fe1a4134965a15f5eea0c492e98f92cf.nq.gz
│   ├── e517a0c5b9dfcdde4c4dee7569fa191b40f208bb.nq.gz
│   ├── e678dbb0a0c12e39d7fbfbaca61c15eb05e4bd1e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7da505936bfca9db003af9b846f7114a0959425.nq.gz
│   ├── e7ffcf41d481a7ee14304f475bd4598cf5e8fca1.nq.gz
│   ├── e88789bde2098daf33f86d11570d30105dc78aaa.nq.gz
│   ├── ecbc5e5eabe512cb919046f9837a9894f23e6af0.nq.gz
│   ├── eccf11c3713b9014d013a36b61972d45834baa28.nq.gz
│   ├── f02b60a562ef14101a9510242dacba4ebdacbc59.nq.gz
│   ├── f05ce62efc993a3a2e6432099d5b6ee8513feebb.nq.gz
│   ├── f18764c0eb061b11367ffd1c104a000e129d3048.nq.gz
│   ├── f2e7c13d4137885d841623ab947d133d1e8a564e.nq.gz
│   ├── f341f4390c9d0caf5715b8fb2e765ce818331e63.nq.gz
│   ├── f4a3d40ab77987ec6b5fb282b37c4806d29dc64d.nq.gz
│   ├── f4ceafc51adcdc6f486e202384172cca098cc898.nq.gz
│   ├── f8c815aa92cf7a8a2cdcf6ac3380aec4e29e5dc8.nq.gz
│   ├── fa155c60502aae154673f5d1f1418ad496051fec.nq.gz
│   ├── fab4c2931d759835d3ded0bfe800477523722fdb.nq.gz
│   ├── fb8cea662b2434571debae37fa6ba09fc5f24776.nq.gz
│   ├── fb9cd86000c1b797e3de97e3d24b931c906508b9.nq.gz
│   ├── fbb8951801eac55caf9004f080aceffa0a1defb5.nq.gz
│   ├── fcd1ffdd5a971079c9bc485534eaec61b604de57.nq.gz
│   ├── fed920191975b5e1fab3d1dd04dbbbfa67e935d1.nq.gz
│   └── ffb879f9a2762d8065a308d35b5a7609134df317.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb1a86b2d71ed0bdd3e8183570a9ce9d1f5abac1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 190 files
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

[rochacbruno/flasgger](https://github.com/rochacbruno/flasgger)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
