# Repolex Knowledge Graph of YannickJadoul/Parselmouth

RDF knowledge graph data for [YannickJadoul/Parselmouth](https://github.com/YannickJadoul/Parselmouth), parsed by [repolex](https://repolex.ai).

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
rlex download YannickJadoul/Parselmouth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b5e97e77e74b6f0a064f1bf2743f3067bacc9ac0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b5e97e77e74b6f0a064f1bf2743f3067bacc9ac0
│           └── chunk-001.nq.gz
└── blob
    ├── 00e4d6871d1cfeca3943b6b677a77949bb35a2e8.nq.gz
    ├── 00f1a5ea161d526496005bb37b619562c00c013d.nq.gz
    ├── 015491594a88a247f44ea2751d2968085858d29b.nq.gz
    ├── 018673baa9e33b678970f7cdc9c8fd20bc650886.nq.gz
    ├── 01fd1746e0ca156928f5298484372656e3411c0d.nq.gz
    ├── 020988c6713d99ec0188be147084ccd21379c7b6.nq.gz
    ├── 02c6da6e1a88b492b021ef6f2b504181b2c9e05a.nq.gz
    ├── 02f221bcff8798a5abe5f1deb35e88a807401675.nq.gz
    ├── 03587443cef352f7ceb67272162a4e28ba437aff.nq.gz
    ├── 039b877ced716cd1b61010b19e111784917aafd3.nq.gz
    ├── 03d2bc5c10bb8f776763d4f1a3f816495003e6ed.nq.gz
    ├── 0462bf4570d4c2edbeda76e9f44c615b0bb17734.nq.gz
    ├── 056ecd70eb0c50c2fee79b245c2e5540de02a6f6.nq.gz
    ├── 07146f162d306bff7f075b1175716a02c56032ad.nq.gz
    ├── 07d110b7abded287bb1468365ea74aa788e312bb.nq.gz
    ├── 080f76155be1062da6db73535702aa4d6431a1d3.nq.gz
    ├── 0875a751fd9f73520c0a8a2c5b73f5e1a2d477f7.nq.gz
    ├── 09552600a8a27223105ab39fc78906a0601e3de1.nq.gz
    ├── 09a6aaee5ee63f9e10d9d5b296451431aaad16e5.nq.gz
    ├── 0b237d487d263670ff20dd7e1a3b4a7e87e2c604.nq.gz
    ├── 0bf9e00fd025003f5185627d78bce07cf9656e20.nq.gz
    ├── 0c1603c2e16a3729ccd59793c3c4c76d68f5b8d4.nq.gz
    ├── 0c5b04bac70b0389a59e0b4ccd5483f692cccb35.nq.gz
    ├── 0d57f4f079c33f35cffc75c5304eef33bf160137.nq.gz
    ├── 0d8bd0e4d6064fac174451e04a708434c4210e94.nq.gz
    ├── 0da9baa9709854391434ad8def166c906dea955e.nq.gz
    ├── 0def9e9176ff07c6872904508ee29fb271410833.nq.gz
    ├── 0defacaa6e3e0412f44adcd0a0404f73d4b4f6d8.nq.gz
    ├── 0e7c3b07d716534572ef9eef9e4711722aafe8f9.nq.gz
    ├── 0f46a8560ff5bcd561972bd6e18ecd406f4a4ff2.nq.gz
    ├── 0f9c9254d4051da342212516874375d063c46f30.nq.gz
    ├── 0fa9fbab563a0370d8eb480fc3a755e6f4f42b9e.nq.gz
    ├── 1041d9e3bb94d68595b5962ea78805bf5eb66b8b.nq.gz
    ├── 1071809fa0fecf7c28d3356f37363266e9128b81.nq.gz
    ├── 10a0566cd496eec1dbe425c7f03f578a5236edd4.nq.gz
    ├── 11c04d28de59f87861bcbfda995d0585c07bdbd6.nq.gz
    ├── 12ccee6cf2338bfe13b97c550e81430d78b7c0c3.nq.gz
    ├── 1331b722f91ed6ca700ff210b11317ad44d73552.nq.gz
    ├── 139568fc8925fd7ed74d22076e5b39196028ff55.nq.gz
    ├── 13c73f119bc8657a3d8273480f8e8e2dce8446bd.nq.gz
    ├── 14417c1fdfdb3af16ef717d90a078f5c9b8468c3.nq.gz
    ├── 14a72add86bd5a8dc2c7f430454b8f63e5958762.nq.gz
    ├── 15266f425b2b253c388bd807df5480f2ff086f61.nq.gz
    ├── 181ee477135fe7c0741f20e0f187f8190a6f98dd.nq.gz
    ├── 1831f9a9643766087e447184bfb49a4eeba651dd.nq.gz
    ├── 183ebf625f5946be84a41b2944f322eb7920f52b.nq.gz
    ├── 18423f1679c4361289bdae93ae665075fbf8323e.nq.gz
    ├── 18a3d974b1ea86cffbf1a7e5998bb728bff5f14d.nq.gz
    ├── 18d9a4177940312b78acfe8b1225ae05e76d3b83.nq.gz
    ├── 1acb42b4d8e0427da4f702f16432b7c13d64cea3.nq.gz
    ├── 1b091615da5d4632d15c325b1c5d0a1a5aa4d8c2.nq.gz
    ├── 1b3665e528c93be04c57f417368ac0d633ee744b.nq.gz
    ├── 1be0655dfb00424415501c6b57d08af765ebc8d9.nq.gz
    ├── 1c4fad6e3c312c290dab1d936c2edf6b448cdd82.nq.gz
    ├── 1cc10c876841903aa1eaa555bdc867c796d69a95.nq.gz
    ├── 1d556ddaadebb1b4b5378a60af8fee0849378e5f.nq.gz
    ├── 1d6db21611d89f4722235f2d5e52cc6f4885064b.nq.gz
    ├── 1d989522005a3c44dcaa54190167062d684f26aa.nq.gz
    ├── 1dad8be8fabfee956dbea7f57626987be7e14e7b.nq.gz
    ├── 1db3b1f57ba851931586823cbf9d7f924951ebcc.nq.gz
    ├── 1dfbf953290a2fc0c452eb9caff809a4a37233a4.nq.gz
    ├── 1e5d2bb876d17f24b88b19ddb525d4146869944b.nq.gz
    ├── 1fbd7141c36258f251d03a733efb782f121823ee.nq.gz
    ├── 1fcb10ea83eb016419ea72eccdc2e6b616ad282a.nq.gz
    ├── 204aaf989ff6225543efa7b9fb85fb7dbe817b1b.nq.gz
    ├── 20c19f8bf629251d2ed1fdcd444ca7e641538526.nq.gz
    ├── 20e743136f3f2efea7deadf3e08c5b104c22a7f3.nq.gz
    ├── 20ff92ae40a3c509d97802295a99a2519092bd0f.nq.gz
    ├── 228d361ad19a22cb83ba2293959c93fec86e5a53.nq.gz
    ├── 22b98fe650b9a8f845acd66d3cfceecbc9f0033e.nq.gz
    ├── 23232e1fdaed10aa8e6e7e8083d278403ac041f4.nq.gz
    ├── 23891f276380d7b0346766f14f3d3405f2744f14.nq.gz
    ├── 23c7fb70249820f3e83c7ef1de75309a06997f79.nq.gz
    ├── 2420f89c48c64937313049ce6488f54a03c83268.nq.gz
    ├── 24c263373b3036d0477a8e9af333c46efc766b6b.nq.gz
    ├── 25582fb550cfbaf5ac8942b699a2c019ba90a6d5.nq.gz
    ├── 2585b18582383960d9a13d9e2010ffd3fd7f5c5f.nq.gz
    ├── 25888778cb1063805253019e640089c175b4cc3b.nq.gz
    ├── 2621e2a1a61572220dcd17d39a24374f336ae5b6.nq.gz
    ├── 2705f0ccd4da730e2ade12a16d9fed945f044694.nq.gz
    ├── 27491a669e60f7485d55a830ffe3a007ebcfc9c4.nq.gz
    ├── 274b7558a9e80cab3cc390b03dd303eb37533f5d.nq.gz
    ├── 27a2712af2df7835b414597dd065e3a6d6bf46bb.nq.gz
    ├── 28755b6660618e344e304eadcab5cf2b8ba25c21.nq.gz
    ├── 28eee2e1b27ef9e1daac57285bc6e582b1f4e8bb.nq.gz
    ├── 293208327568e826d0996de35528bca79bb5bad8.nq.gz
    ├── 29f45da3773faeba36b685c5521a676d07d31985.nq.gz
    ├── 2a689d405004c7811771b3607e4f5213c43964ca.nq.gz
    ├── 2aaf9331fd14d797315779a7949017cce1651655.nq.gz
    ├── 2de9e31bb363209ae6b557397b0931f591f56c4a.nq.gz
    ├── 2e45fbd1903431ea4c34fac94d1ae4b9d76f441d.nq.gz
    ├── 2e65ccc0a9cf63c98d996b664a8d39a762fb6ddf.nq.gz
    ├── 2ec293c1b75cb8232db80984bc00686949a396ac.nq.gz
    ├── 2ee272ceec803616f146241fea4f40a0af6179d6.nq.gz
    ├── 30cae4a57f56799313367453b9564847973f2e6a.nq.gz
    ├── 30f3b38d666801357f5445f1d10334115dedae82.nq.gz
    ├── 311a168d3f723ae4efb4ce16a6a2868cfe85d641.nq.gz
    ├── 3171ad517ce7d692fdb351b534aa4c3275c57457.nq.gz
    ├── 31b14e53dd60db67d99416d420361d77c364a383.nq.gz
    ├── 31ff683df9a5820b0ddc1ff747d21a0a664713ff.nq.gz
    ├── 322e9bb85dde51b461c2351177606b81a350a683.nq.gz
    ├── 3233cab633427aa0bf6fa47d5e04a717f0d69930.nq.gz
    ├── 32847954745cc9d647c3f465baacedd53e550932.nq.gz
    ├── 3286da84523f968f5c0ab7e79e07e798012f259a.nq.gz
    ├── 330017544de22232a9a929903e9062e94dafd71a.nq.gz
    ├── 33d78fb4e6dc7bd1b99ed5647d33660c80d064b0.nq.gz
    ├── 35bd477398ebf66711fca6bca3fd0ff833fd6a75.nq.gz
    ├── 3605aebcf354218aace7cc95f33da300b02615f1.nq.gz
    ├── 3660f4c42f9b9e916b94d425272acce060d0f473.nq.gz
    ├── 36d488fee08b2dfb716937237dbdc74428b79679.nq.gz
    ├── 36fd0af0a243ad9892bcf08b028383665a82b930.nq.gz
    ├── 373b67bac8e6c0d5659b3ae508fd50c296e460e6.nq.gz
    ├── 382d1e070689caea434dff43156992c6bf525b53.nq.gz
    ├── 38c6bee9e6808da26990b2f943cf8cf7bf73fb03.nq.gz
    ├── 38df0bcb8fbaa58c454d2ee05cdcd95d6bcd83bb.nq.gz
    ├── 39a488d0af07b5c6f3206d506b6bd1aed3c499cf.nq.gz
    ├── 3a5e8445bb909bff5123af86f6eab22f21aebad1.nq.gz
    ├── 3ace4210752941865154880daf18ec4958f21481.nq.gz
    ├── 3ae234d6decbfca306db6a19ab30a46433569750.nq.gz
    ├── 3b8c120263c6b0f18bd764408d5e79857986c062.nq.gz
    ├── 3be1ae545a71f988af71e83a019bd5dd41a1ab31.nq.gz
    ├── 3c0c3ccd96b6882d3ccfec0ccbfd8e96adf1e5bc.nq.gz
    ├── 3cdcf6a660ec3595b1c1873a4667382dca27e4a1.nq.gz
    ├── 3d65b6c1768dba03434b8bd7bd79be83e88655fb.nq.gz
    ├── 3dbc767a878f06e5602f778f2172772e8d784f05.nq.gz
    ├── 3dc3af7b9d5d868a2bb1e2005b08e01c8863751d.nq.gz
    ├── 3dcea89faa02e64cf3680f1c213f4838bc6db038.nq.gz
    ├── 3df35e76374dd3b1e1f28a7e38504ea72fdfd19c.nq.gz
    ├── 3e31cb9975a926f5ac193fa69dfe6f8ea5c0cf64.nq.gz
    ├── 3ea39d99d53010e3a2f37fe6fd7d7df8e858ba44.nq.gz
    ├── 3ed7387d7303360b376aa8dd88c9fca9ace3c51c.nq.gz
    ├── 3ef78c1179f5b533c3ba3f637420c8125d632a7f.nq.gz
    ├── 3f1c9c19278f573e31a8d6d5fa1202ad6ab55ba8.nq.gz
    ├── 40bb45d78d2c92f99cd846fa0d1790554b0d1a57.nq.gz
    ├── 41d11f15e0510065329caf4f12420a79011a2a8a.nq.gz
    ├── 42dd90ea312869edc6d53c13d877e211053c1375.nq.gz
    ├── 439716a77fe9faca818fb4849c38a4310fabb559.nq.gz
    ├── 43af7aea160f69cc9b698e28a06399f3dd8de25d.nq.gz
    ├── 43d2e3c2cf7fe976e7d1b2661515314db0cad41a.nq.gz
    ├── 4414a12ee467d53de3e32e262770d973d8acbac3.nq.gz
    ├── 4490ed757928ce7f75c8c534127e7a97f903491e.nq.gz
    ├── 4505f03cdd309fdd1a22f826dd7f089f06ac5ade.nq.gz
    ├── 4523177c24c27f6d0bda6159581c5765646006fb.nq.gz
    ├── 45f2a1b827e82bbfa5270b3e3a023dc238a2c15d.nq.gz
    ├── 46002ac9c30ca73ac0af0fb216d6a3213505d828.nq.gz
    ├── 4600ca767fc4911742ed6567a785d3157105f8e1.nq.gz
    ├── 464d00b474f8aeddac0caf239994a141a1241f87.nq.gz
    ├── 4683fd3e18135bfb806ffae41044978261300164.nq.gz
    ├── 46f50758e19dc5201baea7eba9b5c2ab4fb276a1.nq.gz
    ├── 47421683077dc0c8cae84e16030cb90a8d0c82f1.nq.gz
    ├── 47519f518251f736192d358d00a0259c9993e6b0.nq.gz
    ├── 481325530cffa079b22a1b9a3171aba8fb1265e7.nq.gz
    ├── 49f8972dff7a62c20717e7d64f0a2a78f4d726e7.nq.gz
    ├── 4aacdb64ba2c0b6dd7ddbf41989ab88796ecc20f.nq.gz
    ├── 4ad8f0cf0c2cd27a3c02ed659b73c1673fa12bc6.nq.gz
    ├── 4bb5bf87699a35905b5841a0133f9bd2b5f8a2fd.nq.gz
    ├── 4c145d57ce5fc298b1cdbd9456fc92c1d1ea5256.nq.gz
    ├── 4c32561d6b95b9715753bc50a1d6570bfd887a8d.nq.gz
    ├── 4c4bf3d115009e96dad3c27ce76cb7b4e448a3ac.nq.gz
    ├── 4c65c4818c0bb9bd202adfa7bb3f681dd7825645.nq.gz
    ├── 4cda23d98e1084e87c3219d3c42408be15fdfd1d.nq.gz
    ├── 4d7a554a7f42e99b707720d4ef8c04d9e7990f97.nq.gz
    ├── 4e2e8ca3a04a072d9adfdfa4bb98f5c221be10ea.nq.gz
    ├── 4ec00303f14a0024c0870cf7a8f910b86c284b15.nq.gz
    ├── 4f001af82d7471b97f9a776c7633dee7f7bb6269.nq.gz
    ├── 4fc0ac1d2be1034785f363eebd6fac8488a8f037.nq.gz
    ├── 50abcfbf4b5203c50785c238d35b629161d5f788.nq.gz
    ├── 50cd8be933104ea9da682a676d687c2037bd3f47.nq.gz
    ├── 51d04e736c2b47d44d354743d9a0ca61a7af6254.nq.gz
    ├── 51eb2b19460dd7cd97209f30196e92acfecf87cd.nq.gz
    ├── 5219808639e8f00f3074c0122b8c9e4941cb7705.nq.gz
    ├── 527c40cf38be9203d20a56c8b8bb1b8a2203621e.nq.gz
    ├── 5296d07a13179526c021eec79c0268ece3214bcb.nq.gz
    ├── 52c5ac93561331143a9caea14d6c0f008216b4e9.nq.gz
    ├── 5346764e92a298b9dca1f1a82fd2553e09d2031d.nq.gz
    ├── 53d71e78caea5f6868ee304f7125ea83e733b9af.nq.gz
    ├── 548a01bcf017abbcc46437941f28b108e2a56ec7.nq.gz
    ├── 54d39083108a57f37a583097fe33a59b7261e49a.nq.gz
    ├── 5523144bc7ade87bb76bdd13d9da12b365ce7a32.nq.gz
    ├── 56471df3e8cdd779d18dc60ca253b1a896e06a9e.nq.gz
    ├── 577cecebf51eb503a4cb755dfaf7d0a5a60b4478.nq.gz
    ├── 57cfc1106eb12ffb19e38ca0174b2232c197be9d.nq.gz
    ├── 5802d61b3a494b73b499ef7b228d8089f000bf06.nq.gz
    ├── 58d03c87e7164d83d78dbf20fed46f58e25e0343.nq.gz
    ├── 590d31fc9c96c4ca8f54648aef72afea8884d890.nq.gz
    ├── 59555ff8b6b88d2758c170c383e25f2bc41a3861.nq.gz
    ├── 596c8c378a980c10ea0676a45c29155d6681406a.nq.gz
    ├── 59c0702412ef3bf2bdb2a65b9e390f0c4d8a65ec.nq.gz
    ├── 59ff18b6bd4fa94cf33fb0799a822c0fb3a28d34.nq.gz
    ├── 5b516b3e4c0b02e356450610b18db57f195691b3.nq.gz
    ├── 5c13041733936d771fcbf9d2bfd827e60f5a628d.nq.gz
    ├── 5c3c57e7144c744a840b16a4c96b78009d11c3e5.nq.gz
    ├── 5c3d5a45f997ecd416ed6f30c301e0b106723644.nq.gz
    ├── 5c671fa8fdc4735bb4c4829a1a0ed3c6c2fa9560.nq.gz
    ├── 5cc34db2c249581d67f2e03d6c455088d70f21c3.nq.gz
    ├── 5f12fbdc282f68bbe51d4d1bba3feb5427c17556.nq.gz
    ├── 5f574fef3f82c42d109964faf5305b6c729bd015.nq.gz
    └── 5fd89572201eb78a9011f0f9a0779faf5384af68.nq.gz

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

[YannickJadoul/Parselmouth](https://github.com/YannickJadoul/Parselmouth)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
