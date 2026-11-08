# Repolex Knowledge Graph of google-deepmind/cryptids

RDF knowledge graph data for [google-deepmind/cryptids](https://github.com/google-deepmind/cryptids), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/cryptids
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f9ffee29e707e4d21d19168748c7660a87c608b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f9ffee29e707e4d21d19168748c7660a87c608b
│           └── chunk-001.nq.gz
└── blob
    ├── 001817eb5fcedef0168651e1b5d54368c89892cb.nq.gz
    ├── 0045462f69772037fc555c16ed3618549ede2056.nq.gz
    ├── 005eb2b8c0172bbf1e87a50851b85019fc76ea94.nq.gz
    ├── 02975f77c212a6ae3119e4f696a671149f7471b5.nq.gz
    ├── 03744dfea297615a9a64e45de55d6798ae2a987d.nq.gz
    ├── 03828ae956bdb640b73787f42c8511f06274229a.nq.gz
    ├── 050ded8e419dcb2f8e8551caf75d9a8711e4c152.nq.gz
    ├── 07584786e5e8a421a09e26b9085675cc90b40fe8.nq.gz
    ├── 07596350a1d7cc3d136f962df955a9c05ad0afe9.nq.gz
    ├── 0802b364dc5f0cb23d369776fdde01a96fee811a.nq.gz
    ├── 091a5f77f86a7d82a7978ff165f8f241512ab6b8.nq.gz
    ├── 095f1c173b54bb120604eea245956ce2b502168e.nq.gz
    ├── 096aeffc26350ca0fb65ac3683f7405b1ebcdfdb.nq.gz
    ├── 09f2f52faf6b26699301f98ebbb285576f1b7aa4.nq.gz
    ├── 0a323875fdc83fd7623e9f6098ea035e5eee62df.nq.gz
    ├── 0a59f135cf7a9033afb898d3c7fd30389f9452b5.nq.gz
    ├── 0b54a9ffe5123792041cbd5cdc24ae6a46e26d49.nq.gz
    ├── 0c5b118f03d5318c0026e4fe6b7257394b5b0417.nq.gz
    ├── 0c9d4411492ca7ac380076487e39c153453a2efa.nq.gz
    ├── 0d48faf318fca4a85b455fc64aaedb9b3fd1c6e2.nq.gz
    ├── 0d6a45311b24ac02f3aedf76339826ffb0a944d7.nq.gz
    ├── 0d79f3ed12f1e282187b6af0c6b7318300bb6cae.nq.gz
    ├── 0dcd8d1ff84949053c3b7460e11d2ee40e3dc8dd.nq.gz
    ├── 0ea40875fa1bb024c2b1ab9a441bf74ecf672bed.nq.gz
    ├── 0f7d81d8139daada1dab1b161e728cb777d29356.nq.gz
    ├── 0fe5ac245f1d19e4c5ad3d6746618583963ad78b.nq.gz
    ├── 102687eeed3c5568bb32357a41d98a6bac75ed54.nq.gz
    ├── 107bf8569ecf958cc413eba1a1a2063f56ab055f.nq.gz
    ├── 107e864a9ee0c5041d9b11e6833d1ecb829b9afc.nq.gz
    ├── 110020dfcfc969bcccda2f1ffa4a449f2129b552.nq.gz
    ├── 112bc250a86b00782386ba92740eb1c57fc303a2.nq.gz
    ├── 11d3b915f9e756426c1b93fb6240d00ea1e10415.nq.gz
    ├── 11f5f2b5b3357a5239666de395ff41dfafafe1d6.nq.gz
    ├── 120543b246c49353419be6a824cd462acd91e0d2.nq.gz
    ├── 13e7fa3bd805c4ceff3b070215db6f2c37c2abfc.nq.gz
    ├── 14095de2446bd7d6295ac1725d72759aceec8940.nq.gz
    ├── 14764f66ada887ae382a985ff3293b7d00726c73.nq.gz
    ├── 15237fbea194d4a117b9319f95df487ab3d47ff7.nq.gz
    ├── 157ad6c8e216ab8f3434d84e98f28bf52854e83b.nq.gz
    ├── 15830e7ff0a96f29410ab6e71905e8f3d738ec00.nq.gz
    ├── 1588e58c5957f8d51d947251c7a7693c3ae418ec.nq.gz
    ├── 16d583f574881bcc560a4903e109da4fcd577a16.nq.gz
    ├── 172f7483d5a6c078a2f4c7600e5f1ad0ee7a4e67.nq.gz
    ├── 17aabbb9beea67c4fb95e57ec2bd55debb87d975.nq.gz
    ├── 18befec598227e3a99e9afdf5d2cd7be6f0df759.nq.gz
    ├── 191783d79af842b1f74d3f79c702a05191897b7d.nq.gz
    ├── 19495f903f4f9eacfa1acc904b1bc91c7b2ff7bb.nq.gz
    ├── 19eaf3575018036c0b3099b3c7ab0ee8ea4e4493.nq.gz
    ├── 1af17e9b5d009180c9bc9154bba4526eebf9f7e0.nq.gz
    ├── 1af3eeb417c85afc1adfae3edb05eaa959fb2cf7.nq.gz
    ├── 1bc10620d7ec5b4cfceeff84684d7aa5628c61d1.nq.gz
    ├── 1c72cce67d856ab3f02eae269322e7a99fcb026f.nq.gz
    ├── 1ca741ec4f4afbfe1cbf7aec33b24a08f5b9c219.nq.gz
    ├── 1cab016cf6061d2b0394a09b4ad762cdfd971ec9.nq.gz
    ├── 1ce1cc5d15c943cc9766e0780a859de64d2e9873.nq.gz
    ├── 1e417361692f3475555c3d21db2e6bef686f8bad.nq.gz
    ├── 1fd06a712211a21ccce4ccaee24137275869b204.nq.gz
    ├── 1ff983163b0d7f6180957b3d90b4e629bbc64dfc.nq.gz
    ├── 21ce980ab7f1fbb3cfe5d6f9932ecd9fda371967.nq.gz
    ├── 227a5a0310230c65e25f03a9006ed7b71163b50d.nq.gz
    ├── 22cad8961da49f7c829e2fded42f14ee4a2e910e.nq.gz
    ├── 22ccdf118c2b70527dfa574fe155e749db3d430f.nq.gz
    ├── 22cde684209c3b4de265f46e1716e5b661733605.nq.gz
    ├── 233cb54a6640a972b111c3bdebb9febe3c2154f6.nq.gz
    ├── 2518de9c357c95f6b06c0c9ac7c412e324bed423.nq.gz
    ├── 256c6fbe1c45309b741de15b1ef6da883dae7d64.nq.gz
    ├── 257eba82d54d80e50c5c787c5ac7c0c62355e027.nq.gz
    ├── 26ae1c9c4807710a39c2de56976e49b49c4c1994.nq.gz
    ├── 2769737cd8f68468a1534718226f92f2a6a6fa5e.nq.gz
    ├── 2783aaa5d61ad4d17eef1aaf72dff98127d33a7d.nq.gz
    ├── 27d63097aca2262d3fef45202e21c181f32aca7d.nq.gz
    ├── 28fe31d3790fa0f88ab04d18d68c9382ce027252.nq.gz
    ├── 2937a1766a9a13b3e5ce8364e5db88a044722aa2.nq.gz
    ├── 294b8e7d5e8617f205a2db6c05c56c15524927a2.nq.gz
    ├── 296d1500b7f60c6472d3d9bca7f6b9baa7ee0b51.nq.gz
    ├── 2a40194a4b439df71ff001537716bb0b544855aa.nq.gz
    ├── 2a7af70b77d7dcacbd603ad92f602522ea7ef3ae.nq.gz
    ├── 2b524999ef0b24ee575a331f3b924ae47520aa3a.nq.gz
    ├── 2b8686244085adc88b61170bc8f5a735f31ead86.nq.gz
    ├── 2c36ae9ee2b4801129684d6eb6aad518829edcd3.nq.gz
    ├── 2cc4af3dfedd4e8fba7d8a0d7b3ef22ad2db45b6.nq.gz
    ├── 2cfa9f17eb4878522e4e7667911c56323648b727.nq.gz
    ├── 2d14c77c68264d5e1890a4a43921acdea3bfc972.nq.gz
    ├── 2d471fcf96a60826a4e203f333dfd0e57088c9d0.nq.gz
    ├── 2dff6fd666e9a3db914d8f72b62288a0041bf5fb.nq.gz
    ├── 2ecddd35a9625a429738ba16af15c7e8d7001fe6.nq.gz
    ├── 2f0b9fa8e289468aa1a18cdb0cef719eb7e1869e.nq.gz
    ├── 2f87bc93fbd83095c4084696f7b5268259f35342.nq.gz
    ├── 2fd1c83066694a23e16d11b23200748cdb520b05.nq.gz
    ├── 3007bfb60a03c452177ae7f4b286c1a1e266e183.nq.gz
    ├── 30491f69e8eef03a817850e39009f00fa7019a57.nq.gz
    ├── 309c7f11408d297315a32068fd680826f6b231b8.nq.gz
    ├── 33463324c0547d984338846ab31f831ef859ec14.nq.gz
    ├── 33981627c528044b058c7c2a570ee3c5b2b7375e.nq.gz
    ├── 344c300442f738f8745886241b2be025a66eb7fa.nq.gz
    ├── 346101d2899a43bd420906a08b7f05d93a8107a0.nq.gz
    ├── 35faf577be5ac7bb79f89924bc05668522a897e0.nq.gz
    ├── 37a3c4564afc2cede16238fca2c54af104a39454.nq.gz
    ├── 37ffcfade16ade2bfb0de0f90ea6601024f0058c.nq.gz
    ├── 380f5b1101a1ab1430251a662ecc04d0e20c8e09.nq.gz
    ├── 389aa3a884aceb5ffdbd927965657ca4e4fcfa56.nq.gz
    ├── 38a0eb8022d6a099efe978bd235bf2fdff0651bc.nq.gz
    ├── 393bd4ca26ae68091dee87ef20d5489808e84c3b.nq.gz
    ├── 3a2f40d5c103b81338035383b09a32fb12b903fe.nq.gz
    ├── 3bb8b74114324eb252e5a5f75f6a551ec5b8e96e.nq.gz
    ├── 3c6eae70196edf6d1beb66c06d7b481e2acdf387.nq.gz
    ├── 3d1a88b0ef3ea29294a4ebe2918d924f0c0977a7.nq.gz
    ├── 3d213cefd531044b76afe7985557136e0c16bf95.nq.gz
    ├── 3d7e3f05b7916a77f0bf7ee0973aa70f23e1c060.nq.gz
    ├── 3e0a5350a45c2b390b477e2968e17408fa7199c4.nq.gz
    ├── 3e72ac981d235d17ed5a1b9000e2b3b96e5bc8de.nq.gz
    ├── 3ecf7e9e650f7638b4b688d58e074279dbffbe3d.nq.gz
    ├── 3ef478f0fe60f7a092555a81b59965cf7c806b32.nq.gz
    ├── 3f274f92d826d04f6411b2275f07638297393e6e.nq.gz
    ├── 3fb18e327adf3e41f40dd57c5e81f8fe1de245e3.nq.gz
    ├── 3fd86d0b954485707b620846f36ccd98d5ba970f.nq.gz
    ├── 40c0987589544c100513c7aff45d4b1e6280e1ae.nq.gz
    ├── 40cbd15136718a57903a1acf856ad40b30ff6116.nq.gz
    ├── 4109060052ed316e026f0b6b48f949e458a8de85.nq.gz
    ├── 410d91e7c1764fb927f40bd04a10f99585e8b5c8.nq.gz
    ├── 41100bb7024b842f86bbfea1e20b2c68aca14dee.nq.gz
    ├── 411c0b6fed3479d144158dd7140ec2fd64b3e265.nq.gz
    ├── 4173d0a5998d0ad7ca3f5df7ea815ef8c8b4a3c4.nq.gz
    ├── 4217238dcd27dac9f278d13562910720afa94eb1.nq.gz
    ├── 42268d7f921949cd03284f3197ac5f82717032fa.nq.gz
    ├── 444850dabf0f49cd5ff9bc0883ef2a0113cd5b0d.nq.gz
    ├── 44ef97dd7852b3c35ea0ba04ea8ea67515671b2c.nq.gz
    ├── 4609668cfed828c1d266c69700c7d990cc9103db.nq.gz
    ├── 462982bf38c83f1c5dc4d5b96ba5d68de2a899d8.nq.gz
    ├── 469ca1a628495aef02674162dce48c95cb6ec1ff.nq.gz
    ├── 46ae1d9009895affea6433438058db0fdc9bbf78.nq.gz
    ├── 46c00e527fc3db1380d774020f6d3e10cca15c5c.nq.gz
    ├── 476d1101cb827e1a29ce61232d2e7b8b0727fecf.nq.gz
    ├── 476f8e6af5917948eb0c08bcb8f72d9a67e7b3df.nq.gz
    ├── 47b864c35d60b91d53d8e61a91e5b1452c9ec9fb.nq.gz
    ├── 47edfe287a094c1f896e912bfd05be1b243835c6.nq.gz
    ├── 48e9c12d3693aff95188a773f48f3004ffd8e79b.nq.gz
    ├── 49cca7160a8a08d4b59d30b39aa08aeaec659cf5.nq.gz
    ├── 4c56373ec8b39c24789775cddcf1641e3e68aa5e.nq.gz
    ├── 4c7937b91c98fac78fcd51853f2f91dc17dd35cf.nq.gz
    ├── 4d8b763407d9432ba7d2755a0e6a9d98537bb176.nq.gz
    ├── 4dda34730cd0321d8e00fe54b776580c5c95a343.nq.gz
    ├── 4dea8883d1fdb9d0234b1dabe95292a585f74444.nq.gz
    ├── 4f494ac0f5d5b0a040743c25e2947b7dbb1e7a81.nq.gz
    ├── 506ddf380f46012b09469116fdb554ebb06a2672.nq.gz
    ├── 516a2e86aa82c5c72baf56f9697764ad7b7d36c1.nq.gz
    ├── 5291515939b52bb65669ba9871f23e1966fe551c.nq.gz
    ├── 52be35969a5d73dd9c6a66fb0aa99ef80ff20d84.nq.gz
    ├── 536fccd80893a65db13f9b8694debe80a10f06b0.nq.gz
    ├── 53e8005a4f17f15833167ef9aacd147c39d166a0.nq.gz
    ├── 54a1a29d44a55d4a9b34ee05659dd1b7caddfc18.nq.gz
    ├── 55415c3ae72669262f8e2df5cf26b5cec2d78692.nq.gz
    ├── 55b4495bc0e47d00650367d7e69681a4b07d35c1.nq.gz
    ├── 563b1c4cbe1678903bba47b660236a3e08e73611.nq.gz
    ├── 5645700d5b778305e630af2c861b33620fa60842.nq.gz
    ├── 56d25278efaae4e6b7aaa1c253ed490845f785d9.nq.gz
    ├── 5715fed21890744cc2fb74f71f701973fffc0e2d.nq.gz
    ├── 571cd2be2ea8b49dca859b849e510a5805c63059.nq.gz
    ├── 57c1aad42d29fb474a2c93754e0cf4d1e47b9df9.nq.gz
    ├── 57fc201a6b2f5a4bb68f7cfa9a47ed1e3c6fd76d.nq.gz
    ├── 5938698a0bd38474ff7e9a72d8f1b05db7235ee2.nq.gz
    ├── 5961e04bb7149bf3aba6d7dac40c3b556cdbb429.nq.gz
    ├── 599ad718f70f1a96583e1b50e4da8f20bd2764ef.nq.gz
    ├── 5ace947bdb4fd8e5065dc61734ba701f5f2c7356.nq.gz
    ├── 5c313d95f1caa7e96f1c1d2e85c8e45922af7532.nq.gz
    ├── 5c9c7f08fc15fb7fcf94613ff6cb8a3991c76a20.nq.gz
    ├── 5d4879acea0d5a191387302e74a0f910df8c5e16.nq.gz
    ├── 5d60c27f820df600e7881fc671c2f3adb16a7fd0.nq.gz
    ├── 5d8dd2552a131e3128a7ab57069a0973f56265ab.nq.gz
    ├── 5f5691293cbc7f12cfd70313707451cdcaf290b6.nq.gz
    ├── 5f6727cf467adcbea87c6d30333923e14b2bf8eb.nq.gz
    ├── 5f715a57f2675d8f427cc2804d34189628689545.nq.gz
    ├── 5faadb7cd7193ddc0520d6c84f23bdbcae372feb.nq.gz
    ├── 607f3199679c6b11fce25594ebec712398083298.nq.gz
    ├── 60f9da81b3f942efb285a888f629f1899cdbdc20.nq.gz
    ├── 611e3edc534df805b76f13bd09bf4edecd5a6323.nq.gz
    ├── 619246dc6d9e9c2ec4d0b63c1fdc5aeeb976b8b6.nq.gz
    ├── 61caf1686bfe1675bd2b119d36fdfd18a6b542b9.nq.gz
    ├── 61d5aa35cc78e98c373e5785b833f33b5253aba1.nq.gz
    ├── 63a816f4a0c0142373a41ddd4f3edaa0dfb9169a.nq.gz
    ├── 63fe8922b365175f8763e1469278c5c0b5938b48.nq.gz
    ├── 645f243eaa72d3f8a8a1f891437950d8a1d61d7d.nq.gz
    ├── 647f287e3cfa833ae1298231829446ee850a1d46.nq.gz
    ├── 6481b36171ed31919fcd6bd9e4ec985f5980eabe.nq.gz
    ├── 64cad3b571297585c2f3936fe2394a97de0acd13.nq.gz
    ├── 65c1bee79fb7ef0232249b34828bb81c3acf40c6.nq.gz
    ├── 663b2af6fa87b2cfc3c8d73b88102044c4325346.nq.gz
    ├── 6692e85e3f30e27373a28d0708e50811efe5af06.nq.gz
    ├── 67e4453ae28f43fe4593c3334ee219bca4f58f7d.nq.gz
    ├── 6815914d9d0bd8e37533fe4cfd1f20daab680b51.nq.gz
    ├── 691a83c46cea61b058f624e73dd8c24ae94f9026.nq.gz
    ├── 6929ef4758bec5a69123a37ce6cc7f40e9fc6acc.nq.gz
    ├── 6955c0d454833fb188620475f6f72aa7244f09da.nq.gz
    ├── 69b5e05048f27a224ad681520fe95609350f4511.nq.gz
    ├── 69e0957db6aaf4a5f2c6a13f6def7c532e8e6e6b.nq.gz
    ├── 6a87720698f4a6042e925d2b8822abc6f31e489c.nq.gz
    ├── 6a90f30a7d0dd3f1bbbf62797a134f1656a73d43.nq.gz
    └── 6ac5913b6e93074fadf2aa8283a108500bd922ea.nq.gz

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

[google-deepmind/cryptids](https://github.com/google-deepmind/cryptids)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
