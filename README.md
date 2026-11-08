# Repolex Knowledge Graph of UKPLab/CARE

RDF knowledge graph data for [UKPLab/CARE](https://github.com/UKPLab/CARE), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/CARE
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b46d9a4b494b507dbe3703d8f34f0b1132a3bb1f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b46d9a4b494b507dbe3703d8f34f0b1132a3bb1f
│           └── chunk-001.nq.gz
└── blob
    ├── 006bb24cf355a2b78c58c6bfc4a5b834730ca29f.nq.gz
    ├── 01b1a7700bb8e48cf712337fd809db1d7baef0d1.nq.gz
    ├── 01e23f771beaced5eb8a2d0783a89511f0186410.nq.gz
    ├── 02e4ea3aa51054c97a2e17c97aa6b8a194f288b0.nq.gz
    ├── 03a78c1277c08f7751d50aad8aff86cda3fdd1b5.nq.gz
    ├── 047204ea5921afff13c24351504e542dcada3316.nq.gz
    ├── 047520d7df3e040365d4d35368dd5b0adbc93517.nq.gz
    ├── 065bffb03ea7b7b82aaf4c93936b7c0b7ade7b56.nq.gz
    ├── 06dd7c4db59bbd49f04d0e01aa679fb6bfecb5f8.nq.gz
    ├── 070cab747bbb06840ab9c9cdd39d7b9f52bfa7c1.nq.gz
    ├── 074f9365c89a6d3cb738658a609c629f16adeb3d.nq.gz
    ├── 0772099568d546220e031efaaf960d9255b07615.nq.gz
    ├── 07811d9fefc9c1b71c087b6e3dfc19fab63fb87e.nq.gz
    ├── 07ab9ba3124b8331df408f08a3c70228b50f188a.nq.gz
    ├── 0812fe6ebe0bb6332557cb6bb0894b7a1d948f56.nq.gz
    ├── 0882a8eb8a22683d62fe96937dcfd0f484e3e497.nq.gz
    ├── 08c478a7c33d73c90e282aa0b85209fee9e4ed16.nq.gz
    ├── 08dbc945ea088d29ec9288ed0a1d0ac6f154e56f.nq.gz
    ├── 0bcc6e382edc1a85a803101e1e7167bb82a4ae1f.nq.gz
    ├── 0c4b368130506c4703d10d20520bfb84afefd658.nq.gz
    ├── 0d40e2499f609d1d826a7ef4fbdc3442a42df2e8.nq.gz
    ├── 0d789dd5596fb86d047048793baed8b0ea01ffb1.nq.gz
    ├── 0de2798a2649d0a0f7403cb465777de7b83a1acf.nq.gz
    ├── 0ef7e286275944af6e37ad19f097e2c41a681491.nq.gz
    ├── 0f634a8598bad99a89e7754742c4b103e5220a03.nq.gz
    ├── 0f89085f9e795e55584043baa67913363fdb1f2f.nq.gz
    ├── 1052321c76e49b595acd70fc1e29662eb70c7e4d.nq.gz
    ├── 1090d0f3d4a9e42778586d3203d89e2660563fbb.nq.gz
    ├── 10abdbfa3106445391b27d6ac2767a8516033075.nq.gz
    ├── 11a332a2582f31a86d351298f8b1d20ff10ec514.nq.gz
    ├── 11dcc9799b95b3376b6d1f5d9e11a6ca26f650ce.nq.gz
    ├── 11f8ece58f21adde51a9247ff74cbc5226d666ec.nq.gz
    ├── 120b07398eb75ba07e16af67e552db9c47db5ade.nq.gz
    ├── 121f7d95cb57b2b3232a92699e835971cf038651.nq.gz
    ├── 125dcbf26449be499dfe452f17c37eaddeee0722.nq.gz
    ├── 12e239e646dbea51208770065be9f80325d06fc7.nq.gz
    ├── 13014def9f8f06e6f59f6f96d65a3aeb4e0a93c0.nq.gz
    ├── 1306b86001d1767e7232031393ba2ba0830a96a8.nq.gz
    ├── 1343bec3d378898d50ad73c467244dbc81812af0.nq.gz
    ├── 135b8caad10b630fe6378a341fb337ff090da41c.nq.gz
    ├── 1431c38c585190c49c41b8279d603cb4f782cd2c.nq.gz
    ├── 14c9c82e0478c61264e82bf05043c234732dca92.nq.gz
    ├── 14eb1e344a304da5acc946062697941d045a4b59.nq.gz
    ├── 17162fce77e603870e0ec8f275b05e80b85dac0a.nq.gz
    ├── 185653bd906cb8d4ad36cf50a2bdd9505d41864c.nq.gz
    ├── 18839bff839ae19531cd0f977046062aa133634f.nq.gz
    ├── 18c193ce94985ce2acb93dbcecf5104e647492ce.nq.gz
    ├── 19080df56b237e6fca6a7f23c27c862ee7f09aa4.nq.gz
    ├── 195e93676a74214eb6d22b41eb5583c592421d5c.nq.gz
    ├── 19e0f0deeb3e65aac6e9d09fc215d59afa9e3c4a.nq.gz
    ├── 1a2abb67c5e89cdd4bbd860aa211e42e08f4ea7b.nq.gz
    ├── 1b3fae8e1edf8ff37ff06718a92f1732ba10add0.nq.gz
    ├── 1b42c61d5bc4ba6e4fddbf6df297aa1e35808287.nq.gz
    ├── 1c1d330006152681b1f12cdb0c982de1d170c39c.nq.gz
    ├── 1ca18c961748d88101b42b57e90b43da10818210.nq.gz
    ├── 1d1578242710f712e2dbface1709c9ddc75f24fe.nq.gz
    ├── 1d9b98ca7486efd9710b1f1bbdbcb5c4621dec9a.nq.gz
    ├── 1e5de6e6bba0fe733398de38705516a30ae1161c.nq.gz
    ├── 1e624fcf7dcefa76ea292c92663c298b163bae56.nq.gz
    ├── 1e62a0d14e3bb4ce4338253cde755c086732c8a9.nq.gz
    ├── 1f02b7d166fa4cd4a4bae87b30bb54c20af871d7.nq.gz
    ├── 214ad1c70913170f49369458aa02ad05038ca1e8.nq.gz
    ├── 21dac99f73346b12733cd9a133c4ea6ea385bf67.nq.gz
    ├── 21de960daecb134c81f8494b00333e853e5ff15f.nq.gz
    ├── 223f6a135c6f59b88301007e916db3bf9d568189.nq.gz
    ├── 226e7702435bfb1b8bb4ea3b63b33907d40fdede.nq.gz
    ├── 22838d3b88f18bd0ac481c6875a6b08ea4c3af0c.nq.gz
    ├── 2315af73734ce8d19d2a118af4cd46cfe62f8b36.nq.gz
    ├── 2371d8364133fe69ae7fa9255123d653a5caa59c.nq.gz
    ├── 23fbd4b4a83b0cd9a217ba709399dbbde56dd917.nq.gz
    ├── 2427b02723db3393cf578f956c9fc61cc2e3c37c.nq.gz
    ├── 244d4db26a593395b8b13aec8e36ca4bbdaf95f2.nq.gz
    ├── 24b412553acf476d3729ed51f7f48ee8ab3924f1.nq.gz
    ├── 24fdc9879b934c7434f4b65a756c8980d2ac3d02.nq.gz
    ├── 25756d9d78421621dfd69f9017ddab7c5a39bb2f.nq.gz
    ├── 26e7dc5c1c386d322070ae543e19c5aa0cb3b1e7.nq.gz
    ├── 26ec2cff194c5f4819cf88a10b1dcdb0d704c839.nq.gz
    ├── 271ee79a8b1af8add2aeceaa3c41e6d4b5aba43d.nq.gz
    ├── 27ae971f3ee654f06a7597c5a1f9d532dec579c0.nq.gz
    ├── 288042e5ee924a899c4b10b8670c7aed1a804793.nq.gz
    ├── 28c0a533b5052fe56cd092639f272cb5d069b579.nq.gz
    ├── 2d7fb6afd6fc438542aa39e966585d8c33dc6d02.nq.gz
    ├── 2db1caa77d837b382f49fe6abb510b9fc8a3ad4f.nq.gz
    ├── 2e270f098d5359a471f3a15cc0d00c33ce309039.nq.gz
    ├── 2edd5e5fe14fb573933a19b241f995beb16ebbf8.nq.gz
    ├── 2efef361d5f8a2aef2522d21934510986214e588.nq.gz
    ├── 2f1bf93dcc5efb9be874b166777f20b31c0fd685.nq.gz
    ├── 2f22fb6f1932b54b628557c538bc8bb2a42d8e3b.nq.gz
    ├── 304dcd89305d3c930fcf8a48823f3723db782d7d.nq.gz
    ├── 311689d95ed44f6258a52c3f1e0342c5ad87d53e.nq.gz
    ├── 3146e9647bfa917c8a20a37637c506f1a03b2c34.nq.gz
    ├── 31494633a4feb38acf0c1effc0e294794399c4ce.nq.gz
    ├── 318ec710d402264c1bef41aa72ba06cea2f69668.nq.gz
    ├── 31e27cadeda78eabe1fb5fab11accf0d7795e79e.nq.gz
    ├── 321d2892d4219af3042d1043e955b4ed60d164c4.nq.gz
    ├── 3249c39460df396fd51ba701ade33bfaa193644a.nq.gz
    ├── 325128079379d35ebba4110652fef4dcedb53c05.nq.gz
    ├── 3256cf71603e12b493545368a594be374f3a5ed1.nq.gz
    ├── 34084214e3383f5b8d849267fe872c4da5e93c2d.nq.gz
    ├── 3468c1e0c43ea8ac28047d4551680c19b26a4606.nq.gz
    ├── 348dcda3ba12204d9b529b54a3c8f3598cc54ecf.nq.gz
    ├── 3516f434673fee97238402dac57fc4a2f45376f6.nq.gz
    ├── 35833f71fa715c9420d5ab31bd25fe77727d2782.nq.gz
    ├── 35ef684188b4c21767e498df99b758f1d1623253.nq.gz
    ├── 370b2911a94ce7940486c3646a2f8305bf8edc7d.nq.gz
    ├── 37a456b6f7ccad72f02af0ff40e4a61fafe4c99e.nq.gz
    ├── 37b073676dccf090f5ec7859b886f0446393f378.nq.gz
    ├── 37d192a3b7324fc07d4b42d26e1ae1e7e5496412.nq.gz
    ├── 37e3d269c7d036cf6a3566e5aa797346816b6f93.nq.gz
    ├── 381234e2df41daa8766d4fdf3ab210b8934751c3.nq.gz
    ├── 3824e65118a71727dc64cc098169b94bcb6b4c1b.nq.gz
    ├── 383b0e83f3b4009e167743bd2f14430612771223.nq.gz
    ├── 3874801ce384a867ac976711b8697d9795a19d17.nq.gz
    ├── 38cfdf51355c4588c2c565bd0d3a67440d805912.nq.gz
    ├── 3950d87bef6ae3d932096dd42e0ea21aea32aef3.nq.gz
    ├── 39c26d00a1f7f5680b5e990285cf32745fcd2ad7.nq.gz
    ├── 3a6061fdb6e2a000e5ed8c45f445b59aa1ebf37c.nq.gz
    ├── 3bef4789c36b11084c2b01e917ecfeb0a61d5b4b.nq.gz
    ├── 3d62d1f93789074fbf7d1d8c80625b969d7a399e.nq.gz
    ├── 3d676cc56e1ba75d25b7012bbb08def1ec3b79f9.nq.gz
    ├── 3de80a086547a8f89f2690a784e5038fd61cd265.nq.gz
    ├── 3e1ce15ba354f47431bc03f2692026d95369db27.nq.gz
    ├── 3e2a17bb1159ea635b8fe714b653c13f85fabfa6.nq.gz
    ├── 3e6383c366575c29f038dfe4a72dd24c2ea1c9b0.nq.gz
    ├── 3ea2907618742d7dcdf5461cf7615728cfb41d08.nq.gz
    ├── 3f875504cee7c011e239e6b25a886ec758928c28.nq.gz
    ├── 3f9dc83e029b23e4253a9802535ee0ea4a6f8331.nq.gz
    ├── 3fb03f5163e0b4f91a74942ad4d8fe1c40ebb38c.nq.gz
    ├── 3fca73db07f0658c3f24810123ddc444f4a85467.nq.gz
    ├── 400cd167666a643ed1ec37eece7e2f07e69e8b80.nq.gz
    ├── 40e94f403856c999e7adabfd96e714181ec6381c.nq.gz
    ├── 42367fe4ae6a940f25e7b893e7ff9df52eb3cdd9.nq.gz
    ├── 4537d0591b95055467dcd06b805b45da7b904a8f.nq.gz
    ├── 453b0a278a85a58c0533414b9ada44adc85ee752.nq.gz
    ├── 4576ec9fa3f5b75323ddd0cbb6b2736d07a9045d.nq.gz
    ├── 46c42bf73c248d2d9d77b3324df2d8735572f8d8.nq.gz
    ├── 46d2cbc4a02842b38b87556448a75c7a56911743.nq.gz
    ├── 471d9fe3f342423d1dcf3fd5dea24d0157979b91.nq.gz
    ├── 47b0971cbf5ff0ac589de7f28c99a7ca19c10417.nq.gz
    ├── 481e36ea7921a4b26110e8ea7c31aa22d5fa22a2.nq.gz
    ├── 483eb457557563631ba38c9f348b65e871cae56d.nq.gz
    ├── 486c8e720239b5c9590f84aea3128ca4e2252046.nq.gz
    ├── 4b2b743e6ae26697b6d030931cc46b555e02b5fc.nq.gz
    ├── 4b7a6de3682e114ebbc373c60a4d7f09c4ea6370.nq.gz
    ├── 4bccca3d246676200d0624e122419b53424da5ae.nq.gz
    ├── 4c50e6de205d5627023c4ebb515d139a4fae53de.nq.gz
    ├── 4d5048569b939eb7b370cdfa97ad48c6b1cb4dc9.nq.gz
    ├── 4e3102c5f1750b2ebd654665603ba69e867d1865.nq.gz
    ├── 4ec0ad199655a8aea9ebfb2ffe68b0180dc32b75.nq.gz
    ├── 4feacbf83641cc8f41cc9b142841e4b8a4a1f12f.nq.gz
    ├── 503dee4204c91babbf65dd858f8767fa3d66eb80.nq.gz
    ├── 51e9eb88e173ae2a43d9a00049577d06dda96406.nq.gz
    ├── 528cbb589fbce1b55a08287a59a9f8615eb9254e.nq.gz
    ├── 52c4dc18fcea2373559724a5ab9fb4524b2488a6.nq.gz
    ├── 52f103870bc02036aff7343582b74c5ebf5b708a.nq.gz
    ├── 536eab485699835c92cb749bee15f58903a54c92.nq.gz
    ├── 53a484b2c8bbe85a0112df5190f186945c626ce3.nq.gz
    ├── 5412f7f6ae894c2017476df920eb81feec5b8c27.nq.gz
    ├── 5467f9c602a0ac5467b7ecc277b9451dc903ef11.nq.gz
    ├── 548e236e3a8114185518d13cf316218b4178fa24.nq.gz
    ├── 555666f44eee8c1c97feb3c40d56075adc06c731.nq.gz
    ├── 557b0709f65af484f832bd7d2a369d8225d23751.nq.gz
    ├── 558435208024b56f37c20ddb3bab080814e54035.nq.gz
    ├── 5600eb50b100feaf9bcd80c086082af9bb9edf2b.nq.gz
    ├── 567bd8d6f21850e4611d91f5801a31ffef521be2.nq.gz
    ├── 56968a8fc15280d65ca535112978aa19fdcf5974.nq.gz
    ├── 56f81a073fd3383042d5ddfc3ecfdb50837bbae6.nq.gz
    ├── 5749574a5e4a95e56731c425e6d6243e7a4c5a10.nq.gz
    ├── 576193c4fe7ddc7a1a8c47381d20993ec0ee73dc.nq.gz
    ├── 582bb8c152df983c346c71c7e88b653932e5cfea.nq.gz
    ├── 59396f2f739cc39195935b2fc7a63ce8cc3e76c2.nq.gz
    ├── 59974474a7a70798cfa290a548d169668a387c73.nq.gz
    ├── 59abde09ca2fd977d2d7a1ff7c2feb74c8be2e38.nq.gz
    ├── 59b354a91378aa23c3f7eb93247eb5d461c8420e.nq.gz
    ├── 59c029ea0e7d83c3b9bb0cd6a1317dc6c29bbcb9.nq.gz
    ├── 5aee04944fdfd027b498392fb4c9deb447182ef1.nq.gz
    ├── 5bfb19748e718ba333aaba54d37b8472d79be419.nq.gz
    ├── 5cb088448bd52f4c36238f29a8ce11fc488c8c13.nq.gz
    ├── 5cbb197e30a438384e34afdb842ae804f5edcb7f.nq.gz
    ├── 5cc1e3c4974df13d33cb2d0bbfc6ea8d74ecdfcf.nq.gz
    ├── 5d7c9270237cdb4ca3c1995c398c010c742878b1.nq.gz
    ├── 5e1009abdfc0f4ae5ca8a8702c399414cec5f3dc.nq.gz
    ├── 5e8570160c387db1fff45485729461f6a9625ced.nq.gz
    ├── 5ed10e9b969c6188fa6c5d81a2ee81b1fed546c0.nq.gz
    ├── 5f06bf0cdffa671dd7ba65de1e33d4fae6756efb.nq.gz
    ├── 5fbcbeefe7ce5ad520ecf6bdafaebf2a32ce2ea8.nq.gz
    ├── 5ffb9f51ee608466c5bcdd696b2f82245e6eae70.nq.gz
    ├── 605c4cb87f61b411550ad4be928a749df7a629c6.nq.gz
    ├── 6062ad707f46880f24fcdf97eba428e2cdfa7df4.nq.gz
    ├── 60a78d37fa839b0bf6add3b1208e448460aea7a6.nq.gz
    ├── 60f850e70184beddd12edece6c080f97b5c8b710.nq.gz
    ├── 61e830ee328415bdc7117f86c232098f9df11dad.nq.gz
    ├── 624917fcc8918ec172a4f95c08800516da85a873.nq.gz
    ├── 63237a6cd556cda8eef56dbafda5ff29323fce90.nq.gz
    ├── 633136ba07323b9b97483e90ee89c9f10cca1598.nq.gz
    ├── 638fad98cc4518299a22a79888c3dcd641c71eaa.nq.gz
    ├── 63a08f946112ac27e745d524db94ef204efb1e4f.nq.gz
    └── 64d79f114c374a39c6133f9db1060b48fe3e05e7.nq.gz

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

[UKPLab/CARE](https://github.com/UKPLab/CARE)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
