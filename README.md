# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-serializinghtml

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-serializinghtml](https://github.com/sphinx-doc/sphinxcontrib-serializinghtml), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxcontrib-serializinghtml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0f3b15b2e6bb47570d605ebd5687643d7a85b9d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0f3b15b2e6bb47570d605ebd5687643d7a85b9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b52be71bffc639a555eafe0ab891d4a93e3029.nq.gz
│   ├── 059fa9af3d4c43885fee7d766570b98576be3b71.nq.gz
│   ├── 0758298f8e6ecb6193d6fbaf053090b43e6ebf0f.nq.gz
│   ├── 08754b39c49e222cedb7f4d5ce475b7f81ee8b12.nq.gz
│   ├── 0d9d19c4a2174e2eeeff4d1f3cce0cc445eadca5.nq.gz
│   ├── 0f690fb0bf33af9a309963ee330fba7df9b634af.nq.gz
│   ├── 0fda33247b97708b24ed539742ae3162c628b696.nq.gz
│   ├── 105a05678141d80b59db9c26e8474a8e705bee67.nq.gz
│   ├── 10cef947b5c9825090a209f2e6a9f0409e20de24.nq.gz
│   ├── 12777a5008004c0710c3a9b28a026d547c9111b4.nq.gz
│   ├── 1421df244bd6ba6f7a85cc94a2684ee515e6a27b.nq.gz
│   ├── 1864262954037ad308a119133e50c1ac4e1c6c42.nq.gz
│   ├── 1898268fd76c58fd1c71d2ff7fb52ffc779ed489.nq.gz
│   ├── 1b163d2395760c5929a9246422450cd898cb3c34.nq.gz
│   ├── 1b7e20ebc722cddbf6c51243f08b8f5c92139646.nq.gz
│   ├── 1c17c86034755a7eae357d2d2225b89104b290e8.nq.gz
│   ├── 1c3e37bcbe5b30f1ee821b1af66dc681b940d703.nq.gz
│   ├── 1de9d832c91207ccd1355fbb638aee1581e07419.nq.gz
│   ├── 2532510adab3ccb200e76b7b769fb6bf469653c4.nq.gz
│   ├── 26273b4217be39f5d4d67b0a0a862024fd8e19c4.nq.gz
│   ├── 2a3178e7e09d98981be578521375044432cfed89.nq.gz
│   ├── 2aa83073c5ab05a4a7e5960c66c6dd961db5eaeb.nq.gz
│   ├── 2af56846afd125cca5f55d781cf1c0ed1a65ddd4.nq.gz
│   ├── 2d1a23c49c47b8f706704a143e4f08b704886342.nq.gz
│   ├── 309a780ffd94c68274d8e03333bae1c3a06ab1d6.nq.gz
│   ├── 3198abf09d6dc8e0a5392a2852ad935a93a2b6db.nq.gz
│   ├── 3241a9a45b4d9e5e383644c68012dbc5d808a912.nq.gz
│   ├── 336e12fb4f5fa637304c021e3ef2758c65ec9262.nq.gz
│   ├── 3588d0de0bbf25b07ed76e3281d7e00d94351a65.nq.gz
│   ├── 35d98e80f19a031512c2f6eb7b0ecaf579f15556.nq.gz
│   ├── 3661945d3d6ce38efa1a71d5e83f452a972fcee6.nq.gz
│   ├── 380cbbcf752d43f58f7a2400634e3b312bbcf4d6.nq.gz
│   ├── 3934d3fc39cf1fbfb6ff26d92dddffb9b818bb43.nq.gz
│   ├── 39e428b828c72932fee6168574ce0ef36493f4fc.nq.gz
│   ├── 3c4af30e19caaef3a3388aee76d32240758a15e3.nq.gz
│   ├── 3ca202108923b43a28901d14f84bb99c7d28f5e7.nq.gz
│   ├── 3e9e4444872832ea9e6ccb69ced2bcbfa476d7ff.nq.gz
│   ├── 3fed4304054e801bf2897feb90d2138793f61317.nq.gz
│   ├── 401768c966c0469c323c5dab94b9e66910ec1a42.nq.gz
│   ├── 41247c4b1ab85add56565ebdcf44656b0490ecd7.nq.gz
│   ├── 427a37623250f8932c47f580b96433b415f013ec.nq.gz
│   ├── 432bc88232a6176e24cfdfad4f9acf94a860bf08.nq.gz
│   ├── 438ee542159fe05dc8a18a22cbacea27001281b8.nq.gz
│   ├── 45b7649ccdd45cf7b24288eb428e0004a8dcfed5.nq.gz
│   ├── 46c1508926f0654655ffe4f834d688218d78163f.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 480930bb801aac7d7c4a8654d0b655de39beb63a.nq.gz
│   ├── 4b7dd2a5ac321d8dca7fcecd8e6507f3da934aa8.nq.gz
│   ├── 4c2252f0287f8f92e103bc84b1f3e32d5e3f03de.nq.gz
│   ├── 4e9fdbfc4874deba370b4b00d8b6a2d44828e9f3.nq.gz
│   ├── 57819c2fa4806741bfecb0f3f06a321f9d62f41a.nq.gz
│   ├── 58db803941016eb94af67c465731e55ad7fc9da2.nq.gz
│   ├── 58f82a2d421a8721e06fe49d3c41d8e06e6fefe0.nq.gz
│   ├── 594f00ab951a2324efec4277af131b1ce2b7bc65.nq.gz
│   ├── 5cd95986b531f25553e24a7843dd85175bb423fd.nq.gz
│   ├── 5d95e182938bedb357c5698b560ebbd5949b47da.nq.gz
│   ├── 61803dc227e9f704c3485899f184d5bb63c48c89.nq.gz
│   ├── 6425c1ea3d189190325a4177924d9613adf02fbf.nq.gz
│   ├── 64481553c3edd7a52aa4b9084af0187f3ad62290.nq.gz
│   ├── 64d76ed5b6dd7b1f8c759549a4f8011e4514a9de.nq.gz
│   ├── 66fe449c7d82cb8778a4be068d059b24e40b5b2d.nq.gz
│   ├── 675daed30eb5c431b63a56170dd71b530d1fd030.nq.gz
│   ├── 6c9c648ea36b5e28656ebbfaae07990b92312426.nq.gz
│   ├── 6d78765c690306b48cf0b01da180982cf3343c15.nq.gz
│   ├── 6db6ef8c0dc205643a65fc34b2c6a10cef5ec5ea.nq.gz
│   ├── 6f06d0ec6a27d4f6fd171b75824077c64d88635c.nq.gz
│   ├── 7037a6c3c32940c71aafd9bd58ff7b465887e67b.nq.gz
│   ├── 71d76222846d1e492995956b4bb38385d8311265.nq.gz
│   ├── 760921e9752f00470e3c2521cce3eda5bd09cc59.nq.gz
│   ├── 76da5bf2ac67d8cec9a7b9ada0af468945e171b3.nq.gz
│   ├── 7b768cd735f4e9ed7a9543cca181c8ff8968ebea.nq.gz
│   ├── 7cc7f52711423a85ab78a1b0533d06a54a72740a.nq.gz
│   ├── 7cf12361445e2fb046fb5c4b90180bcca7c41fa6.nq.gz
│   ├── 7d97af27d0cebcec3b4cec40be807efc3be0fac9.nq.gz
│   ├── 80398a2b75deb4f93ddec95fd680172fc79f6d1d.nq.gz
│   ├── 8ac464d5f91809a861528f5bd283fcd00ceb76b8.nq.gz
│   ├── 8bb908eacfdac0b3288509e9bb0d163dbd3be3d7.nq.gz
│   ├── 8c16f3d6bf65eb2b2815ce340dd3fbb524ea740d.nq.gz
│   ├── 8cc5c48e5d9217cea6d1c404b6c8826fc0233497.nq.gz
│   ├── 8ee42a8d63aea68b51ce790b39b4113539513d68.nq.gz
│   ├── 903c734b5fd1d3b390f7c6b3778aba13767562b9.nq.gz
│   ├── 91df8415310a4692575c2c158f4ce781c66ebf37.nq.gz
│   ├── 94d861ddf2c1c69088e704dbc7cc5f954ffacff4.nq.gz
│   ├── 9803e852f5e7cd2563a7926cc6ae4e21c832c2b5.nq.gz
│   ├── 9a1b8187fdfb1b2cec4afa5f4b584a6af47fa7cd.nq.gz
│   ├── 9b89875e0c1c9db5e787aa1e2fc48b93df0840ba.nq.gz
│   ├── 9da78becd2c9650fc421db43a62396d2294da93e.nq.gz
│   ├── a78b954145525dcc864d0b121343b7a51864e2ab.nq.gz
│   ├── a97bc7c96bbbc347a633fa0d1eebca4320d9b32b.nq.gz
│   ├── aa5e819ce0616aabac4f9423d6f6ade0ecdf7b45.nq.gz
│   ├── acd4e1748fb70bed03340293a4e02667593961a2.nq.gz
│   ├── adf0efbafee95a2118f3b4e87f032c0387499a15.nq.gz
│   ├── ae3e78b153353ca128bde352e2ef1b29df18f325.nq.gz
│   ├── bd60c1fa1bbf87fcd24484b00f1d849c939ce76e.nq.gz
│   ├── bdbeb6fb792acd4bac49c95334eccee80c289f49.nq.gz
│   ├── be3a9d28d81551d109a6684f4ea4cf48d4902175.nq.gz
│   ├── c123b430b1346065240a388ac96b3a9b859fe384.nq.gz
│   ├── c89446768c34e61db36b44450359c2ec578dd182.nq.gz
│   ├── cb6939c32b65a5db58840286f4988cb544ce65c1.nq.gz
│   ├── ce7bb5a31520e4f3c2a855ad1e2cbde2be1b6921.nq.gz
│   ├── cfd3ebc8cbaba217377be4bd1ff30a0d637888ff.nq.gz
│   ├── d0452d113d2c18e56ffc5bab749cbaa636331e7a.nq.gz
│   ├── d29c0947ed9646430d9cbf87e5c3c8080a3e7819.nq.gz
│   ├── d31dc6bf00723365361bb38fe2fc4bad0cc83bf4.nq.gz
│   ├── d445d83e204f12a4dedbb65e733e62e2ccbc2454.nq.gz
│   ├── d46bafa47ee9da6f5eac647eb003808f04cf3df5.nq.gz
│   ├── d97e5e0e19f261a89c19a73320dadd862fd27b40.nq.gz
│   ├── d9ed40aeea075273fe4ca7dd2431b9cad3eb6912.nq.gz
│   ├── da8bd8ca7b29151f82e27dbd97f3a09c77e24a5a.nq.gz
│   ├── ded0ae975289f1d1f7afc2b936ce8098643950ea.nq.gz
│   ├── dedddb3953e16aabe13f8b7cb1c2181ef0d8d72b.nq.gz
│   ├── dfd9f8538a24d5203d7ef3ee55c17347f06bcef1.nq.gz
│   ├── e127e7c9fb7ea31fb59ced325cb08409ce8fd1a1.nq.gz
│   ├── e337f0f6b13a21f1bb165fd67cec569e65c94ad5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e77aaca6ff54cbacff329984a387b4897d7c7bba.nq.gz
│   ├── e8b1b13ce8d5444d862f027a1b6bcd0a0e42684b.nq.gz
│   ├── e9b30234d83a805c743f98f21e619610830bdfce.nq.gz
│   ├── eb455754f826b6d8f899a25a3d82df1427cc4fc8.nq.gz
│   ├── ec04d633850e167ee3b324d8f944075c65e2e15e.nq.gz
│   ├── f14054e39c0831c8e22400e2f4a13c0805a921d1.nq.gz
│   ├── f2621c80c2c3d67276508f53207a482f441fde4d.nq.gz
│   ├── f79a27a4357a53ecc55cef593c548cc3f4790281.nq.gz
│   ├── f7ce23f7f24c4078eb12ec767ff7cfcd6b198d1b.nq.gz
│   ├── fa90c2bb090af7dcb405e8a4ece4533c8d62dec9.nq.gz
│   ├── fb0cbba0140ab4392b2b9afd209b52d568f7cd9d.nq.gz
│   ├── fb9cc94bf53ea0b1eaaff5de5932ea1a83e0d4cc.nq.gz
│   ├── fbae9f4eaa61957069662713b220fa0d9c290562.nq.gz
│   ├── fbfba9a57691a47aa29c2108b6e47e34e5b8d431.nq.gz
│   └── ffc521e87e17ec32f75bb8bd005e3f3076d2453f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0f3b15b2e6bb47570d605ebd5687643d7a85b9d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 137 files
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

[sphinx-doc/sphinxcontrib-serializinghtml](https://github.com/sphinx-doc/sphinxcontrib-serializinghtml)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
