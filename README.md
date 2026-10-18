# Repolex Knowledge Graph of fastavro/fastavro

RDF knowledge graph data for [fastavro/fastavro](https://github.com/fastavro/fastavro), parsed by [repolex](https://repolex.ai).

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
rlex download fastavro/fastavro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c62f6fe32505415824df1672dfc2195478187bb0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c62f6fe32505415824df1672dfc2195478187bb0
│           └── chunk-001.nq.gz
├── blob
│   ├── 004dcc54038b0ec54cacebe0005145e9ce599105.nq.gz
│   ├── 02e9345ef75b34e7a2100e23c0a750079a32174d.nq.gz
│   ├── 0376180829d8bde4f289d76d9fb8fca9cd43ffb1.nq.gz
│   ├── 069f1a3c0f8aa71c8b48112c5f84987db3b1c070.nq.gz
│   ├── 09052a66eccff21a48e5e21f0112e7efac30159f.nq.gz
│   ├── 0a493724bf3d9cd53f299a9965210c871ec0a576.nq.gz
│   ├── 0b006f76d5654383d890f0c0b8c63085361e6362.nq.gz
│   ├── 0cbc73759e5908a02e3cb61005f2bea409a98747.nq.gz
│   ├── 0dd44cbd39c2243f3fa0d7b3ce3fe31f83404fa8.nq.gz
│   ├── 0e5eda83d7ddf31ac06dc4ea12a153639c626c7f.nq.gz
│   ├── 0e8612bfa7893be10d2ddb944e6edf129e409996.nq.gz
│   ├── 0f9f0e87eea0bfa9bb3653fb013a3d3349d7a70e.nq.gz
│   ├── 11a18ce81dc2d1143da69d0543265d53e229dca2.nq.gz
│   ├── 16aa02127a7b5874e305c072857be5e498cab05d.nq.gz
│   ├── 18d39ab10c9129581ac5659bf267eb63bb2dfc17.nq.gz
│   ├── 191a30e2be8361b6be2ca6a7202b464887b93db1.nq.gz
│   ├── 1960f704ff5e67f6bdb2431566b299ba163a2f23.nq.gz
│   ├── 1a4624d0b66d9cf3a6ef2c83ca95d133da4dd002.nq.gz
│   ├── 1a4aea4e1ea650e713e6bbe28f1717f3bc654a3a.nq.gz
│   ├── 1a90ce81bba1da028c2e53017a431090f6177c2b.nq.gz
│   ├── 1aacf492dea2f3327689d1dfa4892005fcaa61ca.nq.gz
│   ├── 1b453079991670e89a57fb68c6d5fa2daaa7ea0f.nq.gz
│   ├── 1d806b415fc3b22a906358114dd82ffcc59cacf5.nq.gz
│   ├── 1df8a865ff2af488a8ba4986703fdc10591ca6d2.nq.gz
│   ├── 1f13d5d49806c338bccca21d1cd98c5c39ff64e8.nq.gz
│   ├── 208efb2c3110fc777a6ecc84bbaf9ab6eeb4d3de.nq.gz
│   ├── 21aefda78890f97f2318e34a214a59951fcb6382.nq.gz
│   ├── 2323e377266be3d0ea0b2935550c9f585ae586a1.nq.gz
│   ├── 235e8cb35eb062f96abfadeeea0a544e8cb12cf9.nq.gz
│   ├── 24651f8078d1f2fb64383a119b1e39ad81dd534a.nq.gz
│   ├── 24baaf5fa9e140d543601918c21177fe164345ed.nq.gz
│   ├── 2607fc4e272fcc85cb4d5dd0ce2b414b505b9bd1.nq.gz
│   ├── 27f509f3c9abdf4efda833db72253e7c414b4fe1.nq.gz
│   ├── 29b7dea236d7f4dd21773b08320e1074fa5ce33d.nq.gz
│   ├── 29e89227793c8292c7d9536cb40dc2bd0c919c8e.nq.gz
│   ├── 2b0610e676c1d4118d7e38e71d5a77c24e8204a8.nq.gz
│   ├── 2c19679e8a48dd260d5bad158229620d3cb81be9.nq.gz
│   ├── 2edac4d3bfb11a4a829c84bfe375fe2f6d9c302b.nq.gz
│   ├── 304f5d6a2d7a42e2589b0566b4c4ad5cf114c068.nq.gz
│   ├── 328665a5618b0ad839983856dbfaa21febc979a3.nq.gz
│   ├── 32daa89cdfa58bf9128c0f85a4807f18b5520264.nq.gz
│   ├── 330751678723efcd7879c4d3177dac868448bb82.nq.gz
│   ├── 3336bf253becc0ab6974a832dc4445c222b70e49.nq.gz
│   ├── 343a731e0916f83a1f28299e775291c1c6c73793.nq.gz
│   ├── 35855bcb6fc4a77fcad83076c7341e4edf231e08.nq.gz
│   ├── 3775f6f5a67cbbb0b2c3341b6def3201e8260807.nq.gz
│   ├── 386347a6ab213b1382d573fd965cd65f5d63ae06.nq.gz
│   ├── 3882910a6931635e377a024c6fb403ac75f4a250.nq.gz
│   ├── 3988bdfe24764847aad077f183b8ffa0eada9fdd.nq.gz
│   ├── 3ba72612ef395ce1d0732022b217fc7062b100aa.nq.gz
│   ├── 3c9f6df8298862eea05513120818c73a6fdd789e.nq.gz
│   ├── 3d61b70ff0f770b9c143afbd9551f92df5b728d6.nq.gz
│   ├── 40488a68f7142cdecbedee6299799d1cdfb9de4e.nq.gz
│   ├── 40fadf204339ef49e4d2fa4069f8b23d14b3c11c.nq.gz
│   ├── 44ff434e32dc63868f068ac1fbac6c3800b7dacb.nq.gz
│   ├── 46ec583647b1bfa138dd12383616e73a78c8a67c.nq.gz
│   ├── 478845af5297d2c453febdfec289605f44cba42c.nq.gz
│   ├── 480e06cb5833eb2ad56167a7efefb44ad591eddf.nq.gz
│   ├── 4971709fbabc75891900dabe6ccfe24ffee1751c.nq.gz
│   ├── 4a953ec6261186479946cd87220dd83420b3a3b6.nq.gz
│   ├── 4a9fad6beb9e6595ce3e22fc68e75a7e87afa09d.nq.gz
│   ├── 4c268174db2750eaeecf6312fa6c4b70a1fcb523.nq.gz
│   ├── 4d627ee0b3fff869487837ff4c478c9798af2d16.nq.gz
│   ├── 4d70ce2d0279f95630e6e62e1d4a905ae4068269.nq.gz
│   ├── 4e7a4d4cc6811e0ddd02c9eed750814610ebd4cc.nq.gz
│   ├── 526d41e50edce3377e4b37186c3ec89eb1ec02c5.nq.gz
│   ├── 544967ae8f639e3c711e003cd92febe2543c74f8.nq.gz
│   ├── 5487959bd1fb50c3662b2ff1fcde2e32f4c3be9c.nq.gz
│   ├── 5751adf0f5d5076a8521f93a08ea4d3dac169583.nq.gz
│   ├── 585d37534e60b0800d4481caa79ebe4818a23e60.nq.gz
│   ├── 58dc80750c959b140112d999ccf686142d4f54ff.nq.gz
│   ├── 5a17002ff7f61d626822e8166406bde42aed7d71.nq.gz
│   ├── 5a5a11cc3471aa1deb78ebe7b83737ea14bd736f.nq.gz
│   ├── 5a79c74f6aca98f3f6656c11154bfc5055c1ee7c.nq.gz
│   ├── 5dc07a882fb528bb1a6b4294e18adaea9fea6fc1.nq.gz
│   ├── 60782f255772feeec35b7f23a3df9bde896c8eba.nq.gz
│   ├── 63a3f919f809fa68b0b1b856759b661df0401840.nq.gz
│   ├── 647df69d8b48fab872f97e41bd331330bf0d1257.nq.gz
│   ├── 65a98c39d9b692d96f8c8b6d26d10bc978e72edb.nq.gz
│   ├── 666e1103e16014f9c3116e84b2b76b60a392ff37.nq.gz
│   ├── 675350c1d8902e79b7b17a76a7172592aeacc9cc.nq.gz
│   ├── 69c23e6a89f7804009ae983d9ad5f45b8674d086.nq.gz
│   ├── 6a48ad037578e6736da7bf15f8d11173f2af3596.nq.gz
│   ├── 6a7e6b6a382618872c1047bc773bacec7ab2e08c.nq.gz
│   ├── 6cdf940ee9a1974481a158da2deacdf4db8971c4.nq.gz
│   ├── 6d66e3a8535d01f785b05264f983e1081ca8b68f.nq.gz
│   ├── 6e0c33b8d4357be945b843498c91569dba85787a.nq.gz
│   ├── 6ea8a1d677e35db6830292327e0387c0faed5736.nq.gz
│   ├── 6f962692d6bbf42b8bd3b5beec5faecc2692059d.nq.gz
│   ├── 71adb631384977bf52fe0bc7e89bd466c4b0ca60.nq.gz
│   ├── 750f0e8c70197232fe03118b2dc068ae4c842cc2.nq.gz
│   ├── 753cf1b899854094343de20f9f95f8e58f2d8c26.nq.gz
│   ├── 766ae9c17073a0cdde2dc9d61dadf523e256aa9d.nq.gz
│   ├── 76cfbeba67833f3f8d204837a0bd542fa85964f1.nq.gz
│   ├── 771af3382b2da25cce0c0eee8d903399c00bea04.nq.gz
│   ├── 7a238dbf1013a0d4c9a6c422410a7536b9109bfc.nq.gz
│   ├── 7df3e53cc436ef117ef08f6364b6b2294e765ed4.nq.gz
│   ├── 7df463c6dea1d847cd290cdc164ce4c2502f65c5.nq.gz
│   ├── 7fac83390763bbd22a04a17fabd0aa2d0a1f69c7.nq.gz
│   ├── 800297f659dd74ea6f3f11fb4197da89052c79e7.nq.gz
│   ├── 80f05364923b011d5ec2d3fbb879db925f0ac732.nq.gz
│   ├── 8208aead6ebf2a964a4e74bed4709eeafc9affdf.nq.gz
│   ├── 834ff508d3f436cfa3465e9b09d2a6025458ac08.nq.gz
│   ├── 83f696dc9945196208d61dd07c3102b015c0bb6e.nq.gz
│   ├── 84bff934d75206f25a1b6ad8964e94fee618f9ad.nq.gz
│   ├── 854d604753fd935b261edda03ab9a58514ad6896.nq.gz
│   ├── 87168cc1462d06e4d03efc25a7366b6cc9153dc6.nq.gz
│   ├── 87c5cfade22959f860f89859c5d36f974c9ef4dd.nq.gz
│   ├── 88ed65e27e1e6dab6ebb297577532205447e794d.nq.gz
│   ├── 8a64af5757ad48bcda30598cedf55b433a6b17f7.nq.gz
│   ├── 8b3653847dae1ec3ade494fc2d04ec2a3748b10d.nq.gz
│   ├── 8cfc737ee16484d8cc084a7f44bdce65cf246a3c.nq.gz
│   ├── 8d7bd9ea9009ac0e7b880a284adc1d9d065abafe.nq.gz
│   ├── 8dca8cf43f29a8dd5fbc7b58098f49f3b234d982.nq.gz
│   ├── 9095d0093e1a8cea8a8e892f2c0f110e6397e66b.nq.gz
│   ├── 9109652dd2d4b69d8a7093f83126f4da5badf2ce.nq.gz
│   ├── 92e8d4c77e93a4ab020a51e1e1dbb9554e99511c.nq.gz
│   ├── 9436d1781b885705bdfe48236c909b51a0415ac0.nq.gz
│   ├── 96a24b64e17b9ddb3a5c2fe6c7b59f23bd83b727.nq.gz
│   ├── 96c1ac6c66c64bf027d177ab64c7c1b0a90f78e1.nq.gz
│   ├── 976652ac297cd6967e7774fb956ac3c25d795c66.nq.gz
│   ├── 978233d32cc0785846fe24d586afd74f5098e8a3.nq.gz
│   ├── 97d20f7d555b70e21854919d3647d842096ce9f5.nq.gz
│   ├── 989414e5e62373fcbd94284bb43d40e8742429e4.nq.gz
│   ├── 99cd10669ed35a59ef215916094a982127ea6138.nq.gz
│   ├── 9b4fe3adfe44df56611466b49ccc483b3bf8ebe4.nq.gz
│   ├── 9ca849ab3702968efcdf31b21a3ac08045e9d2ad.nq.gz
│   ├── 9d0ee33ab1cf1b05affb54c968381718ebcdb482.nq.gz
│   ├── 9dc1bf40afdb67d680fa5ba4c87d49912b8c078b.nq.gz
│   ├── 9e380df0335940b23bae05f2a6d0594f26703352.nq.gz
│   ├── 9e9ff93c7c9b25390d938fbbc728d01a09575860.nq.gz
│   ├── 9f1be465533820b8256381192d9c40af66669646.nq.gz
│   ├── 9f3bd56998c9466315a740a21a5d460f871b6fb2.nq.gz
│   ├── 9fe79f034dca4eefe5d61ec279f78ac8303daa14.nq.gz
│   ├── a0a15b7caa5600848b982a652690d007d49bc8bc.nq.gz
│   ├── a0b0775fe1cebe906605ac20a2e19c00e7e728b1.nq.gz
│   ├── a1d6789f70ee18531248ed5b49bb4045c746728b.nq.gz
│   ├── a3e6710963640371e054e1b53dc8244af6c27e28.nq.gz
│   ├── a45216494e6d209c26ba966cf42d8ba67ba8d179.nq.gz
│   ├── a61bacedbc0f33edb8df24e5f9fa5ebe3e688b6e.nq.gz
│   ├── a6ab48ad2cb51c6cabf698951944f653bc1ff2de.nq.gz
│   ├── a973a978ff895040bd75ae754286c795ff3c725e.nq.gz
│   ├── aabde50b827ad418fab50b9e477dcd8bd37a61a5.nq.gz
│   ├── ac1a26c9d90cfb9f04d3eea2fb98111255cf6652.nq.gz
│   ├── acadea26b0fe0eab2afbd22fcac7e240ebc333d3.nq.gz
│   ├── ae5540d364d0e799c5b56c5f01fcd8203678f65e.nq.gz
│   ├── b37990f5cb3cf14f46fcf5b8f776eb3309d9d9a7.nq.gz
│   ├── b4d841d2d258e10201cd9c9991f604fef41a8c51.nq.gz
│   ├── b5b6b8a9f7034746b2374311f55832fc342b5666.nq.gz
│   ├── b67d5f91f28d088d73dc968cef19e2848956ca1e.nq.gz
│   ├── b80f90686f89ef15972accba85ea7aa1078a7d2b.nq.gz
│   ├── bb621f2a575177bb74a39e86e7cc41fa3818b695.nq.gz
│   ├── bb684c2c5df9dd87c26846047941cf7acc61e263.nq.gz
│   ├── be2ddd38488054e48da10480ae3114d6ae158769.nq.gz
│   ├── bfc9d8bd65c6cb766ed004753bef7a151052ccda.nq.gz
│   ├── c22aad01f85f844200ecb1ea9354642841ad098f.nq.gz
│   ├── c7f7d654939ccc62dab86ff78084a3d458b06780.nq.gz
│   ├── c8f45d45a205a014cf77f3da6b3f2c4df9846f13.nq.gz
│   ├── c97fcbeb64bfac3caf9faa556dd9f40d03250bcc.nq.gz
│   ├── cbc1eeea3b180ac8bdf70b05241607c80528d177.nq.gz
│   ├── d007785597bdada1e0b5d51d6ce6e2f6d709e77f.nq.gz
│   ├── d2e5f3b72f65a5e48e5a9164c7cbc893e2d3943c.nq.gz
│   ├── d3dfd1932615474a181a0a9957a8c5512b746105.nq.gz
│   ├── d3e9a63107f7280b08b5720b614347b179a8d900.nq.gz
│   ├── d490e8e8d24d43ea1908fb899d705a14acb95913.nq.gz
│   ├── d66e713188716ec49e4d26af51db61570817ef07.nq.gz
│   ├── d76eaaace828a29e3377d5999b865fbd08a45b66.nq.gz
│   ├── d770c24c6bd898ed74aec0311791d4e174686445.nq.gz
│   ├── dab3005b1a871ad7d3770d53533e309ae7f0d310.nq.gz
│   ├── ddd7b05702c6726623d12abcb75492d120cf8651.nq.gz
│   ├── df37585ed073e167e0400ad261e5151f6c5de02a.nq.gz
│   ├── e0d103f84516f79f1d55177ce75da9fb33da95d1.nq.gz
│   ├── e14545289e22a9efdfa93466edd954618911c7d8.nq.gz
│   ├── e279dc4d79f7278bd6fbc7e050001e591c12ea5f.nq.gz
│   ├── e33a6f06611b0dd849f2db1d18da95daf910c378.nq.gz
│   ├── e45e724b104de23bca40134cb986ef7a8280d541.nq.gz
│   ├── e5834acaa90070dfe9e8ed31124fe20fdbd2b8e0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ff892023f324862e6b352e43614b79d22ece8f.nq.gz
│   ├── ea22e63ad7cfc8edb1925fd78a42789248a84f50.nq.gz
│   ├── ea4665d887c13616524dc712c2dc7fd18d7f1711.nq.gz
│   ├── ec792891d9b89f54aba5d3d5670099e5cc89fe9c.nq.gz
│   ├── ed91c9ab4fbd671762eb3159349bd3307f487633.nq.gz
│   ├── ee07c1a0510658ed9ede04a74d872fe38bf4bdad.nq.gz
│   ├── f271870fcc95f584de12fb814c5990e830df673d.nq.gz
│   ├── f357b35ac76f5e15f37e0b9125cd2821b82bbc47.nq.gz
│   ├── f410d19d1a2b8a16e6f6e4c262e5beb7fc3535b0.nq.gz
│   ├── f547a0c7ebd27010d714e07bab8eb0a246866a02.nq.gz
│   ├── f6e9d96093db9c5886885fcdbbf964270600064d.nq.gz
│   ├── f8cc93db8d90891d4a8e47ec0acb33cc6ed2ba00.nq.gz
│   ├── fca5c4a3c15da6390ebf8d2492dacdba8efc2f87.nq.gz
│   ├── fce21e253dd3e678f0d93af609cdf4825fc5e25c.nq.gz
│   ├── fd3dedab16e18a43ce0aaf271604c0e4cf0127c0.nq.gz
│   ├── fd867d1e90e4a8cf04b8729d26c129462743604a.nq.gz
│   ├── fe55d12fd96759c80e828e95fda000fdbcd7f160.nq.gz
│   ├── ff98fd5a608025d060745998baadb72a12ebfad9.nq.gz
│   └── ff9fcb555ec7c3e9a2e0bd8332128d4ea8c6e670.nq.gz
└── branch
    └── branch.nq.gz

8 directories, 200 files
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

[fastavro/fastavro](https://github.com/fastavro/fastavro)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
