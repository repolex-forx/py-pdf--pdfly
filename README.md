# Repolex Knowledge Graph of py-pdf/pdfly

RDF knowledge graph data for [py-pdf/pdfly](https://github.com/py-pdf/pdfly), parsed by [repolex](https://repolex.ai).

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
rlex download py-pdf/pdfly
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1612f4263692842cd622167a456f0bb490df5219
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1612f4263692842cd622167a456f0bb490df5219
│           └── chunk-001.nq.gz
├── blob
│   ├── 0045d4fa37b618efb369fd163f63c0874e69b465.nq.gz
│   ├── 0191a924202638e9ad4bbd5279a7f2fa9e2623e4.nq.gz
│   ├── 01ec92bb114a395dd985a4bbfe54af2424a0b1ab.nq.gz
│   ├── 03273027c74fa8d462a39f1eec3e18c3737ea946.nq.gz
│   ├── 03deabee5d4c2055d85a84059130336a375b6d69.nq.gz
│   ├── 03e3535cd166420858cd741adb105f2d5ed0944e.nq.gz
│   ├── 05a12a400b314eb29c6a952d0a9e841853bd0ffe.nq.gz
│   ├── 068bb5e8c5e0abf8f54b593cb0142a7dd4b57bda.nq.gz
│   ├── 07a7fbbcb0acdf9e860d0c2e99aa7de16beef809.nq.gz
│   ├── 0d25432fc042ac2e772d6163cba0ffa1a68860a7.nq.gz
│   ├── 11fcd89a638f99a031c52cc00d7d92a9831aecb0.nq.gz
│   ├── 156b838efa2b5776b6db9ab93beafea3d665ce0c.nq.gz
│   ├── 1790fb3f32e17e46442bd0198bbc02f6fdb985aa.nq.gz
│   ├── 1855d0927c2c220d5973d65fa35b7956ba3440ee.nq.gz
│   ├── 1b06b0112f866bacb172f6698f2d7934185736fb.nq.gz
│   ├── 1da25cd3dd5ad897acea87b91905d7195d93d63e.nq.gz
│   ├── 1efc402e9fb9e21da09416b760a7c3759ca7da3e.nq.gz
│   ├── 1fbd13d12c9b7e5746e278558ac13858e9bb98fe.nq.gz
│   ├── 20671ec8738483df5327a046e9e165773f25e7f2.nq.gz
│   ├── 21da9fe1d68bcd5542addf4375f90a1f37ea847d.nq.gz
│   ├── 2794af3865156a9dcd3c4366bb546a0bb5feaff4.nq.gz
│   ├── 2a79014aef87048ca059e6d0071baf97a0b61d88.nq.gz
│   ├── 2d2de2cc304866aebc81fc2f0ce18a156cc66bcc.nq.gz
│   ├── 2eb2465891909934d7e5ff536caf2314e029f6bd.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 346269d6c347763ab4d82ef459a73055f43e74ff.nq.gz
│   ├── 35c7aefc44c9e1d40ce6d477622a9306bb05b668.nq.gz
│   ├── 38c55b1ed4ed1725ad3399409a97f0d995d70355.nq.gz
│   ├── 3d582745ece8de0b130c98d2795f33b5f13f3b0c.nq.gz
│   ├── 4146d70d168a4e5519e1b6a0a961579dc08874d5.nq.gz
│   ├── 41f690ca4a7c3447474e9b7eac1ba87591481948.nq.gz
│   ├── 449bbb7f1e1d4a3e26416c68daa7133bde54f299.nq.gz
│   ├── 4aeed4c1ec67d54ef4bfbb3b3e327a4cad396523.nq.gz
│   ├── 4b30170f8916d8e64743ba29112327218a57a0b1.nq.gz
│   ├── 4e592454cbfb519c3f5a9faaaa1a1be81283d4dc.nq.gz
│   ├── 505a625dd22962df1e34102b31d511722d419557.nq.gz
│   ├── 513b7e783a3251c4b8de616fcd99e1cb9c4c1dff.nq.gz
│   ├── 51e0e33fb00ac4f9eada0ea2e867cb945398b22f.nq.gz
│   ├── 5949040cc2c095e60418ccdb76c2eacd081a4a63.nq.gz
│   ├── 5a706e82a8ecd3bf665f23149dcbbf52114bc368.nq.gz
│   ├── 5c6a7689e75847cc0aece361dd70f508f1eaca05.nq.gz
│   ├── 608056d8f23060abfbb56e50367443049dd318db.nq.gz
│   ├── 665e262f5516f9cbb633ac452ffd438999c60fec.nq.gz
│   ├── 685e57c8edde7156a3fdbd6a9f717f345c704435.nq.gz
│   ├── 69d440666766ab148b0f0fe6f3113c57663dd49d.nq.gz
│   ├── 69d87791aa8a65f90554a1709a0cb42919e53af2.nq.gz
│   ├── 6ce320869e144a72028125c95541a811277a75fc.nq.gz
│   ├── 6feb389423b84ebac18ac99b64097aba6030a43a.nq.gz
│   ├── 7141011e98b3526fe94df4af594bd02bb4e18414.nq.gz
│   ├── 7159c40db909fe18099d43196784f1010a5e69b4.nq.gz
│   ├── 75f7829fb686f024ac70cfbb30b80367845e0341.nq.gz
│   ├── 76200bf87be9799b640db58ce1717c4efab60631.nq.gz
│   ├── 79a63f9afc3c6dbc95d79166b66febb8715b49ad.nq.gz
│   ├── 7b8c053c2b20fc77d2255216c126fdb0879b2d98.nq.gz
│   ├── 7e6e5ecd1ebcd298dc54a9f3c222b483fe2b8cc3.nq.gz
│   ├── 7e981668e96b3d925c9b24b9d9ed3f7130537433.nq.gz
│   ├── 85875a6952a46b191296685a263ef6b2523e722a.nq.gz
│   ├── 87b3847b0f602d85757aee2680c0abedaf161512.nq.gz
│   ├── 89bed3c451a5e0dab809ee46e32513f020a3ea3a.nq.gz
│   ├── 8bdb983253a9c4b846a682357d9d863ef54aa475.nq.gz
│   ├── 8deace2334eb54108e2e239c8194cd1416aba836.nq.gz
│   ├── 8e32b0ac90e9a9582a6b508389726d22cfdd263e.nq.gz
│   ├── 8e7fdc05559358c19605896035ddf263e85d6e13.nq.gz
│   ├── 9181daf9b68cb2400fd2e07cc9a77e18a19927e9.nq.gz
│   ├── 954ad1fd0a50def0a8af05a904c5f69654dad9ca.nq.gz
│   ├── 98013b54ec2799d8bb890ae940590295fca8725b.nq.gz
│   ├── 988d95bb7fed74ab1c541bdb9b42349cbb48e3bb.nq.gz
│   ├── 9b6e1f73e32d292e7956d33124789b2666095ea9.nq.gz
│   ├── a390ea2f154e674e4e49bc23bc9b2f1ceae22811.nq.gz
│   ├── a4a5f6321adb998866f4ace2b9dbfc7e6ac3e565.nq.gz
│   ├── a4dd76a7ecc9e4f0bd71afefcdc6f56e0fe007b5.nq.gz
│   ├── a5b393770290d33e7a146ff07c840d1c0982d812.nq.gz
│   ├── a94fae37b6fbdb3b1a8c5f164f40cf7ef66646d9.nq.gz
│   ├── ab20b2a069b70c4afb96eb7d6384732d97aebc3e.nq.gz
│   ├── ad2ae08428ffb61a7f9336af23230a4c46fb7ca8.nq.gz
│   ├── b50df354799b5a58cf87ceddff713c91be6fe99d.nq.gz
│   ├── bdfec450a4de4a1b031313cc9ab258507d949236.nq.gz
│   ├── bef37821bf81c502059a5c61ff8b98b1c9cfa74b.nq.gz
│   ├── c1d07386dd3f17be876e9cad60c51e87e40a6368.nq.gz
│   ├── c4b14ef556be1045143a43cfb52a4d79ce3d3f89.nq.gz
│   ├── c7519b52c5e5b7f4a712a51e93535818fd15b1ef.nq.gz
│   ├── c858fffcadb18584d22a5e275c64ffb5564a41f5.nq.gz
│   ├── d064df95dc1f32e1c6cd5185967c4f0eed0c7001.nq.gz
│   ├── d0e638254d0678438c314aa1655c23b271c5a916.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d4eebbeb2010ab25b347e9e68df8d6e8fec93a03.nq.gz
│   ├── d61f7a5518bb741889076b62ec272d84de7ece96.nq.gz
│   ├── d744924299c9cf90ba2b6e709e03aacd1ef82087.nq.gz
│   ├── dbc5b383617a0c2a8010b4514832516a393a5165.nq.gz
│   ├── dc1972330a9c3f00f08b38ac2d592a0b12eff32e.nq.gz
│   ├── dd9b22cccc1fd4469ceec38987ae57ec4429c12b.nq.gz
│   ├── df364248f42967e404dd7dbc8d065e36bfa8d8ef.nq.gz
│   ├── dfc3cf1c5a9cea48a4c23ef79b6f1e2e5e56606a.nq.gz
│   ├── dff405fb3bc1dd44442f362def8b328c06ed25b8.nq.gz
│   ├── e10fdae9efd808f18c73ba7ceab7502b8baa003f.nq.gz
│   ├── e3d8e3b257b3217156c461d4ae94e4b21fb76750.nq.gz
│   ├── e5db66955f00da9b103065b2f61ce95214148f47.nq.gz
│   ├── e94288b77bb282c8b70ee52ecb0fbadd718d6c34.nq.gz
│   ├── ebb563686387ada34f4c6b8050f52892156d97c8.nq.gz
│   ├── ec51ea0f7b1992b5cf431d766547fcca20265f76.nq.gz
│   ├── ed0004c80c884a44300c36392a58af0acd2ea9fb.nq.gz
│   ├── ed19e006f3d69ab513162fa438938414101da0b8.nq.gz
│   ├── edaf44c27dea41cd1b4f2673c27ac5f4276bcfc9.nq.gz
│   ├── ee1dea0d2261296718a15c02e0e3b36759d2171b.nq.gz
│   ├── ee60ccb3899ebdc0e89bc36384a47e825ee143b2.nq.gz
│   ├── eefeaf22505e4cbf50d29523af1536955e43345b.nq.gz
│   ├── f024562a452912b2c671c850815c9af8808e3e07.nq.gz
│   ├── faa31c0d61eafbda7538e1d9a846e18083da35bf.nq.gz
│   ├── fb2bb0a976775dc29498d16d0cc4f8f9c29a55b3.nq.gz
│   ├── ff3706426c9b6cc5049ba2e79b71678762df40c3.nq.gz
│   └── ff84c5815439269a640a3cb16688b974d08e3877.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1612f4263692842cd622167a456f0bb490df5219.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[py-pdf/pdfly](https://github.com/py-pdf/pdfly)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
