# Repolex Knowledge Graph of slackapi/python-slack-sdk

RDF knowledge graph data for [slackapi/python-slack-sdk](https://github.com/slackapi/python-slack-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download slackapi/python-slack-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d9618f86e9ea7e4a7692240f7418474f4849ebeb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d9618f86e9ea7e4a7692240f7418474f4849ebeb
│           └── chunk-001.nq.gz
└── blob
    ├── 0054ef3be4270195b507b1e26aaef4dd19e6aaea.nq.gz
    ├── 00b3126d78e840afc1049dff589d5911a74ae992.nq.gz
    ├── 01cd284418ed3ab469746ec96907e8ac1c080797.nq.gz
    ├── 024d941a30196d204a50be898eb55bbe4acf8e29.nq.gz
    ├── 03427b45a51e058d97157f3e3a798384d240d726.nq.gz
    ├── 03f11d266816a5ce0b09f1f392d4f4ed4fc9be6a.nq.gz
    ├── 04d8f7cc6f5b867b7533b01f7d067c50cefbc45b.nq.gz
    ├── 05a4de420971b52435accc093eaa061041963a54.nq.gz
    ├── 06289cd70b7aa73579882a519ee74f5fb7e24c7b.nq.gz
    ├── 065bb0204b0f05c38557ae6b5d59d044eb9aad3a.nq.gz
    ├── 06f014f59338b4ff4e10564b56f271a65d676021.nq.gz
    ├── 080e1b9882f288e6531cbcadbb9120fa82628de3.nq.gz
    ├── 085b103d9f890b64e7182bfcb7969255aeab4762.nq.gz
    ├── 08969eab2441cc1aa4e270e6dcbe7ecd481ba53a.nq.gz
    ├── 096bd7d042649f0b6304ca58346b705f865a2e4e.nq.gz
    ├── 0b95677e1e958972d66500516fbcc3d1d26c64b5.nq.gz
    ├── 0c0e25c5d00e00cc0ea4c9b32e973d06d85c4cad.nq.gz
    ├── 0c84b59ff796eecd35e9c658a48ccc31a4c403bd.nq.gz
    ├── 0d89c4cbb268e06d30fdbdeaf364aeaedc4c72b6.nq.gz
    ├── 0d99d67a704932c2583e5a51bf3ca23868733210.nq.gz
    ├── 0e18bb48d25f1288dd704388cf03e375ca8e93f5.nq.gz
    ├── 0f8e5e8b9280e31ea77f3e73569537570f74aba3.nq.gz
    ├── 0fe55a65c915eb2857a287f712364b027d31b35c.nq.gz
    ├── 10e2ec4f07b557c97dfaf18827eea6b31480f38e.nq.gz
    ├── 11ca100ac15ae40cdbacaf141d3c24cfede2628b.nq.gz
    ├── 12c9004c78f2bcdb04386a957d28ff79d8ef1989.nq.gz
    ├── 12d99c89cfe93bb4b33d9617b666dcf17a8c7618.nq.gz
    ├── 12eae76faf271178dcd0638f02451be952d0d831.nq.gz
    ├── 13290367e34cf03d8caf662385696da83146bcc6.nq.gz
    ├── 13cbd710acadce30d726a4ee9a28e14888591c4d.nq.gz
    ├── 1446b32e6f218ff08a077ac980a3cdbb337c76cc.nq.gz
    ├── 14635c661691dd20f14b80bc4c488d1b9e54fe76.nq.gz
    ├── 14d69e48dbcd5ebe262deb02f666a9cc40060c2b.nq.gz
    ├── 1580b9b5c7b5b90813fb4c0fdaa3b72a5232932f.nq.gz
    ├── 15e1eb286b3b31a94f25ad9a47e20629cef8b20c.nq.gz
    ├── 15ef9de6d4026c3e84566cf6446648432504ba54.nq.gz
    ├── 16d58f4213fd99151c4c733ba6f091fffaf398c5.nq.gz
    ├── 17dd3302f7f66c1ce47243f1c262b9d89e425082.nq.gz
    ├── 1819d4ffacf0e63f90eb62a672b836ba0fee7da8.nq.gz
    ├── 18ca8e0b13b5ac7a8c2a6ca2dacdb394873c2de4.nq.gz
    ├── 1925abae798aa89379baa865646879131deb504c.nq.gz
    ├── 19749f04d9e908e971bb7477acc908f84cafe51b.nq.gz
    ├── 19ac9a805fc06128aba413ef41fc30836c2172c1.nq.gz
    ├── 1a267cb727b57499605e24b5b1613883d69849d9.nq.gz
    ├── 1a2940a81bdcadf3f9906f89d3d6df67bcd2fedc.nq.gz
    ├── 1ad5908388e7bcf368f24c4810ce66935b38ae9e.nq.gz
    ├── 1adf7b504c492ad60ea752e6f5af25ad97883c6a.nq.gz
    ├── 1b5310d3fbcb13742edb7c11707bded8334e15c1.nq.gz
    ├── 1cc6b2cc115868670230de76ab7767c3febbf233.nq.gz
    ├── 1d3d1a05ea5f40b4aad68e6ae76c0e38d6b90fde.nq.gz
    ├── 1d988946c8cf8a7fc0527684c75c9421d2984df7.nq.gz
    ├── 1dd94deeb4f1f3d852a2d8365e502090690b333c.nq.gz
    ├── 1f7a9eb98ee72393f589d21937eaf0d9fc7c35e8.nq.gz
    ├── 1fd986c695bad936af967c1bc040915efb198e5b.nq.gz
    ├── 2001b7c63b944367bf8c1051a6bf507ae29d265a.nq.gz
    ├── 20126e3d97ac86bf0592bffb4abf3332e84709fd.nq.gz
    ├── 20981d5b71348a28b8143b4dd43b0104fd9375fa.nq.gz
    ├── 2102db125be24fb338e8fcb9a543211d3257aa1e.nq.gz
    ├── 216453afe2ae8a635856e43b1c3805983f4fca2f.nq.gz
    ├── 21adbb56945794e211a857b11f24997d726c272d.nq.gz
    ├── 22353f1c3cf39118228b5e72ca8131c56c956977.nq.gz
    ├── 225d27e278a1a0e5f575551e95bdd40e01ad446c.nq.gz
    ├── 2263c918ef4cfbf480e06e165e8054ebca605b21.nq.gz
    ├── 2282ce4275f419432d9c706387913064d7b587b7.nq.gz
    ├── 22e883bbe0aa22e626d52479dd10756d75648d54.nq.gz
    ├── 232a00cf139ae920dcf1872302c78cfba0f4eeab.nq.gz
    ├── 23e3e0ff7d88e2f27ec78ea43bf81a4f2efebdb0.nq.gz
    ├── 2455779ddfe633b3bdb1d6225af8e47bc53421b3.nq.gz
    ├── 2567014a60fca52d3a37d0d090ab1b779cc168a3.nq.gz
    ├── 259da684b0fc4620dd947ac70e46a2efdc22da11.nq.gz
    ├── 259ebe9f6982cad912cc6d8ccae0d758d8ba58ce.nq.gz
    ├── 277b8b83adf053d00a50a213cfa5ea2205408561.nq.gz
    ├── 2a845dc4d43694983f7c406888e53ef5aa8c5561.nq.gz
    ├── 2af633430e547ee105ef9085a7c9c8b85a91d7aa.nq.gz
    ├── 2b4c02a7c942c66f61b17170a566217fa1206f79.nq.gz
    ├── 2b6b18f135ce972eee989f0e3ac54dd807dce48f.nq.gz
    ├── 2b95382ce51aa69dc7b5d3389d48a7e4d26608e4.nq.gz
    ├── 2ba68b1d5ecd1fb558ef052e3e7ff23b33a95d19.nq.gz
    ├── 2cb27988738d22b8a0f400115ea14fce872f39d3.nq.gz
    ├── 2d0638e7d6238f05675b6310e6551a8e745c3181.nq.gz
    ├── 2d3ce7904e283a684cf90c14a57065e7a997bc21.nq.gz
    ├── 2e1620b84ffd31b412e19e850edeb4e500c6dd5f.nq.gz
    ├── 2e7f132be9b0c7eb2ad550d89cd853b59bce68ef.nq.gz
    ├── 2f40a71bde35153472f1b96844272f0d5849e13c.nq.gz
    ├── 30939e59be0f7308262e9afbd20a4047e86045f7.nq.gz
    ├── 30bcb70024f1d0cb5ca91a8fb1973db1986c42c8.nq.gz
    ├── 31310c96f7b23d5b8803e65446e9d02431c2c035.nq.gz
    ├── 3160d7733c10bbeb89199cf61389d976200be7d7.nq.gz
    ├── 317354a51aaa5a61f4759ba1dbb7d45a8b634e5f.nq.gz
    ├── 319c718f9b8b83912b6dc1ca84b4490741bac0d2.nq.gz
    ├── 319fdefed98e76b6f50e01fe8fb731f0cca6fec5.nq.gz
    ├── 31b0dcb78e84ec00fb2a014e59e2ef7015f7c4b1.nq.gz
    ├── 322bd8c73331fa8f5e97abc6413645e140a59840.nq.gz
    ├── 335ac7d0a5635f0294352ca0e270d94d22b02b46.nq.gz
    ├── 33b393830999a47fb1f2da7fe9a00912026eed63.nq.gz
    ├── 33c349f68ed65b45720c43b862acef4d8ac756c2.nq.gz
    ├── 36311318df8de1ab045754c15e5e6e0047829dc1.nq.gz
    ├── 3643dab11549abf2a375b96b5dff30217e60af1b.nq.gz
    ├── 36762479cd41c6bcdeef42e343bd4f930d915555.nq.gz
    ├── 36d350f53943935931c0913f088ac25da7815963.nq.gz
    ├── 37147dd3bbd18a22f29e78a46aa662b203bfca5d.nq.gz
    ├── 37203fc353416d472ef8d6578f64cc9deb437a32.nq.gz
    ├── 37b1dca6fa94ccf608c61cc2f2452f27ce9ac7ff.nq.gz
    ├── 384126b6341137fd72325e01614db9a48ec9d5fd.nq.gz
    ├── 387778ecbb7abeb1bdf126e40968e466b18c2601.nq.gz
    ├── 3898c5b320560fc610f3cde4064f7b1fac2a892c.nq.gz
    ├── 397fc458440941daa540f11af663c0267a7bab1f.nq.gz
    ├── 3a18c4682b4719a17d79a0d7567ba1557f7ae4b4.nq.gz
    ├── 3a2f7f6a12d5e38ca2f8016098d0add044b2320a.nq.gz
    ├── 3a3599d1adc51273c9aa1978ebf457387d94baf9.nq.gz
    ├── 3a6db7203e0254a1af5d257c6c641b07d997e961.nq.gz
    ├── 3a76e30b9d87613d590231c72a035761914036ee.nq.gz
    ├── 3dd12fe76d3d70836d9b43534de6afcbd993d854.nq.gz
    ├── 3ddf0519efc9cc48777e72e81eb1080fcf934a1a.nq.gz
    ├── 3e4de7b49186c050b1645587a2b368d56a3465f9.nq.gz
    ├── 3e606fb5fb867cf2cc11f8d4a307b9c6ad023b1c.nq.gz
    ├── 3e9681f2249977ad8b6dddc5df91e65427d7e242.nq.gz
    ├── 3ea4e7695c7a2fdc58d4b76caed313482003809a.nq.gz
    ├── 3eec0f0c91c22096620e80246171e02da2375bfe.nq.gz
    ├── 3f6ea3e63008b1da34bb7f99f5ddc3f225aa87fe.nq.gz
    ├── 3f85c408cbd335e10ce13c61306a321b16e1fd86.nq.gz
    ├── 4100051b401c47f59cbed375c7195bed8ea76db3.nq.gz
    ├── 4208a4923470ce9117a76d1574bc52b41e1d698e.nq.gz
    ├── 4209195e849570a092864c3dc230b1b0a5803e44.nq.gz
    ├── 4217eb5719cde8f5487e0655cd6bcba32c912dc4.nq.gz
    ├── 4290e7a29345ae10ff50e152e82e7f90095d59bf.nq.gz
    ├── 43b1ec7b2c6cacfab317c12315722dfb641aa81f.nq.gz
    ├── 451c8bb97abf0f5e2317eef9358e21c8aee6cb98.nq.gz
    ├── 4530f7ddc43a7669064cd11359f4e4ef35629541.nq.gz
    ├── 45c086e61e9af37a0e7f583b1965162f8d1cfa10.nq.gz
    ├── 47d7adfc33f82a2eb12b0225117c4d986038dde1.nq.gz
    ├── 47deb103816b22fbf5d73770d123bd03023eff8e.nq.gz
    ├── 480b8ae928f56013a40f28153253b00da2b9fa19.nq.gz
    ├── 49340f56e8f755956fd71dc07dca8ad060fdff68.nq.gz
    ├── 49394bb3044f4f53d1d05518a19eac1710c2694b.nq.gz
    ├── 49e430cc83b70da8fb51437efd141369e8405fcf.nq.gz
    ├── 49fd15230b95cba6b69ca4f8d90ce537c92b1b25.nq.gz
    ├── 4ab780b2b00d54b1dc79de0706d3b0f5c4d2ca23.nq.gz
    ├── 4adbc848a055c7585c497cb30c3490e6139ab48f.nq.gz
    ├── 4c16bb3b55c7796943f4a58a984b22d15688e375.nq.gz
    ├── 4c24f8ecfdfe8a98dd559ecad3dc9c8b7e7f51fe.nq.gz
    ├── 4df8de337c685d97db61c0feaf63307653b9a39d.nq.gz
    ├── 4edc638ef006866cc96193759611081be97e5559.nq.gz
    ├── 4fb9772441e6b7a850f4b68812ef8de97a4f5f19.nq.gz
    ├── 511fbe025079656a08d3cda790e568942800bba5.nq.gz
    ├── 522fffd06f34b89f275df099f1d555f97e7b8aaa.nq.gz
    ├── 5281514fcd43558c5f5509413d94fb543a9aed45.nq.gz
    ├── 52cd7bcb5253aaa36d8bd4751eb9246b57d3d81a.nq.gz
    ├── 52dca49c4ea57a7e7f7a52eb15bed703e1f8ce47.nq.gz
    ├── 52e59db8eb300eef79518c546efb457af3aa6246.nq.gz
    ├── 52f881470a783f8d36dd822cb9f8cc1e0c6851ec.nq.gz
    ├── 5416f4d31eec745b9439b462131d788c509ca3a0.nq.gz
    ├── 5477be0c216e893d59f54aba7409ac8ffd961a3d.nq.gz
    ├── 54ed0e04b83ccbec731f5b54dea93ae50a607fc3.nq.gz
    ├── 554f849d0e93e1fbe1ace2269cacfe96ba825cc5.nq.gz
    ├── 5568e5e6ba7ee779d2d638a4021c695b807ac664.nq.gz
    ├── 56695eaaf2d7ff45eb5a7d66f6b070fd1a9d3625.nq.gz
    ├── 56dcab440664d49be32731069074f53a2d4ec6d7.nq.gz
    ├── 570d7d1fc8ab40d278bf8b77ba07bfb49c8696c7.nq.gz
    ├── 575e48657d8812fcd5e972899705f028759e3138.nq.gz
    ├── 57e8e991b5eb7f0f68e2caae96d6a48a6472a3d1.nq.gz
    ├── 58311a601e812e6daa77dfba30376e90d42a8d26.nq.gz
    ├── 584dc5456667bbcd666c69ee634e83dc491ac9c2.nq.gz
    ├── 588b0b5f0df983c85627c92d80c62b4623bb5281.nq.gz
    ├── 588f504974aab8c1603de0bb4237b0c9fb78ed36.nq.gz
    ├── 5915afef7af9fe6ec9fd66bd2c4ef6110312921a.nq.gz
    ├── 59b09a49d902d1a0aae9a66a8f119440f14ff6eb.nq.gz
    ├── 5a8ac17c7d4386648ac8a984ab53c99c2e19be8b.nq.gz
    ├── 5bee7646082a938bee44a7703acdd89844970aa3.nq.gz
    ├── 5c29732c88ed67483ae2db185c1e0cce54150e86.nq.gz
    ├── 5caed8a00daf65aed7d7e9b354503e292c52a267.nq.gz
    ├── 5d253cf89ac6d5900d7507077571b29cd83adfa7.nq.gz
    ├── 5da6b8086b1efe2234bdf4be917e58791d144fba.nq.gz
    ├── 5f1495b21caee942a799bd6c0bc12688e16b3f07.nq.gz
    ├── 5f1a34bf5ca740660ec555cf305b8849977f0db5.nq.gz
    ├── 5f316a34159dd4fd4ca8ca6b1744a8a523214e4e.nq.gz
    ├── 5f6e6c732e1a84b5807a365ffd26f85978f0321e.nq.gz
    ├── 601900a0dc1cd2522b4510e9d6e38f1b009c4cd6.nq.gz
    ├── 6022bb14b26ba24d14d10aca33d46baa993761b2.nq.gz
    ├── 6025aa029e01d53e4d35cc4319a579862d869960.nq.gz
    ├── 607920efb58195bd443d47cafa10b9dd3734913e.nq.gz
    ├── 6129a8a4233a99676769118965e99574993e5a1f.nq.gz
    ├── 6370ffb77e9504a4c4ad73f4a5824223c2e057d4.nq.gz
    ├── 640ed28846eecdcb9836b217298c8452fed7a46c.nq.gz
    ├── 644ed31dd89287f7b00eb6a5df282cf69bea7189.nq.gz
    ├── 65c8c35b2d3e80ae3f0f4b11e649c80cbdec58df.nq.gz
    ├── 66971561d73a261d345c332b788b6ff59823992f.nq.gz
    ├── 6701cf6f0267f429d330e5f12da518053de600e6.nq.gz
    ├── 6785c59c96a95332b34208af768c1f7470fc6ced.nq.gz
    ├── 67aba957c357d688300d0cd382d9db064cb0f894.nq.gz
    ├── 68e3ce867e935d466a5a6d9f3c2884e9f912d383.nq.gz
    ├── 69f351c6df84069bfb9769d1440cb2d600e2c00f.nq.gz
    ├── 6ace8f8ba71ad4ae42820f41a643ee9bcc32c71c.nq.gz
    ├── 6ad4fc7258e9182d03d9f9962e15c690a36e9ce7.nq.gz
    ├── 6b03c460af8988dc33882b2a229fc7bc6d67376d.nq.gz
    ├── 6b31f4b1e0a19a362362ae89502a8c48fc1a08b7.nq.gz
    ├── 6ba64c9a39e35afac4f070e60786720675fa8125.nq.gz
    └── 6d813bffef3ec8b73981aed8cf6e2b7095e8c728.nq.gz

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

[slackapi/python-slack-sdk](https://github.com/slackapi/python-slack-sdk)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
