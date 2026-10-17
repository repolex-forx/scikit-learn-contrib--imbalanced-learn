# Repolex Knowledge Graph of scikit-learn-contrib/imbalanced-learn

RDF knowledge graph data for [scikit-learn-contrib/imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/imbalanced-learn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8504e95f0160f61d1b617ca66f779646d2ee609e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8504e95f0160f61d1b617ca66f779646d2ee609e
│           └── chunk-001.nq.gz
└── blob
    ├── 00a0ce599c2940f1be492ef963e3291e2c0872da.nq.gz
    ├── 025f7744a0b7f76d42529dcbaff8fe948e3d529b.nq.gz
    ├── 02c921a9a14504e5afecb77d38cb07c1d8c217e9.nq.gz
    ├── 0311ade92c5888dd8af6a3127706bd93e3a520cc.nq.gz
    ├── 0448da5af550e4c4bc4b404fe5454ac34aa7fdaa.nq.gz
    ├── 0472df3deba0e8891a51c1741d8e3c89a0895d74.nq.gz
    ├── 048ffa14cb557b7dec23e45ab7f88232088e41d5.nq.gz
    ├── 060ac8cbf6166f076d1bfff69632e911a9764394.nq.gz
    ├── 0663e399e318257c9ff4729fa91afadfaf85ddc2.nq.gz
    ├── 067569ee605876ee7bf03a2f212d31b9bfb18fe4.nq.gz
    ├── 0a12ca831ff3e4fad38006ef08029252c765c29d.nq.gz
    ├── 0d85c4dfeacadcad0a2221d721ef8ba95213591d.nq.gz
    ├── 0dc6e5a23ed06221f20643392c17b9ea0f6b1371.nq.gz
    ├── 1011d142b0023578c43fe04f57eae6eeb61f258d.nq.gz
    ├── 10a1ced616066abbb984b642ea53f1fff3fae4c8.nq.gz
    ├── 10a968e78739c06842e25a65478931d7af8afef4.nq.gz
    ├── 110f2c714e2a546b75f5ccf79b2ccf770e38ece7.nq.gz
    ├── 129343b767fd60c9d0c12371297601bcc56e0475.nq.gz
    ├── 131f9592971966a0472bc0a905b541a042938ab3.nq.gz
    ├── 154fd937d6dc7e318ef5aef492b53f561d331925.nq.gz
    ├── 157c35a0b0fdd502d0464b57af7ba78cf30897ac.nq.gz
    ├── 1673e2111200f54034e792e0074f23aff13531f9.nq.gz
    ├── 16acc318232d490532028d2949941b9d3771f8f5.nq.gz
    ├── 1b1d94e91b1690072645ceeccbe932705e545f44.nq.gz
    ├── 1b37978c2564844ffd2b27b5a10fa6dd104121f2.nq.gz
    ├── 1b430535b8f9ec87674d6458971598267b7c1f08.nq.gz
    ├── 1b810970b2c8ca0a904278c83fed9326ab4f4101.nq.gz
    ├── 1c76a06b271a045e31603373351b40c9947e79dc.nq.gz
    ├── 1dba0cd2ffabb4cdaabaf42cf39c1672dda33727.nq.gz
    ├── 1de9b7f51a31d67ce2869a7f9286dc3aa531e0c8.nq.gz
    ├── 200e88d97c62b0d59a30703158f094fd13b1b64a.nq.gz
    ├── 219c3e7f11ede3ccda3820396ff323de1ad6c357.nq.gz
    ├── 21fb47db2582d4839df9d6744dbb73da0558d71b.nq.gz
    ├── 2235bc12caf73d6255bb64ea6b46157f852ce89c.nq.gz
    ├── 233230381af9936df86d0a0f92f0e13d753609a5.nq.gz
    ├── 238786314069670d17afe9ad4e64a0453b7cbf25.nq.gz
    ├── 245139a025cf01a4fab9610d51d653f110f160ab.nq.gz
    ├── 26fa8adbffee23ad65f6bd28550ea847211884b7.nq.gz
    ├── 279531468aa0b40f334dfea43f00d79184af1a21.nq.gz
    ├── 27af25f8affb22b8a3fbdc87408e1acf6abf2746.nq.gz
    ├── 28d428e5ad3c07d62dcc1511d89ee902bce37a0b.nq.gz
    ├── 28eb3ece1d8d3a0050be952714ab328875e2c77e.nq.gz
    ├── 29ad49fb161b0eb8a0c511ce5e6a1e7ed57a63dd.nq.gz
    ├── 29dba0dc2f197110bd8d98dbcc7a35b97be896bc.nq.gz
    ├── 2a022e27144338c1df8d6fd74f693854653acd93.nq.gz
    ├── 2ab403d0b32d463bf458709ec3262e3d3f3ce989.nq.gz
    ├── 2bb23f3745305ae7f13a040ab411fdbb0df69683.nq.gz
    ├── 2c6752890c0df24f4d18c6a04572c05cc2e02cd7.nq.gz
    ├── 2cd1fbd83af47c308ad9fb4a839008b194064bac.nq.gz
    ├── 2d36622cb7e55bf87691be85e6cebfebd71b0272.nq.gz
    ├── 2e66a01b1e52951b69fffaaea807d1ab3806a961.nq.gz
    ├── 2eca14029405816dadb920cce31836fb3accc1ab.nq.gz
    ├── 2f9c48b91efde058be55eb35879c3a79b7161d13.nq.gz
    ├── 2fe8f26e29ed417545d21507451e0afc907830e7.nq.gz
    ├── 319ed3fc10f53f31a0029023f85290386a2aa05a.nq.gz
    ├── 31fad3ebbae3eecb61a0d0444b4ecccd391eae6d.nq.gz
    ├── 321f5e99c48a269ccfab2e2d7507e98ff96a257c.nq.gz
    ├── 325367769a7f99b562ab53b4dd254c31804f2695.nq.gz
    ├── 3376d0ca086597b847d0c33967b4f88b7ff77999.nq.gz
    ├── 3778ee94cb4d4ae227e39f77583b53de5aea31d3.nq.gz
    ├── 38f9978862615edb9955e9b47ca508ea221ce70a.nq.gz
    ├── 3bc975b89955ea4b70f36f66cd56499b52007a42.nq.gz
    ├── 3c0894dc9873a407610008578ec87da420300425.nq.gz
    ├── 3c22dd7c574dc50475d657ba44f2ecee2188cd0b.nq.gz
    ├── 3d0a6efb0fd310b17e1a0675e7eb2f58fc122952.nq.gz
    ├── 3d70980454c4c2348210b9a3d1927c1be8921a38.nq.gz
    ├── 3e17c58dccb9f55fc5593eb961ba6c68c781cc0b.nq.gz
    ├── 3e82dbb3c1ca69b9f68112264779366ea1182765.nq.gz
    ├── 3fd0719a626e2d2c436d0b672894634dae397562.nq.gz
    ├── 41acac7edf62b32208a9036b0d8931d77bada6fa.nq.gz
    ├── 421f1309802f8eaed174d90b362ef90714ef5f65.nq.gz
    ├── 43517cf3b02105df80593893504b2aa10a8ce4c7.nq.gz
    ├── 4394e7b21df0e47a588c36a838f31172143d5fcb.nq.gz
    ├── 455a709fbb79d266ea4ff85050e948137c1f1b86.nq.gz
    ├── 45fdbe9faebf84d310631532fcda5ebde2f01a88.nq.gz
    ├── 463a378dd3c30701e633e787978b78aca6bef5e3.nq.gz
    ├── 46888a7d1451fb2e8b1512e563b12b992cb80af4.nq.gz
    ├── 4707c9680ac42ccb4f8e5543b2dea01d70b1062a.nq.gz
    ├── 489b6089833bfbfc2552b688a502e05f7a78d773.nq.gz
    ├── 492552c585d2407abffd84408ad5246181088393.nq.gz
    ├── 49e01f6b94452d1246ed8e0e4024bc27b114add3.nq.gz
    ├── 4a0753663cced71dd387f00846df5f01acb721cc.nq.gz
    ├── 4c58fe9d0dc12cac9626cfec4136069546a84b7f.nq.gz
    ├── 4df6362730996804f4f64f7c560e301de8edf49a.nq.gz
    ├── 50368454776c51a5137c6e46500ce2160768ecf2.nq.gz
    ├── 5039f9a6f0981fbc31972cf36601124f0ded3231.nq.gz
    ├── 53b36ee6477f11488c5bf74c33350f6ac9bfb2bc.nq.gz
    ├── 56773d4bea3f8c612f7d5d74dee3ca3ce03e89fb.nq.gz
    ├── 56d6d289f6fe13fd87e5803bc60a146d9800e3a8.nq.gz
    ├── 57fd06f3274611332f4fdc897abb4a6da47f39c3.nq.gz
    ├── 5a20ca5f8c8c8baf30cd103d4c0930daa31c7990.nq.gz
    ├── 5e9f54686292d287e5f500a80a13509c7ff70624.nq.gz
    ├── 5fc12d0d85bb7f3e90885a5d4a8016cda3ef7608.nq.gz
    ├── 5fd8378667f95bde3e1e04357fe519a61b16f296.nq.gz
    ├── 602e477e51e3417dabb32186ba43b1fb35e77495.nq.gz
    ├── 61921c3f3cfb9df62a5442df287dcd033a03f088.nq.gz
    ├── 61a3822795896d1c5faf1816a269e7d1f8464131.nq.gz
    ├── 61efcddcfeca7211d49162d9017f47921e6b9304.nq.gz
    ├── 6377c39ccf649d8aef3bb7069db871d4ce7f5b61.nq.gz
    ├── 64000775705052d22b409c42cf8edccaf0902b4d.nq.gz
    ├── 67fd9a8b0fa98c55c661685930459d8b93908b59.nq.gz
    ├── 69e4ab629c27baa4be9f75447759900e99ffc6ce.nq.gz
    ├── 69f7ba1d2d114598b32a93552ac9bb89b3173d6d.nq.gz
    ├── 6a75694cee3908b25230abcdf56b698ee58a3ab3.nq.gz
    ├── 6b22f63a9000fcc525d239d55e0cf9abf9b4198f.nq.gz
    ├── 6e4f08db39cba47a3dc0d42e09a46596a0e394d8.nq.gz
    ├── 6fe66f8198d737836edd743ab1d34cdf3dd2d02a.nq.gz
    ├── 6fed60efbd7f8c6064272f9d15b81e7f136d9165.nq.gz
    ├── 701e7475a1fca1438d996400cedf1fe2dfac98ef.nq.gz
    ├── 708c3657f80f2b2e55eee43d3b7378fc9142a080.nq.gz
    ├── 713781dd741866b6a084cc3eeb026317d96d6ec8.nq.gz
    ├── 71fa47c66cd259e904ddf87aa6a026f6055e1c64.nq.gz
    ├── 7248a5b1fe70a4d0614f3fd7c7b286643f506eaf.nq.gz
    ├── 73fb8a2ac8a763cb524c9a42a86052e664481849.nq.gz
    ├── 74f9a628aca30cafdbc11cbedc4bc04f7ae15f8b.nq.gz
    ├── 7756154e3174974675b6f8c81bb9ae6ce4d3c032.nq.gz
    ├── 7929fdd6203dc0b292a32b8de37d8f1dacf006af.nq.gz
    ├── 7b1ba5d94cb4bed9400369ad470d977be47c6cc9.nq.gz
    ├── 7c340b7939eb5e0339498670eecca43d80b84abd.nq.gz
    ├── 7d21371b4f51a47f83e622c651566d5073aeff14.nq.gz
    ├── 7eeecd171fbf7cc21f5f7a28f9a0b9793c96eb7f.nq.gz
    ├── 7ef7284b8c8e29b19d31941b1f97e0f3d935b5f6.nq.gz
    ├── 7f364e53bd65aa74d7a41565d3d0ef4fbe4eb341.nq.gz
    ├── 7fe1784ceb187bff29f02e82d3733bee22e65dec.nq.gz
    ├── 805611ba53775f6fadc66d2c7a29fa0f68225cfc.nq.gz
    ├── 825ad7228c060526c9edcb39266e66988a6a4c96.nq.gz
    ├── 85524e7efa6453ab3feef861bc16af244a22847c.nq.gz
    ├── 85ec598d1fcc60bcf43babbe401fdd720ca8053d.nq.gz
    ├── 86e093f59a06f59203c28b2e22a09f0a98297022.nq.gz
    ├── 88bc41c161b8c0ae94bd80716bfe8cf167154ff8.nq.gz
    ├── 8b5f57d1dd30a40ff024a1362dd51647ca6edc20.nq.gz
    ├── 8b6f774234d1bf7295fbd792b3727acbfdccc223.nq.gz
    ├── 8b733a738cc96375bedf24fca337571fb28b3693.nq.gz
    ├── 8bd8554bb6c62a66018276c36dbf1efc1a2dd2a3.nq.gz
    ├── 8d4e26fa82c6c0470a3846a099077a82431cda0c.nq.gz
    ├── 8e6478bba27b9dcee69296783e9b090038d4d66c.nq.gz
    ├── 8f421ee69ce606cb1c1b5b94fb27748c92b7e65f.nq.gz
    ├── 8f59df07152481f7cc7321cdfca699ee95f17df6.nq.gz
    ├── 8f8e7fbb89abce3b4bc411b8d829f9c709f17370.nq.gz
    ├── 90aa634657b9ddaa04a5f13676d5ae586e4e69df.nq.gz
    ├── 9175427fab4610dbb2f73b77cca5ff6e7ec1e019.nq.gz
    ├── 91a5a3d9a79c30715fd62bac860842048c182859.nq.gz
    ├── 955e10d1e2b9eed1ef3cd1cd2be231ebcc935d0c.nq.gz
    ├── 97795e4bc1054cd3c17ddc0b724ae690b0e408ed.nq.gz
    ├── 97bdb43af145bb92e8baddac2e49f7e017e8de06.nq.gz
    ├── 985b9211acdcfac506224460ed5ede95aad5d797.nq.gz
    ├── 9927fe8a2ca596094a3d949d128d48964619c1e7.nq.gz
    ├── 9ab0da4f35f35b46ab8ac419d8189966739d8dd9.nq.gz
    ├── 9b9239f57f7f2d3f3263b5b60ad4a825c575c5d8.nq.gz
    ├── 9cdfe0058971598644e016d2804ad89665a892a3.nq.gz
    ├── 9cf6fedb6725e80efacb3d6480d2ea7f62b300b9.nq.gz
    ├── 9db06ca227f450bb3c417d4f672378a034763511.nq.gz
    ├── 9e97b730c6da099ea4d0f2eb46da68721aba243e.nq.gz
    ├── a1ad34a59ffc0844065e027e2ebfa93a93672268.nq.gz
    ├── a1f2e03b232ec44c00414804b3fb3a852a463a39.nq.gz
    ├── a21b5a08fb940df2b37136a03b672f804cd2875c.nq.gz
    ├── a28da0e00a0fe31904c3a3def64665070a172760.nq.gz
    ├── a36042528e4cbde9d36d76525b483905596e08ad.nq.gz
    ├── a5e99339ac5db72e73687873c5bc2dab160e9495.nq.gz
    ├── a63bb45a02384858312c5c59e29da8b888c134a4.nq.gz
    ├── a6d3d8e0af2509d9ed0d2fd9276dff33bbe3b1cd.nq.gz
    ├── abb36de3a26f7acb1774fd37ae9eec4037af7637.nq.gz
    ├── abb418ae9ac082dda069c369d93f4b9233c016a2.nq.gz
    ├── ac3b417c7301e50e56a4ec84ebe5fdb162173e06.nq.gz
    ├── aca0f93e28db3e988ca88351070860c9deeeecbf.nq.gz
    ├── ad61cea1cff069792d008a108911ebb0b97062db.nq.gz
    ├── ad9212fab5559310bc104fe3f157bab085f42a2a.nq.gz
    ├── b31bb68915581d08bbe63ad183598fafcc5d0796.nq.gz
    ├── b3340cd2605b36a6888c4a97f04e729060706e33.nq.gz
    ├── b376c3a79398a28ef734a94095d03cb120ed08cb.nq.gz
    ├── b4ff4a9c00c23aed1e0af1dc311c6276fd050768.nq.gz
    ├── b51e3501c01fa52f61e115d6a9b837c337803216.nq.gz
    ├── b53d0c8ac5d00684fa70066d792af279760fb987.nq.gz
    ├── b5777a383f70a0d463b93790efbd12e037295747.nq.gz
    ├── b5e142c9c6ce36ab20539f2267b381d499a515f0.nq.gz
    ├── b71a3c748e58082e9429127ccd4dce04431a93fd.nq.gz
    ├── ba081584b5e65ddfc3b9e3520ac919ad3ff39d42.nq.gz
    ├── ba77face1d894e9722d248fd6be6609596c8bf38.nq.gz
    ├── bab74b90815730555b83e4d6eac1005faf2534e5.nq.gz
    ├── bd170535170a3b40235482d895678e5d939e32f9.nq.gz
    ├── be3bfc7c5c10f5e609c5da9054c281c995bb2825.nq.gz
    ├── c19a86c1c4236ca2ae2e806b878f6a2e9bd630ac.nq.gz
    ├── c1ccc9afdaa811df5c4884b1415532ebfba38a53.nq.gz
    ├── c256208633b973ef08ddf4b199273ede1cc8bba4.nq.gz
    ├── c29a5effcbaa5d91955812549238fe150e0cd4ae.nq.gz
    ├── c2f5d5d1fa0546c5b0364fb98a1fac611c9a6f89.nq.gz
    ├── c6247ab4867cfcfa5765ef3a732adc3e0a0ca4ef.nq.gz
    ├── c7e2db83e2592514e8a8dad5892652c2bbb21d4f.nq.gz
    ├── c803f0ae96665b25a8a793967b19b6ca0ede4f59.nq.gz
    ├── c9e053006ff18113f94d8cd23b280124ada40619.nq.gz
    ├── caeb748b430234aaf20dbeac0bf43275a6fccde8.nq.gz
    ├── cc0347e171d7f2a133a305522c96ff4c1b6d3a62.nq.gz
    ├── cc10cc44fbeaaa308398167c9a114b2d07c34ada.nq.gz
    ├── cc1e0f6c1bb92462ce97156f85d2f0565c90b2a1.nq.gz
    ├── ce2a28770c13b432608b348cb8fef4643eac455f.nq.gz
    ├── ceeed75d4168ecf246744a06471cf01ba0c844b3.nq.gz
    ├── d0d286d51e2d8ce1b8c12c831554200b5cc5b9fd.nq.gz
    └── d28157d97ab0447672170d982dabcdaf87775edb.nq.gz

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

[scikit-learn-contrib/imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
