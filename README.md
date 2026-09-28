# Repolex Knowledge Graph of pygments/pygments

RDF knowledge graph data for [pygments/pygments](https://github.com/pygments/pygments), parsed by [repolex](https://repolex.ai).

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
rlex download pygments/pygments
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1caade11303a50e8f6b6cb32952c7f8c49cd9720
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1e4ec98d7066246394d3275b394bd44ee206e19c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 26e29a62a0dc720a7247047fe81abd13aca36c32
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2940180dc984b5fabb008a6f1a37ae0bc1d48a5b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 389f7caf0dc0fecd78e7b93379ddf0f76569468e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4d555d0fffc914a2a4ac9874416cdaaf8f8c9e74
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7efbc3f766e6dccb5cf269469396ccbea1a7f5d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 91301c1560a83e2dce84ef282cb7cd89fb8c4485
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9162c079eac12bbf17b187013ab0c46efb7eb43f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 97a22b120e586123e8ca5d66bae5ed20ac89da9a
│   │   │   └── chunk-001.nq.gz
│   │   ├── a70c8a9ad53c3dd606440f36bd6912c37ffca27e
│   │   │   └── chunk-001.nq.gz
│   │   ├── aa1deea0045f0e630dc06edf9927e19b916fa82b
│   │   │   └── chunk-001.nq.gz
│   │   ├── b583de4794e94b4dc4c2da03a7c29f462482293e
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── bb81e6c194547874e37304681e0b44b85ee77127
│   │   │   └── chunk-001.nq.gz
│   │   ├── cfca62e6e95136e48a255e8cbffb0bbe1d98456c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── d7d11f6e6d3aa97805215c1cc833ea5f0ef1fcbb
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── dd2d2960f36dae992d8005f9cbcca00db6b68c76
│   │   │   └── chunk-001.nq.gz
│   │   ├── ee30ce132ae252bd72f3a74c86d9314a2214d0b4
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── f442d0e155a062c4a851cfb344056d8abbf8d865
│   │   │   └── chunk-001.nq.gz
│   │   └── f5eb039c39446562e140dd64b9b0c5743e933df7
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 1caade11303a50e8f6b6cb32952c7f8c49cd9720.nq.gz
│   │   ├── 26e29a62a0dc720a7247047fe81abd13aca36c32.nq.gz
│   │   ├── 4d555d0fffc914a2a4ac9874416cdaaf8f8c9e74.nq.gz
│   │   ├── 9162c079eac12bbf17b187013ab0c46efb7eb43f.nq.gz
│   │   ├── bb81e6c194547874e37304681e0b44b85ee77127.nq.gz
│   │   ├── cfca62e6e95136e48a255e8cbffb0bbe1d98456c.nq.gz
│   │   ├── d7d11f6e6d3aa97805215c1cc833ea5f0ef1fcbb.nq.gz
│   │   ├── ee30ce132ae252bd72f3a74c86d9314a2214d0b4.nq.gz
│   │   └── f5eb039c39446562e140dd64b9b0c5743e933df7.nq.gz
│   └── repolex
│       └── bb81e6c194547874e37304681e0b44b85ee77127
│           └── chunk-001.nq.gz
└── blob
    ├── 0009082fc47a94a06f523803fac371ba79ebeb22.nq.gz
    ├── 002acbcdc026ed95b5ac69f3cc1a811a22a3d3de.nq.gz
    ├── 002ffeddc6f165a77986f486abef79db2495b2da.nq.gz
    ├── 0032612fa9aa2409d1541148dc7fd8a4a630212b.nq.gz
    ├── 0032c8f5913f356b28a22e9ddd038bb5f9adc07f.nq.gz
    ├── 00346c20cdef2d9f27e39a61ee9f7bf43d425108.nq.gz
    ├── 0035c723f094771057a20308f2cb1d9129079e50.nq.gz
    ├── 004919ec7d64f44efa33c6c1752dc12a83ea61a9.nq.gz
    ├── 0049bb9164fb46193e7ba18c4642b2bf3177ad6b.nq.gz
    ├── 0056e008700744c661d28faf5dad03a74c4d53c5.nq.gz
    ├── 006b89fd3d22e38a677ab0394fd2e98db9c99aa4.nq.gz
    ├── 00745edc635354ee140a923b9ae87faac947dbc1.nq.gz
    ├── 008dc88e62c1f6541de1f47bf05712dc275a69d2.nq.gz
    ├── 00923569539aa51e068fd295a6e1c477ca0cc809.nq.gz
    ├── 009460b0b541d8cb13bea2f21ec08cc5be7a8e03.nq.gz
    ├── 00a45276ead9a43b762efb9c40c24a8fa39f463c.nq.gz
    ├── 00ae789233da7fe25e1af9db4a1e3907bb470b20.nq.gz
    ├── 00b849a62b4cc7ce9b91e397e29cb181927601c9.nq.gz
    ├── 00c7318584036c501104ad1aed41772ce0a68166.nq.gz
    ├── 00dc26f0b42407322d044224759e200b76606fa0.nq.gz
    ├── 00e80b608b739b9acfc7ca0215602cf8d94b412e.nq.gz
    ├── 00f3e7f16bbc507f5097e0fd2040ae63aa7f55e6.nq.gz
    ├── 0107431d7150c8974f88dc1286ce29d01e276d1d.nq.gz
    ├── 012d943ac332479b9052fb983b1b8683736b4dae.nq.gz
    ├── 013429228bc8278fed9599fdea1e132190066651.nq.gz
    ├── 013c85ca32280c78470bdd27fdded836e8d724fa.nq.gz
    ├── 0142d74787b0dee180f5d5522b7945bb4d148044.nq.gz
    ├── 014de975f5d5a054057f2a2491b3d7c0f618bb98.nq.gz
    ├── 0156b6dfaded98e40234e766dbaff3039fc77001.nq.gz
    ├── 015c14615eeb5ad8645c6764d2f9184f5f8016bb.nq.gz
    ├── 01656d61322f346920d4ec357f7325c88d32575a.nq.gz
    ├── 01688d572c14c5b864a506bd3d39fe216dd96767.nq.gz
    ├── 016de6cea37be964eec54e97c53e6c20227d48ab.nq.gz
    ├── 017a48e9c0bd6ae2666fe178ae8d182b6984adb8.nq.gz
    ├── 019199fdb85800a9696a515a5e7b56fa34964357.nq.gz
    ├── 0191dce0aacab7a9a876684a4f1f914b27fd64af.nq.gz
    ├── 0192d289d369d95628a888376cb496c0e77d69c7.nq.gz
    ├── 0193d0bb4e6c7906f6885a1719a2a06081c92003.nq.gz
    ├── 01a231d3ddc1245d98822d58fef68f30520d0050.nq.gz
    ├── 01ab1e7d706709e9c257ccd35b45a2bce1b8fe7a.nq.gz
    ├── 01bb089c059e3ada9b698dbda834eb4d0713c0e6.nq.gz
    ├── 01c59ef77df2d891fbd1b2f4d66116cbe26483ba.nq.gz
    ├── 01d053dd367eda3bbe02aeb26190c7f1e97c69fd.nq.gz
    ├── 01d74e9554014fc5ed78bd3a6ab218aca7c9315b.nq.gz
    ├── 01d75743abee16bac4c6ad8314e9fb27f63c6158.nq.gz
    ├── 01de00e453db747a5f4510b6a86ec0e6ab9b178c.nq.gz
    ├── 01df52810c4828c43bc04ffa4b9e290bb8dbbf2c.nq.gz
    ├── 01e456b5bc57321c1da63de5eb24bdf723e3f5bd.nq.gz
    ├── 020f6acd3669ff0e3dc88495481daedfd2ba5d16.nq.gz
    ├── 021d4501d632533ddb8d1f43fd2b7e59543100f5.nq.gz
    ├── 021fc19d5d4112d0a29a2905ad3ae7ae7da3265d.nq.gz
    ├── 022e05519af3788e1b0ab39cce98c03c4415d257.nq.gz
    ├── 022e6c55a93c093f661ea68115bc43167cce1f4a.nq.gz
    ├── 024a461ef86d0052e3a65b0bbe92f2552af3f288.nq.gz
    ├── 024ab8d59c107a1e1f47e4e65d7729fa90183e7a.nq.gz
    ├── 024bfc01d5c6c7b925d02cbffe953fbed78ed604.nq.gz
    ├── 0269384fac1ac51eb6c0fff6c0d2a380a7b3b887.nq.gz
    ├── 026ef22acd6c0ce61dfcf3b828afbcdbe87b25a1.nq.gz
    ├── 0270c939678455b273e2c1fd60ff36c30d159ba3.nq.gz
    ├── 027175b14548198ea7608900b1bdad217c3b10e8.nq.gz
    ├── 02768c5c9b99bc610fe53065c86f4afd1fd4727d.nq.gz
    ├── 0289e58cf0b0878054c4587f0dc8eae2fa3f67ae.nq.gz
    ├── 028fec4ea49c5ba2eb78fb032fb98c886f4de90c.nq.gz
    ├── 028ff6f375ee87856391efdb19969d68e840ce2a.nq.gz
    ├── 0290b7a17c5d419397e1db83f63e472b8bbd81bd.nq.gz
    ├── 02a8f56c2fbfde9be0f9e2fca1e1b3fadb0ead92.nq.gz
    ├── 02bb9fef362ed6100597d1a8e77e9f0772e4948a.nq.gz
    ├── 02bd665709f5dc65e401cf4ce1ede383aea2cc19.nq.gz
    ├── 02cb3ff14d881e6f046358505159be7bb2f2ee04.nq.gz
    ├── 02cf836e8d3743569353b725f764208b7e0503f2.nq.gz
    ├── 02d16508f725f020e19ab468095bf0d2586d3890.nq.gz
    ├── 02d3e779dd936263a56b8290a859ead58c023933.nq.gz
    ├── 02dab490e4eadcb721e358a40bb3aaf03ce0bb08.nq.gz
    ├── 02e5b47b7b1e098b043bddababdc25fb1384867c.nq.gz
    ├── 02ea6e964c37e233b40fcfce845fd98cfc785d48.nq.gz
    ├── 02f3bb0d0a83c86fd345d9e12d27cc86bcdc5ff1.nq.gz
    ├── 02fdf4812b79e663447dcca9063f688c04b4c66a.nq.gz
    ├── 02fe8f731c9d8e911aaa5029467aca61e286302e.nq.gz
    ├── 03220697ceb907b80f24dac40b9700058517096c.nq.gz
    ├── 0323d140925d97b02da198d58769e2ef504ac015.nq.gz
    ├── 0324e3510df53ce39321c2d291b0c87a560770d8.nq.gz
    ├── 03328477459085180afc57abc8301cea3f8c1f66.nq.gz
    ├── 033c219b98cf9fc2724208cacd13d025656741d1.nq.gz
    ├── 03494fb6fa6c8a6d844a46ccad8251ee6b766c69.nq.gz
    ├── 036a2120bf953cc41ec974d5ed2fee5c9a450404.nq.gz
    ├── 0381f19f583c30a1579acd58e257784e5f990f6b.nq.gz
    ├── 038b96bf562470f3f0f7dfccfe7059ecf4b52e80.nq.gz
    ├── 0391507e389f72a33c446feb3d675f8a6e950364.nq.gz
    ├── 03ab6a0611c3c1e97b55a68f6eb5e2fc770d03e2.nq.gz
    ├── 03adc5fd0f335ab0c2d9d2f8af10357a78c14a40.nq.gz
    ├── 03b7b1b592e88c154d7450d53516359d37f8cc86.nq.gz
    ├── 03befb0956a48c67363472f7a46bbd6527b3ef2e.nq.gz
    ├── 03c0d0496b7a7bf640015c518045da2287b0d282.nq.gz
    ├── 03c34ae5919b28cec9994b2bddfdf60214260ed2.nq.gz
    ├── 03cbcc99d09151d22d2cf2974a2e8fa1d0c055c5.nq.gz
    ├── 03dcffb8c8c4af30686618d90592c54a90b87481.nq.gz
    ├── 03e1fe9877b0804922ef732cd00152a6aaa105a5.nq.gz
    ├── 03fc268ff606ca88d17a1dbe752f536d8afa738a.nq.gz
    ├── 03fcee390d97e7816144ebec7e0883fab0aecb5d.nq.gz
    ├── 04077ec6e53c54720eb00e3e3894b1b9b4b206d3.nq.gz
    ├── 040b908ab1f825aa647542393b8ca5519501d9bf.nq.gz
    ├── 0415ac6a7ff532e3e7e653adbbd986dc5dda4f95.nq.gz
    ├── 0417a1f7044a336de543133206760cdc56c8a9c8.nq.gz
    ├── 041bec176633cfd1d2b10ef3213a77776852906a.nq.gz
    ├── 04223c56453cc6badd9835ecc0dda51b31e04fe7.nq.gz
    ├── 04237f70d6dc8905e9cfa8c127aedf7ecb203b4d.nq.gz
    ├── 044f963296f7c6a991d8b2423a1bc81c9d3832bc.nq.gz
    ├── 045a2f1559de70c6bb4f2fee8fe74376c331ba07.nq.gz
    ├── 046a444324fade8e0677512587f73dfa04e2830a.nq.gz
    ├── 0491ebe85c3feda99471e4e97e5ba7153b8ab67f.nq.gz
    ├── 0499b6fa754953f00d6765f56496898c2d8e8fbb.nq.gz
    ├── 04c7ddfbb04e3f667eda8592cfd8e5beb1ee6a47.nq.gz
    ├── 04cef14e99b309a4e8c02d73956805a58efaf897.nq.gz
    ├── 04d24bcf5b56cd24d18cfdbc9a53a72f085a29b4.nq.gz
    ├── 04dd879a0a59c8c2bf05898562692f09a5a3c260.nq.gz
    ├── 04e15c8c774088546572430ef158c480f4667181.nq.gz
    ├── 04ea2540ac79da4423c56fbbdf247885e4b2b2f8.nq.gz
    ├── 04ec326281e383517c833b7fee71115033c42c45.nq.gz
    ├── 04f294194e5b8dcbea6e948aae2ad51edbc54bf9.nq.gz
    ├── 04fe57292f2703f395ba1546b938f92d59f093de.nq.gz
    ├── 050011a97554f296b7e508daeaaff1f814fecdbd.nq.gz
    ├── 050e56a6dfae25dc1e3f191425a55e6388d6ccd4.nq.gz
    ├── 0511c5dda66ff236a6146e59ba00759660e6ee45.nq.gz
    ├── 0512ac436adbae2714d96e197672391409010673.nq.gz
    ├── 0525694956e8d7bb53163123921be1105825632c.nq.gz
    ├── 05352c7bd2629e802e191cfb6013fe2d02acec7e.nq.gz
    ├── 0536b948556a030567e6e1f8b3a0a8709d6fb989.nq.gz
    ├── 053cf8741ee5b83fb6416fdbebe41baa1308a14a.nq.gz
    ├── 053e554f7643c53eaaf41f748377baeea1d5c190.nq.gz
    ├── 0542095dadab49b302850f0ae32d98d184cef818.nq.gz
    ├── 054739acd98dde739a985a9621becf0091eae404.nq.gz
    ├── 054f5b61e56a53d2bf04d2bba2fc15c1fa85566d.nq.gz
    ├── 055423a4694c3aa9ecb5f3ff6e64d17d6487be93.nq.gz
    ├── 055446cfbc89ebad9a29566dd14c695c3f31c3d7.nq.gz
    ├── 0557f2f3c9b35bfdd6f138661c62bf21af6457a2.nq.gz
    ├── 05a39b8db682f63beab43d39d04c999719595773.nq.gz
    ├── 05a6b573e92b54f5894af1a56669669a67e22f88.nq.gz
    ├── 05a6c3ace8ce197325e2d8f8b484ce59611a638b.nq.gz
    ├── 05aa2af42ba96d7228a022a35753ff28ffc8eb41.nq.gz
    ├── 05ad900b29f75fb51eaeb30e4b45e24ab369a4f1.nq.gz
    ├── 05ada4f3acfa9eff4f724060122d9fa303b2b7e2.nq.gz
    ├── 05b01d22f4bdbdfbffa23db1ee0c5ec6270b7f31.nq.gz
    ├── 05dae1bc35b1ab4f8064de42da8c768b577b809c.nq.gz
    ├── 05e90751a25053966abdafc28ac2f767a881614b.nq.gz
    ├── 05e95e6a5123a71c0b1b7e33c19523f590c66600.nq.gz
    ├── 06096930541cb3049aa2ee7529770c020f0ddad1.nq.gz
    ├── 061192312d11707518cc9fb8267b5c75ce75d258.nq.gz
    ├── 0623b055056ebd67670a09720e93c4a2c91b06c9.nq.gz
    ├── 0640cc5c2df8b94e96b5def73c45d29c810dcc33.nq.gz
    ├── 064167ffd4f4a0d30111106cade6ec67876d6032.nq.gz
    ├── 064b1ab96c435d5742291850918ad696eef80534.nq.gz
    ├── 0657c1f5c62893266f1de624a9b974378db69d18.nq.gz
    ├── 06714a57e1a69b4bfb90fbee4a499e99ba6d5a7b.nq.gz
    ├── 0673e4a161da992e88be6686a021f9be207dd4c9.nq.gz
    ├── 069c44fdc7416b05c96c983db0a2cf578036f7b9.nq.gz
    ├── 06a74c3d7683f9dd7a2ab7ad591f92b7e780ac37.nq.gz
    ├── 06c2e861f544d9d1f8c1e7a31ff8611cdd698f30.nq.gz
    ├── 06c82ccfedb0cadb2cfd86d40e8974cf6dac5039.nq.gz
    ├── 06d48d916b7a3dedfcd2693510828b6b8b2a92e8.nq.gz
    ├── 06dc098d68ceb265eb377470d0a88625c6ad2b69.nq.gz
    ├── 06e3245d04b3ac66b5604987547a44e3ff78c0ea.nq.gz
    └── 06e3f0076d055a1a82f2c79552e0370b987e6b30.nq.gz

27 directories, 200 files
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

[pygments/pygments](https://github.com/pygments/pygments)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
