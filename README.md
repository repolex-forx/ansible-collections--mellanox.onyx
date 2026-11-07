# Repolex Knowledge Graph of ansible-collections/mellanox.onyx

RDF knowledge graph data for [ansible-collections/mellanox.onyx](https://github.com/ansible-collections/mellanox.onyx), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/mellanox.onyx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 895d3a20969fa24b1ddf45f89ca57aa1a29b5407
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 895d3a20969fa24b1ddf45f89ca57aa1a29b5407
│           └── chunk-001.nq.gz
├── blob
│   ├── 0025ed0b8dfb72cc2053b5af9eb4fdcf0471abb0.nq.gz
│   ├── 00c49c2528f7cc879446cd0b7c493288ce685104.nq.gz
│   ├── 03128f1e018d127d6e93c05bf3162dd32cdba9e5.nq.gz
│   ├── 03288550b108452e8e8dea92f2875c0e9bdb8bef.nq.gz
│   ├── 0511b7c10870c3e6d44e66f9047d4765c1083e82.nq.gz
│   ├── 07258f8c1a44de158f48d650958c09db93168be9.nq.gz
│   ├── 09e21b104be537048dfe960814091c4185ae4a8a.nq.gz
│   ├── 0affdda25b35a33937435e12fb996e07c5b6c56a.nq.gz
│   ├── 0d51d4d5c75b6514ed729b8544ece51f53456f07.nq.gz
│   ├── 0e043194ce8162b0007663ab9f9dc37f8b0695f6.nq.gz
│   ├── 11131cc5e5ee67441ecc303d810a83ba098f3465.nq.gz
│   ├── 1296173418f3c13d73d7ef816b43583bf90cf3ec.nq.gz
│   ├── 133ccbca3817e6c961dd786bec4c81f32e953aaf.nq.gz
│   ├── 13b19d949ca2ac31f88f1902f1f432dc080c2e55.nq.gz
│   ├── 153b335956812de0c8b813ee5747d86bd874c01f.nq.gz
│   ├── 1996a6b31b50d0292dc99fe5432dc614b5adce02.nq.gz
│   ├── 19bee48f85016e0d459cba1479e8e78b4f7f2e4f.nq.gz
│   ├── 1a7314e2ad9f54c469e9a5bdb0a998631b8e037a.nq.gz
│   ├── 1de0e413f15300d0c6f3ac7fe83767161e9b51f2.nq.gz
│   ├── 21ab4fbb641812ce8ea5b5e8962d8e3d1ebf2b54.nq.gz
│   ├── 22641d8b4839e59643fefed1dc1035be0dd2ab42.nq.gz
│   ├── 235205c2d05de56a80e482a0dd2632122eb283e0.nq.gz
│   ├── 2367a6b1b523b355a38898f19bcc983cf16272d3.nq.gz
│   ├── 28034732ddd9b9e36b96a6a48fa54f4d25bc0f5f.nq.gz
│   ├── 2d5e56a4dd1939c354eba2cc130a59c4bb0de3cc.nq.gz
│   ├── 2e1b289a625a884e2500b2d04949225be5c6383c.nq.gz
│   ├── 2e578eb16449c70253de3596157b6f47671b1384.nq.gz
│   ├── 2f5d3c2f6b3a0b59ddc4a5c1fc5f8f7c4cb74711.nq.gz
│   ├── 2fc2ada110e83fee5080ea674694358613eafca6.nq.gz
│   ├── 32fa0e54d658ceccd744bf20940aef3f4297d361.nq.gz
│   ├── 33f8d2d06e58c217d094781327ba5a3ba54e56cd.nq.gz
│   ├── 38062a8c74ba919920446cbb4f99bf557990bd8e.nq.gz
│   ├── 389612e0ca7f25f6c213aaa6cb347b1acf6c631f.nq.gz
│   ├── 3d84667b2e8e98ab31466e45c017552bba7fd391.nq.gz
│   ├── 3db5d20ea57df907f43621b16798981934f1ab2e.nq.gz
│   ├── 40abbf21838970380ef2214f70e39c9d604d267a.nq.gz
│   ├── 41dc3366d67789577af5b34a7490b194fe94ef72.nq.gz
│   ├── 43410b18477c5bef78a186821cc59c4183849be8.nq.gz
│   ├── 44c26fe110cf87091f403836a2bf1c5c699fc549.nq.gz
│   ├── 471edc8c65720b61c1cbe334687abc08410f85f1.nq.gz
│   ├── 4745af58f84430c0116089ba6853b1ec6b7e4664.nq.gz
│   ├── 49543f029859a77845473585f4af2ed6529dc4de.nq.gz
│   ├── 4a1312cc261fa4c0daa70515eaf3a21bfee5e7b6.nq.gz
│   ├── 4c41b01e416d45f5a493e754e90a28137018d85f.nq.gz
│   ├── 4fa74b30ebce88a496208953fa963ce784801578.nq.gz
│   ├── 52d630b9fd0624aefe776d3e2640f36f3e287586.nq.gz
│   ├── 56d1e2a6a2540aa3ab38b37893b300dda1431900.nq.gz
│   ├── 5b388c5f223ed2a0502d8e5c37f286f8ce811a5a.nq.gz
│   ├── 5d5f6f01d5643c5046031c036912f11b529e7ec5.nq.gz
│   ├── 5ef7e6a46df0a78de5d17049a8e9727fbaf47fba.nq.gz
│   ├── 616cae52cf17bf4e3676ad8566e6bfb94ac7f15e.nq.gz
│   ├── 6257a5c86c2b463464cf18121018fcc146271ca8.nq.gz
│   ├── 6298953bf81a9970e58c440c0140d0b0866adf41.nq.gz
│   ├── 66a5509e21ca57cc820876691133230f928d03cb.nq.gz
│   ├── 6926d24c1a1abaab5d69dab6b6dac9c45566942a.nq.gz
│   ├── 6c0fdcfd4e671fcd4d2b02f8cd98967dfa7c44dd.nq.gz
│   ├── 6c957ff0e525805c9824a3851e7190062766f4d9.nq.gz
│   ├── 6d1f3df57795979fe8b919c89039ff9bc14429bb.nq.gz
│   ├── 7172e8dc1aa26c650ec87d916388e67d2f86ec02.nq.gz
│   ├── 7262a8725769d6623477f98df728c512b408e467.nq.gz
│   ├── 72e385684b5196d36c2ef4897dfa09ae1b2a8f20.nq.gz
│   ├── 73b5da1687747921958ef0bcf0e5213a7a3fca83.nq.gz
│   ├── 7440c8aa857c77e74b2aa4969595444c45278c04.nq.gz
│   ├── 747e62eefaaf6a3b1ab49b15d16855ea5ee29965.nq.gz
│   ├── 75663058627fc2a14b8479118de69e19af45c1b4.nq.gz
│   ├── 77a0996029d7ba15ed7275d4279bfb52c53cc19a.nq.gz
│   ├── 79074e66dfc8cc37abd88356f198faae39e4528c.nq.gz
│   ├── 795a5286b40fc4660e9a6cc6189c0d1aa07dc5ac.nq.gz
│   ├── 7a3a974ad33251a107fc3d5d6b978eaad533ff39.nq.gz
│   ├── 7bb1cb02229cc8b3252ae6144e47ca4a6a4d62b3.nq.gz
│   ├── 7c49fb0c8e75bc2cd0518c642ae51659f0aca448.nq.gz
│   ├── 7cc90b7a40197c8821651ed1c89623ce45aaf45a.nq.gz
│   ├── 7ed02a7ec9cfaf5a06d2662f90d45973e37770c0.nq.gz
│   ├── 805853f46e26cadc73762303a230a2688e3e0267.nq.gz
│   ├── 82fbda2f56a8ebd75f57263be863c4373020bb2a.nq.gz
│   ├── 87f8d9cfac79ee45f0b08370dbffa729f9307df9.nq.gz
│   ├── 8dc43ef5d0942af6f826737004f6887b9d508b6c.nq.gz
│   ├── 93092b4e61fb9a2181fe2ada53385d3b22c153e4.nq.gz
│   ├── 934c4e641d4b2be7927ce89bb079263dd925d9cc.nq.gz
│   ├── 94189cd3efc02d4d406bfb5c66acdc792c9c9ada.nq.gz
│   ├── 94e127e339f7b14fa25e02884c65216d71bfc338.nq.gz
│   ├── 9750074ce6fcbe05abdc048c148b79325dc0d3c0.nq.gz
│   ├── 975b67230089481cfd7b6a6daf8a5146d4985131.nq.gz
│   ├── 982e58fdbdb976b975020e59bc52dabc31d70f1a.nq.gz
│   ├── 99df6eb6015a292ed6d8c9ea21efbdd7327701fa.nq.gz
│   ├── 9a486e8c4e8d5222642d3c689553d7ca94852a3b.nq.gz
│   ├── 9cf51f92a3823689e079d15833c517b7d87e3923.nq.gz
│   ├── 9ecf72fb55ab8b620b09480a5719056d510eb8c9.nq.gz
│   ├── 9f9f1b3aaf86d56354a4b8ee2a9818a2ae3bfbed.nq.gz
│   ├── a0a7f12821432b047e927f0f0eb6a9da766731e4.nq.gz
│   ├── a164343feff32887d44f0561c25e5ad9035152e0.nq.gz
│   ├── a5d0f6b3ead0b52e8b1f512b1b4e9c3bf260c3fe.nq.gz
│   ├── a82fcf75198550ad71fa6cff4433f0be61a5e3dc.nq.gz
│   ├── a907d168d99f1d53808cf59fc5a5a76555b03b8c.nq.gz
│   ├── aee71536c66317125e762099630d0b5766c506d8.nq.gz
│   ├── aefbde64e78268d7dee40552cae61f00ed422e2f.nq.gz
│   ├── b0b4a8dbf5fe5a0c5bb67e4fbf99e7ec4e9c8f5d.nq.gz
│   ├── b0de45a44009ee2d245d9f5f2f139e50470efc9a.nq.gz
│   ├── b1c9089b492ef593143a9eee2d92fe6cf487852e.nq.gz
│   ├── b59401a51748e9cdc2ece8b47e6e4106f393390f.nq.gz
│   ├── b64c260d3be3f0e2d537b9d85f567cd576f0f2e0.nq.gz
│   ├── b6bbc30f284ed11302ea7f254df47adc7edfcdb0.nq.gz
│   ├── b7df229ec221496511e3efcd054eee4c2e2e034b.nq.gz
│   ├── b9c5c952eb284681277c2d565536397af0e79525.nq.gz
│   ├── bab8c3b78910b2eb51c3080822eaeb782ff413f4.nq.gz
│   ├── bb0d44028892bc4147765090c3a3af3de5122738.nq.gz
│   ├── bb35e6e8864dbe4bbf39313cd88c4cc569ef6250.nq.gz
│   ├── bfd95b6dadd58b84ad8ac354fcf6f1847aea3ba8.nq.gz
│   ├── c28c84fcb488563d2e6ef9d0d4e1fde2a390a154.nq.gz
│   ├── c2ad495493f7c04a1ade754eb5b7e3bf393866a7.nq.gz
│   ├── c3a1621538a44a8e9f4919453700cf86828cf09f.nq.gz
│   ├── c7721844e517dd557479e3cbbe0c7550e3d26f85.nq.gz
│   ├── c7f6fe8824f861b78b03f8b99d6b00270abd0de1.nq.gz
│   ├── ca2d2ba0f4e18c3664b9ad9fc975fb95a447413b.nq.gz
│   ├── cca075b6063aa772c256b2d8833780ca4af098cb.nq.gz
│   ├── cd173497d4ccd70bab1f65be45a61b463e2bd048.nq.gz
│   ├── cdd532f062813451d5549a9a04f5fb3573901075.nq.gz
│   ├── cf2bba8f205931690b6f6fbe7b6b982e07bcd222.nq.gz
│   ├── d1ae46bf48b05775f068b42356fdae8483eb92a1.nq.gz
│   ├── d1f308e9ebc022c8aed3e54eef8489d4127fb3a0.nq.gz
│   ├── d3a364b985ed631d3574640878066c9b680bb359.nq.gz
│   ├── d4e10cca03268f995704cf3cc58861ca9affdcbb.nq.gz
│   ├── d50f497607c56824800ab9018b8ecabaa84a96c4.nq.gz
│   ├── d5de67bfc5b3196b9dd35106e85494465b435894.nq.gz
│   ├── da447dd07aa3f831d44aa49435fa8bbc56ed7f5f.nq.gz
│   ├── da7411e906cadc41eb91a04500d1f54f929e8fbe.nq.gz
│   ├── dc3704e4227ed04afd0ca5a99fec96f27c819557.nq.gz
│   ├── dc54698b4ddd5dd09d28a949bb4cf607fa30d63c.nq.gz
│   ├── ddd5f089c2e84143c7a6588537474a6d825dd28d.nq.gz
│   ├── e0c1bc0c109dcbc00bc09470142c86ec62044135.nq.gz
│   ├── e1f1b37c307e6a758abf8ca6279f8cebda86b3e9.nq.gz
│   ├── e438a80d8184bed9330fb524629160dea94a6895.nq.gz
│   ├── e4c1207f313c386786a197e9c91fa9bb09a8f72f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e72bfddabc15be5718a7cc061ac10e47741d8219.nq.gz
│   ├── e883ecf38dc228be584db9d7c65d5322e8ced642.nq.gz
│   ├── e904bcc349a5d1bc5a05c0264672d28b989bfffe.nq.gz
│   ├── ec804d278dd0e7a099f440a84579edf8a6c59eef.nq.gz
│   ├── f118eb07b3e7ee3e0c7715287df68aa7af3cce83.nq.gz
│   ├── f3cab2bf29a80a596404ed120a067515e3e9c0c6.nq.gz
│   ├── f3eb1f1105f95e6e276560cc0acad334d1b84a46.nq.gz
│   ├── f535e95e39b27219cdab379132f490ab6cdff981.nq.gz
│   ├── f5f9a154f941e10355659ec98179d3fb6dc3d64e.nq.gz
│   ├── f69926a3f988c3827f484e6915c2e6b725dc73d1.nq.gz
│   ├── f6f6f318d3a50eeeb496203008a3d64b42c3fae0.nq.gz
│   └── fd4549cdf291c5f5fa9fd8cba59d4f6836d4de76.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 895d3a20969fa24b1ddf45f89ca57aa1a29b5407.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 154 files
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

[ansible-collections/mellanox.onyx](https://github.com/ansible-collections/mellanox.onyx)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
