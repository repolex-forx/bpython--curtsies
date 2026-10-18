# Repolex Knowledge Graph of bpython/curtsies

RDF knowledge graph data for [bpython/curtsies](https://github.com/bpython/curtsies), parsed by [repolex](https://repolex.ai).

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
rlex download bpython/curtsies
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c303d0fadaf73c6909b2da08816c275cff33172
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c303d0fadaf73c6909b2da08816c275cff33172
│           └── chunk-001.nq.gz
├── blob
│   ├── 07f80737bad91e12339144738b00939fb7d233cd.nq.gz
│   ├── 0c2410682633809dd01738a6179603050ead3810.nq.gz
│   ├── 132fc17eda5fea55fb561e5785a52278ba9f69b4.nq.gz
│   ├── 154c25a547959dd47f405231317022ca7bef04e5.nq.gz
│   ├── 172009bde5d6e8f38611c870c807a88d09705faa.nq.gz
│   ├── 192b99a05c7bc5fcfeb2925c10338a3540c4c1f1.nq.gz
│   ├── 1bcf15f652fb97a35540a07145c7441a0ebe60f8.nq.gz
│   ├── 20363a93b5f6192067fe65f583f86a50cd2fde38.nq.gz
│   ├── 21aa9893fbe81eaf85e9f387fb5037a4cd7c3d95.nq.gz
│   ├── 24c906a2d518d1e8562afdfbf9139c888911c3c2.nq.gz
│   ├── 269964302c087aed05166905854e95024b4ff9f1.nq.gz
│   ├── 2777bb6bcb315a368df4347bea678c782afed417.nq.gz
│   ├── 2a090599f7c0b09597dc259b146ad5eeaaf720fd.nq.gz
│   ├── 2b9d9b2f23829e7370bad7019c3cbb720ef75bdb.nq.gz
│   ├── 381823ac3c77336eb9abe1ded53bb8253036f8cf.nq.gz
│   ├── 3cd25a122ae936c2339d486da2dcf0427fafa60a.nq.gz
│   ├── 3e9ffcb8b20bcf5b041581c62980f9c5044f77f2.nq.gz
│   ├── 41ce4e180af69583a6d1e049740861c87f6f4872.nq.gz
│   ├── 483b0d8db5a2614178f900610e885ecee1da97e0.nq.gz
│   ├── 4dc5506129277d3872c7732e7b99e411b90d47f0.nq.gz
│   ├── 4ef7878eba35ff82a9d1bcba88b2729a866aaeb2.nq.gz
│   ├── 522dce13e59002257d03a6102938b6035ef9c419.nq.gz
│   ├── 55e4bdd9a28403f1ef921905055fa147745eeea1.nq.gz
│   ├── 584721a81c64cff7faf8dd5d4452c94ac0df3729.nq.gz
│   ├── 598a077e8e5746c6c396a505299d8794bef7d17a.nq.gz
│   ├── 59a047eaffd2fbbf4865225b82dedfa0f5b09122.nq.gz
│   ├── 5c4e4fe1c44268150c735a3b22c199e9b054d2a4.nq.gz
│   ├── 5f480c6a844e308c6e29de3f33e9733a5b99e82b.nq.gz
│   ├── 665c235a566aea72a3156ca76419c4f3b59d0e09.nq.gz
│   ├── 66df9e5d79b0de0a6e8076564f4eb3aaf94e7814.nq.gz
│   ├── 68520006ebc3f8d646a1e0c20c805cfa4f6086f1.nq.gz
│   ├── 6a8bc247deb63e6cc45fb50a5fda68602c694843.nq.gz
│   ├── 6ab0a678de37811dbbefeffc5543c91e1f058a67.nq.gz
│   ├── 6b435b0b88ad840006c7a3982cdd0ceea0a364b9.nq.gz
│   ├── 6eb85ecbff86bfbb4ded0d0c4e7f9d21e4c367aa.nq.gz
│   ├── 726aaf7dd911ff01e1f5b0e9194a2be46fed557e.nq.gz
│   ├── 7492044307615125afbae7dd39dfe6c0a6ae6b5d.nq.gz
│   ├── 7d0b98378af693634d07152611884a689fcbd553.nq.gz
│   ├── 7d27d25d1cbc0a14be0dec7b36388f5e94e0af2d.nq.gz
│   ├── 861dd45013c2b7b51f303c9f5e7c64cb9a64b16f.nq.gz
│   ├── 8688641cbd63ad005d2703c7c3084c36c531bbf4.nq.gz
│   ├── 8bb92d5447e1acdf7b665f4ee50a9d418dc6cc32.nq.gz
│   ├── 8c139c7bec29cd1fd808ae643e5b9181813f32b8.nq.gz
│   ├── 8d3f7b099e7978a266c35c236752cae416e092ae.nq.gz
│   ├── 922554df9ec8701f6b986cf1be1848629c7400c7.nq.gz
│   ├── 9821b6ccde34650d6c3e017b96b7040e3c749d6a.nq.gz
│   ├── 9a6da54be4863bc019013328a803b002b34ceb82.nq.gz
│   ├── a163f38a900a4ea662a0380c8b2a2e52469129ef.nq.gz
│   ├── a208fa03be130112a2f266788697f81c95589314.nq.gz
│   ├── a29d278fe57b5c765140eb3f6c9147f0a6ea0ea0.nq.gz
│   ├── a4229ae65c0b584a0c2d3d981ea0839eb6af3471.nq.gz
│   ├── a5687801ef4a7264f5b2398011662f081bc1d853.nq.gz
│   ├── a6572092031af5ebbbf50075ced3574abd1e481a.nq.gz
│   ├── a7e47fcbc393aec67117863041014621d105c44f.nq.gz
│   ├── a841ab3694250cc89b19384805d97bc174d79f2d.nq.gz
│   ├── b8ebd7ffe2c4c1f5b6b24ff12b0807d054bf8e3c.nq.gz
│   ├── bb91bc3c4952cccdfabbb6b476841ab43cbb20cb.nq.gz
│   ├── bd70bd2aa097746a3bee0041db0bd63f57aed88b.nq.gz
│   ├── c205261a4644704fbbf4bbcc866c4eacd3c166d4.nq.gz
│   ├── c5b6780325029f309bd39b381e55f30d44eed1fa.nq.gz
│   ├── cc0077ed1e158311ffba98eff6f48da7f623b34b.nq.gz
│   ├── cc48a5d0d6fc8acfb9369e18bebafcbd5ce86f01.nq.gz
│   ├── cda54e9088e53b6557f3c87851f9161d79038a53.nq.gz
│   ├── ce24896cb65c2387a259ed73df566550dbfccbb7.nq.gz
│   ├── d1aa4d91f8cc71a8b02e31744e02776eb59f0450.nq.gz
│   ├── d5b39f733559cebfe471c83fe0918bb6aeddf705.nq.gz
│   ├── d6bd19e1c8558f6efb43931f52cef6e8fe4ae5bc.nq.gz
│   ├── e24d69c5002b4fce366745b931c804ffb7dd363a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fab1b7a0d3383b6ac814c4c4c394128e937c54.nq.gz
│   ├── e8a179e9505e073dbf598d863c36d4657324be4c.nq.gz
│   ├── e8bfbb2197f88568a4048df654f5e158c7b256ed.nq.gz
│   ├── ead977f902828be0bc8fe94890bfe25120f08dcb.nq.gz
│   ├── ed8583a96e2105dbafc65ef072fb20c75081b9d2.nq.gz
│   ├── f032c364af5672afbdd99f4214bb6b7c703c49d2.nq.gz
│   ├── f406c3cea7ced461d438a73c6d7b4563f9f1dbca.nq.gz
│   └── fd9916c34680bb7198947770eb85490c7325dc06.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c303d0fadaf73c6909b2da08816c275cff33172.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[bpython/curtsies](https://github.com/bpython/curtsies)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
