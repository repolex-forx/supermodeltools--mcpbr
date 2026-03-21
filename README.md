# Repolex Knowledge Graph of supermodeltools/mcpbr

RDF knowledge graph data for [supermodeltools/mcpbr](https://github.com/supermodeltools/mcpbr), parsed by [repolex](https://repolex.ai).

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
lexq download supermodeltools/mcpbr
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 001b11f9eb616c7c59a35c6cdb18c9e2f5afba7b.nq.gz
    ├── 008e94772eeef5e2de1d740393e1a73b4460fa48.nq.gz
    ├── 00ddc2c3ad94b53b50fa12af5491dbf7bcfc9388.nq.gz
    ├── 0165193ef8c86712e31fcb62020280f80f49ffe0.nq.gz
    ├── 01b32fa575e1d42dcd106d19fc507593ca1722c4.nq.gz
    ├── 026dafa93a729692abb94d804dacbfba358b7835.nq.gz
    ├── 0311be6ee2a59a7eac43c038999e551ed6dfafe7.nq.gz
    ├── 03771d03ccb5da4c833cf4ea84b1a641d9ed751e.nq.gz
    ├── 05bd82c684370c0fabc7248ebec1dea89c4d562e.nq.gz
    ├── 05e74aa6027c57ab487a99e1c4de34aed2cfe340.nq.gz
    ├── 074af39f0b5cf40ff0879c2cc5eb24ce909237b9.nq.gz
    ├── 0769acd62494006a1a4a18b18aa920a68943fdbb.nq.gz
    ├── 089aa7c406ed54b42cce2c2ecb7852f9863c3270.nq.gz
    ├── 098dea70c57d53699380cab2f345528e86968a43.nq.gz
    ├── 0a2bde3caa439335583c65641cbd18c974753138.nq.gz
    ├── 0b655d758371c3a5f8efd4102815067c021a19b3.nq.gz
    ├── 0b6b29e8a7c084f367585df74e6829a8dac17274.nq.gz
    ├── 0c06675a21b0573ec6c2c55ef529ca40eef54349.nq.gz
    ├── 0cc2de8a842b4fdf8104b83fb864e4dab9fd57d9.nq.gz
    ├── 0ce340e578d5fabcb56e9a2aee483713acb511fc.nq.gz
    ├── 0e476bf895114189111398986debc6d1a5b9f9b4.nq.gz
    ├── 0e7903498c3e67b02c022be0dcc3494d895d7ebf.nq.gz
    ├── 0f328c0b78ba581edbe42c5cedf7349ca392899d.nq.gz
    ├── 0f5f7ae36080a4cc37b11228951b0b5b2d43a238.nq.gz
    ├── 10598cf142f07ccdbeeace27967042db040d53a8.nq.gz
    ├── 109c290c70a54d75bfe2175ff70ba65fe67be808.nq.gz
    ├── 10ee150bb67cab9f9ec57f24e4f5759ea9430738.nq.gz
    ├── 10ff6dcb14310294ba322d52dba3ba4441e80a76.nq.gz
    ├── 1105715eed8483805534ad8592661f3766d56b65.nq.gz
    ├── 1159fca907f29e654dab32a42b9677372e066704.nq.gz
    ├── 11a9e67033d745a0a231d72898b9dcdce54d23c8.nq.gz
    ├── 11b441e58bf61517175b1adf88397bdeaf96af28.nq.gz
    ├── 122b2983cfe186bb54401d3823e8285e5d62858c.nq.gz
    ├── 12e4e10655caec8eeb8933a20b3a04e528db4640.nq.gz
    ├── 132196fcfdfc31c03965d95390661d2b7bb63d50.nq.gz
    ├── 132d3e91da8badb27fc760d487b0ea8cba385ec2.nq.gz
    ├── 141468ca5d4bc451b5d845db121edd5781a38ba1.nq.gz
    ├── 150c936e249364871847f7378510335402e551c7.nq.gz
    ├── 1541c166016a7538f468b5ca56f3422f1c385e9f.nq.gz
    ├── 1555f42c9b185a38f7c818a4404d44808285c24e.nq.gz
    ├── 155a40a5211dc02b91e62bd34a0cd5ee3ea16d1c.nq.gz
    ├── 157f5e9397fc6a93f573c2f6fcf445c657f1b81e.nq.gz
    ├── 16b89c681eff5bdc7895b1bc8ea65239830568dd.nq.gz
    ├── 16dee89c7637e3378315ed9e91fea35ffb999f8f.nq.gz
    ├── 186cb853ad4bf0d2df7bb3a87a8e4ac43178688f.nq.gz
    ├── 196077172aea211a26397cee39371a7e931a23c8.nq.gz
    ├── 198a477b0fff202f0f4a4e9f4a21e7c21faafcd6.nq.gz
    ├── 199c3f395683449b133bdd20dae6bd596c4ef18c.nq.gz
    ├── 19b62d8dc6da545a822929246c46848e7d9414d7.nq.gz
    ├── 19ce75c0b21ff7cf78e984ff8c46f93efad71a2d.nq.gz
    ├── 1bf94f2ce5d59d093f451c7d1e98a17936b47169.nq.gz
    ├── 1c1fd11cb87b3b430b0540c62e98eb3086108628.nq.gz
    ├── 1d498d341b39d2bae2af4ba263c8cbace44079f7.nq.gz
    ├── 1dfd60a2a388e44775e540bda8127c49b5230f71.nq.gz
    ├── 1fdd2a49a7b928114449dc05293306fb39d5dad1.nq.gz
    ├── 209cff5f5d7f81f49ed629cc9495979d34b0137d.nq.gz
    ├── 218f8856acd0cb3fbe94c7679b8039b80439a877.nq.gz
    ├── 23bf3e84aa37ed71cdb9b38ea6d30a0a8bf579fd.nq.gz
    ├── 245ef21321d8f8a1777dd691b2fc2b8d2832e846.nq.gz
    ├── 24c6c1b30e54e6f656729d4f9a060202fb16e377.nq.gz
    ├── 251e845e68d32654203366673ddf1449374c4a69.nq.gz
    ├── 253bc2ef8a165ddb3afcb08644129b2ba73ce85c.nq.gz
    ├── 256aaa85a2de27a5e3ff06914641fae5a4fb156c.nq.gz
    ├── 25a8cc26671c18c11bfad3c5c00ecf4aac3aa2fd.nq.gz
    ├── 2628e93feb5452bb0b929afb43bf0e0216f4dbfb.nq.gz
    ├── 26667a58734e07ea14ece677af3447eae27b7bb1.nq.gz
    ├── 26bea15bf5dcd72eb058d9f1bda914b943c2f2db.nq.gz
    ├── 276c0694df12d738b2e3e2915bd9c0244f688eaa.nq.gz
    ├── 277272cccd19d8c5a24d547118f647b89956d696.nq.gz
    ├── 2775ad7e361db21497342c9835f7209c8b57255f.nq.gz
    ├── 278f596f4c0bfd5a0b6155eca908c6daef739cc6.nq.gz
    ├── 2a0e7d2a01b3ab0f8cf57f95f21291d9f3737389.nq.gz
    ├── 2aa60cc14993b8b57591f8b0f98cc1fdcd5d0a90.nq.gz
    ├── 2bf963eb8a9a37c2b7d482c9d4b269a99bdb1ac8.nq.gz
    ├── 2c2263df14df55f70e2e750c98d815bfde698a00.nq.gz
    ├── 2cb1d2ae862341ff744f2747d778947b7c78b33a.nq.gz
    ├── 2cdc067547e50169382704f5bce96ca2ad2e6bcf.nq.gz
    ├── 2cfe166c920fba0f03af541713c6c78a64676d5c.nq.gz
    ├── 2d1c601465ea8ceceb8aadad8e7de54bc839a437.nq.gz
    ├── 2d38c6a689e5272e64cb2bd3d22340134a903634.nq.gz
    ├── 2d695536067a282beea9b224f6cb0d582f0e184e.nq.gz
    ├── 2d7197ec10570c9c1bee666d96c28ff9fc0f8beb.nq.gz
    ├── 2dbcbf42466cc6408e707135b245f00591bd5bcc.nq.gz
    ├── 2ef563cfe6b58a55d16140dc3c67ddcc3a53104f.nq.gz
    ├── 2f0863afa22a6d0a55daf19b9382edb9c86f1f0a.nq.gz
    ├── 303c91beffdb6dd6308d310597ce7dfce0c07146.nq.gz
    ├── 30b7a3055e1ce086411b554432bc490fa8ad94f2.nq.gz
    ├── 30da203286ddd7e282affff07f10f93738347e54.nq.gz
    ├── 30e704c53aab8115e27c7988ddf77a4de8c0d01e.nq.gz
    ├── 32daf7f074dcc905b84b65e0a7031846b5cf3526.nq.gz
    ├── 3367ae59af6e4da4dc8a188080e78ff160e98820.nq.gz
    ├── 345ed7d4ce3924f9eb61dee89fd60d4bdb2580cb.nq.gz
    ├── 34c0ffdf9e754757fa43b7ddf10ac5b8026b7675.nq.gz
    ├── 34d99c4fd4a18e6fbb648fdf6206432894cf4088.nq.gz
    ├── 36e5aff36b05c714191898056fd67cbc8d124d33.nq.gz
    ├── 376b2eb1c7f777568da4389c11f8bbfc612ac660.nq.gz
    ├── 379c4adad28b955710f8c05bb59a5abbd2e0baef.nq.gz
    ├── 37ebea48989123681973fe42754f0b20ad0962fe.nq.gz
    ├── 3800c077d9dc436c63f80554115376f05b2a3460.nq.gz
    ├── 381add963ea0cf09c46fb33c428da9d904dbb050.nq.gz
    ├── 3838a31936552087d3c89301128978f4265437ec.nq.gz
    ├── 386d701c682dd3de8ffd883428b4c0be8b67162d.nq.gz
    ├── 3871038db299902137de909c0f241e3855204ce8.nq.gz
    ├── 3a052172e06430dbddcd795f556b332307ee335b.nq.gz
    ├── 3a2b8cc84251173bf19c482adfc4afe6178a3027.nq.gz
    ├── 3b7a5a68371b7c98c77b40b7544c9a49b58342fb.nq.gz
    ├── 3bad9617fd367e222c5a5edbffc3ed904cf90746.nq.gz
    ├── 3cca38f3e505bae9f6866af5f3f03c6ad5ea0496.nq.gz
    ├── 3dbfa4618cc6154e3ddede3dac4ea4e651090fe0.nq.gz
    ├── 3e388680e294766a3f5a9d85fc00469c8c192ff1.nq.gz
    ├── 3e8c1a9ddb6007b6223cdcd50665c44b7921e5dd.nq.gz
    ├── 3ff090612d150ae0d5644014e0d97734af3cc7cc.nq.gz
    ├── 41701d2d63c6f1dabaf4ba34ea3d61f389ae5323.nq.gz
    ├── 419ceb9a9be7d71b913f3cdecf25c5fed9344a0b.nq.gz
    ├── 4323fc3cb9e44c71cce8978265d2404daaaaf2f1.nq.gz
    ├── 43454a2bf80a7b66782b3b34c4c13ea0d4b8523c.nq.gz
    ├── 4346f7f6e01f821609064da055a3f1123738432f.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 43d365fcd2b4b5c0366496f1dd105dd31a06e36e.nq.gz
    ├── 459a7122df8098ed381fb72ba7a8b3bd6317f1fa.nq.gz
    ├── 46ea78da8787a218e2bdf8d2b0472e9654515844.nq.gz
    ├── 470e0f4d0bdc6b73d7c497d1f54c33e0441c697e.nq.gz
    ├── 47af63f0142c2b4dea6a396811c48aac40841c62.nq.gz
    ├── 48907ad64f1bc65d8739291aa98b0361ad29a173.nq.gz
    ├── 49420f3f2af4a0fc3a6226454675af4b184410d4.nq.gz
    ├── 49a8797c1fd49872d961241702c3240385585380.nq.gz
    ├── 4a60db52d6100856922867c86101d2539a4ceb06.nq.gz
    ├── 4a6ec352fde336b1bfaaaaaaf03befc7b772b4b7.nq.gz
    ├── 4ad34943415061724e68dfc385d95134efc73dc0.nq.gz
    ├── 4b4b07ab9489bd150d3e1573d6291963f8555506.nq.gz
    ├── 4bc74537cbfa2220ce0d13120b089be220cf6d72.nq.gz
    ├── 4bdacd948ad692a2df0f03259f05da411d6f9302.nq.gz
    ├── 4c49dae5340afdabf7cb51f359a4c7c0cf36d9d1.nq.gz
    ├── 4ced527f81fc6aef15f2395c82e2a445d7ddaced.nq.gz
    ├── 4eb6af00eeb1bc27b0ab2c4ad00471814496536e.nq.gz
    ├── 4efd483df8276a88ab6b5ccde23efe0085cca58f.nq.gz
    ├── 4f9185a251e8f02699d9aa22193059dec7922968.nq.gz
    ├── 4fdc179f5808673bbf6429ca7d7e5dc6725bfaf1.nq.gz
    ├── 50160a67c15957fe6a42c844d194e4c0e77b0ae6.nq.gz
    ├── 502f72d0fcd39fdadcd0ee2d15a57a18e94722bb.nq.gz
    ├── 50df5d8153b224a87c3c6f391466e9b0c90520c5.nq.gz
    ├── 519dcaa746296765677a066126e39b4dca6d872d.nq.gz
    ├── 52a47ca18f0b7d9f86311f1becac420b3ad4e2ee.nq.gz
    ├── 5406f6e8c36c8d1108df5eb90c736d4ba6280624.nq.gz
    ├── 547cc858b0df875d8f7684b5a0ead461c1a91710.nq.gz
    ├── 54be45ecba4037b721c960e2605369812284bc2b.nq.gz
    ├── 555e8c0cf015038e5ceaf566d2bf6c92770f30e9.nq.gz
    ├── 5587de69ad3c00937958edc6e33289735903fa43.nq.gz
    ├── 55eb3a0fab095375bb099a4f86ec36ba83e6fb78.nq.gz
    ├── 562163ad6dd5407d47c50654d1be2e213ed6900f.nq.gz
    ├── 5649f255ccf9e30a5e0fafcfa02754c897ba150e.nq.gz
    ├── 596e0453bd786d31695e194e82d0559fc60a339f.nq.gz
    ├── 5986b5483f735d219d665e985e1148a3b4ccf375.nq.gz
    ├── 59b50a6c79c8fe5a28e1ba4d2f3703d9b040e0e8.nq.gz
    ├── 59cd874329bb4a74145d35e7f368d5cc5cc772d7.nq.gz
    ├── 59e7fe276e2d18390eef1e2fdc99ebc9f1b906b6.nq.gz
    ├── 59fb3f46d86fc3e5aedd0df449d497ef94af3e19.nq.gz
    ├── 5a2d32a63dbe6a680d3df02196ce57183858d0a8.nq.gz
    ├── 5a492d1bd53d2fd01182433dfc1880a703513f1b.nq.gz
    ├── 5ad73fdf4ef621309fb074742cac9cec191c6622.nq.gz
    ├── 5ba2fb51ca3f9ec4e19c294c4394d3b9a1acaf66.nq.gz
    ├── 5c78e02f10bba07fc23c38e69dd921265a2e4df5.nq.gz
    ├── 5cbb454199da719b99e021b0f78e1f943f340ba0.nq.gz
    ├── 5d0f7a3d9cf2f6aa57560a2b0ac0adcc725f1f4f.nq.gz
    ├── 5d1d730ba656824f780f2dc6a372bae5459e9b5c.nq.gz
    ├── 5ec7eb465f2f39f144f2472613263e23856c9ab7.nq.gz
    ├── 5f039a095c9bfda01b38eee785b84110ba154b0d.nq.gz
    ├── 60fde105f3094593bc62fadcb0b809c0b82c105d.nq.gz
    ├── 61222671404d21037c0ca1553ded0a9303820d78.nq.gz
    ├── 617d070cf4fbc2bea8c81d91f3b114930c9e1b0d.nq.gz
    ├── 622466f116cfe1f8d3907401ea5c169d8fd5d80b.nq.gz
    ├── 628054309bc21ee524d3bef0fe9566a9a255efc1.nq.gz
    ├── 63502f08e990e74c1c6deb2e850b2797724aaa93.nq.gz
    ├── 63ab350d0ba406c1df586796c8bb15ef523575c2.nq.gz
    ├── 63d4a4af5f1ff7db38506ae6a40bbdb340159204.nq.gz
    ├── 63dcb0790c8c9c8c245c3822303ffcc1a095f609.nq.gz
    ├── 64b55f209797212171b993c294ddd1026507d1c2.nq.gz
    ├── 66feffac9ef8babeb5d3ba2b95f257fb2fb412fe.nq.gz
    ├── 678742e4eed09d171eeefd3c8794ee5e738f5291.nq.gz
    ├── 686ec5deb8d991575892b8791d286c09f864beb4.nq.gz
    ├── 6965067a3b411452f99a39ac1cb39b58cc23c002.nq.gz
    ├── 6a5916869392f62b571ce46acdb6e91b422720d6.nq.gz
    ├── 6a862c82c10c072fe115bdabebe016580c646908.nq.gz
    ├── 6b58f6f2483acdd52669d4e97e3a981f38f98b7f.nq.gz
    ├── 6e5c5d3962ce67cf9ee6e8291a53e4364366611f.nq.gz
    ├── 6e969b10fc44dba1c36c4921cf8622b28c4ccf47.nq.gz
    ├── 6fefed4c0ec1b35effadd61deae6c073aa44db8b.nq.gz
    ├── 71ecf266ba93d176cd76a62d8c43d32516d80a3e.nq.gz
    ├── 7294c00923743040f54c22cf534282c71055d3d3.nq.gz
    ├── 72abb4a6904e70b075fcf08e823221b2a81a299f.nq.gz
    ├── 730f9f5fb6a64bc3bd1b80e5cc082ce561fd89c8.nq.gz
    ├── 73b3bc0033925c66ab7817fcdc63079ac9a463cf.nq.gz
    ├── 73d146dd4a29ddd93775bed22d429e11002304b3.nq.gz
    ├── 741b276fcfd85dcb1f955a0093c5eec6df3d5da5.nq.gz
    ├── 745fc6088e69e4569e87bffa7c2369a60a79335e.nq.gz
    ├── 74e99b8bc3f23bea733c66dc0a6d945d61eda66a.nq.gz
    ├── 758012710ee94a5fdc5058535bd7a27976e70c8f.nq.gz
    ├── 75a4454118a87cbbbd7c5a817a28aae48079b36a.nq.gz
    ├── 7824bc20cfd40ed309663a5bb4df864943980d5e.nq.gz
    └── 78b1b708cbc8e2c133c0bed70991b5514de12642.nq.gz

2 directories, 200 files
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

[supermodeltools/mcpbr](https://github.com/supermodeltools/mcpbr)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
