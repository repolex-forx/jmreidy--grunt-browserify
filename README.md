# Repolex Knowledge Graph of jmreidy/grunt-browserify

RDF knowledge graph data for [jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download jmreidy/grunt-browserify
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd0f242873afc3d8bd4ed80df8bd462f52b72dea
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fd0f242873afc3d8bd4ed80df8bd462f52b72dea.nq.gz
│   └── repolex
│       └── fd0f242873afc3d8bd4ed80df8bd462f52b72dea
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d275d31f61545ad04a99ec7640e61e73f3204b.nq.gz
│   ├── 02b8a1ac71578d84e34af037ca8460ffdbffeeca.nq.gz
│   ├── 03893c0ba290c73cb989337e1a9bf05b75fd866c.nq.gz
│   ├── 050c9011b56ad2859dae9633ba9bc821888bedec.nq.gz
│   ├── 0b62c7ab3189f46d2681605ebf0a7dc5b0358868.nq.gz
│   ├── 0d49e9daed5ed24551acf3258c544c19768e9ced.nq.gz
│   ├── 119a4aa636801c3472c803effbc0a3ca3eeaf0f3.nq.gz
│   ├── 1638cfc8e9ca8f0ec31152cc6bb619a2d37001ab.nq.gz
│   ├── 18248adb93f9329d2688d38b9e07a6d9893d32fc.nq.gz
│   ├── 1aa5b878c3c8a77f7b632e3a5b228418ffa027e0.nq.gz
│   ├── 1ad39cdac4f431e2fed24b458952ce93b22a3abc.nq.gz
│   ├── 1f534bed245ac41dfb8efb75691b270afc21710a.nq.gz
│   ├── 1f79800639b3eeb55e55b7e0d8620795b04c8d97.nq.gz
│   ├── 204af35ca9ac9a47f5cfa9e0eb613e6688cbe4c9.nq.gz
│   ├── 21653f812fec1202cc3f7e3e6e7cbf729170e2fe.nq.gz
│   ├── 2329e73fda5b435e1d223b09ecccbe1a5db2b6ae.nq.gz
│   ├── 308508fd15525d418326ae1b882de9185346d19e.nq.gz
│   ├── 3154689d8810588a6ebb9f6a7168f8f008880af3.nq.gz
│   ├── 3602fa616617f6f46bdf08ae4c4f36b10044208b.nq.gz
│   ├── 3822ce1b7baeaee9678f88de9e598fcd62dae7d6.nq.gz
│   ├── 38bada4b1617e245890391001cbf94dad8971f3a.nq.gz
│   ├── 42afabfd2abebf31384ca7797186a27a4b7dbee8.nq.gz
│   ├── 42dcf38079089077bef184bdae518dd69d52a918.nq.gz
│   ├── 44667317517a2ff00eeda92228cfd7f412ee81f4.nq.gz
│   ├── 487ed9aff07c96898083aaa23c9dd81f6bffcb2d.nq.gz
│   ├── 4dcd2fd6178613933c6c09be90bfc835e59742e6.nq.gz
│   ├── 4e4274f83bb134515c3b711475a6599891b277b9.nq.gz
│   ├── 4f0ad78e68fa8581e37cdfa5445489960096f92e.nq.gz
│   ├── 538d5192efb74bfe0c3416478246e3ee8e38ded7.nq.gz
│   ├── 608fa7048fb4a237dcb6158e262ff31cf56b3208.nq.gz
│   ├── 620a9e36218d536851fe12e0da01ac43b1d6083e.nq.gz
│   ├── 62f1111a7d6d951b8b86eaa2c6fc4b120cb18fc0.nq.gz
│   ├── 64b21ec9353c5081e34136f66937faf50380bbf1.nq.gz
│   ├── 6eacc8200da2c2acf4b7bccebb2385f7ab5e8b95.nq.gz
│   ├── 825cb7ac1ed2b05d387f0b61d26bdc1079f1d731.nq.gz
│   ├── 8b1d8853f7e2075cb503e0aa7dc9766cdb7850bb.nq.gz
│   ├── 8f6f8ae60297af9719197f597cb9600cdc315fef.nq.gz
│   ├── 9301eef159e0fdadc82f510a649aaf7b73f80891.nq.gz
│   ├── 957e66c4e21c507e8995378b84122025cec0b0ab.nq.gz
│   ├── 9a7cfa7974ee1f5eb768bf29ec04ee62df8cbf66.nq.gz
│   ├── a279f810facd27a01d7811df53f6b09cf60f3699.nq.gz
│   ├── a2ee11a06498b2f66be60a9be836912235080df8.nq.gz
│   ├── a4a51c54682db1f81f22f8a80596294be28e1189.nq.gz
│   ├── abc4e4aba01a027138fc1e80f4c0b092a8f3e708.nq.gz
│   ├── ade02df93d16a7eea69eddb956f9ac018feb974b.nq.gz
│   ├── b604365f3b7f87755fbf753ff74ebcf6aa21bcd2.nq.gz
│   ├── bc640eae30c461b9b78d15ce122d44d115ab8628.nq.gz
│   ├── c508b0af276ef6d67a302391fd4f07d960597be9.nq.gz
│   ├── cb5fb1c9a7b04186262d5c1e0d6a961a391733d9.nq.gz
│   ├── cc74fdba96e86d3c453d2af896ed3cd8ed09a185.nq.gz
│   ├── cff4e39a465170f52734142f53360907f672e576.nq.gz
│   ├── d09021d56d6ce084436e8c099c568032ed6af9f4.nq.gz
│   ├── d15078f3a6e4ff8ae2eca3d86e62e45e68b684eb.nq.gz
│   ├── dcd0ed213a44fabc31739ddfc93fb6c76b127c7c.nq.gz
│   ├── e1b0f24b4e14f065906766ce850580b499eb9e09.nq.gz
│   ├── e46c19705f6eb2017e83075c68a3acf7af67dd58.nq.gz
│   ├── e4aebf5ec01fac2d3599f6077135519c49363996.nq.gz
│   ├── e85830721a8dcbfeb8b3cae485b50e5ecc015745.nq.gz
│   ├── ea8ffd508605cc1697a904441499ffdeaf22bd1d.nq.gz
│   ├── eeac5cfdb21d7718d6f39d5b87e2983dc2b43393.nq.gz
│   ├── ef13661f509d9e5f7f6355b100ecff1682cb77ba.nq.gz
│   ├── ef4d1d841ba2b352e091b9b68b99710d2967213a.nq.gz
│   ├── f4a4677371270cf75508633c8414e52d1f47315c.nq.gz
│   ├── f74b661b5d4c36e7ef290f75664333584a6a8d2b.nq.gz
│   └── f865bbc93ed689bec3f91638bab7340a71425ec6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── fd0f242873afc3d8bd4ed80df8bd462f52b72dea.nq.gz
├── filetree
│   └── fd0f242873afc3d8bd4ed80df8bd462f52b72dea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 75 files
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

## Source repository

[jmreidy/grunt-browserify](https://github.com/jmreidy/grunt-browserify)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
