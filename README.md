# Repolex Knowledge Graph of twisted/imaginary

RDF knowledge graph data for [twisted/imaginary](https://github.com/twisted/imaginary), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/imaginary
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36231bce324fdee9bedf65a7063b4f1767e0cc66
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36231bce324fdee9bedf65a7063b4f1767e0cc66
│           └── chunk-001.nq.gz
├── blob
│   ├── 0061b0d12de20bfe89a865e5739f2185c71959b9.nq.gz
│   ├── 0169247f0b52f9eaca46e200e071e806b2e1d9ee.nq.gz
│   ├── 05bdc32da05cfa289ccdcb7cedd747c0d38c2d96.nq.gz
│   ├── 07e8563f7e1bcee4d885b470f939dcee536b1cb2.nq.gz
│   ├── 0a6dedda1cb628ccdd172f4aab8fc7a05a58909a.nq.gz
│   ├── 0b9e7dbb37fe5e9d5c3f1c40dfbe1f9f2a4e43a9.nq.gz
│   ├── 0e1fb2164d78b0e54d0d0dd42a60d77775939628.nq.gz
│   ├── 1733c9b7298d0a9bcce86776305356ed25e61fc0.nq.gz
│   ├── 1c30687beb3e77c32ee8376ffc89c6780a92f2a7.nq.gz
│   ├── 1cedc375da932f456e1a8f1f7ccf2559941cc184.nq.gz
│   ├── 2190931f7b9e2a44840ed9f841b2623afe862914.nq.gz
│   ├── 21fb1da56bc5c7103401051e51b9f132fea11e16.nq.gz
│   ├── 253858aa280dfeed5acf4aa8f34ddbab4722be2e.nq.gz
│   ├── 25478e1601c86ce2654ce4e798705d356f989b61.nq.gz
│   ├── 2704246137892c75bb22568b102b97060c993441.nq.gz
│   ├── 272ee29ba60d43e7ba56579a8ecfda3a0d6503fa.nq.gz
│   ├── 2ab3fe5efcdab3f58dbe3e1ab45208797cef75b4.nq.gz
│   ├── 2af89130992030e6386d9f6556dc4ecc9a0d33a9.nq.gz
│   ├── 2c9f543f5565ede49add458860a825c73f5cd0c6.nq.gz
│   ├── 2cacf9b72c607b7242b1a5a58e76f2ca2feef911.nq.gz
│   ├── 2cf0da746ac2d951e9d154068325fa5f4a203fa7.nq.gz
│   ├── 2dd04a16450db68a6686aeb237245ee0f243d30a.nq.gz
│   ├── 2f60c63cffbf74d0f901faa65140e58255ab71ea.nq.gz
│   ├── 31ffc8014cb8eaf039bb21cb036d571eb10b397b.nq.gz
│   ├── 3488eecc4a8df4b130bf84d001217297bf48e16b.nq.gz
│   ├── 360db15679b6c704308d972f978c3f1cb73bce49.nq.gz
│   ├── 38d8a05f4e95aedea5ba8552ecffd47c7dcc985e.nq.gz
│   ├── 3ab32845c3406bd8ead25eb06255a3c4734900ee.nq.gz
│   ├── 419455a11ad3629417df2417d3dfb68188f8a2ae.nq.gz
│   ├── 442dacffbf3c02f1047e65972d8bdfef4023c245.nq.gz
│   ├── 45fb32560523ac6ea25328ceb461b5f0b24a8bfc.nq.gz
│   ├── 4842b697d5acb69ed49a153ac6f977dd6a134e6f.nq.gz
│   ├── 492931150f28cb551ce82f11d9cd923f3826ca27.nq.gz
│   ├── 4d51e51395538259fb28a437e25707a816d6f456.nq.gz
│   ├── 4dc5ca13431503c87a715a4c4e5377db30bcabc5.nq.gz
│   ├── 4fc9cbe7ff07e4d558194f9fc754d474ab4f1a71.nq.gz
│   ├── 4ffc83a71fbda7ea1328b1c3f491505ffbcd501e.nq.gz
│   ├── 5016a605487b718eba879dcfdc222070f36baa84.nq.gz
│   ├── 510b3d41657c8852cc408c5d54db5f26a8a7efd4.nq.gz
│   ├── 52e4fa9b0764670894239be4e9d4ef74b62a82fa.nq.gz
│   ├── 535661c27727160f3618660e5d2f29b253b44d2a.nq.gz
│   ├── 53e0de8ede4c19ddf353fe65224e80755134791e.nq.gz
│   ├── 5402a12c47cabab5ca6ee901bc20fce66f349847.nq.gz
│   ├── 57a64e52c3077ef12f3a9b40cfe2c0b997489281.nq.gz
│   ├── 59d3d5ed0844e81ed6d780b82f321f92f7d52b2e.nq.gz
│   ├── 5b01a0010dd80894a7a70b5f4d0ff52b014c828b.nq.gz
│   ├── 5e388d9c9cc2021293d99d4ff10f8d6a4eaf660a.nq.gz
│   ├── 6125fefd93838a6576a004cd2531371d583a9c3d.nq.gz
│   ├── 616239754a6ce41ca9d5214b3dd65afba1bac073.nq.gz
│   ├── 6171b5e82c0ac3b3e6fb150cb96d6892ae23ed7b.nq.gz
│   ├── 61a067353cbac6ae1b5abb97bda2c86056476443.nq.gz
│   ├── 637d7bda1a83cd72257c7d9e0adc37350f051f52.nq.gz
│   ├── 6463a89361d185276c0ee3846c578d6e424f02f7.nq.gz
│   ├── 65902d78351a567eda6046ab60a843065da4af6d.nq.gz
│   ├── 68322e26975669f211206fccfac3c6bedf60bde9.nq.gz
│   ├── 6b3eb463796f2feb55119ec68acd6bd8c08bdd29.nq.gz
│   ├── 6d15feee011e8c92ef2de69e54da9c4f8b716efe.nq.gz
│   ├── 6e4d71cc3c3fc536029a8d8fec1e08070001fd59.nq.gz
│   ├── 7226886d3cf12e2a39bc65b940174322bfc6dd4a.nq.gz
│   ├── 76bfd1940af14b6eb0bcc75d82a9fbb5f1b6723b.nq.gz
│   ├── 7a27d6508188c18724d51f3881ff104ec0c80cfc.nq.gz
│   ├── 7f1c67ff92f8ae34746712f41889b182c94e5fb2.nq.gz
│   ├── 82a08a5021a33e48218fa50f29896805aaeb16a0.nq.gz
│   ├── 84624008ccd2fff7de135a2510366b7ab0f3449e.nq.gz
│   ├── 8488c0e56e67144030cd6c367879763dc4b02175.nq.gz
│   ├── 84ff241e9b9b8b953bd00664b849d3d33ab40816.nq.gz
│   ├── 8799a708be4a3686718eec616d0930055630f607.nq.gz
│   ├── 8936b3a1cf1ea0d17a5330fd9f24288d110d3158.nq.gz
│   ├── 8a9d1deb8c467d72fb5fc040f795c308e36c8e83.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b6a0e9c26388cebe2ce8ecb6f926364661bd634.nq.gz
│   ├── 8cf2267acb69ac167d5709a7fe19e59810e5928b.nq.gz
│   ├── 90a21399395e7cba618ae64641da2e28c8324292.nq.gz
│   ├── 90a2d6f828c14a68f523505cb3b32786f5d0b1b4.nq.gz
│   ├── 91553f4eae7f2231441d4195eac137bcfc3afabb.nq.gz
│   ├── 93b0ad35e69bae287708dd61e9b770de9efb1fb6.nq.gz
│   ├── 95ac18b4a238faf2e2ae2bf9ee5d8202feb61a05.nq.gz
│   ├── 95ecd0197b4f64133a740bcc90a14f4faf6f6689.nq.gz
│   ├── 967a4753f584f1ec705946b0914c925c647ec803.nq.gz
│   ├── 9839bd137ee604ca146b6647757a0152a638b229.nq.gz
│   ├── 99eff3fb99421251024847f81ed2632cf3b68c0b.nq.gz
│   ├── 9bbf8cb5b0e2531b4525ca56569f503c54414a19.nq.gz
│   ├── 9d412b017d9052252ed19ebf57eec0b45b88da0f.nq.gz
│   ├── 9e2b2be957b2095ff77290b4ab2383ffed5cfa55.nq.gz
│   ├── a3b597b6c275337e3be5ab321b9ee5b265d55e02.nq.gz
│   ├── a4f8d4fc29a15cb88e2b5df70b3f21ca54c9b4da.nq.gz
│   ├── a508c2af4cc268b917551c275ba18e28b175ebae.nq.gz
│   ├── a97b1e427403b1ec7e58b80c616412cc9440bbe6.nq.gz
│   ├── aeb73f7a631882dd4cd1bc2ba1ca5df75dcfb397.nq.gz
│   ├── b1510235b5183c88afbc29238bdf04b9813cd573.nq.gz
│   ├── b17ce49ecfc2471a2cd0027f13b41a450992dd73.nq.gz
│   ├── b49c15d96fe6b58f5799be5b992a887868a1098f.nq.gz
│   ├── b669f4a6a5a12bbd5aee72935eaa5b536a5f4014.nq.gz
│   ├── b9794a6dfef7ee8b53dbbfee86f3d42631b5f2fc.nq.gz
│   ├── ba8578a8f854ed38f0ebe1629ec3a50ef423f5d8.nq.gz
│   ├── bb36712026afc3b4f8344274cfa378ff40d5b217.nq.gz
│   ├── bc11d0ed8aac2e2df7c38afd4d420fadeb83b92f.nq.gz
│   ├── bd883ac3c3b1a04ac16fd6795c754c3732c3e158.nq.gz
│   ├── c09bdd798376bd285bea52a60ea216a966d7dae1.nq.gz
│   ├── c211a142500be8b5aefd340e514cdfead0b79bbd.nq.gz
│   ├── c261aa304ffa346973688143f501edff4ef1c02a.nq.gz
│   ├── c3008b336a02506181fe096ceb008797e07bced4.nq.gz
│   ├── c37dfbbc98d5abc7d9b22405ffafbd611404e5fd.nq.gz
│   ├── c3ed70ed5315493b2982c42db34530061cee5554.nq.gz
│   ├── c53bbe67a8a4bdf5f70f63194578243cc804558c.nq.gz
│   ├── c6b95ba886f4b3eef17d61940c46e4aab51f5025.nq.gz
│   ├── c8d150c70c99db1149ce031cd8bae5e4ca73e82f.nq.gz
│   ├── cbfaf73126b196e2236fa49c35c6ea99978a71b3.nq.gz
│   ├── cc82c4be617f44749267d6f8e675bef5e843e4ae.nq.gz
│   ├── cf6ade3612a3362863eb512f8ab384eedc7d2297.nq.gz
│   ├── cfa1fbbad4a755eb2d03e9339e83641f283acd93.nq.gz
│   ├── d0f248f2fe6981e2720230018299943057735017.nq.gz
│   ├── d10fd9401b2b5a032ec065eb2e464761e21b6045.nq.gz
│   ├── d17b473bf7838182be2f514661a22518f807cb72.nq.gz
│   ├── d323d86bc9d095c587ea30413dca365f6549958d.nq.gz
│   ├── d32ccaf8d2d0682d86d9558b173b0b07fa8e6485.nq.gz
│   ├── d419241bdecfb4f4426d7cf7498ab821768d9a9d.nq.gz
│   ├── d499dd5e405c8b6b42d19b4ac87c4be031e5e55c.nq.gz
│   ├── da796963711e7d2f944e760754c58dbf5be9185c.nq.gz
│   ├── db3933cfb0e4e951b365dc20f134512c6c61bd94.nq.gz
│   ├── e4f03ec2306f05f78cf173c4250bfecb54b60409.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e796a5c90ad7ecdaa43992b3b9a7c94727ceb1fc.nq.gz
│   ├── e970262023f2b5804c5a29103b16929dfd9950c1.nq.gz
│   ├── f05b1a94ff4e56fbd9b1ac24194859bb7ba8d346.nq.gz
│   ├── f0689a742138544b27406bb8f6c2a8bd816d5440.nq.gz
│   ├── f5017332fd125a65909de1fd4016d032f4edf081.nq.gz
│   ├── f86a55ce78caf7d13472983349d5dcbf669fc649.nq.gz
│   ├── f9c5e3400b5d4abfd062e417c650a57c1b5f7f22.nq.gz
│   ├── fb1991956f990cf29ba5d1d38cbab48c0a4449dc.nq.gz
│   ├── fe4b14daee2b75ccc958164ecae80989c3f42af0.nq.gz
│   └── ffd200614df16bb3fe7472c046c67b8fc24eff72.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36231bce324fdee9bedf65a7063b4f1767e0cc66.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[twisted/imaginary](https://github.com/twisted/imaginary)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
