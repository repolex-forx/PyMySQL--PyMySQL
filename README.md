# Repolex Knowledge Graph of PyMySQL/PyMySQL

RDF knowledge graph data for [PyMySQL/PyMySQL](https://github.com/PyMySQL/PyMySQL), parsed by [repolex](https://repolex.ai).

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
rlex download PyMySQL/PyMySQL
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4399e300fd8f810d84601f8131dde2c57849484b
│   │   │   └── chunk-001.nq.gz
│   │   └── d7bb777e503d82bf2496113f07dd4ab249615efc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d7bb777e503d82bf2496113f07dd4ab249615efc.nq.gz
│   └── repolex
│       ├── 4399e300fd8f810d84601f8131dde2c57849484b
│       │   └── chunk-001.nq.gz
│       └── d7bb777e503d82bf2496113f07dd4ab249615efc
│           └── chunk-001.nq.gz
├── blob
│   ├── 07ea660315ef321b6114fa8b32ae2abc11e53c36.nq.gz
│   ├── 0928514e091a2fbb34735d62c52393dcdad174d9.nq.gz
│   ├── 09a5654fb68cf1c39c26422a48277a0c0523df02.nq.gz
│   ├── 09e16da6b3f9e69e1e28f15bfb2102b87bbaa2df.nq.gz
│   ├── 0a2eb13775d010f67fb46f0df8d4871437ff3e57.nq.gz
│   ├── 0bc607fe6f909ebf3b27973358e8ce71bb3f7f62.nq.gz
│   ├── 0cf7ec196e245f40cd8fcb527cff58525d0ceb63.nq.gz
│   ├── 0ec7ae6ebba2235a52cbf18b815d8e52ae14de74.nq.gz
│   ├── 0fe13b59de8589d4eb63adccc68bfb90e51972c0.nq.gz
│   ├── 103567f45c39810dfd9cc6e7e35fb729036bb213.nq.gz
│   ├── 140d37067fbfff48eb5dc85dda0e3572f31ececb.nq.gz
│   ├── 1545fbb5ece132f75f899747baf57cbe66d4da20.nq.gz
│   ├── 158d0d12f2f8200f3f0eeb7bba74807daf22d3ad.nq.gz
│   ├── 17b9b07fb26283d333eb29eaa59607f4b9d16cf5.nq.gz
│   ├── 17ef381b14b6e51241540c377731d04d64fc90a9.nq.gz
│   ├── 19706f3c30e0321f091a901f89c7ff4b9e285684.nq.gz
│   ├── 19b3db9315bbeddfb5c369763e37633f08879000.nq.gz
│   ├── 1a16c982a646ad90cd8968df326449313ef26527.nq.gz
│   ├── 1dbe6fffab528f5d4b8763acf13a680124bb5ec1.nq.gz
│   ├── 1e98dcc5e326ea74e59a3079e4564df8d46ea838.nq.gz
│   ├── 253a13acaf3593f3fbfd5de7fe39a769185ceac2.nq.gz
│   ├── 2855e7f4e89d6920efc228289ac049e76fcba6d7.nq.gz
│   ├── 2bda5a96fa7e00120227c3377bdd94da2b60e77f.nq.gz
│   ├── 2d80a6248a7d7c65abf2558870fbb88106df7c94.nq.gz
│   ├── 2d98850b816e063a2163cbbb65e4dd578412c417.nq.gz
│   ├── 2e267fb6a4aef070f7c6ca6276efdbb71a36a02e.nq.gz
│   ├── 30de43d58047a7f24fe43d058c1c752664ecadf8.nq.gz
│   ├── 34fe57a5d4362b64dff330b8141f1f8027514389.nq.gz
│   ├── 3946db9b9f42acdaf8b51958ccbd24e9dd2a2171.nq.gz
│   ├── 4497dacf6a9de334780172896e9e1728d3f4ee94.nq.gz
│   ├── 4790449b8146ce5ca50e19dfe53b630f25da0715.nq.gz
│   ├── 48319f033a9cb0f69098cfe530504648c3bf10f8.nq.gz
│   ├── 488350cadd6a1f601e5f7530be0ec42a6eea7ee7.nq.gz
│   ├── 4e545792a81e19c8024f4b47fb377c7c8c2ca7d5.nq.gz
│   ├── 501bfd2db9caf7585fb2d3e2205eb63a4d24506a.nq.gz
│   ├── 5092214203fe1bc729edd143a724749b08463dd9.nq.gz
│   ├── 52d149cba853c8d2449129c3bc64763380249f31.nq.gz
│   ├── 5458aa1f76fa4e8ba0649a5990108bb6676e7239.nq.gz
│   ├── 59fdb65df0403d6d4d89c8ae75c0b541740111fc.nq.gz
│   ├── 5a145488fa94b7aab35e1cc953e4863199ba12a6.nq.gz
│   ├── 5c34d40d1ad97fa0bbf96116ae3fcdced6514d52.nq.gz
│   ├── 5c4609543371f0f1c3b80fb8207cc29ce2a2137d.nq.gz
│   ├── 5debae20f041dc6e7c60ee24409363972e22bb7a.nq.gz
│   ├── 60a12a82bbf5fe258c65a199d4f613c29b29b7eb.nq.gz
│   ├── 63d19a687efdcd6d852a0dcd4fe5790c2881085f.nq.gz
│   ├── 6a2894a5ab824c4ef796485552ee347817465e4a.nq.gz
│   ├── 6a54b93da94a9906722f730b356c76cf5db7bc4c.nq.gz
│   ├── 6afb71115f5260ede16a123af23f148141d58a0e.nq.gz
│   ├── 6c0220a414f5e0ca5f725403b2e64268863092aa.nq.gz
│   ├── 6dfa9590a52a243b0c57e8344f3d3781e51974f1.nq.gz
│   ├── 6eb0f987db5685cc302e305aee3825b177e126c4.nq.gz
│   ├── 7cce62fd3459404e2aa0b801616a50ebfed50ce0.nq.gz
│   ├── 835074085813dd9c9f8ded0dcd2940b6c2d309f5.nq.gz
│   ├── 86b18e10bcdcf352909301f5542cd2ffe7c68746.nq.gz
│   ├── 8be05ca23e316cc1fe8d23e9fbc3759ef6409ea1.nq.gz
│   ├── 8f8d77688237ea274a5efdacc5ed9204b306162c.nq.gz
│   ├── 8fbafee46a95e7319854f967169c1442a07f9e2b.nq.gz
│   ├── 8ff6926ea55ac67efb364468725e0a6aa376902e.nq.gz
│   ├── 912d365a9cacb3ad4668635f3772f281f4a58699.nq.gz
│   ├── 919adf200a544a36846281cd7143c9bb0af4180a.nq.gz
│   ├── 919f7a239e845b30e8ae8afd6d5051c170bb9072.nq.gz
│   ├── 9313f14d30de4973a47e25a8a3df805a5c22e181.nq.gz
│   ├── 93e95933efe0fcab868ef11ec57a5a8f0e54358c.nq.gz
│   ├── 98729d12d8f3660f6928725b159a30cc65decc6f.nq.gz
│   ├── 98fde6d0c223698598b15d638116fc1f7a832958.nq.gz
│   ├── 999c66f365306348d75d7039a8812b1998827bfe.nq.gz
│   ├── 99fcfcd0b2736aa96209bbc45a872be3837aca09.nq.gz
│   ├── 9c367523f86587f34e9286d17a5f75e0b24b500f.nq.gz
│   ├── 9f175b654aad1b5df266d2440a406ffa8cd20210.nq.gz
│   ├── 9fc29c0db5faa10af9afefeaca5250e0a110992c.nq.gz
│   ├── a10f8d5b79a5c1a18d577c63b4c31c19cb138c98.nq.gz
│   ├── a4ba0927d82c803b9082a39a312a8e1e235fe66d.nq.gz
│   ├── a6511fe404a0e97530a3527a9acae3e30437ffa3.nq.gz
│   ├── aad0bfb29cfbfa3377a654eb6700a06b392fb34a.nq.gz
│   ├── aec3c0d676c8221792a71a79ffbfedd8d9014a37.nq.gz
│   ├── b09b2269c1be4cafc06758cec52d10ac7681c120.nq.gz
│   ├── b36ee4b3989034d65afef1ac8537db0619a37d87.nq.gz
│   ├── b741d41c5615a902c292c31cc4af60a0fe929d90.nq.gz
│   ├── b8b4486605fd1d712d3ad533df2c2ac137574b3d.nq.gz
│   ├── b97978a27b4c8e4e7c35bcc37538930a5ab6b77a.nq.gz
│   ├── ba491e2df016cee76b8058a876a36db3aae826d9.nq.gz
│   ├── bb47cc5f62ee43f0d05e5d7ae04ecc54bf20c5fb.nq.gz
│   ├── c1240d2ba8e2b866534565e1222aa8cb83d4373f.nq.gz
│   ├── c12f103b53bec6ef7fda0d9f81ecb8632ac08cd6.nq.gz
│   ├── c2e9b9c956e1390d6aaf21874aa9456a287fe649.nq.gz
│   ├── c36f162559bf093bf29dbb202609ec98f3966801.nq.gz
│   ├── ccbe11ec379932b6302cacf8c49d0854d58c6a0d.nq.gz
│   ├── d13553dda87ed25fd6eda009daf49bb0e09b8b53.nq.gz
│   ├── d373df4966dafa5dfc0617669bd352cda5136789.nq.gz
│   ├── d5057982f2e59642a5bbbe7185fe0a13e5f9e78e.nq.gz
│   ├── d5e6e2bced5e0a1c5a8d626f5a4dc42e852f8f8c.nq.gz
│   ├── d5f05371146043d378b95ac529864387b6587a24.nq.gz
│   ├── d78d2a01027f7f9f521f38515bf506c76dff3353.nq.gz
│   ├── d7a0e82fccf16208e7c8bdef3992b1d4b6f51185.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dac65d3be90ba78731549f2ac254b9fe206811fd.nq.gz
│   ├── dbe327ef6f1e53b9025ae98d87a9100a37d3aede.nq.gz
│   ├── dbf97ca75bc0f27cd012bcd4014368cf623413cf.nq.gz
│   ├── deae977e5416c10002518851cb1f91b4e121e32b.nq.gz
│   ├── e1afd4f8e5171aa139bc6ec3c41c9a38a7252ba8.nq.gz
│   ├── e2623667324ba8ae3340c3ad590762fc903c1c35.nq.gz
│   ├── e2e577a9d75d5ef94aae49b39e516c7fd4e860ad.nq.gz
│   ├── e64b6423894d9f8e62bbbffa50fda79c7c683d8b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec8e14e21c0d868e1704cf139ba37f56fb3722fb.nq.gz
│   ├── ef190a11737b8db2dfafb977fd67709d6f293429.nq.gz
│   ├── efa9a2ff8428807a4517840249f977bb3930f333.nq.gz
│   ├── f1a8b1c91615dc4716e5598d0f8f6da68d7e2b33.nq.gz
│   ├── f1fe8dd48203a5ad39ec471695445f16a186b85e.nq.gz
│   ├── f271fa8f869bdddf85e5d23f1202dcf01771cacc.nq.gz
│   ├── f2bd4d300f48fb3b261ded5531598d3e5a4e78f4.nq.gz
│   ├── f9ebfad6d5c387f95b5a591c59b4f38c6215ec3c.nq.gz
│   ├── f9f99c8fa32de4a75ef01859eadcc4de94c5c961.nq.gz
│   ├── fd2e944d27a952c5b184588a0a31fbdd11ca12ca.nq.gz
│   └── fff14b86f92b0eb21abaf028f90d0e67af3af130.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d7bb777e503d82bf2496113f07dd4ab249615efc.nq.gz
├── filetree
│   ├── 4399e300fd8f810d84601f8131dde2c57849484b.nq.gz
│   └── d7bb777e503d82bf2496113f07dd4ab249615efc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 128 files
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

[PyMySQL/PyMySQL](https://github.com/PyMySQL/PyMySQL)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
