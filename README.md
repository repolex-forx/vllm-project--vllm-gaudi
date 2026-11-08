# Repolex Knowledge Graph of vllm-project/vllm-gaudi

RDF knowledge graph data for [vllm-project/vllm-gaudi](https://github.com/vllm-project/vllm-gaudi), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/vllm-gaudi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8fe21d1af7caa0fdb93ed6e7681c4c8b29c54632
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8fe21d1af7caa0fdb93ed6e7681c4c8b29c54632
│           └── chunk-001.nq.gz
└── blob
    ├── 01e608716d6fe8fafc2bbc5c61a0e7a564ad0cba.nq.gz
    ├── 02233195f654d562ee8183a4d4375be4a0a5a5c0.nq.gz
    ├── 028303c75ad15c3cc0032c15051f31072e9fa6ba.nq.gz
    ├── 02dd0c2c72668f510703ff8a2d9cb9d7006cc78b.nq.gz
    ├── 038e702a0a54969283a565c6d20af0934d8dc04f.nq.gz
    ├── 045f88f52720d03222588f880f198da1fe99ad75.nq.gz
    ├── 0549b1599115da4516c9cd8dea9d4cf4384d2e5c.nq.gz
    ├── 05bb088c97ad46226add35fd9be8c8ceb6affbab.nq.gz
    ├── 0880545b901a80470d0c415cabbb159977da086a.nq.gz
    ├── 09d5379cf1e87d87aae0ac289b33386c9d9a0c21.nq.gz
    ├── 0d0ca76bb0d7ac20f27518798f465acc9f272589.nq.gz
    ├── 0e01e029f2e9808067bcef205175691d9705a825.nq.gz
    ├── 0f11572d3b2d65379278440e2c878ae5177dcc53.nq.gz
    ├── 0f3cf57d23ba1206124f2a1ecc81683fe25f4ccb.nq.gz
    ├── 0f8f227dad23c710850ea1b606f11aeaed478276.nq.gz
    ├── 1000e3bb480b46c2b60f102fa99d24fa52b8df82.nq.gz
    ├── 11b74d59addb16a76daff0d66d835efbc886a563.nq.gz
    ├── 11c9f035017459d2d19f80db51e0cbcdacb1fbd7.nq.gz
    ├── 1205167abd1965aa7f1eca1ce6590ddb9221adeb.nq.gz
    ├── 12ad56f50bc04fe5eddb69e9c62446f06efc1ecf.nq.gz
    ├── 12cd4408c7bf0ef660bb20c7ffa435b4c3fed71a.nq.gz
    ├── 12f28fb9f012ace1dcade10eb594affd24044e1e.nq.gz
    ├── 130a6030eef287efe80105399618c0b2e4c00fa1.nq.gz
    ├── 132aa836ae65c1f0a58fe1eea878d1062d9e8dcb.nq.gz
    ├── 1355de371669eddbba8d2d90f33a5b310393dca8.nq.gz
    ├── 13e414f9eb4af76a4372864de2e209c8a9a5ce88.nq.gz
    ├── 140f39df50ced294e7278e2dc1ccd620ff84e27d.nq.gz
    ├── 158a9e6d1911de56181031047f1d3fce31a078b6.nq.gz
    ├── 158f55f9ebb3e0b7862d19446b6187ed1eca587a.nq.gz
    ├── 159504be80bf1415c4433aba4f3558569c65450c.nq.gz
    ├── 1705dcfa931b7c1ba092969b50c6414983bff9a9.nq.gz
    ├── 177ed4a4b64a55e21f4e5c69de34729f86a7deae.nq.gz
    ├── 179c1f20a814d2aa6acd4194db090a24589480ac.nq.gz
    ├── 17f3b8589cb32ec3a95c9c40e0777e709464a3d0.nq.gz
    ├── 1852718eae80dc67ed9fc34a1d221b5e60d7be00.nq.gz
    ├── 1a16fa979863727bca629508ffe338a1e1276b9a.nq.gz
    ├── 1a64046edcbe77bf929f39ad4e2b2c91dafe4644.nq.gz
    ├── 1a84039abc14f3c4db6245a62fd2fb06a49cf971.nq.gz
    ├── 1b0b778b867e8ec6e5654a702b2c4ca4920005cd.nq.gz
    ├── 1b232170d0c730dd0f075abdc0254abdd8d8cf76.nq.gz
    ├── 1c35dcc362b2e50244098016a042e71e0f5dd25c.nq.gz
    ├── 1c9159a810773f294add138bcc73da699c7f6f62.nq.gz
    ├── 1cd33cb9644d2ef09ddd80bf66a93f7ab1f820bf.nq.gz
    ├── 1cd77af7f1b96b26dc94d6ee13ca3a944f78bd47.nq.gz
    ├── 1d8575972def9b0c2d51a5c64888a72768a3aceb.nq.gz
    ├── 1dd3fa7e80eecee212887fe3e63723ca0d8111dc.nq.gz
    ├── 1df9c8cdae9857156c5f26ca3cc9bd2fde7587a0.nq.gz
    ├── 1e9150a8bc54aee692b4c61db9b95622539d0ab0.nq.gz
    ├── 1ea616ccfef137c966caf1d6f606398d18cdff58.nq.gz
    ├── 1ead9972879c29e17160f1d3ead150482467b1e8.nq.gz
    ├── 1f1964f2278579951a8b7bf614e1b690fc319062.nq.gz
    ├── 1f326537b704756edcfa0b1513e29e92820811cc.nq.gz
    ├── 1f714065d78ebce42cde2b30521ac6bd71962ccd.nq.gz
    ├── 20056553e09c331d5225c1cf76035c15ed1611a7.nq.gz
    ├── 20755aec4e3a500d8dc8eb7c0dc151c4f3fee704.nq.gz
    ├── 208f01a7cb5ee04c88d276fec2082cd4e830884b.nq.gz
    ├── 20b90bcf9be8c3e40eda432190a34ed49a34b431.nq.gz
    ├── 22683e5c07213ee7636e641ba15b9aff6d7ded62.nq.gz
    ├── 22fdcb0fc4064ba0d86a903626acdc970c8ce811.nq.gz
    ├── 234b2ef38ba2f4f2a2d1c7dd68cbbc987f6d45b0.nq.gz
    ├── 2591372c725d3b37ef3bc1b44cba7481f011411c.nq.gz
    ├── 25e6a939d50ada46c7a2e07ef8eab695dc8f6312.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2626b18b9de9e959121af9d860ec3bc8be06fa08.nq.gz
    ├── 26ead7f83b008072ab4a85162557900cd62a9308.nq.gz
    ├── 27528ceebfff401d0516b73099381c7425aaff3a.nq.gz
    ├── 2776ad9026c7a22485ac36c8f34b1e3ef7e5c658.nq.gz
    ├── 27fb219de55c0815a0271e47adb9e17b70b857b1.nq.gz
    ├── 2816a8334a8c09b2b0750a5972d8ef0e038252f0.nq.gz
    ├── 287eec41fe0d70cbfb21fb048f721c159076f40a.nq.gz
    ├── 290a6c35453c7d5007c945302cfe4efc347695c5.nq.gz
    ├── 2912376f65b6ee8f50dde7c08f4aa68c4362e9fd.nq.gz
    ├── 291554212abe475842570295ef4309cf10a37a0b.nq.gz
    ├── 29d548b34cd3f4a5b534dbbcf8aafa8073adb2e2.nq.gz
    ├── 2a36e15f7bd84dd1d03c8c6005b3b9e9ab40c326.nq.gz
    ├── 2a8bdecc07630ca760dd251d65a24018f99e2155.nq.gz
    ├── 2aeeb173305f2ea1ac057bbf28c8ef0af1c239e2.nq.gz
    ├── 2af43aebeeecc3d26c7db768f665691186468370.nq.gz
    ├── 2b55f1abaa5cd55b9acedcf5de1a4c439dc4f754.nq.gz
    ├── 2bfbf01f3dc4d0e22fd9a0d623fdd4f7a64bf75c.nq.gz
    ├── 2d51cb69862f39a24a466879b7729d3529cd5f41.nq.gz
    ├── 2d8dee4ae827b3d182caeafb51d384ccb4ec8954.nq.gz
    ├── 2dcd670206912ffe45b8b0de279933716adfb506.nq.gz
    ├── 2e82467658aa7e36e7269f64103478d65ec3e525.nq.gz
    ├── 2f18879bf57ec23092571f7203b489628800028f.nq.gz
    ├── 30165a6fa4607c516a90a2ed39501fec5a3cddfb.nq.gz
    ├── 3088659e668a5102ac89e269572bfa5b28791e31.nq.gz
    ├── 30a2615ea83d3cc97e6efe3fb4bfbbac3a3d57af.nq.gz
    ├── 30ff599625751d32160ab541498588f1a115dded.nq.gz
    ├── 32147f6378b8d94b20e741c799a7db7eba1099e4.nq.gz
    ├── 322b6819783e0e923dfcb8309af3086391003615.nq.gz
    ├── 322e0349893f1a7bd55eb091ce801447e6b7dbc3.nq.gz
    ├── 33700b2ef5c47b670cb1d91beb1d27ca09d2809c.nq.gz
    ├── 34a065d70b565eb3b67314cd68cb491e822adcdd.nq.gz
    ├── 35dbef7f057d96e238fa00a7b330a9978ea1a396.nq.gz
    ├── 35dc74de233e24c1ca0493397e792e133e92f24f.nq.gz
    ├── 35e13a43a66f48ab27be25de6835640520853aaa.nq.gz
    ├── 364f77278faefd9854a94813eee219c6ee66c75d.nq.gz
    ├── 369bceda25ab419850530ceb6fa13d480b0db687.nq.gz
    ├── 36da6a63330fcc5a88a29353c8fa54df734bb2fa.nq.gz
    ├── 3747a3607a470ba27a2f7ff411c1c069f012615e.nq.gz
    ├── 37c1afa850b5a68586010f1273f4f59c96ffd88e.nq.gz
    ├── 37c1f1ec67bcb6bcc33db40d44ffcb7570a4a303.nq.gz
    ├── 3841d430a54cc2cbdb511d38929605d43c78596d.nq.gz
    ├── 39b4b6c762502093679dcb036e9ef5e88382bf1d.nq.gz
    ├── 39e6d6d75232a0d45f584630ad23913bb7642af4.nq.gz
    ├── 3a490c6fc0b4b8f66e580409873f2d151163a3e3.nq.gz
    ├── 3ac48c03f42115e861f13ada1ba6172646edf7be.nq.gz
    ├── 3b39c9ec94782be65aa5ae775bbb278a80c7aa96.nq.gz
    ├── 3b3c24e9a9ade960a73a103cffd14efd5edb5463.nq.gz
    ├── 3b41658409d0842e8327e988465efbc0bc36a03c.nq.gz
    ├── 3bcb5c9db48881e8d627fe013b2096a06dfbf2bf.nq.gz
    ├── 3bfba339e466e8cd6479e1a82700877ffb069c7a.nq.gz
    ├── 3c113fbf88f865bb832f880a160fe4c23e16e009.nq.gz
    ├── 3c2d8f698c12b28b5430ea91f34ed1d0e0112a6a.nq.gz
    ├── 3c41a9c8a697cc4b80022a53fbeaf1968b0571d4.nq.gz
    ├── 3c819430ca99fae910e632e3f3fd013b997ed9a5.nq.gz
    ├── 3d4563806d2680a7e1ab090f98f8b37ce3da573f.nq.gz
    ├── 3da0a268740045485a4ae9691702ebec0ad1c0fc.nq.gz
    ├── 3e8a674804c5831cf34e239c852a7cb5bec58b73.nq.gz
    ├── 3eab6b20d8d033b3b732c13490ea315890378fcd.nq.gz
    ├── 3eec03fc9d9047cc216d33a802aba0c709843e25.nq.gz
    ├── 3f11ba3907ad35097b0caf19de1da6dbd0def087.nq.gz
    ├── 3fd756364dfc4be706ee20aa1ebc23c33730a693.nq.gz
    ├── 40624998e564b1a86ca2a0dc81d9a3d8e101c61c.nq.gz
    ├── 406af0fcc56a1919f989d86089f2105d6b90d502.nq.gz
    ├── 417f6a85c364e789a3f267f7ef5cb2d3ae5eb92c.nq.gz
    ├── 4278e61e8f8124284a0c8093e836ecf5e90adbf3.nq.gz
    ├── 42ae7ab3375744f093cbe5d2308e44ea1ae8fc19.nq.gz
    ├── 42fe7e3bb8ec5f695a0cbec929c6c2ebd71d374a.nq.gz
    ├── 430d8d0329ee973020ae052302e59203e3792d1f.nq.gz
    ├── 431a8be4e603ccf8b45978ed14c5156c2d11efd8.nq.gz
    ├── 4349810caf2b0ff19590877d0d88ec0c7d9b525a.nq.gz
    ├── 43d07217ed8edb5b8b3b2f5e253f906280c89bc9.nq.gz
    ├── 44f5e49f7c44a4ff8cf2ab15a83dd34d1b09711b.nq.gz
    ├── 451924fc69e6b8f92cf20fe7530ae450e766aac4.nq.gz
    ├── 453eb239200d0cc3e1deaf62846d6203e32f3880.nq.gz
    ├── 463449c9ec106f1e21a4ea7a54e35474c16d6e98.nq.gz
    ├── 46ad56a1c840cf78b3842c6ec291680e3dcc944f.nq.gz
    ├── 46e651576d21af10d33e7127dd786d0493dab0c8.nq.gz
    ├── 477387750643d81f45bf7275c770c15d9fdb942b.nq.gz
    ├── 47e4927a476a134ca8831d76eabb0fc8026623db.nq.gz
    ├── 4852140742dc79b449f4dce0994e77019927e332.nq.gz
    ├── 48eba5bea836f9cfa372032ae68eccf06f9c2dc0.nq.gz
    ├── 49531f92a54ac1b6b8caf4a20e9ef4d068af4bea.nq.gz
    ├── 4ac9ad8eb11aae985631c8459000557c4caf0069.nq.gz
    ├── 4bb38d07f9ddea6c4e438de53913e6171395139b.nq.gz
    ├── 4befa3867101634fa3ffa70b1697669bcd753723.nq.gz
    ├── 4c3580fa8eb2069807c8a305d973566d08f561b4.nq.gz
    ├── 4c96a8be4b52b42175c521c9ddd1b6d2e6aeb761.nq.gz
    ├── 4cd9da03bf56c049e3458153da564a3bb1eb88fa.nq.gz
    ├── 4d866651c082c3288a7447bde64739805831c54c.nq.gz
    ├── 4dd60e40367e9c8237a97e371d3c51781475a0df.nq.gz
    ├── 4e086cd4538a8a03674e87ea563b081f19b40a3c.nq.gz
    ├── 4e19729cc6a20d6952875ed8cbc162e0a843a1d7.nq.gz
    ├── 4e317ea3ad9844098771baca45548006683811bf.nq.gz
    ├── 4e61427c77e851812558ca69b393e33b5b772690.nq.gz
    ├── 4e67d267c9850327fdf6bbbe252919a8519a7ba5.nq.gz
    ├── 4eda6e5a3f65e6f3957394786302970bb335dbca.nq.gz
    ├── 4f436776f8d771eff0933356e3ace52becd32034.nq.gz
    ├── 501dc736ae9ed63ed0c4227731404e17aa5c7e3e.nq.gz
    ├── 520dd665b9ab4405faa81ee6fed4a496902618f4.nq.gz
    ├── 5242d1968fb611114126de328442c153e1be5f82.nq.gz
    ├── 52815986b74665e56496767dfd726e68d3877135.nq.gz
    ├── 54260045acc27f196f9f07c6135ab5f542c5f486.nq.gz
    ├── 547d279f5cd5957f2beda1834b62338b621ac4af.nq.gz
    ├── 548321b9190939588ae69d69c09e978394c8a1e0.nq.gz
    ├── 54ae14fc58c2bbf8479ec16ebd6defa443f224ba.nq.gz
    ├── 5608600f64f779073849122c4b0ff6e9cd7b4c8e.nq.gz
    ├── 5631346a228237220742dd6ba3833bf41a9cd06f.nq.gz
    ├── 5645c57ef70761408cb13288bdf18c78fc2fa35d.nq.gz
    ├── 56717cfb77f7b94b8313911cc9a66c8d1efcc3a0.nq.gz
    ├── 569b6865816bb16edb4cae5a52ff2840c054ea89.nq.gz
    ├── 57ea3c2d5eec6728c77ddc275fb4e83d81c8ac80.nq.gz
    ├── 591d7315b33d87b4ffb11341a664777b079abeec.nq.gz
    ├── 5991c67b0fbbf2ac1d59f0a7dc88a0771b1e3278.nq.gz
    ├── 59ce400385ebb6ab5ff0a93c39903174411cb5a5.nq.gz
    ├── 59ef830b5eab83ae0d60fd96d4a36a57f0509fe4.nq.gz
    ├── 5b6b1b1943e299a01b30d5a0633970956ff3397a.nq.gz
    ├── 5b8be772a945ca20a98528e60f03d5d2ed9d38fc.nq.gz
    ├── 5ba0cb30cef946d21a70be6464ade0d6f92dae15.nq.gz
    ├── 5c0c4a609195341d085e141a6f9ea61cf7a7d443.nq.gz
    ├── 5c98e999da335578621fda6cee1a02c7f2da5852.nq.gz
    ├── 5d283ea003b40a1be92c8373481ea5d8057ceb88.nq.gz
    ├── 5d7815b6b3dda0c4fbe674472a4023301972e209.nq.gz
    ├── 5f0a99766cc45d3e1a8239a17a1cce6ac52f0d52.nq.gz
    ├── 5f406f2ee1663cc6c6c3c6654e2f8759b761aad5.nq.gz
    ├── 5fa19098ea29b8143cca956ae188cda51bc8eb99.nq.gz
    ├── 601cc0fd3c36ea25f8a07cb6a8b61b23755ba57d.nq.gz
    ├── 60e063d93aa9564f85d6d4ecf8d4c3459aa3eca1.nq.gz
    ├── 6257591006f4f4c633da10b5c4aee2af4d2db10b.nq.gz
    ├── 6290c97576fea813dde8e84925964fc94f062d68.nq.gz
    ├── 62a5d95aca7259df0ebde715234aaf62e5eb1617.nq.gz
    ├── 62e03096391a3346a78642eab7f091be8c2c18f7.nq.gz
    ├── 63173db0da7687d7841fe4d85239d8e277d81259.nq.gz
    ├── 6336dd6359b0c7b15601af11d3736473d8618e68.nq.gz
    ├── 63cd0d6bca2c9b0a913ceae5faa7f223d0ce9aad.nq.gz
    └── 652753508b80c20631d641d3f12b8541a2b54c6d.nq.gz

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

[vllm-project/vllm-gaudi](https://github.com/vllm-project/vllm-gaudi)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
