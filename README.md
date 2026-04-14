# Repolex Knowledge Graph of guzzle/guzzle_sphinx_theme

RDF knowledge graph data for [guzzle/guzzle_sphinx_theme](https://github.com/guzzle/guzzle_sphinx_theme), parsed by [repolex](https://repolex.ai).

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
lexq download guzzle/guzzle_sphinx_theme
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 932d5b152bf55d294e74abf6aa3da58d7b9e244f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 932d5b152bf55d294e74abf6aa3da58d7b9e244f.nq.gz
│   └── repolex
│       └── 932d5b152bf55d294e74abf6aa3da58d7b9e244f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0048da006db46c22f9d527bd4c0809f8b94c3eb4.nq.gz
│   ├── 009e1d7be733658edda64f29820a1a9cf2db9802.nq.gz
│   ├── 03eaf5861873c5b7fdc011e53917d082b0651c6f.nq.gz
│   ├── 056a5ad35a9ec057b7a6ceb1ae484bff1b7878ed.nq.gz
│   ├── 0b2f84530f3de90881acdb0f42b160659649df94.nq.gz
│   ├── 0ba7bf75f66634cef72180ae5ca70c1a7b017bad.nq.gz
│   ├── 11429501f817f546d748bde5e1f9319254d58102.nq.gz
│   ├── 11698afc2c2ae5626334495334d62e3574d839ae.nq.gz
│   ├── 13c0f8e492d27d4434780f423b00072412f3e387.nq.gz
│   ├── 17fb5dc324fece20ea9acca96ae149804e94e4fa.nq.gz
│   ├── 1ac169c06f71da1e5798dd52f8daef59c781dafe.nq.gz
│   ├── 1fd150b409fe8d2f45576d99aec2dff1bfaba26f.nq.gz
│   ├── 2f7ae28d4c5686783e10dfd0dc835f5434e2c589.nq.gz
│   ├── 306b783294fd4b7ed6bfa3b31d03708b9493d52d.nq.gz
│   ├── 3162ff8eb1ecc63453f2c88a43e57fbbee5d5c6c.nq.gz
│   ├── 3ab1eec327d49e692833555607241bebe490226a.nq.gz
│   ├── 3ba49931e44719c9f0092d8553790223ab0ceca7.nq.gz
│   ├── 423bd5d3a20b804f596e04e5cd02fb4f16cfcbc1.nq.gz
│   ├── 4469488747892e5d72de3752a17705b0f02bec91.nq.gz
│   ├── 46778a21796d14b21754178d21ded6431905dbee.nq.gz
│   ├── 46a8f4c6ca5a931f31ea36aaf61a91f8d7fb2157.nq.gz
│   ├── 46cfd5c8b8e686b57c6fce5ca372afb65f635382.nq.gz
│   ├── 4775f7c31a138d5351b963aa2cbc2ed9b05081ae.nq.gz
│   ├── 4e8b4293f9d471d96ca271a987990f0ea5fa2d23.nq.gz
│   ├── 4fb1930709c84de9f3580fc2c5117d3145ba0f9a.nq.gz
│   ├── 4fdfca185ef6e085b82386c7e4065fa87659a81b.nq.gz
│   ├── 53b296dc4a3b58a3eb79b3eda3cbd79e3ff338d3.nq.gz
│   ├── 545b7c15e54a1399b315ebc761936289283eeb90.nq.gz
│   ├── 5b7170178ae2b996a8882b95e10fd5c46df9828b.nq.gz
│   ├── 5d4a1c47770fd38b715d6f8e119869fed1f4d8ab.nq.gz
│   ├── 611b39028f17d21ffed411076b8457c66dda9199.nq.gz
│   ├── 61a138c66086bedbd45e2036691d76bf1ec48247.nq.gz
│   ├── 61d58bfa37b1f2b143527d72084130a59a5eb053.nq.gz
│   ├── 62fedd617a2d31d94ecabcb50c0bd070382598b9.nq.gz
│   ├── 6847179890a0c957aaeecca0e95805c4b41773ff.nq.gz
│   ├── 697763fc17dedb54cc25e82365f79eff05e6a44d.nq.gz
│   ├── 6a30fa9dd37f5da9f303e421c1e9d52f45bd3433.nq.gz
│   ├── 6cb6facf23cca500d1ed041b807a922b34791d46.nq.gz
│   ├── 6d6c4badcc7d29bcdc6904acbec4ebfea0576e17.nq.gz
│   ├── 72b73e4b97a306a19cd520b3b0ebcffbcdbe73c0.nq.gz
│   ├── 739f351518d9d4ee350f6b72d3426d68ef752c2d.nq.gz
│   ├── 76a41f741820fee9dfe96b0f67a2068b13630f35.nq.gz
│   ├── 78c178fde59a0d534c9262112a02d2e8f293f1bd.nq.gz
│   ├── 7ab5d85bfdd1886b621b98b46e5a9d3609f2429c.nq.gz
│   ├── 7cda1026b9aba41a13e24bcd913da94e155110dc.nq.gz
│   ├── 7e636eb4c051bfed4971d912387eb4554ee47cbb.nq.gz
│   ├── 84f3777407db51e6ec0c4f19ad9cb0fece9fa9de.nq.gz
│   ├── 869a9ed8af705e6a216a97d137e5e4c838657a73.nq.gz
│   ├── 8a9f79bfa937b984e4478502ed59811f4f621cde.nq.gz
│   ├── 8b580d386376b197aadaf0911ff906573acd5b05.nq.gz
│   ├── 9044ee915a0d7f636585e27ab969f05df761f89e.nq.gz
│   ├── 914912014ce4efe42e0eb856b2a85a0a3394fe1b.nq.gz
│   ├── 94d75e9d73609f3bd4092b3edf868bcd80c02bcd.nq.gz
│   ├── 95c6c619d305e4aec571cad1d0af35ce677d0236.nq.gz
│   ├── 9cd91d862920b7b06bb54180d1e14a350d4b7eac.nq.gz
│   ├── 9e7f6dc74213f473fd6005b2131c26fd7e72fa6b.nq.gz
│   ├── a0612586bdb1d700a9a3dff246e7399e5f350d16.nq.gz
│   ├── a3cf79e2fe7ca13835da8fe32f20cfb9b5ebaac0.nq.gz
│   ├── a498ef4e7c8b556fc36f580c5ff524025bb11c84.nq.gz
│   ├── a5b2378e5c2f3c0614d06c1d6696e8c6e31c84d3.nq.gz
│   ├── a5b9691c1f329bff2acd569b3c82da44d96bb1a2.nq.gz
│   ├── a6fbe17f63ebc934e0d8967ea2adf0a98dc16018.nq.gz
│   ├── a907b533b3ead23b7387492136b71c7d1e35b13f.nq.gz
│   ├── aa0ed95970530c80d4080415d4e577cc869ea69e.nq.gz
│   ├── acc32c425dd91d5d9012d14c634bcc3e6f00724f.nq.gz
│   ├── ad044c73e3a51e3eab32f63b872502fa73a07fd6.nq.gz
│   ├── ad6518076e32b52ad56d50ccb0e48d8a093b7efb.nq.gz
│   ├── ae8e2ed3abd624eb793a96b6a85b5e0d394a2aea.nq.gz
│   ├── b6f111e0f92f7f3d2308a58f2b713679c71a2a64.nq.gz
│   ├── b711d9587156ec96bfa236741181cd3d59339365.nq.gz
│   ├── b83078a6075d5d7800466c2981158fc721fd9419.nq.gz
│   ├── b8de7138d91a3a96244a1bc4f97d8af6f4f93577.nq.gz
│   ├── b990a76e6515c7df56785dd8481b59b468d36d2b.nq.gz
│   ├── be508574eef8210a2c9281f00e270807b83437f2.nq.gz
│   ├── bfa258b957f117d1cd44cb07387750856c9f99d8.nq.gz
│   ├── c1ee9642429f7d3076b2a9cf8e5027afea73c187.nq.gz
│   ├── c31595212fcbd4ff65267f36b92bb733e85f64ff.nq.gz
│   ├── c6a59aebb3fb26586ef67308dde9c62ec46f4c51.nq.gz
│   ├── caa42d96346631a692b4238482086d598cca95fc.nq.gz
│   ├── cb3fda65e9f6e05f49f7cd67ffa9c2850cfffc32.nq.gz
│   ├── d23a4e9a764ca15c3c91311db250a11eb5f2de05.nq.gz
│   ├── d63bde76b95f06c5f77d4efd12d0a7ba105b45d7.nq.gz
│   ├── d7514ddecf14138a706455af7e04a75da568703c.nq.gz
│   ├── d83c539b8266366dc331c5f746714caefb84c47d.nq.gz
│   ├── dacc5bbb58035bc5203e206454b92cd3250843fa.nq.gz
│   ├── db1b1f6619f4ff70488acd4498407489a5ecdd64.nq.gz
│   ├── dd2bcd8bf93c9c3ae98ebe5e0f164a0a88f11c90.nq.gz
│   ├── de4f8e77e890aa401db7bf258ec31b02ee184053.nq.gz
│   ├── deadc3ef1a6f49be924ab03eea6563f14b8bbc1f.nq.gz
│   ├── e4f4ab0db8c0172efd8c0b6e49c9db1d916a19b8.nq.gz
│   ├── ed11a7b860db3d546311241b775bfb26720f126e.nq.gz
│   ├── ef8b7a2bca2bdfc0019628a362c88ac535cffa6f.nq.gz
│   ├── f17617e0396d6395a3fd3db07604c1754d2e7b1b.nq.gz
│   ├── f6e97d5afd5fe6aaa8d357af39256b24ae6e5f88.nq.gz
│   ├── f7315435aac7b156445eed5109530ba5e1c2e78b.nq.gz
│   ├── f81b21618a3a5665123072c94044839f6871023c.nq.gz
│   └── ff882b6acaa0fb595bb7658ec36d663394de3fba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 932d5b152bf55d294e74abf6aa3da58d7b9e244f.nq.gz
├── filetree
│   └── 932d5b152bf55d294e74abf6aa3da58d7b9e244f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 107 files
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

[guzzle/guzzle_sphinx_theme](https://github.com/guzzle/guzzle_sphinx_theme)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
