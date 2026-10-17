# Repolex Knowledge Graph of outlines-dev/outlines

RDF knowledge graph data for [outlines-dev/outlines](https://github.com/outlines-dev/outlines), parsed by [repolex](https://repolex.ai).

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
rlex download outlines-dev/outlines
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c52af8472c6fe8a607a733ec11b709476af77a96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c52af8472c6fe8a607a733ec11b709476af77a96
│           └── chunk-001.nq.gz
└── blob
    ├── 004bab98d1afb78211e0f59c8cff25b83f8637ae.nq.gz
    ├── 007c376da12131606dfab5cfcde6928f319fedbc.nq.gz
    ├── 00a62544818c3e33102ba86f87e77b631cfeb299.nq.gz
    ├── 00fc1c71ce97c732e4c0d3a869a1c040814ad618.nq.gz
    ├── 031f942b0f9533d811b31aa3c5d15e3fc9741f23.nq.gz
    ├── 033e918701b0c54f9a18669fb9cdd739cc1ee41b.nq.gz
    ├── 05761ac57f6bcedf28c34c3867849df97ef89a8b.nq.gz
    ├── 061ff594c8f7dbcc5126267e39e1f0a98d75c9b3.nq.gz
    ├── 063433ad202fd3d2e1d78a36eb75fbf3a7589e33.nq.gz
    ├── 064cab087f2f655d3074942c658fdb9f82f37265.nq.gz
    ├── 09583f42f00c9bb1e1acd8298a7ae2c9a17028dd.nq.gz
    ├── 0a2c59775b836638532b680c8fdc6c2b69f07102.nq.gz
    ├── 0be6e0ebf94eb6a0964f5fef8b0c2bbf7f0f760c.nq.gz
    ├── 0c9eb2acef001fea1208eb7e03754b6a044001f8.nq.gz
    ├── 0cd759abc48b8ea69b73b7d80ce4595c0b4ae1e1.nq.gz
    ├── 0d705ba14d305c95e0ef269519099fe4433adf9f.nq.gz
    ├── 129be4582c7aaccb9c0c1d0ae6952d54d4b2fca1.nq.gz
    ├── 13ba45f3e260e78ec42f44103d3d7f1bb16883f7.nq.gz
    ├── 1489aebc782a145d793d3c7f5ebf1a115825ebad.nq.gz
    ├── 14a6b37d9f5ff933066b5dd8535f9b19968d19ca.nq.gz
    ├── 152eead0177f65db68c8828b4668e20df703dbb8.nq.gz
    ├── 15f64018e6b41458d250e2b9ff925b3e02370893.nq.gz
    ├── 16b4c55595b4ab3c9cb9c5d633f0fdaa33e1b59f.nq.gz
    ├── 16d4c44a46ef92b330b6fcb8ab241a91918bc9c6.nq.gz
    ├── 18a933b47613eac81d2675abfbd6edbc41d915d9.nq.gz
    ├── 18c57ce6c237fc8b737d49f87ea60b3a531f58de.nq.gz
    ├── 18ec43fce7f0da725cc620d4666e9b36d22ec2fa.nq.gz
    ├── 1a328a9b6a9d55e911028d3e43ff525b5746e67c.nq.gz
    ├── 1a87f3e52071f98264b68269711e5fab0976b9b0.nq.gz
    ├── 1b65d1894709ef2c96a85b31cc38a7da1e0dfc1c.nq.gz
    ├── 1bdf8cb61ff415b10450a9f4a80bb235f048e694.nq.gz
    ├── 1cceb26ce3f6dcc98e6c60c68edcb0045b47b9b0.nq.gz
    ├── 1ead9972879c29e17160f1d3ead150482467b1e8.nq.gz
    ├── 1ed0e876d39c0d88f482ba032833f1561217e94b.nq.gz
    ├── 207363764d7c10b5d16ace9fae0fa03fcebb8d31.nq.gz
    ├── 213db5e958976c9d9b52bc85e5005a064bfd5b4e.nq.gz
    ├── 22f9e9edd013bd071fd3091bba4221a48ad1ea10.nq.gz
    ├── 2332650c63c02b5f3ded849dc61542170c922038.nq.gz
    ├── 2368983798a7e4548b29eda6154979598a26fecd.nq.gz
    ├── 23922d4e9476dcd0d3f457828807271ff58b1b01.nq.gz
    ├── 24c5f3bc36cd271902376dcaebc7c667f9e909a4.nq.gz
    ├── 259b942f3d7c20c8864b7e9a9b6f5cab0ef4b5c0.nq.gz
    ├── 275aa492ef2f99d0532aa79bf709b3799403ef6a.nq.gz
    ├── 28d0d0ddb561bca80a58c74ab15b79e93a6941db.nq.gz
    ├── 29354d58cce72e62d40ed8d5ff4186094912fb1a.nq.gz
    ├── 29f1f8a7463e56f9838b34059bff90f21d71b11a.nq.gz
    ├── 2ad0407f3ee3c265e4b526bc70d45a40dceb35ff.nq.gz
    ├── 2b89b72680c6dff599fc96dc5a2cbfe014a48903.nq.gz
    ├── 2c1b9321ef3de0521d5ebd7181a02b8532112609.nq.gz
    ├── 2d52941fdec524537373218393b2c865060149da.nq.gz
    ├── 2d6d985bddafca57ea8ea0c85e599ed774f8ac06.nq.gz
    ├── 2ddeb04fa2c712a7ba8b7bff49a313c9286fff4c.nq.gz
    ├── 31422734e45f9c2977e8730bcd88ffdb17148dc4.nq.gz
    ├── 32205e5b981cebff4ee40f4eba6f9709cde98e85.nq.gz
    ├── 33bdba058c3e9bd139d2835a7a3f033bcf86b4e5.nq.gz
    ├── 33e9e5888434f24ec087347b62860814245030e4.nq.gz
    ├── 345f6277e05770142af72b27d334f6d631782c88.nq.gz
    ├── 34b66c3b0efda837c7fe163b67f8e56ae952ad15.nq.gz
    ├── 3582afa074d73bd29fcbf17dc1a20ffbc9910c92.nq.gz
    ├── 35abd947081793bb2a727fadf5b720b22107d7f6.nq.gz
    ├── 36ec9dfe7f98d47c3c19563c9d085b3fde78e84b.nq.gz
    ├── 36fb621841f4f89ab280f4f040738a312174b601.nq.gz
    ├── 370bac90181869c000159aebd53737342b616bed.nq.gz
    ├── 37a918b93ff7c7c2d6de7b411cce512f16d07a95.nq.gz
    ├── 381e2fe7ea181d4fc05c4cd7e9aa5276d07a33c1.nq.gz
    ├── 3876a3fedc342cbf29b3b28210f4201eb2127b82.nq.gz
    ├── 39b1c1d6b3f973d4ba9350d07f9f4f72b66f9a2d.nq.gz
    ├── 3e52f4707dfdd972597f22af6360e5cba2d843d6.nq.gz
    ├── 3eced88783f7a98f809fbceef71c570cbcaf009a.nq.gz
    ├── 3f387cfa4f427142a9a9c936daa2edb52b1bd378.nq.gz
    ├── 42c91e3d6e0dd99605db7348af27e89aa7cd64cc.nq.gz
    ├── 42fcbeb51185b9dca953c105b23eef8cd6cad866.nq.gz
    ├── 434063aad878d66a1dc8d68731239c06b1da9662.nq.gz
    ├── 437fa643d31fc8e36c0bc13fd715fb9120c0bb42.nq.gz
    ├── 43d70da33f7c8309d5a05c94f79a0bf742c64e20.nq.gz
    ├── 4512720a3074ea969cf7f92c2d0834fdc938c0e5.nq.gz
    ├── 47b00bd7864450815d74a2b2624cfaf26936fb53.nq.gz
    ├── 47c4969c2837d68f305e5717ac012e97df48e40e.nq.gz
    ├── 4a00ceb004f6b85a8747176cc0902f5b7a989407.nq.gz
    ├── 4a05609e272f7f877161dea964c7ec80e9b71e23.nq.gz
    ├── 4a817906dc075f0ff45cf541edc8b037704647bb.nq.gz
    ├── 4b4b34187b9bf768dad37fe1839a95c96c3f1afb.nq.gz
    ├── 4b624e96043f9fdd3dc061040f645f2e5e93d689.nq.gz
    ├── 4bdc7282eb36d86ff69d3b45e417fab6eb3e62ac.nq.gz
    ├── 4c5e505eb43da98db8c9042bd42e10c1c0efd795.nq.gz
    ├── 4d76addaa6431a9e7e6a52947220d5ac0c80c413.nq.gz
    ├── 4db6081f211d2bef73e4399d79a2fd9076b1589d.nq.gz
    ├── 4e198719775496726b462bf87e0000787465dce7.nq.gz
    ├── 517bf59c5c6adedba0c6eb666904b9bb778b965e.nq.gz
    ├── 521b1e9152a65f83e3885bbed460098c5bcfa81b.nq.gz
    ├── 524283f847cc72c36ef2be90c5302a7d212cb0d0.nq.gz
    ├── 52895da594fab6d4772e0eb28a6085461286e0f5.nq.gz
    ├── 53820258e99bd03b844a90f5c7326b8b202d1734.nq.gz
    ├── 538f5616f72ef1ec1151d896fbc684f362c7f23b.nq.gz
    ├── 54b17dd49c3d795f53b5775f7e3a022371590146.nq.gz
    ├── 5518ef553a6eafb87df0018c72e06841c885df94.nq.gz
    ├── 55f150eb0a1bce23891cb3b7b89ab3540596bbd5.nq.gz
    ├── 567e239eecfedf84042e24e2877d328c3b8a489d.nq.gz
    ├── 5714808d47d9ce47928156e5b5bbbb9a52d43ab6.nq.gz
    ├── 5737782408b65a5fbc1b1956e60332b53f29333c.nq.gz
    ├── 58fd52598913924534243f8cb2a3679ad84181f2.nq.gz
    ├── 5a2a8d205d2221db883ba3d8e960432c95ab9122.nq.gz
    ├── 5b8f1d24cfaa6f4cd9a6642893b91ad816e39ee1.nq.gz
    ├── 5c25adf51f5c1363b0090476675569322e16f5b0.nq.gz
    ├── 5ee17840a3b8d1c9af03fc4e723e66c9eef35386.nq.gz
    ├── 5f190d76f57889fea3e8379eb692f16548088bd6.nq.gz
    ├── 5f466e30ff976fe3399c446a390dc2546d8a9de0.nq.gz
    ├── 5f523b8eac3a37d94c479759ddad869186fb6562.nq.gz
    ├── 5f6c926d86b89493990cff0e14036545998aabdc.nq.gz
    ├── 5fed7bf233b3fad1334b0052584d9921d4b48982.nq.gz
    ├── 5fefd8f9c334f61096c814389cb50013da4ebf1a.nq.gz
    ├── 60c5528e8d7fa4a812511189a2ede58ad9d8b2ae.nq.gz
    ├── 61a84892dadc9a85fcd5441dfd153be3476096fd.nq.gz
    ├── 61e01f40459e26f082fc90ea2964dcc4bd2d70c6.nq.gz
    ├── 645726b07e9e9019fbd591ff0b3a7ce7212fb8bf.nq.gz
    ├── 6663458d89dc8cb4233386aa8a318760edd65423.nq.gz
    ├── 6742d39462449d7264cbc2724668505f6ceef7f9.nq.gz
    ├── 69d4710bfe63f61408b57fd389cc7118971e8614.nq.gz
    ├── 6b66f41dae2e01d19d3012080af2e0a775cb225d.nq.gz
    ├── 6d49e2e92a690bcadd274b3c3e5738f2aead1c1a.nq.gz
    ├── 6e3d011b4f5da1bef27383bdd3eda3e7d496424e.nq.gz
    ├── 6e943bdd0dadc1cda99849ee9a87b73b0caba05a.nq.gz
    ├── 6fc980feda9ab2b0de70f37dc689cac18cb5e97b.nq.gz
    ├── 70be9eb8ee11e2ffa243880d7f60d9b0e461d028.nq.gz
    ├── 70f2fdfe93e561d1d74b67aeb00379f83f769ef6.nq.gz
    ├── 7184b525c86eca129d6c21692fa6ddc60cb5375d.nq.gz
    ├── 726c7d2ba654c113aeef0c738965dd0f06f714cd.nq.gz
    ├── 73173b0d1b9c0e7b13d9cf12fc3b592187c19eeb.nq.gz
    ├── 7429fa5583f92cbbad1d3c239895750dffc460ea.nq.gz
    ├── 743d9fc1b825b4fbaedafd2d72394b4f611f892a.nq.gz
    ├── 7523f51291556cb3ce25c4fe0a085b6c987a3208.nq.gz
    ├── 75561451c2f8896a4b0b3b4a5537177286c73dcf.nq.gz
    ├── 756988c3f2dba3ccdf0569b666d6195733df3496.nq.gz
    ├── 781bc1d3d6bb5d8bf5022735c9c6efc192ad4c93.nq.gz
    ├── 78e6c51a1e187b2a2702224069cc57a846a1022c.nq.gz
    ├── 79a36211e4a3bf12c19d8f8e65d7b3687ee682b1.nq.gz
    ├── 7ab85d2242257cbfbe0e7d77e4521cdc1486f0c3.nq.gz
    ├── 7b59c9636db787e5c67f131bc43df8ac9265f2b4.nq.gz
    ├── 7bca4a4a56bc32a3e81cfdc224d0c5887c6f7ab9.nq.gz
    ├── 7f2747cdc9d2534c0be58a4b125a055ced98ae89.nq.gz
    ├── 7f53983ecbc6981417c31823ed3b65426850b377.nq.gz
    ├── 7fb72dc9e41f202d39bf1d0ae9c4d7ac023b2749.nq.gz
    ├── 813bd48342dacb79482af0039a4c4645dfb7b09b.nq.gz
    ├── 81b3fa1cb2dff49aaf734b6fca5a46c653c072eb.nq.gz
    ├── 81e71f4677d7a61fcae66da05d6b623524793cbf.nq.gz
    ├── 833d5fe511c1e20be469e5dade383fb0252bd50c.nq.gz
    ├── 859b4b441f8150fe5d3d88c8b8f9bb54e2b06824.nq.gz
    ├── 85e1dc81c405d777b6c5ce1a9d571e87b892d91a.nq.gz
    ├── 85f6e6d9904b0d49302a2d933181279e974a7c86.nq.gz
    ├── 867d325c5f3b08dac17290a5f59eff4528350f08.nq.gz
    ├── 86f9fdf9fad82eac3240093a22bef07c98630264.nq.gz
    ├── 882f05c8dab59c626a63e159c3dcc667c8ed9fa6.nq.gz
    ├── 888095d359c12ab97e2ac57ab0b1268763731a84.nq.gz
    ├── 8955d6a27a83b09fb67a1e46508f196645b4d216.nq.gz
    ├── 8a152cdf9e06ef325384c214a2177c096471d917.nq.gz
    ├── 8a2e3770353c5bd2d450a7b8ab590a1c35d39518.nq.gz
    ├── 8a7fd281e26117c855e6a14e6e2b4bd4adfcce9e.nq.gz
    ├── 8a822fc2e77e8749d30ab49a4ba1b9cd2e4bcb06.nq.gz
    ├── 8cf25003580924b88ea8b338513d20d33201e8a4.nq.gz
    ├── 8e1f9bc0b807d1753f4351224dfcc09ea390ae35.nq.gz
    ├── 8e937ce6005d17086dbee348256acd5d28370ea5.nq.gz
    ├── 902379effd91ddfc4c1afbd1bd3365de6e4d5d51.nq.gz
    ├── 90a4af686cb352e2e634bec1e0a805d9fa7bd9bb.nq.gz
    ├── 90b5951b0a369100f267f417671cf99c86e5466b.nq.gz
    ├── 91f621d6c148ae3a27d07a5132663e4e971448fa.nq.gz
    ├── 92668e6c657a903a9d51e549b42a6f33a1e14259.nq.gz
    ├── 92cb0049ee2bee9d398f570a0bfa5b48fc03411c.nq.gz
    ├── 93b6d8091f97ebe1596b3df118eab2dbcfbaca77.nq.gz
    ├── 944f3492798d203640a9b76563d733174e5e1dbe.nq.gz
    ├── 94989df33e44b46b7e86e746e77e72485bf84066.nq.gz
    ├── 9602896638066ffc52f86f1571d9b257fdd05992.nq.gz
    ├── 96be735d3234c0223baa32c64ab9ea557fdc491e.nq.gz
    ├── 9727bc272fd7457b07f162c81dff8e987278bb48.nq.gz
    ├── 979e6592474aa3b912d56c39c606fe9f481ebb53.nq.gz
    ├── 994024a9f73921c14ea691dece47047239da3d7f.nq.gz
    ├── 9a820900158a297a8d1e703a46f12db5d90d85dd.nq.gz
    ├── 9b15d70d18cc5a341a2b4c465d8351195662ec09.nq.gz
    ├── 9b24fb067fad24f4205b863e9001236bf5f73671.nq.gz
    ├── 9b7d319da27616c8ee0c6e54d70f39a8b63892cd.nq.gz
    ├── 9ba7a6f25bf89bd94fa1ba973197e0ede96d3f70.nq.gz
    ├── 9bbb39243415b826a71ba65121b20ada5a7b9503.nq.gz
    ├── 9be5433625829ddb914ee5947414cd1f3533cd71.nq.gz
    ├── 9dc4ae1de30503b8a7406c8d087405f452e1f2a8.nq.gz
    ├── 9efe0762ea0b8d8a25cd5e368ba7e157f8aef935.nq.gz
    ├── a0356502ca20b0574826e30c146f79b8e9f296be.nq.gz
    ├── a0bf4aa3f4bcea9593051f032e79039ac95cbd5e.nq.gz
    ├── a24b1c61a9c371e4fdad95dd5ec9fc31cd71c9cd.nq.gz
    ├── a273b3647904ee2342e4ce2d65f8be40f098a316.nq.gz
    ├── a38b077c26d78ac7583e62d8e7682f02bd71b32f.nq.gz
    ├── a3a183836ad6ff678c0591ff955adf8215509857.nq.gz
    ├── a4f9cb575fccaccb38534bd5abd64e7cced6d36c.nq.gz
    ├── a5660aeb6088d24361c62f79e7c65a111397c5de.nq.gz
    ├── a5a53f0847b1658d5591126dec14c2f253d7f0f4.nq.gz
    ├── a71483a68ebea1b02a8b3b167fa0efe57b498f54.nq.gz
    ├── a77bb3ccc23b366ef3b723527cb13b066ea7d92d.nq.gz
    ├── a95ff7d322f68420c964d3b3b10df5cf9dd66103.nq.gz
    ├── ac04c20f52f01fcbdca2913c22df1e0e9f63d13a.nq.gz
    └── ae3e00d4567176deb355fd36a94ecfc2b88d39ba.nq.gz

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

[outlines-dev/outlines](https://github.com/outlines-dev/outlines)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
