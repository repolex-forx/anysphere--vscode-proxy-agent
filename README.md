# Repolex Knowledge Graph of anysphere/vscode-proxy-agent

RDF knowledge graph data for [anysphere/vscode-proxy-agent](https://github.com/anysphere/vscode-proxy-agent), parsed by [repolex](https://repolex.ai).

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
rlex download anysphere/vscode-proxy-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2a01b8b61cf29d8fcd4a9bfdf56f3d2246329f8c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2a01b8b61cf29d8fcd4a9bfdf56f3d2246329f8c.nq.gz
│   └── repolex
│       └── 2a01b8b61cf29d8fcd4a9bfdf56f3d2246329f8c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f65b377edb42917b6603f3caf57a32b08367b7.nq.gz
│   ├── 01f3a918fe1e86b35981007b9446af4342aa4e44.nq.gz
│   ├── 05ac932af7f0416110ca711dc6d1dc9060b424a8.nq.gz
│   ├── 07b148d21b012c9c526beba91bbd85c794f6211e.nq.gz
│   ├── 08a38da06d60fd20eb8e5cb196e0c30eceaf8a7f.nq.gz
│   ├── 0c2f1596e201640621120cc805c031c60281a50a.nq.gz
│   ├── 0c9d87b895ac54486d8ad33c3d64192d62b72afc.nq.gz
│   ├── 1b47bb867a18e38402859eff74a77f611ed5f6b7.nq.gz
│   ├── 251562c9f51c3817358200a74ac62601a1884b1d.nq.gz
│   ├── 26a3e7026577d3d8f68b47ba69bd1cf995b10936.nq.gz
│   ├── 26e35906248ecbdcd7c2f89ed87685a6398aac58.nq.gz
│   ├── 27239791663702beef5948dfb8bd24a2bdf32bd9.nq.gz
│   ├── 2ba54d135b974c5e21e32a65df743fb3a796549e.nq.gz
│   ├── 3026af275f487a7922d11cc8a5d0121a5f008bc0.nq.gz
│   ├── 31740907a0e286c8732c27310c12b880d21426b7.nq.gz
│   ├── 38faa38d1cfa360e52a49f7756d9e7a5e38ab6eb.nq.gz
│   ├── 3cbfea33bc1619b973e34fb11f03298ac644182f.nq.gz
│   ├── 3f6698ddc6d850154086d1f22cd6d92c3b932ddf.nq.gz
│   ├── 3fd853b0efecf747f2fda85c09cff30af2b6b963.nq.gz
│   ├── 45daea5bcabf074be508608f499238ef12bf92c1.nq.gz
│   ├── 4bcfb63114c9664a21caa8ce1e1fd9871eb6fd6e.nq.gz
│   ├── 51c86a3e91080037743b7dbb95060bdee4076714.nq.gz
│   ├── 5bc129a9809e64eeb7cca1048567875f7f7b80d8.nq.gz
│   ├── 615bf48cc2ae062667f95f6857d0672220bbe065.nq.gz
│   ├── 717c4db883d9976816e9f573e2a751947e2b38a6.nq.gz
│   ├── 72e2be96d4f6f0377b9860c1cfe130dbb1b84e1c.nq.gz
│   ├── 79457ca1641670996b7ea86e379e1586ca29137c.nq.gz
│   ├── 7a44f05a91f8f931379448f75b5b2e8d87822505.nq.gz
│   ├── 8296815c4f90fef418439e9db416269736c5e109.nq.gz
│   ├── 83ab185ce1aebe62214eac4795a25ff2bada8ff6.nq.gz
│   ├── 85efc3210ad040bbc481d2edc003beb6de0ff5a0.nq.gz
│   ├── 88a09fb2e175ec41cea907aade0c6d9197552e5a.nq.gz
│   ├── 92e56ae65f3fe67a8c14906f71a5e7f19377d766.nq.gz
│   ├── 96853b1d5dcad1e11b08b571243e220108d8e8d2.nq.gz
│   ├── 9885d055d7f7f9178571e9939406d1f2be9ffa13.nq.gz
│   ├── 9c9ad0253629616be741b6c3f8e0bb1f668f08a2.nq.gz
│   ├── 9d4b52755d9d2c8b82b913604177b3058c102a6e.nq.gz
│   ├── 9fb71dade46a5e6379e73574362d5892cf8694f4.nq.gz
│   ├── a4645e5167e5eea88b40639ba2ec92a9f47a7912.nq.gz
│   ├── a5d8dbcfbe3e95f836c70f124d548045b3c9b866.nq.gz
│   ├── ab12bb6c352f29ed051ab1e1962014864f33a52b.nq.gz
│   ├── b0089db7f78146b9f7e995ba663479071fd72612.nq.gz
│   ├── b0690d829c7b6651fea487a6c8b6201ed9e19bfb.nq.gz
│   ├── b468014b15293cfce066e2efbd186632ee72a4bd.nq.gz
│   ├── b74bfd65e9501fa1a3f020057e81264fa92cc1a6.nq.gz
│   ├── ba29bb8610fa88539b12db36ff66994e61dbbaa6.nq.gz
│   ├── bdb0541785bcccbc69b84c128f0bd6c5eb8af635.nq.gz
│   ├── c313f85c85098c7397e24ef7344cbc7721cd8414.nq.gz
│   ├── c47ee4ff97e21caef9af8b90bf0c27b0b27401e4.nq.gz
│   ├── c49051d0f029ddf8d5bb830abb0d78bf8dccec3a.nq.gz
│   ├── cc2071a81138a78a86447150065160f84992c2d3.nq.gz
│   ├── ceac30ea4b75c49c08b6c3a94e043783f8ee451c.nq.gz
│   ├── cff76d7f8e4d16251735e767056792bc8a0923be.nq.gz
│   ├── d1285ff3881945e0fd6422cacd0bdf4e2e3aafc7.nq.gz
│   ├── e09059b66ef6163f372002970169f604a132ce11.nq.gz
│   ├── e138ec5d6a77c5e6e09346a69cbdc90c85a3806f.nq.gz
│   ├── e30ba05eb7970fa97e5e3c6d67372de545e46940.nq.gz
│   ├── e3d9afcf1edbd824cb400eebd0ce570fb4e6c56e.nq.gz
│   ├── e9718c6ba460ca23ea84524255a297555123eaac.nq.gz
│   ├── e97dc44e7ddbe44f6cd2fa31527ece16093fc3e5.nq.gz
│   ├── e97df8b9b88984d75c6306e2d27fb65e918b3b0e.nq.gz
│   ├── ee5e2fa776eaeef32b2e0e465a52c8cea52667a7.nq.gz
│   ├── ef56f7c515aa5af542bfc4a01af9738db2df6f06.nq.gz
│   ├── f012f52eb234b37133eb2ffdd6dd4520271574eb.nq.gz
│   ├── f0cc9bd3bd57b4edd81618373bd4842f3a37006c.nq.gz
│   ├── f3a59b657d5ea2cee80a9d0d37f587bfec0b6249.nq.gz
│   ├── f403de5784c00823be705438a31964338e664f81.nq.gz
│   ├── f4820d96daf503c5ff7b77e55273d288909c79fb.nq.gz
│   ├── fbb9fca211806aaf81643136781db644a77fe372.nq.gz
│   └── ff9b204aef87129b90b41e3dfcd0f5953598f374.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2a01b8b61cf29d8fcd4a9bfdf56f3d2246329f8c.nq.gz
├── filetree
│   └── 2a01b8b61cf29d8fcd4a9bfdf56f3d2246329f8c.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 79 files
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

[anysphere/vscode-proxy-agent](https://github.com/anysphere/vscode-proxy-agent)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
