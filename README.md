# Repolex Knowledge Graph of NousResearch/nanotron

RDF knowledge graph data for [NousResearch/nanotron](https://github.com/NousResearch/nanotron), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/nanotron
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2cde8f63519f15aa449803441ec70225644bd25d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2cde8f63519f15aa449803441ec70225644bd25d
│           └── chunk-001.nq.gz
└── blob
    ├── 0156b1bbd4cf479f1147f72ccd982896a9c4af56.nq.gz
    ├── 021d955def70359c8abfc117902f5075c72ee916.nq.gz
    ├── 0299d043cc9ccad884fd82c485fde729a59933d1.nq.gz
    ├── 046a4b30e26f98d8d68a895456d9c7394ab52f61.nq.gz
    ├── 059f5ea4a995194042ed691541fe7aca4a28c339.nq.gz
    ├── 06426b0b1d88b3f9c0134657f39e89260db6a684.nq.gz
    ├── 091981870fa2e8439b37703df4de28f3b3a6696d.nq.gz
    ├── 096995b0164675fc126428b071207a708dd706df.nq.gz
    ├── 096a49b7980edda437ae81f941146c08f34afb62.nq.gz
    ├── 09c94192e765c06d703aa3510be7987ce74b03c1.nq.gz
    ├── 0ab20da62d0ca4bb2d0eb4b200af4090939573b6.nq.gz
    ├── 0acd2d8596efac72712130459da4971f917a1de8.nq.gz
    ├── 0c60dec1b24094c4f37f5f623153e7c9a8b20632.nq.gz
    ├── 0d8708f9327910604983844f1b7a9f311ed43d78.nq.gz
    ├── 0e0b265322d91e30e1850d47116cdfee1d16a63d.nq.gz
    ├── 113c545c6ff03f960ffc4ad7fcb87fa92dbd43e8.nq.gz
    ├── 127ddb5e0a56733ba1acb2a4165416de4ecb9470.nq.gz
    ├── 14ac690803662369f3c8a8a2a6a466ae0227b559.nq.gz
    ├── 150172f5690ab7f8ae68216ffa2ff61d2bb196a7.nq.gz
    ├── 16008eaa4c72d51e6a7a6078f4b490f9ab40b658.nq.gz
    ├── 199527e1580603e65d30221bfa1297dc4d3865bb.nq.gz
    ├── 1997f6b9fef697f66c76f37955ab913a59deea29.nq.gz
    ├── 1a28f9678181866740742bcc3ca599010b8e1ae9.nq.gz
    ├── 1a62fb0cabcb723d30a49ad7ef5fffeae57f0def.nq.gz
    ├── 1bd4e36ec5934ce7716f96d43f0350307d08638e.nq.gz
    ├── 1efbdd1b5441674a9f11db6e19952f3f6271688a.nq.gz
    ├── 1f0e23ea558c53c0deaed22da91458c85f3025ef.nq.gz
    ├── 1f5c1aa54f17c3d21bd29f418295c5bbc691f5e0.nq.gz
    ├── 20332f7d503e18bc040af9d757870bbd926a6df1.nq.gz
    ├── 21ae191a871e80c3edfb2f456e30756cd8566980.nq.gz
    ├── 235d4644551de3e2fc1bfa55ee3abbd94a0f6bdf.nq.gz
    ├── 24a2c125ffa992d971778c583bf44540ccd758bd.nq.gz
    ├── 24e42aecc0d73c1c01cdeb5023b168e335a2aad0.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2887596e8b2ba2178ae6de5c1e4cf24208dd8df1.nq.gz
    ├── 2adc80c2e06f771fd81bf69ae1535a5832430398.nq.gz
    ├── 2e9407444fe93d4e1513a3a64a5372f13e663755.nq.gz
    ├── 2e99aada8b1ecb9d56c4651724995ab30b861c19.nq.gz
    ├── 2f86a0550d48d9bc9640f90ffc66d91c4acc79ca.nq.gz
    ├── 347ce8b618669a48d5086a03ac233c0ef6afb488.nq.gz
    ├── 36384c8ccd8e97bda194d462f77e54dd315d8c11.nq.gz
    ├── 383ab25d070fb5b5556776d942c42698e0ed338e.nq.gz
    ├── 390c32c402b4a325920a3a8b0d7b0734ec9832e1.nq.gz
    ├── 3e91178df8d3c66eea4b5b8b009f41e8ea437a7b.nq.gz
    ├── 3f94031f099f3fbdfb09cb7cef39269161687886.nq.gz
    ├── 3f97049c791eaea21f5d1c479f55388f968e8d84.nq.gz
    ├── 43236093f725b9754cd0c814b1b09d95bb2578b5.nq.gz
    ├── 43343248518ada5e815f86bae869bddfd9728878.nq.gz
    ├── 437cc0bf9f0e2a0760b92421f259270bb3b88225.nq.gz
    ├── 43a7e355131643c3bb6e649a86ab1dd0d4133015.nq.gz
    ├── 4401274377be6c344a4c187ce2e98f22fd3bad84.nq.gz
    ├── 44066d252e0b3f1c6a80cc726294b79424718760.nq.gz
    ├── 457a2cbe291753c824cd7608087d8652ad04a324.nq.gz
    ├── 45ab9e54934281deb0616dfab1b0d22ded7ff1c7.nq.gz
    ├── 45d2aae13d4fe594b013112003448afff687eecb.nq.gz
    ├── 46dc05347841189a9854cf36797701efb74036f7.nq.gz
    ├── 479e1d47160a8a59c3ccf9147c7511fe78be416a.nq.gz
    ├── 483019d5a735d5a7f685525af6c83b903cf52439.nq.gz
    ├── 4aaaf0114c4434151ffc4f2fd01a5d0fb0c812ec.nq.gz
    ├── 4c7325cd22db0ead9712432d0cb766b3e3043f30.nq.gz
    ├── 4d587fcf29d86e65d5c1866d0674b9c5847f3c71.nq.gz
    ├── 4fd129bc4b3a1b8953f4a34f13a5adc8b75d3676.nq.gz
    ├── 5109e97035930aedd0bf2cfb571bdb74466db112.nq.gz
    ├── 51744207e66120c5b032ed72c154e94059b780aa.nq.gz
    ├── 5174d15780b9bcf1fe0a14638cdde76610d8d16f.nq.gz
    ├── 5234710eb30a12c310730b2d1e0b7139fa4adc30.nq.gz
    ├── 56ef1e2edb1f251088bafea0a007a8ca57c3407a.nq.gz
    ├── 580bd99df453d3984da4fb3974c540e22c8024e3.nq.gz
    ├── 58645e2d3cc65d1c3608b197693d63714971b4d3.nq.gz
    ├── 5bcdfdbb1476bfb80fe9b6e43406eb87fa790c40.nq.gz
    ├── 5edcdcb51330c7c7af77f4674cad06a74bcbf970.nq.gz
    ├── 5f2eb5cb5b771babfa8c4b70996fcd25ec68d905.nq.gz
    ├── 61393438cc2b5fc5f7d015fced73671a5e6c0f54.nq.gz
    ├── 61f7355711552ac4c366417f81c39ec4212144d0.nq.gz
    ├── 6314d592d86be65fa3cd14ef44bd08ce9bc3d347.nq.gz
    ├── 64a92b997c9df38207e3509a7d7eece1dd02daf4.nq.gz
    ├── 64f71d420ee2b0cfbd37344250ac2c740cefb041.nq.gz
    ├── 6aa0cbf5a9a9c69ffb1e81cd40f5e6a8d1867f14.nq.gz
    ├── 6ab71fad4a61641e0657a3aa679a9056a44556a3.nq.gz
    ├── 6ac3c46509aae76262945f20bc21922f45f066d0.nq.gz
    ├── 708393b5f1741681b290a30db8e831358fd37f27.nq.gz
    ├── 7100351de5a405d10b15b09ac732ed49a85089b5.nq.gz
    ├── 72deb7f5b44cc96821a5ac24132ce345598b2b6e.nq.gz
    ├── 73ca3484432f4f50b6936f4040e2eee4dbcf56bb.nq.gz
    ├── 7491172b3942131bd7c81a05f1ba4b35dbef4708.nq.gz
    ├── 74d9c787e30ded1ac01918a249c1f806d8e951f7.nq.gz
    ├── 75271fa9b07ae07f06e888e874a369847143aaa7.nq.gz
    ├── 7663399a6e56033c1fec3c0df61936e2d821e78a.nq.gz
    ├── 77fa5d70f38df109f731901528215e954f8ce20a.nq.gz
    ├── 790462487df231b7fb31e885bb2f36ae5e15c646.nq.gz
    ├── 7abd0b13a723fd2eacbf6c2d21ba018561126deb.nq.gz
    ├── 7c0d24628e39b6d93e6c8e7fd48c1d22efddc0fc.nq.gz
    ├── 7c5ae166f331b329e8e9e1a9004f800a05579736.nq.gz
    ├── 7ddb312ff95e5b2bbf20550041eb8e347bd13b83.nq.gz
    ├── 7e84095ffb2dbfb41d97f8084d29c9e9314724a0.nq.gz
    ├── 7f20ad997edc373d1dc978565b345169e92eab2c.nq.gz
    ├── 7fc7b0a961c91dbcea2aec21b3b4a6ead48c4eda.nq.gz
    ├── 818c03a650b2fc7b22e3af14b35faf531bfdfbaf.nq.gz
    ├── 84bb29b92e9f1bb3a89dd5a95e5a9bfb5500569f.nq.gz
    ├── 88ad85d2ed18b6dcda1babc628dff1897eb2074a.nq.gz
    ├── 88fb6bcb081f20388bd44d2f46ffcca8956dd902.nq.gz
    ├── 896a370cad16cf1836ce13f3b54d49c191df8281.nq.gz
    ├── 8985d130b641f8978a7683d19225bd3403f39123.nq.gz
    ├── 8a704cf488990f5231c8c9f5c5127db23b668f44.nq.gz
    ├── 8a8c8926a784dfc19ee0d70faf6d8fafc3ff7c05.nq.gz
    ├── 8adab6c721eae6df0c3c0a50079d69b76a7f29ad.nq.gz
    ├── 8c6100833bdd9601c45ce1a6fbae16058450b864.nq.gz
    ├── 8c636ac6c0d76b03447f4097475bca9f0546c3eb.nq.gz
    ├── 8eefa9c2403586bcf20f6ab0a89683a96f509d94.nq.gz
    ├── 902009670ef1a5c04533f1aaeb0d45bf73120ff3.nq.gz
    ├── 918053dc77a24f39588717faaab5fa3305f09ac5.nq.gz
    ├── 94b03c6e6c3cbae8f71b069b02f8dd83c7bc787c.nq.gz
    ├── 9607a726b223dc96c6a68bfb8495f93e00321707.nq.gz
    ├── 96d2be4c094bca1fcace700ddb4f8401f639114a.nq.gz
    ├── 96dc92373f3bc977e3aa8b163fdfbdfe91201a96.nq.gz
    ├── 970e74071fba105c901a74115061fadcbf794ba9.nq.gz
    ├── 996843bc2806df3f4af11c13e7c0e6d1cf5d1acc.nq.gz
    ├── 997ad347d7390132ebaaa8c9245788778773b03b.nq.gz
    ├── 99e70f491ff0199f5829d5b915a8eb2a50aa58b0.nq.gz
    ├── 9a0402e8f2bbf76ca33cdde6dda90f3379d7fb14.nq.gz
    ├── 9a59670ec8ca1ed222744337cf48aa56311e7279.nq.gz
    ├── 9ac42ad81bc78581ff83139c39867d1f9b92c715.nq.gz
    ├── 9b80390d20c52c456ab6e25ca48c2e413043e4c7.nq.gz
    ├── 9c6e62767585769bb304935168c4b0ec4fe1f62e.nq.gz
    ├── 9cbbf6803724dacc4759b69d7002bb34831e5937.nq.gz
    ├── 9d3285f60c73fa76e68c5072d3398f23513d97bd.nq.gz
    ├── 9ded4b3a6be89daff291ba403f2e1bcda6606ac8.nq.gz
    ├── 9e9dedfc99b75c6f0fdefdd54c2fd348e19cc9c3.nq.gz
    ├── 9fc81949b2903ba1db0873c8ab4d241b35eb1213.nq.gz
    ├── a29f0c209af26932340c340bb1305ee7c9840490.nq.gz
    ├── a562140a9a6764f4a1f8bc63d21ba4b45fa0ae8a.nq.gz
    ├── a74562460b71200a4f6f54204fe19d1e675f7241.nq.gz
    ├── a7f8008f24c045577a746f77e550b28bb1cd845f.nq.gz
    ├── ab77ca056ff604a041c87b952499e3060fb5353c.nq.gz
    ├── abc3bd6249b7123b7ee9b1cee512dda45f476c27.nq.gz
    ├── acfa837024f4dc80e51c031ee36ec2885e09ca38.nq.gz
    ├── ae5d7411e277ddf2a7af534839b6abf19c96f618.nq.gz
    ├── aee11b288aa3e6803c53bde002f7594c44497f5b.nq.gz
    ├── af0688371d34d1566615af93fa398c46939690b1.nq.gz
    ├── b1445b4812f3e2bf9b290c6618f53c7cf86645f6.nq.gz
    ├── b27ac90d53418badd5b4a025e1da33911ac8d455.nq.gz
    ├── b3298b602e5797828d1f05ce02acb5350fd233b7.nq.gz
    ├── b32c55b4db6aab37ba8537dfa53e98b87eb688c3.nq.gz
    ├── b3831801139d0dd37b9bf6622d079c3ead97472a.nq.gz
    ├── b46828758ced5b5f14a1a38f27d07a2955117cc6.nq.gz
    ├── b4759905e1e8b8d22eb3c03069fb5e9de677a629.nq.gz
    ├── b5ce35290d773f313f8d64da6f58014c6de4bf9d.nq.gz
    ├── b5f12059ae429afafc22ece94c7eeb268bb7da4d.nq.gz
    ├── ba0debd6f5f33ca51e3fb1f2e17f2c1f411eeba6.nq.gz
    ├── ba287d2f0e905a7b2cb3a6ea45b8ecd5ca493d0d.nq.gz
    ├── bd41347a84c716a71cf18a7d7461aa71f0857851.nq.gz
    ├── be2d8cbf1115626c692ef70ad8d2f32f53816dea.nq.gz
    ├── bf5059a97e4497051468b095fd50ade6a829c95b.nq.gz
    ├── c1f314ea003bdd3fc8468fccbd4e6a2fc58e147c.nq.gz
    ├── c2ce0d9c67e6cf51a6e6a8708bdcdfb97fe93231.nq.gz
    ├── c42d76061cc1f4af6d35238f7469201bda59e6b8.nq.gz
    ├── c5b60dd7e78de8bcbb3ef47550ed57b39c991514.nq.gz
    ├── c79b9261329f9e66e45025979c4e623ffbd5626f.nq.gz
    ├── c8837564efa1bb406f926f88991667a79871f1e1.nq.gz
    ├── c88f207f22348f78720a08543e8256107dca4e0c.nq.gz
    ├── ca9df312b893c20465bd0a62c1c534b085a2faa7.nq.gz
    ├── cb61c8b7111fc9eca13038cb083ed716228ad5c1.nq.gz
    ├── cbc04eaf5ad190ed900ef3794c9975041fd3af9c.nq.gz
    ├── cc52cc60e7da30da6a757303a213ec9baf796350.nq.gz
    ├── ce886214c52ba07366e2b22b060a6b3250fadf43.nq.gz
    ├── d0fb01b57551b15df0e4c3e25352ffcfc96ce5eb.nq.gz
    ├── d2b01666f50e800a72224264edadfa22c5408f17.nq.gz
    ├── d51de43300d17126686e31cf65b914f1499fe3d8.nq.gz
    ├── d54d2b33e66fd49dc3640f4e598cc980c651e5e1.nq.gz
    ├── d67cecdfb78b2d645daf033a2677b7fb49b4eaab.nq.gz
    ├── d71cba7310b3a2f66d1cbb7c1d5b77adbc32855d.nq.gz
    ├── d8915d38a5a1856166a602a56bfba63fd36d1806.nq.gz
    ├── d91c2bfbfe5af2b7328817a657aa1a43e6af8e95.nq.gz
    ├── d92de40546c1c967322045823c595ef80f656387.nq.gz
    ├── d9d96bf5afab1b805a4a6746dec55be5a2674664.nq.gz
    ├── d9fe211b126a7d78598a85f829b1fc7c6e0a8209.nq.gz
    ├── dcda9b1e9f3dc94464ad578257eae399f66c35ae.nq.gz
    ├── dfc7c4f2bc91e94f31fe374247d22d6bcfae23b3.nq.gz
    ├── dfc9ea40e1cb3ed7823aa2845c26c4d8237ba15a.nq.gz
    ├── e04e26f566dce367b3271eb16fcd2ebbe475052a.nq.gz
    ├── e07cc89acd4c19b63c26396d2c4e099d2cea1208.nq.gz
    ├── e11b27da6d4f4cf9aae0f07dc4c119bee8d0625c.nq.gz
    ├── e1995381060163b10f731666130d3b02282ec02a.nq.gz
    ├── e2c809816635aaa81514545a98ea972473a0e428.nq.gz
    ├── e2ee3a29043b3eaa180e72e766670998b3cb1d8b.nq.gz
    ├── e3499a62f68c6d01a14b7d29c34274010afea4ca.nq.gz
    ├── e3dec27a4dacbe85a8c145547ba6b1b3e13d6459.nq.gz
    ├── e56a1b283d8507a0769573f1d78dda1ed08a42a3.nq.gz
    ├── e5f1bc8e0d77b5fda166c49797e1eeb9843a31bf.nq.gz
    ├── e6241651789b773b025fb41b31e4ce5fb6141d36.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e71f3da9f2fec544f74e50ae6ff8ccc7a9c3728f.nq.gz
    ├── e93b2b91afcaa2c04bb23e1e216fc437b9443900.nq.gz
    ├── ea031ef23e7e158ce5f45a7776cfae1148a3f364.nq.gz
    ├── eb83baf000c17cb78c45729ab82336dfa9addb1f.nq.gz
    ├── ebd1256a02926831730d66dfe7243edbd2bbff83.nq.gz
    ├── ebdec2b67e77f31aa7755108da45994d465aeced.nq.gz
    └── ed8245a80ced50ae4418560f28e377d39d005cc1.nq.gz

7 directories, 200 files
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

[NousResearch/nanotron](https://github.com/NousResearch/nanotron)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
