# Repolex Knowledge Graph of BurntSushi/bstr

RDF knowledge graph data for [BurntSushi/bstr](https://github.com/BurntSushi/bstr), parsed by [repolex](https://repolex.ai).

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
rlex download BurntSushi/bstr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 134195be38c7c9a4887980fd0f6f8bae042dd91e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 134195be38c7c9a4887980fd0f6f8bae042dd91e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0179b66f7e9c893378c7b1aafd8191c00392a53c.nq.gz
│   ├── 01b857adaec54d215402ddee547901d793a89f0a.nq.gz
│   ├── 03a4461b7e6cd60557590f06f21f30e39c6e12d2.nq.gz
│   ├── 08981bdd05c630a959b78ed66b9c17b743dc5304.nq.gz
│   ├── 0c7901909b63cdd04e95a3fcb3c560e7b2a5ad86.nq.gz
│   ├── 0f22eeefb4eeb498ce084a1a0a1feee648ee02d6.nq.gz
│   ├── 13232ac2ceb311ad2616dd402db7c9680f39d61e.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 17d687378cc542b89239e954373ad930201d13bf.nq.gz
│   ├── 193deb0caad00020bc62aaad64a0118cdfca38f5.nq.gz
│   ├── 19d4b122b0e58c27d94c60ce3e320a0b6e30366c.nq.gz
│   ├── 1d1435bfc76ae9159ccb25b3598556fe25a20352.nq.gz
│   ├── 1eb798a34c9055e51c8ba90444c1c736875f90b8.nq.gz
│   ├── 1f830009a8002a9ab2079697a913bd93d3dd8d41.nq.gz
│   ├── 2869fec98f72fbe4b7ea36d5128ee1650cb34370.nq.gz
│   ├── 2ad2e93b022e60b3b960f18a1fc5bd9e7547b83b.nq.gz
│   ├── 2eb98c0bd82e48e5c77b1d12c243552fdab57abf.nq.gz
│   ├── 3594277fc3a75dd4c59c840c2b2a2a6832df3a09.nq.gz
│   ├── 369ebacc239f1794765c1540d2d55d584382a5f7.nq.gz
│   ├── 38515e939ff5f74f9a7bd91d3c7c483c093103f3.nq.gz
│   ├── 3b67349712f6501811d00b3c3d3ad650e22f9cce.nq.gz
│   ├── 3b9905da97551a0f368e8e186149bbfa7643c3b9.nq.gz
│   ├── 3db75c5a7dd5945438d054c932838efeca6604a7.nq.gz
│   ├── 42cacb33b04dc2a89e9ffc3f1ec9a77ab157d952.nq.gz
│   ├── 4533d09320890f3b74a85f9910a1053d78d14ac2.nq.gz
│   ├── 48363adccedd3a4f49a1c853c6246ee3b6cdb1cb.nq.gz
│   ├── 497d00e0120ff2a6539161f798163cedcabbf6fd.nq.gz
│   ├── 4bffc67574a24329f7f5a963290d0c707cd193fa.nq.gz
│   ├── 504f824f7ce552bffa11d335ae6d832015ca90cb.nq.gz
│   ├── 50a6f566db47ee6f7e9c7595ccb5ad47d718932a.nq.gz
│   ├── 5d7d34a01a21664ef6f34347b8aef69f684965d2.nq.gz
│   ├── 61ea42cf1a21f94afbeb0c7a847e28c84bae66b5.nq.gz
│   ├── 647739d4a06435f8aeb4f23aefb60ff481762be3.nq.gz
│   ├── 667026958a7753fbf5a3349c4abd76a27cd2ae8c.nq.gz
│   ├── 672bd717124d4b143aded809e5d2e9066bc59bbe.nq.gz
│   ├── 68df36c8e9ba5d350a54d0de80dc7e30d6026a6f.nq.gz
│   ├── 69fc6a586c717ed34640e25939502a0c54427d77.nq.gz
│   ├── 6adc7019d16a47785534047af88d05827d3c78ae.nq.gz
│   ├── 6bfe6b19e3753a35e40496a9f2b2ab1722f65055.nq.gz
│   ├── 6cca67ff67aa922c8c6b12856908e47768e65f27.nq.gz
│   ├── 740fcd0402a5d663bfbf5befcab94c672d5dff2e.nq.gz
│   ├── 7472844d4d514c0ff641a887f10314ed52d7625d.nq.gz
│   ├── 75cf7117baf1731a1241f48a03a438295ab622b7.nq.gz
│   ├── 7ef6b5cde82c17db413f1d1d121038d0a59741b2.nq.gz
│   ├── 80638e87cb2e70e2f8225b2c485b807569ce2e45.nq.gz
│   ├── 825782f1ce1a84e5696347504f8d278677130407.nq.gz
│   ├── 883a6fc66cee15b6aa4cf23f68339086ec41fe18.nq.gz
│   ├── 898cc04bdabf035ee68879485538baa94304d311.nq.gz
│   ├── 904fcbd6e1f9a201d8d3bfb1d143ff85d1a30aae.nq.gz
│   ├── 9231b22f9742ac5f7bfbbeab5f6b035ea7b3f575.nq.gz
│   ├── 9701087c1abb84d6966465ad4fd2a84cf92bb28d.nq.gz
│   ├── 97bd006fb4b1d78f18ea11d712f6c3ced2d78e2a.nq.gz
│   ├── 97cd47d9d18b061d289e872d40d801296590a9c2.nq.gz
│   ├── 9a155eb5cefbb5816b2b7773cea713e1b04d9f38.nq.gz
│   ├── 9af98b8abcdb8f4da2c1ede0544d5e72b9ab9836.nq.gz
│   ├── a591529e87075a8a5821c16069f14aec221ca148.nq.gz
│   ├── a9c2078a966bfc4874b36e38cb67829c39e24e08.nq.gz
│   ├── aa37a218b97e5f6ad37a74a62b50727279a5e460.nq.gz
│   ├── ad06935770acbcc9d62b2b5f4da26043ce0c12a3.nq.gz
│   ├── ae6c499fc3ff73968706f148ff4aaf0ba2bfe900.nq.gz
│   ├── aeeeb26ff36f8cc1c8622a1f3e1cf140f57aedc9.nq.gz
│   ├── af1c73051364ec0b13f0fac788759b23799c955e.nq.gz
│   ├── b0db99dd15c42de073b65b4ee9b68d96ca287f0e.nq.gz
│   ├── b23c8dcae4e4cbef1a132409d533bfdb47d552ee.nq.gz
│   ├── b48cbccce23d604fd9ec2c144ea3f4057522acf3.nq.gz
│   ├── b74c281690a11e9f87058cef048a31ea77eeb8d4.nq.gz
│   ├── bf1f47c8e5edf88ddff92c5d894abe168bd710fd.nq.gz
│   ├── bfe58edc7185b0ebb27070aa0eecc9e6f3d4b206.nq.gz
│   ├── c392a2229cf81231bbadf620383365de021e0884.nq.gz
│   ├── c4321e2c98aa7484061482236b52e7e226f58d87.nq.gz
│   ├── c6731d0a01ca980275dfca72eb9d10289aa775fb.nq.gz
│   ├── ca1d35defd05bd34976c49ae9c219e36d912df13.nq.gz
│   ├── cab8b5ac4e91c1a7aedf2cb3e79a98a6cbf29d00.nq.gz
│   ├── ccba7d95209031b2d953897362160a67305842d2.nq.gz
│   ├── cf8ef736b5e1be86fe16dc9fd44a2bd61e849782.nq.gz
│   ├── d4bd841e541a71f32e2be1fbc50fab183309d463.nq.gz
│   ├── d806cc6cd04a5b7df24d8a4626ad07b4df9edf1e.nq.gz
│   ├── d8bfd0126639bb6ad80d4b7a958d79a6a692d457.nq.gz
│   ├── d9fdf9174c67032ccae22cb24a15e7ef7b9673fd.nq.gz
│   ├── daf01d60cb8aaec9a3d0a47a1f96b49eed6a022b.nq.gz
│   ├── db305da0dbd4e872b4909994c0e58b2bf6f79d88.nq.gz
│   ├── de3aa3b4cbda0d03ba9e4bdbeb5d1509b1f37dee.nq.gz
│   ├── df1e9521da231e39f16fa85997b1de9ed861ac39.nq.gz
│   ├── e343d38645740accccc1b176f7baf173b53c889a.nq.gz
│   ├── e5619b2f00483a8dbd9c10b081b820b3f5c4152e.nq.gz
│   ├── ea7b66e12db4f20991cf2ba6830a09f616e689d5.nq.gz
│   ├── ec84b2c522058b2a596a14da849533c782ebd8dc.nq.gz
│   ├── eff2fd33b0fa19dae7f8438d4393b878e45fd681.nq.gz
│   └── fe32b0d98f1bed58db630938c7c56c01458401b1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 134195be38c7c9a4887980fd0f6f8bae042dd91e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[BurntSushi/bstr](https://github.com/BurntSushi/bstr)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
