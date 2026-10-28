# Repolex Knowledge Graph of Kozea/bobslide

RDF knowledge graph data for [Kozea/bobslide](https://github.com/Kozea/bobslide), parsed by [repolex](https://repolex.ai).

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
rlex download Kozea/bobslide
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f567ce388d63688e431d94c336bb613da9b2dbea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f567ce388d63688e431d94c336bb613da9b2dbea
│           └── chunk-001.nq.gz
├── blob
│   ├── 09a731654218c15e8b3c6da0147e230dd0ced82d.nq.gz
│   ├── 0dee1939a5ce150d70ee5a41303804dc26f984b5.nq.gz
│   ├── 0f696f27c6568a9a92d5728f09318f01663dfa9b.nq.gz
│   ├── 10877fdfe8119b02f04c50a2702c79ee22193397.nq.gz
│   ├── 1795a728fa48013562e31b1222c77cb6c34b46a1.nq.gz
│   ├── 181894792737e5229c0f24cd8d9cdc507eee5a00.nq.gz
│   ├── 1893457ae70dd546dc048cfdf50aec132258c3be.nq.gz
│   ├── 18eb54d3d411b1f243874d1d666b074cf9f2877e.nq.gz
│   ├── 199c7afe1c39c72c8ad3c5c859083a4019548daf.nq.gz
│   ├── 1bb24061a18e2320cd64b6a82d040ac248fa3292.nq.gz
│   ├── 1d116cf97cc47409b9f5f35f62beb96dee997a01.nq.gz
│   ├── 228aa7f8eb9b72f13a79117b825ebe16735f0068.nq.gz
│   ├── 24940e892c0c3e5d39d0cf908a29d6141a8ce4b0.nq.gz
│   ├── 30352d51ab6c713a492df0eb802de2f934e47ad1.nq.gz
│   ├── 3214a864b05e5a63d809d7dc71a92a8acdf491b2.nq.gz
│   ├── 334342e51acb46ba6f4d24c85bbeb92bf0670e01.nq.gz
│   ├── 3496cc4f387b13b0dd17b87b043dc4f9a0685dcf.nq.gz
│   ├── 399d24b6284042c6d5d0fe5c19fa079336fce80e.nq.gz
│   ├── 3a1707ab2187c14fc0519144330c5919963403f0.nq.gz
│   ├── 3d7409139b48005b57e399267d2c6e4900877707.nq.gz
│   ├── 44f8deb2c892f1d061fdf484a1c50ea3640aa4a0.nq.gz
│   ├── 46c3f2b78deba392b9898ef7a25c11e635817c7d.nq.gz
│   ├── 4f048ad771484172edceabeee0ece1d6860a1206.nq.gz
│   ├── 52f0d3bb28e4b3689552c2970e8bd93a2a07d3f7.nq.gz
│   ├── 5bee6d9c875ed15e94e7ea5f54c25dc8d5118e39.nq.gz
│   ├── 5c36edd202535b9518c71575685bc3d64fb2e65e.nq.gz
│   ├── 62a0a4d9b37f4b0ed08f65a83bbd37ad5b634ee7.nq.gz
│   ├── 6562cbb2a71543791b613b821dc12c08010d4e35.nq.gz
│   ├── 683364ccfa4c6c70bb7fa6726acdf2ab0f712776.nq.gz
│   ├── 6ee634f6ae250a85ee3adca3584c850c5354af63.nq.gz
│   ├── 758566e2c9886b5408b4f3612ac5af44bcd570e9.nq.gz
│   ├── 7a137592650c96ce8c32404e59a11bc319207c94.nq.gz
│   ├── 7a57de8aa3f40a869cc0a194fc2fd06fda6067a8.nq.gz
│   ├── 7b3dc743ebffdb6fe8760b0ea207e4f0bd59122a.nq.gz
│   ├── 80bffad7ad074266bb9d205f6ed62543a19c9972.nq.gz
│   ├── 8245b73427741258abbb1eccfeb50b8fd70e906a.nq.gz
│   ├── 82961ee3882f300440602ca34245322d84cf6931.nq.gz
│   ├── 84a2754a1b0d3a0bd8233d6cba508ed69604952f.nq.gz
│   ├── 867e764377695009c59f6731e4bc1d163a1cf553.nq.gz
│   ├── 8cb1c15cf825bfb369dc1ccd2f3d7108b92f2971.nq.gz
│   ├── 92e57705ab299cdce100ce26c45850685381d0e5.nq.gz
│   ├── 945e98fdb9909e532cee1348616ea7f420903469.nq.gz
│   ├── 97da259a9094571137645f7fb113178b1d3071a3.nq.gz
│   ├── a2706c0e3240237aeccf55d297891d64b009619e.nq.gz
│   ├── a50ad6ea16dac2ac60f849670a3cc4797f835752.nq.gz
│   ├── aec0998a921f6a5647b12d0f0ca8fa610b10fa39.nq.gz
│   ├── af537440c7c5d7874d9b7b7878d79cc2b8f294f2.nq.gz
│   ├── b39636dd5049e843f14f62298c45a6a44b036ab9.nq.gz
│   ├── bfd2614b81b76ae1ad374bbe76ceac95edca2ae2.nq.gz
│   ├── c21e035a89de789b606b7cdb514dda7ad731242d.nq.gz
│   ├── c72dd215eda89e8d3f8a471052b5cb4f78f5aa15.nq.gz
│   ├── d759452752773eeccfaa76e5ba4c12a6c9510d53.nq.gz
│   ├── da9436727b8d7ba53e6159e63b55d99f9e42e628.nq.gz
│   ├── db02cad6f1edad5cb635c1c719658e9c39510c31.nq.gz
│   ├── dc8072e38a4239818adf7c60c99ef4f1575b80ac.nq.gz
│   ├── de26ba561b8b31dd26e6f80d86d765695a1abb22.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e96f8dbae5bf53668dbd8875c752198fff0b746f.nq.gz
│   ├── f40b72af11d62022e361fd944292ee736631f292.nq.gz
│   ├── fa461738973c6e3a5c566e5da8bf8a9381a89ff3.nq.gz
│   ├── fa80209beb23db05bd68e2ffe65bf3c2ee8d7448.nq.gz
│   ├── fdcc151ce1cbd20f396c270b2412368056e2322d.nq.gz
│   ├── ff61bf7ced391f6832c2851b734ebaf4722e70db.nq.gz
│   ├── ff6c8e2e7666dd5ba99e03dede986605e01aa588.nq.gz
│   └── ffe27865aaa6eaf96fefe0800afe02a3be71cb2f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f567ce388d63688e431d94c336bb613da9b2dbea.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 72 files
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

[Kozea/bobslide](https://github.com/Kozea/bobslide)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
