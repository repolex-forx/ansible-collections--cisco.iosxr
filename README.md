# Repolex Knowledge Graph of ansible-collections/cisco.iosxr

RDF knowledge graph data for [ansible-collections/cisco.iosxr](https://github.com/ansible-collections/cisco.iosxr), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/cisco.iosxr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bf4c479053376d57ff7cba187429108c049c765b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bf4c479053376d57ff7cba187429108c049c765b
│           └── chunk-001.nq.gz
└── blob
    ├── 001d08bd185230a4ffa8b7e3ea1ac5f05a33b457.nq.gz
    ├── 00c62121a35e84c9d6497a77095e0b0acf180d1b.nq.gz
    ├── 01776dbe665f702f4766440c285fb88815187565.nq.gz
    ├── 01800361df9bc167839c2506429f7bf5967aaea2.nq.gz
    ├── 0265308a88c69396445b180bc1e3093c8142abbb.nq.gz
    ├── 0267ab162c87be1c2a6d53f30dcbd4f96e899649.nq.gz
    ├── 03d2c4c6046b918ab3e69a9f26f59da508088995.nq.gz
    ├── 04aa0d0add9361d7eeaffa77701c02952e3dc0a9.nq.gz
    ├── 04acd8a3821db687b986034fe338766710f001d0.nq.gz
    ├── 052dd7fc269a03991d84ec64273014e71b2e5822.nq.gz
    ├── 07672e6b78a581a600a0499a9e65fbbfbbd9b4fc.nq.gz
    ├── 08e18c2b0216c62d56861c7ad7df086763744ba3.nq.gz
    ├── 09498c57a3620487224203483020ab13c7dd0f48.nq.gz
    ├── 098741faa0126d6fc07741395e5414605eeca78c.nq.gz
    ├── 09b01343b5c79a3001c26d5e446e306f7e5aa410.nq.gz
    ├── 09f14686a2d8a22212d6ba32c66da063293aba3e.nq.gz
    ├── 0a8edb0bee3f79626bb8b21cf6ff8d85bc53242b.nq.gz
    ├── 0ab53a52913f8cb8f3a46b17287211c8df9b5376.nq.gz
    ├── 0b1f58baff5b0bb21d3296990098fcbd65cbd3fe.nq.gz
    ├── 0b3ef95ffc7f90d187401cab441db3ae46e661ad.nq.gz
    ├── 0b4673e72d16aba86bc4522c8eebc534061076c4.nq.gz
    ├── 0b50df7222451c23c57327913376f0d77b6d5318.nq.gz
    ├── 0be96b2638c24b3b3ca7ccebc2b676bd11c50cc3.nq.gz
    ├── 0cb3c6936acd9237f726c2038c7a44cd6751a740.nq.gz
    ├── 0cde87902707f4da99a3b028877472a6c6e3a68f.nq.gz
    ├── 0d27e63556c671cd837b1f15312b0631bdc78c01.nq.gz
    ├── 0d5ded6af183291e445f5f32680f3f83f2f2082c.nq.gz
    ├── 0d68c20fac3c589ae22f65a0f8f5672ea8c4d343.nq.gz
    ├── 0eef88587b54f241d06cbbdcf9d647f60c3973e2.nq.gz
    ├── 0f0ab168becd84f435f8fcba0931dfcc4134fe2e.nq.gz
    ├── 0f13ddbef837145438612f23a123035b5ac38007.nq.gz
    ├── 0f2919b749237d87f6a6de39b53c8e44cf032a64.nq.gz
    ├── 0f58a44fa7637d4d07a050df049946bb75a29b6e.nq.gz
    ├── 10e2c784c363e44e206b441691ca14e052a423a7.nq.gz
    ├── 11517fc9e9d6ddd19f0046038f6462465073e45a.nq.gz
    ├── 12f38f4c881039ca1d6e9fbd2845b34f0e1d9cef.nq.gz
    ├── 13a8c5fc3268ad67ff7beab7d48c90d0f94b4e20.nq.gz
    ├── 13b9cb5542a5460deae4bde2d94bd847b914bf7c.nq.gz
    ├── 14435c1f906a196c8ef158554b0d53002e755c2d.nq.gz
    ├── 164afead284de6add13c8f514561691b2f1c8dba.nq.gz
    ├── 16f5195aeb2e3ade19062fc3083d5a0e2a42ef25.nq.gz
    ├── 174bfeb734b7e4011821bea132ee7dfce7183222.nq.gz
    ├── 18322e6e3f9010cec73b982585fe8fe9159ec507.nq.gz
    ├── 185014b4b3c5ca86e41e62aafea36fbb09dd4962.nq.gz
    ├── 1968ade94ae304ac4488467a8af5bc0674b94573.nq.gz
    ├── 1981162c822cacd48eb99b48049e228aaa61afd7.nq.gz
    ├── 19b2ce1e69aecd5445a1159d59570e1ca0880b39.nq.gz
    ├── 1a78008ef43c397f29e1e354fa94f393894b202e.nq.gz
    ├── 1b4080f14b13327cc4cc6c4b2001fed27cfddc20.nq.gz
    ├── 1be361fe095e228be0d3bc15dcac9746c1798c00.nq.gz
    ├── 1cdd253a4c251fe7449e7d1de576c551b92c1484.nq.gz
    ├── 1d36234e85d2c7c4d2bce81cfbb6051d123a5371.nq.gz
    ├── 1f412d0993c044b2480f900643f661c34be19e01.nq.gz
    ├── 1feedbb433e41bcd5b76f9b47be987f5882207ad.nq.gz
    ├── 205740f19b78cb8a8535f7c26e04328ade0340eb.nq.gz
    ├── 2086222331e9c78f9345975c318f10427088db4d.nq.gz
    ├── 2199c1446114383a1fdc143ff07da891eac2e1ba.nq.gz
    ├── 21b9eab17b1cbb9124dd2ea530f5be80912c0312.nq.gz
    ├── 225f6b1c5c37c1dfa2b5a46117679c52610f803e.nq.gz
    ├── 230692117e90309491c699ff2b6694eca0ae2d52.nq.gz
    ├── 231b5ef9d6209629361ecd763be7d80537454fba.nq.gz
    ├── 234373fe451d99a662b75152a223c86532d3ed5e.nq.gz
    ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
    ├── 24723a9d5114961aeb5578434a01728b5c627c79.nq.gz
    ├── 24c2846f599b5b408c5afc88b9c7764e069f3cc3.nq.gz
    ├── 24e9ce68de2182658699dffc0c164addcd64c0d6.nq.gz
    ├── 2554f294e7ed553756c4fd8fe50b1c08add3abb7.nq.gz
    ├── 258640c0d42b27cda6f56525d0f5186397c27d41.nq.gz
    ├── 26284ddb9c0be1fa05d63095a3714642fd1d58c0.nq.gz
    ├── 26ecf9931c488b8adfd3a3586c18d1540b30e2a7.nq.gz
    ├── 27d2f1dc747aefca4d483022bb9c0e978c653fe0.nq.gz
    ├── 27e0c000dd85558d77d5f200f76a364b5e3b6df5.nq.gz
    ├── 2850388be502e4ae1f20a0e9d385326a13943dc8.nq.gz
    ├── 28bba73ffafe069a8087646ef2224a8a96e9b763.nq.gz
    ├── 291caf30a87b238079708840bad9a273e931feeb.nq.gz
    ├── 2a2bc8a1df839d1752de8bb367e7077a46bf34c0.nq.gz
    ├── 2b28b525b67e54b42b8800d8e7f5ff38aecd2e8a.nq.gz
    ├── 2bbb2f6d052e3720988fdae261beca782d125776.nq.gz
    ├── 2c44713a8a8c907e03cbbdb2401be89b7b913b88.nq.gz
    ├── 2c7c5ab4be0725aa5bc33c16abc79905a4c9029a.nq.gz
    ├── 2d8faf120092e76c1d9ee58edf5a669bb78e2c49.nq.gz
    ├── 2dab5aea8c4839bdefbec379dc31734db7f939a4.nq.gz
    ├── 2f9c97b8430e00642da0c110de6497bc3e5c2eac.nq.gz
    ├── 30711f8b2d226dfb64932d3809371fbc17320920.nq.gz
    ├── 309b8238b9eb4352c330552dc071e8247948881c.nq.gz
    ├── 30caebe2f7ba9cb446b0813fbeeac7ef65d3194c.nq.gz
    ├── 32085d51ef2289a35bacdb8efa93afea602770cf.nq.gz
    ├── 32cf48121a8e86ea84ac72c81227f70c431af04a.nq.gz
    ├── 331ea44fe174c4fc54d8d91a1f290aca8daafc6a.nq.gz
    ├── 333eb06968639cdab232e6e0792f2e09982cb9da.nq.gz
    ├── 342026211ab551862ac01b83ecdde4a1e01f8cc2.nq.gz
    ├── 34e096751ed5d7a277c69f057649e5c552e59229.nq.gz
    ├── 353162c0257cf95777be6f1f6e1b18516d90ec8c.nq.gz
    ├── 3568ac8b2a8d3c13fb5573f67c1b4af3183ce8c7.nq.gz
    ├── 356fee927f78292f8cf67c0de2fd048a34c48a24.nq.gz
    ├── 3616cfdeba9b6192816093a7a38c36f724a81a0d.nq.gz
    ├── 36467651b3ca3da4faa8c8e07aa0ebb1528f94da.nq.gz
    ├── 36696fd10307e3ce9557b507d9dc5bc05b076061.nq.gz
    ├── 36a715bfb63f7b69fd498a127d1b19a88f3114d7.nq.gz
    ├── 38b5adde4da4d23669e27e0558283bdcd35d85fa.nq.gz
    ├── 38cb4c0e7b3449d2ec0280eb4fa3527e20a1aaf0.nq.gz
    ├── 38d007d952418953fb0a52419987baa3c817e7a1.nq.gz
    ├── 39031229557f5076fd3ca8e2391f71bfb2e34f0d.nq.gz
    ├── 39471d59f5ecfe760e63d6170dc4a2be9824a0a4.nq.gz
    ├── 39b4bbea5fcd7000495c8940daaab84d45675e82.nq.gz
    ├── 3a355adc6e90fcce7618ac8e8f4df8816b2c8821.nq.gz
    ├── 3a3b647a3d773b8ce98196ea369ee0f5129be31a.nq.gz
    ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
    ├── 3b338c2cbc08a5cd45d127eabba2aa9d5f15180c.nq.gz
    ├── 3b56d814b90b3b6bc35e590a2638081e2a6c1251.nq.gz
    ├── 3ba25aec4dcb9f90624a24860b2115dd66ea11b9.nq.gz
    ├── 3bf665762eacd7c8cc86cdf4a8ecabddcf0f31bb.nq.gz
    ├── 3c36cdb7e474b0e47ffa00dfe00a81b1badd9bf5.nq.gz
    ├── 3c4f66909e1757fbc3eaca241bf05dbb1971fb78.nq.gz
    ├── 3c6768c38c0eb1e528e78b6a7d76a1c6cb3d08e8.nq.gz
    ├── 3c70df5ecfdd206eaf08d8730122a51f4c74f366.nq.gz
    ├── 3ce0b0d2afe982620f26633a280b1c0d9b299af4.nq.gz
    ├── 3e804679c4e11792e4ec5941300afd6c1738b8b7.nq.gz
    ├── 3f2b9c1e5932864e45359e31643b0e49c495004b.nq.gz
    ├── 3fcaf8cb01f596d68b51ee93318d976465fed96c.nq.gz
    ├── 4067f50fc58bca65716cfac55545b1fb854fd6f4.nq.gz
    ├── 4192ee398caedf208f63ce25854ec2b2147dba92.nq.gz
    ├── 419a6cde6862a5f5cb0c6f0cd2b39af15c1bfec0.nq.gz
    ├── 4231d516ff91fbdbc639bf9a8e35186112da0f70.nq.gz
    ├── 4254a6ea8f7f1824a06a886ed5a00d4089dc46b6.nq.gz
    ├── 43dc39121fe58d46ffe5dab8db63a56b929dbc40.nq.gz
    ├── 4464f0cb753f971bb4e23e8a531e6ae0dd8f8b3e.nq.gz
    ├── 4470966ac6915e095348f11fd5c9b05113548f33.nq.gz
    ├── 447323e7ff50e4b0e229f429d9e66ade69cfe3ff.nq.gz
    ├── 45f8125984bddc0977a7b27313b1fc13d549474b.nq.gz
    ├── 4657d771a87109fa924d5029b0c313ecb68caafe.nq.gz
    ├── 46d10568237195abe804f0df2254255ae7e5f594.nq.gz
    ├── 48b4184d4a0a6afcedd0b2c39bd2df5e2a25e3ad.nq.gz
    ├── 494562fc50edede2e38d04fa4628444e4a884709.nq.gz
    ├── 494f024093e1cd18526530db988a2ec1f9057295.nq.gz
    ├── 498f5f916f81aeed70455cd3c859de3149457ec3.nq.gz
    ├── 4a2bf6ac06f32169cce169dfce99d087e1f4ce06.nq.gz
    ├── 4ab7f8fb9605e0cb26d50381225603bb75b8b6fc.nq.gz
    ├── 4b02dbf35b96b1dd4c2f039ca740dd6066f2671d.nq.gz
    ├── 4b7d599c6cc1ac3d70de8c2ddbe2fab15f79daf7.nq.gz
    ├── 4bd23847d6c8a867dd6f7f0c3dd34fb632265264.nq.gz
    ├── 4cac56e63ddd1e4d788ae77e719e298d535938ca.nq.gz
    ├── 4cd4e1a6090b98d9c1528e44f17af3635b68decd.nq.gz
    ├── 4cf49d2be0c6ca7e9affb9023c97d77afe716f56.nq.gz
    ├── 4d7dce10e590a283d6b4ebb9133f2cb262397c70.nq.gz
    ├── 4dbe5b3037498e853b9e8c255cee6b91e5679156.nq.gz
    ├── 4dd456a18d179c1ddb02ddcca0996845ff222974.nq.gz
    ├── 4e2b4c71c794f56c9c6e33d0dfe3a35534e2db8b.nq.gz
    ├── 4e380804496d75687de5e94b1f9883437a8f6e17.nq.gz
    ├── 4f04f3845d2d85e03a77fc69d25d44d533d4ede4.nq.gz
    ├── 4f21c18103a073b31cba5d5aeba6ffced7c2e829.nq.gz
    ├── 4f317eb5d4aff8770122bf908979d964a14c9013.nq.gz
    ├── 50114e633a4942cddd0886fe3bbd6f351d3ddfd1.nq.gz
    ├── 50490b78f6ca5af914a875fefe7f6fb612a0870e.nq.gz
    ├── 507142664bcfcd5d90f02f6fd39aec4d94d705fc.nq.gz
    ├── 50bb2e5410b4c36128c8ff6aa8003ab55d41fa79.nq.gz
    ├── 50c2cdcb87888f3357a3757cf9da89035894df08.nq.gz
    ├── 50e6fcef92bbb082f47f8b2fc0996f31646e9e07.nq.gz
    ├── 5191b38a5decf6f5c51ba5f7dcafdc6d5fe09a3d.nq.gz
    ├── 520448debbe56870a9165f8c4651051158934150.nq.gz
    ├── 5210080c21b1425eba3f700bba4272ac33d1e4e8.nq.gz
    ├── 529e437d88c66739e8cfbbc18a5083651aec83e0.nq.gz
    ├── 53a4631ae192b2e7653226b39cec353255baf6d2.nq.gz
    ├── 550c7bcf33fb5073ccb93edcc85dfba2c4f44893.nq.gz
    ├── 559de6c00c2384225b3255418bb06809f51b1da4.nq.gz
    ├── 55cdfda8f4601f7492550164f6213c77f20d3c2d.nq.gz
    ├── 55dd23f6b212d2235b5964e058214610bf78daea.nq.gz
    ├── 572fb3f6d401a8bb4fa869a6213dd28dd7f98a37.nq.gz
    ├── 580027f626fe8ea016fb05f36386ecded8ce51ad.nq.gz
    ├── 581b57ce5cb81df5113839a83d109671196be8e2.nq.gz
    ├── 587fbde985b2058072c8add252832021e900c226.nq.gz
    ├── 588af81d2aaea41b52b107bc677edff5a20beb2a.nq.gz
    ├── 5928f93f0393ccf15c8a396643ce99fd2442fa60.nq.gz
    ├── 59620f2092176704e595f1300d7d6072e36a2b3a.nq.gz
    ├── 598d2d691970862fa50ddcd49f86006a12a809c3.nq.gz
    ├── 59da323f169b184a08c4145d42a99ef764e74bc8.nq.gz
    ├── 5a3ae6c6596ee641d007ad9cc0c98fa0c179e3cf.nq.gz
    ├── 5aa174c468fd3c4f01e3d60ac76e4dbd7a050f20.nq.gz
    ├── 5b32d4c1097ae6224bc65d88f0406972563164da.nq.gz
    ├── 5b5bff5f9b3d1a9d0694053ee87c787a82e25bba.nq.gz
    ├── 5bb6db4d57c271777256577e5877d689c672dbb6.nq.gz
    ├── 5bba47df239249883a91ba25769a5fa4bdbbc7c3.nq.gz
    ├── 5c80d30ddd5162e6e63149b68486cfc123bb9679.nq.gz
    ├── 5caa453bc39e3a851b5421b93dac0d97fe448df8.nq.gz
    ├── 5d2708a304c6c3d94132193d9504455ed36a3230.nq.gz
    ├── 5dd4a02fdd7814331452c525e5041a16f309876f.nq.gz
    ├── 5dfe512bfaecc9f56150c1959e5132e51c59bf5f.nq.gz
    ├── 5e066b8301a99975eb83c0a28b30a9e6759a9dea.nq.gz
    ├── 5e5794d978538915fda0d5fe44835ba65f588881.nq.gz
    ├── 5e639264489401f18c03fc966669a9d2a056f164.nq.gz
    ├── 5eb6038af711f1b9389d5ff62797e0ba77cc0408.nq.gz
    ├── 5edb90e93ad4f040840f2f89b9ce6c1a0f4e035b.nq.gz
    ├── 5ee6930f298fa34f7ff99f050188247341427acc.nq.gz
    ├── 5efcd6084e1d964f72131502dd290ff765827738.nq.gz
    ├── 5f08fd677515a7b7310e811d52c437886f0b40a2.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 605f28514395b6ae4d993569667de5bcd35ead00.nq.gz
    └── 606bcba7d89e9c6a54853a41019030f10cd7a994.nq.gz

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

[ansible-collections/cisco.iosxr](https://github.com/ansible-collections/cisco.iosxr)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
