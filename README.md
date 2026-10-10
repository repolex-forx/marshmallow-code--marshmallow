# Repolex Knowledge Graph of marshmallow-code/marshmallow

RDF knowledge graph data for [marshmallow-code/marshmallow](https://github.com/marshmallow-code/marshmallow), parsed by [repolex](https://repolex.ai).

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
rlex download marshmallow-code/marshmallow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d08471b17880c62b789971ada638707a11d3f8d4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d08471b17880c62b789971ada638707a11d3f8d4
│           └── chunk-001.nq.gz
├── blob
│   ├── 02307b008f981a1bd70008f9385bdbf999246103.nq.gz
│   ├── 0ae9ee968056e1f4ac2cf3bb19365e06021f426f.nq.gz
│   ├── 0f26a51b8715d9dbce4132f40f9b7e1b29bb85c9.nq.gz
│   ├── 105c7651b723fdd20e19b4249b3bcd71dfdcbf52.nq.gz
│   ├── 123ae552eb6a142e2624ec89c2d4664afb2339ed.nq.gz
│   ├── 12c83dd819a1dff360bf6fce28c63314c168ff23.nq.gz
│   ├── 1719665be23d51e7933232e85d685d98a77bf883.nq.gz
│   ├── 17838bb4af0301bd7a445d2ba9c2cacf318e7aa3.nq.gz
│   ├── 1996177b62c5493c120e882b3951af8b65ac29ab.nq.gz
│   ├── 19c604f5d07e9872d679f91680ec53ebf41ba423.nq.gz
│   ├── 1bdea0d896cbff9b897f90a3e74103e7a8363aff.nq.gz
│   ├── 267792a9779c1c366f98d5121aa7ca808a10a954.nq.gz
│   ├── 2946615a21058d0afd382a6f573734a84d83caf5.nq.gz
│   ├── 2b1c40d749083dfe12a16a8e053517ba77a850ab.nq.gz
│   ├── 2ba7bff6bb8b1d6d0d8deb32e96e48f9fa2fea97.nq.gz
│   ├── 35af1c7140fe2e8afeb3574e02c6ade2b47fcbb2.nq.gz
│   ├── 35c0e8bcef27641b6710fb1be4e1fadfb9487b6d.nq.gz
│   ├── 37b861531d804e47476d3d5bc5debe067869a12a.nq.gz
│   ├── 3dccd6be9940be23c7aef2850243b3bc6bb230c0.nq.gz
│   ├── 4149a25e113b88ad658ec2b0c3f34a5391286da3.nq.gz
│   ├── 41948b48d552e3b45d1cbfa5966786b26f239c4a.nq.gz
│   ├── 43661cc9440b9bd36408c61a039b22aa621711d4.nq.gz
│   ├── 43e08a1c503e990516cc73c50643bd515359ab82.nq.gz
│   ├── 475aabac34ea5a525ccca9352e954f3b66d99024.nq.gz
│   ├── 4a2e2311e3e55a0de0636b028d12c4863d54a6ec.nq.gz
│   ├── 4bf96dd9d222f265d72c43de63a79473f604cc09.nq.gz
│   ├── 4f2e65253c626baa78f53e92746541a2e3993011.nq.gz
│   ├── 50441ab2ca3d20b9691260c50b0b7cdb311460ca.nq.gz
│   ├── 50f8e0e618f34d28b733ad91debfe1c04ba56133.nq.gz
│   ├── 5156479c46c663fccbec2f5786eab962de684449.nq.gz
│   ├── 515bcfdb0f7f86ecc943425598f595656c0315c2.nq.gz
│   ├── 5bc0bff4806293cf15d52d5635addbff6f58ee26.nq.gz
│   ├── 5cb18a0e0e5aa3e7dbaeadd2bbcdbc216f3f4d1c.nq.gz
│   ├── 60825ab5f043f6b0e875ca9da8084a3e08f70e97.nq.gz
│   ├── 60aa6effbfb9bea747207bcbdd2d1a4e303ce562.nq.gz
│   ├── 639dc65c7861752376a4b4e8cd10b129853bb807.nq.gz
│   ├── 65c70f0307027114150cabe9265fa5b13d7b748e.nq.gz
│   ├── 67bdf7314dc4a6bb0b840420deedab82736e13d4.nq.gz
│   ├── 6a88c387fb2350034b2db1ed3a783af5f8e80763.nq.gz
│   ├── 6c0058da70a328d718b3f17d1066309991cc669a.nq.gz
│   ├── 6edadd9db7570b083f3236a08d6aae60a9a73670.nq.gz
│   ├── 70c5c8725a1ab74d0713a2f86aeb8ae70b3351cb.nq.gz
│   ├── 71e8df8463ed439745a0fc06cc727bbf08931aa2.nq.gz
│   ├── 73a5133bb6b21c4fdb88883b98ef2e6c0d4b8480.nq.gz
│   ├── 7463c5ade0fcbcd2cbd203ac4691152f1d1efc64.nq.gz
│   ├── 752e544e1215f22008e998a111bf31d8375bfb25.nq.gz
│   ├── 77d2233d5d6be98e143438c0d7ae75264560d223.nq.gz
│   ├── 7f1f3e563895b3e669dadcb49251d2ba1d6ec280.nq.gz
│   ├── 7f5396738a523277323f083ad405b22855591802.nq.gz
│   ├── 7ffe0673ac3ecbe8a4228b7cd3f0f291a417179f.nq.gz
│   ├── 802ce0d31e0f3caeae35323242416b8843ff1158.nq.gz
│   ├── 84121592f0855f15ea81e2ddd88ff2d7cff3d276.nq.gz
│   ├── 8758b7eeb2b16e16a2cfd0a2cd0aea86fe64b407.nq.gz
│   ├── 8b55c9409e3c3089cef417224ec13f996d42cdab.nq.gz
│   ├── 8bf730f19e5b95325089bdeccb5303aad2fc1ad8.nq.gz
│   ├── 8f3cf1fb7bcd7c0b4461f0bda1841b90ff8c1a49.nq.gz
│   ├── 91c7875aca5aa11218ccf66a25b7f6eaa365cc80.nq.gz
│   ├── 92ec2bb600a1e1f3ad8666d355b485b696332790.nq.gz
│   ├── 95a0e8f0d589417648a263015861f7e586dec296.nq.gz
│   ├── 96d1cfdc462e2e5497bf63ae96ce7a9113042833.nq.gz
│   ├── 9a0075b74aff9aca837de50c2d1abc98793450bc.nq.gz
│   ├── a05b887b9a18ab374d4c34053b2f5cb112fa1ec8.nq.gz
│   ├── a08bcacb1a0692cdb43c63b6011c6b7f2e72d909.nq.gz
│   ├── a0c6c2bc2633bfbcbfb90af7edb4c48409915bd4.nq.gz
│   ├── a2c4af80b23aadf9f6e923b3ff06368e0a5dc6b7.nq.gz
│   ├── a2e8b30cf6f943df14dd6136637adce2f5769a93.nq.gz
│   ├── a4bff72b566ae6e22be734188456d8e99a10c09a.nq.gz
│   ├── a7e055610ee99d28599dd523c0954f9c10e29f7a.nq.gz
│   ├── ac0fd8fff9fb1c3d5aec10d21f7fe7de5d090d4f.nq.gz
│   ├── b20df7cab259cfce3d02bd8da515ce65870612b7.nq.gz
│   ├── b2607ba20279ec319a7601617c62d7302ee157ed.nq.gz
│   ├── b2c94e1b0023b311d566e2da47eb3b185caa49c3.nq.gz
│   ├── b393588aec88ef883e862dfab8ed5ae773a7dd0e.nq.gz
│   ├── b3d21b1708674928cb0e50e246a1af3207d9e8e2.nq.gz
│   ├── b4ede4ac43dd1b70066bcfea14eba71f3029d1da.nq.gz
│   ├── b85e76d67fca19dd4f25b8b1db115ffbf68790d4.nq.gz
│   ├── b8f6f65baec8701c72d664909b01d55d65399f3a.nq.gz
│   ├── bae246669036e4463236c0260988ac2b8a4f7699.nq.gz
│   ├── bdcd132818592d16d4478008d1bdb803b6343b53.nq.gz
│   ├── ccb17113ecc0525cef0fa5c12532703bc037f589.nq.gz
│   ├── d2bedf78ed7a0b0ed11d42548c57ed86ee6370cd.nq.gz
│   ├── d3b01ec3e5f22d2ccf8ad3323e7862994664f15d.nq.gz
│   ├── d98d2efdf569b21ca1d35e52c2d18694111d3f0a.nq.gz
│   ├── db8e00bcdf02e8ab6b412be17284a1d6f0fb429b.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e13637862ebccc8f329fdbfab4665261336b14a1.nq.gz
│   ├── e4f144a118b9c11eed490ba76159d2a152110f2f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea2c79595006a2144f6d1d70ef1867a92979c21b.nq.gz
│   ├── ee40263f42a6e0bd2563fd1cfb1ca56b15a33300.nq.gz
│   ├── ef5b9daea091198303bfb793036042b09ce8a39b.nq.gz
│   ├── f04e21b5cd23b7285523cae6b44222be66b2d83e.nq.gz
│   ├── f40ce91be5fa3ae6afbf5457462f0d87000e4f1b.nq.gz
│   ├── f476d078cd197d58d879628a1f320d8e6cbbb829.nq.gz
│   ├── f68da9d2133584f165a9ba415c68618e8cb798b7.nq.gz
│   ├── f703f339284e74682d8f1b674ea1f47d75625ffb.nq.gz
│   ├── f93993586eae95df3a8fc4a9e97b5755087e6316.nq.gz
│   ├── fa9759a4bd3a4aec03ab589b54511917f4400c8a.nq.gz
│   ├── fce7e442b354bc11dec7e73679d7a55c003d947d.nq.gz
│   ├── fe04fd9dde52040ebac3afc4f6f77cc075da22fc.nq.gz
│   ├── fec4c5cc4de97a3f71d1dbdbdae7ef902a9cff9c.nq.gz
│   └── ff281173796dc278fc26e1975e06bd2cc0ab3a64.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d08471b17880c62b789971ada638707a11d3f8d4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 110 files
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

[marshmallow-code/marshmallow](https://github.com/marshmallow-code/marshmallow)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
