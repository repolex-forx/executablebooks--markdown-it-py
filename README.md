# Repolex Knowledge Graph of executablebooks/markdown-it-py

RDF knowledge graph data for [executablebooks/markdown-it-py](https://github.com/executablebooks/markdown-it-py), parsed by [repolex](https://repolex.ai).

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
lexq download executablebooks/markdown-it-py
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c62983f1554124391b47170180e6c62df4d476ca
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c62983f1554124391b47170180e6c62df4d476ca.nq.gz
│   └── repolex
│       └── c62983f1554124391b47170180e6c62df4d476ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 005105b1c7ed1a93772c62af8bd5ef54d97dfebe.nq.gz
│   ├── 00cc1198871da110905c6e0f89465501be967fd1.nq.gz
│   ├── 00ff675c8715d01243af1fe7104fb1053fb45ee1.nq.gz
│   ├── 02a23b178bae598c59feb74aa6f0a2b09f3c8a59.nq.gz
│   ├── 084557a92a4192d7ba30599e565fba963c4cf902.nq.gz
│   ├── 0c136bb68173de52fdfa1e6561098349b23a6927.nq.gz
│   ├── 0c9081b9cbd4b49d39d75427fd806e56c485a5fd.nq.gz
│   ├── 0f71482d6beda9eb2c3594c5ec63463ea6a67510.nq.gz
│   ├── 0fca6c84e035b83b21d5224be92fd4973f25b80b.nq.gz
│   ├── 11bda644c260b714cf010ed44d2ed345de80314e.nq.gz
│   ├── 14d08ec9546995f8eea3e9b83ea896f29ef020cb.nq.gz
│   ├── 178d717e05a37790740cb102a410033e542b3f08.nq.gz
│   ├── 18b2fcc7a8f5a40d4820df53838d29fcce833f3f.nq.gz
│   ├── 1a7233791a74912c4a5481436745f22d09ff65de.nq.gz
│   ├── 1e10a8c213ae76bcf17219f38ae98541357dcffa.nq.gz
│   ├── 1f89e66f2ada1fb77c32ced2376f04afcab88b92.nq.gz
│   ├── 211d790cec901828153cf9d8e52cab29b2a52e5e.nq.gz
│   ├── 23749bafe1b34c260c0fc3a2e1954cdb7f6bedc4.nq.gz
│   ├── 23825e5d2191888d2b3958370e1e86e017e6cce1.nq.gz
│   ├── 2414f41d02c6499c24ff424b24028de91f1d29fc.nq.gz
│   ├── 2571a15861271f25e60fd5dd414af3ac5b450ad3.nq.gz
│   ├── 263f1b8de8dcdd0dd736eeafab2d9da34ec2c205.nq.gz
│   ├── 26ec2e636d458fc7a431ddacc8a49c4763613643.nq.gz
│   ├── 2e92c7d83629f00283b5ed885637c8c4a851ffc7.nq.gz
│   ├── 30ba877799beb764dc0a603caa21fe6e6b641375.nq.gz
│   ├── 3100af7f7fd6dfcb7afbd51b264d0e6e1cbfd764.nq.gz
│   ├── 312048bf79c33be8fe58f87453845b2b39614efd.nq.gz
│   ├── 32439243ef6ebfa424d202ed63635983d4c9ea82.nq.gz
│   ├── 33f30b12a85e544169b129dd227e8d003be1c673.nq.gz
│   ├── 3522207abb680510decdd6c54d0be81401128ad7.nq.gz
│   ├── 35cf925c697144c98bb134284e06c4abe7b4756c.nq.gz
│   ├── 3669396e3e7d51c125678f45a862139fe3b3fd9d.nq.gz
│   ├── 36bd0b67183e902e39287041da8ab6f728edea02.nq.gz
│   ├── 37cb7e2428ef4070a5193e054551e5b3dded453b.nq.gz
│   ├── 3913de4424d896aaa826c79b626b199c2db89869.nq.gz
│   ├── 3a6d6aeb05eb2a8c0cfcac0891061c239e236e05.nq.gz
│   ├── 3bcc08e24f237be2cb403a19878fe85d69814779.nq.gz
│   ├── 3d43f6ee1deb527a42f4d99da40bd052d9b02886.nq.gz
│   ├── 3f1fc18cf6c86fd3c0e19a7a573acff28fd042b4.nq.gz
│   ├── 41d399efd963b3252de73d87b74f68f621f37dd8.nq.gz
│   ├── 4403598115d6eeb1c1816236b39b52f933adcefc.nq.gz
│   ├── 445ad265a01e3f1dededf9f72848686a2b5ee901.nq.gz
│   ├── 45915b06591ecebc4e1fe4c1672d9986d4852aee.nq.gz
│   ├── 46e5f73438d6c93d028d5611b0fb32154081dfcb.nq.gz
│   ├── 48b1981c7ee051b2f9d53957b96627a52bd35410.nq.gz
│   ├── 4a005089d4a6d13ab687ca49a70ccb763d13b2f4.nq.gz
│   ├── 4ba749ee809724ad5f9631af33995517cf300804.nq.gz
│   ├── 4e7dc8579e839e8e6015437d55abccec1ec4aafc.nq.gz
│   ├── 50a7184cf4746fc86a4e8032efd0604bf819021c.nq.gz
│   ├── 50dc41294d6b3df03f73bfb40d740ea4ba36c8ee.nq.gz
│   ├── 517da2312aa4c2ec89a8ba4c9f061793ef470f1d.nq.gz
│   ├── 51a2fa63ab43238a63585cf0c9c1e378cb4fd85e.nq.gz
│   ├── 5369157bc3caeda3ca53c5cdaaef28a94e47c522.nq.gz
│   ├── 5379f6d7a8e9ea3ee27a6462a4108a26549ae520.nq.gz
│   ├── 568393cf0a4bbcc110a252332f11c0f4c5817dfb.nq.gz
│   ├── 57b576496466feddbae004cae2d4915f1e3a40a7.nq.gz
│   ├── 582ddf59e08277fe6e78cee924d2c84805fe36fe.nq.gz
│   ├── 5bac04456e67730ebb499871d2738e7060bc2010.nq.gz
│   ├── 5c5ed4785113d9ec40b8578c09d98d2ebfe1136d.nq.gz
│   ├── 5e7cf822ccb464b28ded87d6670242de4afef9f3.nq.gz
│   ├── 5ec210b1f3a6c2148316498e1788e3c99aff0561.nq.gz
│   ├── 5fd6321c1dddfcdebcca947d53d2528c2ac91d21.nq.gz
│   ├── 62b5bf85e7cd99251f6a4e7e86f652986bbda562.nq.gz
│   ├── 6546e2502f93a1b38a49c3fd728963a156cf0243.nq.gz
│   ├── 6605d2eeb35cedc2ede3af50daacdc8f7a1c11e2.nq.gz
│   ├── 6834989fe7d1079f18117c385a9dd79270fe9e2b.nq.gz
│   ├── 68eac5e6d063ccd8ada5a9f2501aa82025fb87d3.nq.gz
│   ├── 6d60589adaab5610ab0ec3c53380dcb5d0912cdd.nq.gz
│   ├── 6e5fb4b4d7c7432d3baf9bdb4ca5e2fb32771ff6.nq.gz
│   ├── 7286f8ea90969cafe9604f388e3c48e855432f2c.nq.gz
│   ├── 74c7ee4deb72be54621defcde2e2d0e4430bdf67.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 786be571a2fea0343f1107421961f2a24032b85d.nq.gz
│   ├── 78826a39add283898368bad998ab17cf025890ec.nq.gz
│   ├── 79f6f74a31afa5466055708b9240e5fa655882fc.nq.gz
│   ├── 7c0512e0c82cbf7ce32f1e4ca3bb4624a630e4e4.nq.gz
│   ├── 7ddcffa400937cc68a64840a3e68e09ce9351ea8.nq.gz
│   ├── 7ffa058cb78f8fb9beb974d9fd429004d2d2e585.nq.gz
│   ├── 87075a706befc8bb8b02b64ca25ad0a154e27045.nq.gz
│   ├── 87fdccf86e106e4eea079a117fcd5e3ddf762b84.nq.gz
│   ├── 8822bf7ce04759359343033c0795dff9ea1ed915.nq.gz
│   ├── 8a3b0b7d5ab7bc174a3c96cbc8976816278a6c21.nq.gz
│   ├── 8aa858f7ff7b6e2f0f6e5a2155dab99415255d39.nq.gz
│   ├── 8ed314e2285a8916bf9152037bf0689c3958272f.nq.gz
│   ├── 8f5b921cbd3bed2c85734b44ccd989a0fd0e6788.nq.gz
│   ├── 9065e1d034da76270f7d3f1ba528132c8d57d341.nq.gz
│   ├── 91740067dca67a106cbd63afb63e5bcaa5cb0417.nq.gz
│   ├── 91ab58044cc9f93c540fc5d7e49a6c704e805d58.nq.gz
│   ├── 92720b31621b0f6b4ac853179d886cb58e4e2f36.nq.gz
│   ├── 97f8a65adbf99dbd48d30d7017b104b7c5e5c71f.nq.gz
│   ├── 992da4ffdd04c4e55f443075726f543d07c92a67.nq.gz
│   ├── 9a98f9e216c94db0217e986270aaaa72fcc99f7f.nq.gz
│   ├── 9c63b27f7186eb99c61938d27309fda7e900b88d.nq.gz
│   ├── 9d48db4f9f85e1752cf424c49ee18a6907c3f160.nq.gz
│   ├── 9fac279576ebf16e43323f8807db3e6a1e2c79b2.nq.gz
│   ├── a066c217356c2fa56c117779757dbd8bc5c6f86c.nq.gz
│   ├── a38ff0d98ac7feaba80fd67f3c8f0d0454dde47f.nq.gz
│   ├── a50c0575a6b7e4ac2abc520babaaed02b2e485e5.nq.gz
│   ├── a6c3bb8d7ae18880fd638690fb5b09beb78b103c.nq.gz
│   ├── a6c443143623c5b7abc0bfe09f01f50b11fa9018.nq.gz
│   ├── a6ec6e1fb0637390626347685cf06892b3c19372.nq.gz
│   ├── a890c0a68a6412296e29c214429ce9ba03fa69f3.nq.gz
│   ├── a8e15cf3f89ab6eea6b0cd3072a6b1542fa451d0.nq.gz
│   ├── a938041d992fdf7ae3f2843a2e0f9ef298c45790.nq.gz
│   ├── aaa878f4d59318baab3910d21490a58cf392f8f8.nq.gz
│   ├── ab822c5fc487c5a494966604a1e89b57a06e0564.nq.gz
│   ├── ac58ce55bbf0ea3cb28c371d92f65eb328434192.nq.gz
│   ├── ad94d40941ee7cd43c7d3873ac64276a47c15d8b.nq.gz
│   ├── aebd2a7cb7a3ccd8bd03e57df3da8046ae5df559.nq.gz
│   ├── af8a41c8058b1a4887252469bdc6f20f085ad7d5.nq.gz
│   ├── afcf9ed458124e52b9b365a6c17440872ffa0975.nq.gz
│   ├── b630fcee0fd7512d3f411160938be0d1bfd95ff1.nq.gz
│   ├── b6d21da9842a16a0dc84464ed8a65f1cc1f486b6.nq.gz
│   ├── b7668a54ee953c9496e420fbf489b798e9f671f2.nq.gz
│   ├── b79389709d2de232e237525f3c07da9462c7579a.nq.gz
│   ├── b94729f8545451707b22f447c2071beb07ef4bd7.nq.gz
│   ├── bcc9980046bf76723245b1ca2543af132efe5541.nq.gz
│   ├── bdee697c2e11a53faa523059bceda258d8035be5.nq.gz
│   ├── bf9fd18f3f33a55d5de2fb61bde806a3377d51a8.nq.gz
│   ├── c3fd0b5e25dda5d8a5a644cc9e460d0f92ae2d1d.nq.gz
│   ├── c52553d8c21265df65e23be253686ef00b3297eb.nq.gz
│   ├── c695dc70766325a39368c793e719cac6302fdd74.nq.gz
│   ├── c726e823bb46634b72b3cfb8580caaad8da1718e.nq.gz
│   ├── c80da5a7ec54521281dac45b66977404f5384491.nq.gz
│   ├── c83dccb6f15c4d7f53c7c75ab4a0e7122742c745.nq.gz
│   ├── c98323c056e0103a12849671fbbac58dc76de4b4.nq.gz
│   ├── ca15b6ff00c687f7a794898d0052c0ba3653ee7d.nq.gz
│   ├── ce2dde95faa6224dfe63ae1673b6c7363a5b3efb.nq.gz
│   ├── cf83708beeebd42eb593aecc35261e6cc59ef2bb.nq.gz
│   ├── d05ee6dac712a2211ab24f90dbea64a99e4d80b0.nq.gz
│   ├── d3e262d3529ab9ad8238900ffaa8d301323a5ff8.nq.gz
│   ├── d555be18e2ea0db071d1f11551338a0bd5ac8685.nq.gz
│   ├── d59364f0d1486a68f07d139963bac3faf718a5ef.nq.gz
│   ├── d6d0b4530d283f4fb925ca4e95c75eef0818117d.nq.gz
│   ├── d71458c559e4a07a2a7704bf1489c620fbaf0120.nq.gz
│   ├── d75c2159423cb1db3801f82f8ebccbbbe75a43c3.nq.gz
│   ├── d78ef69762d4d954167a05129a9e222d8416fcbb.nq.gz
│   ├── d8070d747035dd6b43f11c4bd88d05533b22bc5b.nq.gz
│   ├── d82ef8fbcca54eab4bbb40e8410104eef7a27f57.nq.gz
│   ├── da095edbf29dbff0e4c4e6e8d2d7738c56cdf62a.nq.gz
│   ├── db9c56ce42a743993d3f666d9b279c4e72840d49.nq.gz
│   ├── df7e230651c3b6fd03b4753d411dac51437f9f2f.nq.gz
│   ├── e21c7806930223fc6a2fda250f1c3e4065ef8c8f.nq.gz
│   ├── e2cf7e7e5eccb509619f316c5efab1c74c0330c5.nq.gz
│   ├── e468b853bb7fd6755a0b2dbb1cda540f24d5cce2.nq.gz
│   ├── e51994776e329e560e51a29ba79493161ae9be12.nq.gz
│   ├── e5c0d99d4fc34514e9e2f4de8f22202e93e080c3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d775363c6e1d454e73a7e3fff9af3115be4339.nq.gz
│   ├── e84034b8fffaded6abe157247a682ff22f8f7dcd.nq.gz
│   ├── eafdb95d61309ffadc7d37215ddaaab241916ebd.nq.gz
│   ├── ec816281d49b23d0774bf91db6600d996aaf8b06.nq.gz
│   ├── ec9d39650e5bc533e694d3d6699677068d22c69f.nq.gz
│   ├── eccb898b66437228fb05a6238d347f536c4c0d2a.nq.gz
│   ├── ed0de0fe4dfbad9e3ab82477433805ea0b6650c6.nq.gz
│   ├── ed8d8205b91748f07bf7160d4846000109c97428.nq.gz
│   ├── efbc9d4c9b1cbada1c936401b3421d73fbff5b64.nq.gz
│   ├── f0b31dbde9ef46b9ec47eb75de2f018bc63d726c.nq.gz
│   ├── f1fab281e98b6006a62afcc59ed910ae4bc6741f.nq.gz
│   ├── f4e2cd21b94b9ee9ecb0cac21da619233a5258b9.nq.gz
│   ├── f6e63419e8a4e73433ac51255847664b00fac440.nq.gz
│   ├── f795c1364b8ac098b7a17f34cd31d7070280cf36.nq.gz
│   ├── f8a9b27e425676f9961bff46923daf0952662f70.nq.gz
│   ├── f9b8b457b6c134f5736fabd3b14dc746e75ab86b.nq.gz
│   ├── fa656082978224b2162758e2a3778dc9729d1501.nq.gz
│   ├── fc60d6b15cdfa7012a05bcf1ccbb06f44d870dfd.nq.gz
│   ├── fca7d79d2780a5e656e689ac4843b8464b4ab5bd.nq.gz
│   ├── fd985587976994bd48e817af41021909bd39f19f.nq.gz
│   └── fe346b2f51b055b62966c081139f9706e3295363.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── c62983f1554124391b47170180e6c62df4d476ca.nq.gz
├── filetree
│   └── c62983f1554124391b47170180e6c62df4d476ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 179 files
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

[executablebooks/markdown-it-py](https://github.com/executablebooks/markdown-it-py)

---
*Parsed on 2026-04-25 by [repolex](https://repolex.ai)*
