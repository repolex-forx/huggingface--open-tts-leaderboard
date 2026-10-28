# Repolex Knowledge Graph of huggingface/open-tts-leaderboard

RDF knowledge graph data for [huggingface/open-tts-leaderboard](https://github.com/huggingface/open-tts-leaderboard), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/open-tts-leaderboard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9dd06fb9bfa087f6d943e1b88c928c4781f084b8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9dd06fb9bfa087f6d943e1b88c928c4781f084b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 02c9374dcaaddf5e947268ab85fb992f291209e9.nq.gz
│   ├── 07c8e04a2cbbd7111fddcad91d4bbb7cc7954d4d.nq.gz
│   ├── 08dadefaeed5d63c1be3d843258d09e18a669e89.nq.gz
│   ├── 096d8cd8571f4e4fe389c83fd2bd7a7e10b21902.nq.gz
│   ├── 0d1a32697fac632af1514f9da9f82331159060c4.nq.gz
│   ├── 0d3bba06d4352c4767e63bb8b22b3d91e9f5050c.nq.gz
│   ├── 0d4df314ed57e2429c011535d6d831458b197125.nq.gz
│   ├── 142e7b2e0a4cb2b93857f0bfa7013a7d1cbf0ea4.nq.gz
│   ├── 14605eaf18096741705ea0c85f84006c23cd861b.nq.gz
│   ├── 15d05577b586cb50bf985010214797dca3d71356.nq.gz
│   ├── 18e63b6f6ba779af243764920fa3e996a62b31f0.nq.gz
│   ├── 1aae5cb28ba9bb97cbe460dabd491dedc8eb2768.nq.gz
│   ├── 259e4bfe5e58b83fc61b8d93dbf881fbf5c439bf.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26df312ec2a6fc34602808dbab4508e7ced349b0.nq.gz
│   ├── 2932c8494ea64ea147ceb6f7dc91e1c22306efc0.nq.gz
│   ├── 29e547e4720e88539367fdae0d65d23f4cb4e8d8.nq.gz
│   ├── 2e62c3a0ec0f8b3eb8452969fbd35ede973cadeb.nq.gz
│   ├── 360e9386729c84b3b7507eaaaccd846e7e4f821b.nq.gz
│   ├── 36955fbe38b4568ef9466c1edcb3d547a98399fc.nq.gz
│   ├── 3ef0c36d4923c5811071f9b9c4a84949ae202297.nq.gz
│   ├── 427ee901d6db7f09696655c66998019a9dfa6bfd.nq.gz
│   ├── 44bbfde768144973d74283a3f0e5f3c414fd9fec.nq.gz
│   ├── 46d69e9002be38bdd00e32a765cc4aa24b74765b.nq.gz
│   ├── 485fcea1cda9b9f240e20926909cd3d65f86da9b.nq.gz
│   ├── 4fbdf2c4879a8682a6023f80d9a55688f31b777e.nq.gz
│   ├── 508e2f259345424f7cb828ea082b10882b275600.nq.gz
│   ├── 55dff4f47567b560bf294beef5d53c7b8cfeb670.nq.gz
│   ├── 593bc53a2c138395e8faec356b3eaa014e7bee65.nq.gz
│   ├── 5bd1a2dc3936a1cfd2b45f7bfe3a3add6651a9d2.nq.gz
│   ├── 5fbc46f5519e1bb1cd967dd62692acf5e088b7b0.nq.gz
│   ├── 6563a2526cd073d698913ab03fb037729701b2ac.nq.gz
│   ├── 746208e32b67a9c20fb638beae23d1d4dc348e89.nq.gz
│   ├── 7e48e6e8ac7ea7135d34993d41fd59d580ff2aff.nq.gz
│   ├── 7e596caeadd5c9827a2b3242509dc950f71da93b.nq.gz
│   ├── 7ebcff3fde183a30083e396ab8cd0460cb1658aa.nq.gz
│   ├── 86a215540b09fcdcd483ae0ce318e86cec4b202f.nq.gz
│   ├── 94293057c259743c1bd93578eb9273cf79f14eee.nq.gz
│   ├── 95238404a872fdf6374c74139c81b443236f51ad.nq.gz
│   ├── 970dc649b493324cd6eee9439214de5ed35d3804.nq.gz
│   ├── 9b14d25003fa3842f0ad3d673fbc71ab7a2e306a.nq.gz
│   ├── 9ed4d20f99c6bc1fdfcc067ffcec1130357d7ec4.nq.gz
│   ├── 9f0df697afdd48d6489e483674a96a2e522ec4a5.nq.gz
│   ├── a7354be980606eac2003cf28ee4950d091760891.nq.gz
│   ├── ae3c2ee9e33969c424b00f304aa71c518e7d03d0.nq.gz
│   ├── b2ac50a5f2fa1f0bc4620033f5285ea90bd22ea1.nq.gz
│   ├── b44e994981ab7af1289c587d760e2b2bbf2bc14d.nq.gz
│   ├── b46630f34946a016a1803c0b26e675e4e56e4b5b.nq.gz
│   ├── b57cec4e23130eae47c0361ee4f9d030235917f5.nq.gz
│   ├── b7fc4dfbf1f8903022c0c87308078a604c82fc66.nq.gz
│   ├── baad6fec84c394eedfebf708cd3f253c5f9680fb.nq.gz
│   ├── badf68f1f9e31343ef5a02ffc8ede6dbc1736041.nq.gz
│   ├── bc83386359d783e007709324a96be7b4b1f7cfc0.nq.gz
│   ├── bd59054a5b651138423b6cef9822be28b463e306.nq.gz
│   ├── c19af3db32c0fd226502ca8f478d4362b4bf5b3e.nq.gz
│   ├── c26f3f99b1a4bde9973e9f3cb5fd770f4a4b7925.nq.gz
│   ├── c3c1c22efa421989b9db12e6e2432f683970988e.nq.gz
│   ├── c5d87f251dae800cb407e241e87d4803b4bf107d.nq.gz
│   ├── cb0b33916df2d005ebec79a5f89c2524fd3e9d3c.nq.gz
│   ├── cb880133c865b796c9d5da47d45dfca851202d8a.nq.gz
│   ├── cc6d2772f21e6d760b6918e24f6926c2b403ea26.nq.gz
│   ├── cd734bb186dad8997233ec05a9fc7899e1c0b0e2.nq.gz
│   ├── d4e1a16cc37780c5498b7d2bf3c2fa00f1b45e14.nq.gz
│   ├── d7676256b6f2aa36eaa99c18845e2f61cca12cb0.nq.gz
│   ├── d9c300aeb0bcd74dddcecf9c7b7acf98227c8b09.nq.gz
│   ├── dee15527de25c5dce98831f955eff1b93c7b4db2.nq.gz
│   ├── e1536898fce8f89a28279343786264e12d154ca4.nq.gz
│   ├── e78bbf253203a1cfb1f525bde9048e6b49828185.nq.gz
│   ├── ede2ec6ccd6fbff7bdf136d90d283709b92ecf39.nq.gz
│   ├── f384f5f5d7963c762fc75c7e6a9b006c622b0809.nq.gz
│   ├── f43632cc1c76dcb2ebf1c10a74456388504bb29e.nq.gz
│   ├── f5594a0947e159364cb0db53da1dc5b3c1d1047c.nq.gz
│   ├── f5e5249f86aad30054b0244e2fe4a926835d053a.nq.gz
│   ├── f6341dd3fd995d5a6846c6df177cba1de93f0dce.nq.gz
│   ├── fc274dfda90d2ec02dac26817c0d4ba233cd9440.nq.gz
│   └── fdb6d711dc19447502929234fb116069fa4f4949.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9dd06fb9bfa087f6d943e1b88c928c4781f084b8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 84 files
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

[huggingface/open-tts-leaderboard](https://github.com/huggingface/open-tts-leaderboard)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
