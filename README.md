# Repolex Knowledge Graph of mne-tools/mne-python

RDF knowledge graph data for [mne-tools/mne-python](https://github.com/mne-tools/mne-python), parsed by [repolex](https://repolex.ai).

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
rlex download mne-tools/mne-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8f498626a53704a6a96bcd8a11e22cbd8866efa5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8f498626a53704a6a96bcd8a11e22cbd8866efa5
│           └── chunk-001.nq.gz
└── blob
    ├── 0066b846550246ba8de540354d121fb8e374af00.nq.gz
    ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
    ├── 00adfaa637d2982f70f7fce97ff71b709f96553c.nq.gz
    ├── 010337b2ef41f8529cb90ea8402ca02dd55ad64b.nq.gz
    ├── 013a84fe7deb15a3586cec402fec8a0221cda4b7.nq.gz
    ├── 016c444f3a73a05d2e95b1a8e7df25e4c30ead64.nq.gz
    ├── 0229aca817a2cccb86fefd339d7694f88225d9cd.nq.gz
    ├── 0392fcb968adcaa44dfd1edfba2ded8897891b45.nq.gz
    ├── 049f81ac3a6d3f4d5b25a3cdb823384501dcdc3e.nq.gz
    ├── 04c673b4e4d9d97d52ffeae54ae216d14fd30e09.nq.gz
    ├── 05e1743dd968d5ca06a35cb6fb14f694a1947dee.nq.gz
    ├── 074bcac1f9e5f86e7aedec671fc21305bb430e42.nq.gz
    ├── 078d02faf59da472c4ad7f38f0bfef2b309c5b79.nq.gz
    ├── 07b5c2d3f39ef521f8ccce345e9034b5837f8223.nq.gz
    ├── 080bfa70d24ae105dfd5e86ec0f5a645c55de30e.nq.gz
    ├── 087d4e16b79c6e579e469b893d88b658eb5e4b30.nq.gz
    ├── 092e4808337f5f02111e8c1b9f2b9dd2379287b4.nq.gz
    ├── 0a9d88699d0cab2af8565dfb670f98e3fd2df762.nq.gz
    ├── 0c3103a6cf7f48e1afacce2bc9e7bb5213ef597b.nq.gz
    ├── 0c581d74ef4e97c5589847161234ff65defb6880.nq.gz
    ├── 0d998f8e51bab661ebfc575dc0a6cafd68bdfc53.nq.gz
    ├── 0db1ea092ebc6e884b15af38a756cc8d3bc2010f.nq.gz
    ├── 0dce41283d0dadaa8853c612e577f2b6bd94b1a7.nq.gz
    ├── 0e220de6e62823a2c3132d054624ea24857d0dcb.nq.gz
    ├── 0e555e0ab7f1d381ae3d528ccbdffddf8f91596c.nq.gz
    ├── 0e7b4fb1a8b9b9299942e6fdc91948f97db98a59.nq.gz
    ├── 0e9caa212a27df03f197af35578358c985ea8910.nq.gz
    ├── 10180505862eb5000767fb7549b3e7bc98dee096.nq.gz
    ├── 10534f3820ee850052cdfbd605dda2f743214505.nq.gz
    ├── 10e851a06938dfa462524ce6bb905e2e28e32c51.nq.gz
    ├── 12160755e812c9b5bf2088086a96c664f1bb0469.nq.gz
    ├── 12c5db254279712a153b6a72fd3836f76a91b196.nq.gz
    ├── 12d0a24e1830886e3422448fcaffab4f43b1afe0.nq.gz
    ├── 13a1bb58a7fc9d792d86f271f4cf880b3aabe90c.nq.gz
    ├── 140c61e5a66233c6105a79fe698e13e8f95e9015.nq.gz
    ├── 141553b59877531cff925258f7c4988da75d568a.nq.gz
    ├── 147ea3bc1bd9955969b9d757699675166121335e.nq.gz
    ├── 15a1fbb95ff6976940ab376db58a521a62d12763.nq.gz
    ├── 163efb0de9fb9daf819441a0297b9c2ee98afff3.nq.gz
    ├── 164db2ae4fddfb4d1bdf87d08045aa21c4778aea.nq.gz
    ├── 166a3dd48248386206bac16ea6d1f872b63ce290.nq.gz
    ├── 17bada2681bf135f90407ba06b0e9f2d2b7b22ef.nq.gz
    ├── 18942672858109baf6bad51c680a7e57529c377a.nq.gz
    ├── 18e529a6c375a5d3ef07e60bd5099cd04ec6fc7f.nq.gz
    ├── 18e97e6a4d340be1c81a02aa020c279f1cce5cdb.nq.gz
    ├── 195c0c0c1d47f4de4b6d9aa87969f85fee50695b.nq.gz
    ├── 1a6473f6bb610c86d95160bf33ca2b848306be5e.nq.gz
    ├── 1b93102f7c564f8c49db653ede33407dc55a10c1.nq.gz
    ├── 1c1f3d3690560ba68728cad49167ea35c1509f43.nq.gz
    ├── 1c970001d58d61a1d6742a3578860ee4f6bb0973.nq.gz
    ├── 1df3fde518fa6806446611924152671c07234a47.nq.gz
    ├── 1eaa8d89c67bda830bbba977afbb75e718613dd2.nq.gz
    ├── 1ed6149866065e98e31def9ae6452673485b4052.nq.gz
    ├── 1f11d724763eace6127c4bf8427205f0d8cf7bca.nq.gz
    ├── 207e43cd7a14daba8a30fb2822eac94b1eae8f3d.nq.gz
    ├── 219c4918f0526497d5ba571081033b6197ca8eee.nq.gz
    ├── 220bc73e44c30611d1333f413815ccbf3f53a742.nq.gz
    ├── 226d5f7daee2d9d1454a2bed7c37fdd1cc938900.nq.gz
    ├── 232a5e6ec138e9c51089759538b71543bf80ba2c.nq.gz
    ├── 23399729f7b79e370fef32386801e443b0031e49.nq.gz
    ├── 23e2600dbabffb7aa038a2cf0add38cab452c47c.nq.gz
    ├── 23e90ec9f5214ef736a260812c3c4e3588be0cb8.nq.gz
    ├── 240dfd06bd7d711be888e74046f1b410f131915b.nq.gz
    ├── 242d98b6bde79fe329aafb610b32625a776f2b92.nq.gz
    ├── 248907a9736c2dfcc0f758434051858897372d9d.nq.gz
    ├── 24cd65ae2b9a2ce311a1e3ab483ae718b75943bd.nq.gz
    ├── 25060b67cc7f78cf8a5f6ad5fecf687088c4454b.nq.gz
    ├── 25a040855f1b68d6640d6762702206aba47fe9c8.nq.gz
    ├── 2668f0fda922c321d1565a27db749f0606f5fa00.nq.gz
    ├── 26cb5fb09dfa78a788ce8882d9dc87e3d8fd3cb6.nq.gz
    ├── 27320f43ca2b728e3a63d575df238183be3af1ec.nq.gz
    ├── 27bac6427df14e70af82089442715eaad7948b40.nq.gz
    ├── 28954a4eab7bd9e931cb352c022f57ed3ed6c093.nq.gz
    ├── 28a61b2c0c35ebe1ba6720b0fff2c4db9392fb57.nq.gz
    ├── 28c3ec138a35a2a4550f140875afc64a93758d2f.nq.gz
    ├── 2a577c22167f606f01438587f9dbc75b5c26c8bc.nq.gz
    ├── 2aa0a49af9e2cce5e5001fc4baf68fcdd053d373.nq.gz
    ├── 2b663eb2290b4d10caca23565ae6328fdc688c16.nq.gz
    ├── 2bb9331bf07094658fa677631882a091ff669c52.nq.gz
    ├── 2c3fad2af61021ad6d312880e11791cdf254996f.nq.gz
    ├── 2cc5784ba9a9e91ee63df10dd792b77a03f9d506.nq.gz
    ├── 2d0b2232179ce468bb379cfcf6a31329856ab7bd.nq.gz
    ├── 2dc9323e1322a872b5edb714cc8ba4da85281465.nq.gz
    ├── 2dcc966b887aeb7f4262b46b8eea6ea7744b5048.nq.gz
    ├── 2e69f6a92940499081580b351326af193c203526.nq.gz
    ├── 2ef7289b7e696a4b31ae8f13169006dec250691d.nq.gz
    ├── 3029ce50be8d8876efa9a99f92e8e893338550f2.nq.gz
    ├── 31c9fdc5fdac57d6c44b710ceccc623c20ea675b.nq.gz
    ├── 32c3515c138470a624ef353fb1dc1cf0caa820e3.nq.gz
    ├── 33dac2f56a96493c5881ab928a90fc89daba6682.nq.gz
    ├── 33e9fb9eabc7d888caacac0e5cdbde2e93977b0e.nq.gz
    ├── 33ffd8737182494ae51702bc34a65ad5b8b803dc.nq.gz
    ├── 34b2106876937a985c106151ab75348cf88f03a8.nq.gz
    ├── 34d7bce1cc37d9f7bdcecfe5df4c1966bc05752b.nq.gz
    ├── 3544306ccf7a26cbe5947b88d342dc069f8b3f76.nq.gz
    ├── 357b2a332a095ea8d235a4363584fa153259245e.nq.gz
    ├── 35f3ac620a5ec4199587343d62ff26b073a1ac7c.nq.gz
    ├── 3694e36a6cb23daf6830d338b1799d72597fce8d.nq.gz
    ├── 381540eba1a9a7cff77a3d0bf4b4851a45d74429.nq.gz
    ├── 38849b02d203035548c2413cddefc712d22b1c8e.nq.gz
    ├── 3a4190f8fd8b3ea110a6619b21ae1b072f74a79b.nq.gz
    ├── 3b40c4c832c2bbc9930770dd05d8128d259b9d40.nq.gz
    ├── 3b6766e2cfb78ee073d2864e551e3dc4b1444a25.nq.gz
    ├── 3da7008bfe9db92d0bcc73ecd96720443cce9962.nq.gz
    ├── 3e499aaf7ff15f9e43045f1955e82f316f236c34.nq.gz
    ├── 3e6dfc3b331b00ef4715f86f6206a35695c3c215.nq.gz
    ├── 3edd7d16b03054adeae350b5b2fd6ef42f9fae7d.nq.gz
    ├── 3f805c8761bf68ac90c9acfb14596534e879417e.nq.gz
    ├── 3fac13fd94bfbe6082a8a1d7b7b15d8cf29d402b.nq.gz
    ├── 405f55f9c8af272c336c500827e544b025f89ed0.nq.gz
    ├── 40e151b7e4b1520ffe9430430c7c25421cea204c.nq.gz
    ├── 42391a43021565efce444839044e1a9621bd8075.nq.gz
    ├── 424fbebb12ffa941c5560da60b34b2a6739b90fa.nq.gz
    ├── 42e8092d23bb7c979499e9e239ff9f862bf28763.nq.gz
    ├── 42fb585e357bcb29becca907f763dee9969566b2.nq.gz
    ├── 430af0783fa1770db65bb2e5b4e8c2d32fad29bf.nq.gz
    ├── 430bc57bb88dde357bf16e0aa2d18044ed9d6784.nq.gz
    ├── 43d69f4f8b69ea8e20c14d73a56e2a3de9748e11.nq.gz
    ├── 43e96812baebf41bd8152dbe7afd25c4e9590205.nq.gz
    ├── 43f7b2c7770756b24db76bc85a8adde2bb2d7668.nq.gz
    ├── 447aa3b42914ff3bb87624c46f206c994fd6988c.nq.gz
    ├── 4485e1908c9160ec42232f936574d5dd09338036.nq.gz
    ├── 450212344d88604f54f2677d439f4571ed0ac11c.nq.gz
    ├── 4624c2e77122bae1cfee4b6ba99381eb45c7df75.nq.gz
    ├── 46873d977ecf20cb4bbd7ed84619d1d80c5b4812.nq.gz
    ├── 46bf71f495f85f874f5bc955cd5b9b6528b3ac0a.nq.gz
    ├── 47223a8365f577750990c9df5fc905a23294250c.nq.gz
    ├── 47435c0d491e784617744c383959d8e947ffa1ee.nq.gz
    ├── 47cc1bb90d42acfc0ebc1532b04a8a12293ea6bf.nq.gz
    ├── 47ed5136f372ec2e52326b217a0a891e964dee59.nq.gz
    ├── 4847e61fd8da5c1c5c3670a91717efaddc3b884c.nq.gz
    ├── 48489cedc5e5145c2cd730fbe853bf8334874724.nq.gz
    ├── 48eef63d628ef4b7357a3e70a0afe93710a62d11.nq.gz
    ├── 4a6df5d4f964324ae5cc7e8cb686a5925b1347c4.nq.gz
    ├── 4af6f2ddfa49ae7788039440f39d2345bdfe1168.nq.gz
    ├── 4afafa54e89bbe47520cc7b0e9ce14815f92c270.nq.gz
    ├── 4b17567d7ee9041801ad621d4124b07918dd2292.nq.gz
    ├── 4b409c05f4830958f8dc3d2ec79c81a63d44d63d.nq.gz
    ├── 4c74048cfd5cb80d51103f0572f4febe68ea0a49.nq.gz
    ├── 4c90a0fdd23a53e4d046a8c8759307dded058dd2.nq.gz
    ├── 4d88a797557283a5682fb5dca49b7296aef1071e.nq.gz
    ├── 4e2fb6d86a4c70514e612894053de23f19ba81ea.nq.gz
    ├── 4edfb5b175c4d99197cc84876b933e698fa788d6.nq.gz
    ├── 4f442b7847a126abe5614b6907f4412d1413e55b.nq.gz
    ├── 4f51025f63ff37e2045fe0824489f8f44bbf9bd2.nq.gz
    ├── 503f81f0bdd3cfdb8be2574708cae3522487d477.nq.gz
    ├── 50b8d3b9499077503f89082859309207d3104136.nq.gz
    ├── 519d68c168afa18d8d74393ecca49ca1858e40dd.nq.gz
    ├── 51a038400cdd1ce92db82da2fccae61db22c0a3a.nq.gz
    ├── 521e75ce0eef31afe455af0987c32319128fb443.nq.gz
    ├── 528aa66221056f39f1a06b72adfef15469f0f20b.nq.gz
    ├── 52bedeea7b5449ad253b9d486579989d60f16b0f.nq.gz
    ├── 52e02fc9a21a55901e428a7425dfced235102a13.nq.gz
    ├── 538d63f0ac3c18abde377b62f2df07217808ad35.nq.gz
    ├── 538ec656910a4eaec74ba2314af2e0145b5397e5.nq.gz
    ├── 53d7b0b6a5c53b8b87eef7ea2aadd7cb4ecc0dd7.nq.gz
    ├── 546b14bd9031ea812523f9ba68cccfff016f08ef.nq.gz
    ├── 552b7f5ef53657100697990b66b6fad19e0a1c65.nq.gz
    ├── 555f012fc3113c606f6504b5f708d20c5b1d150b.nq.gz
    ├── 55962342003e157654cf8d3990418ff891c31d72.nq.gz
    ├── 57621858c33b1ec1b0559dd351986c3ccc08c520.nq.gz
    ├── 577e9537986420cb55e6ae08ba2bebfb8c7f8d22.nq.gz
    ├── 58c537b06f35df369814d446da4eb0b757be1e43.nq.gz
    ├── 5ae4c4a35601cf43e6bf5fceb944d3e3130a951e.nq.gz
    ├── 5c56340e2f8c53c2a76318b7496fb2b3c9613b51.nq.gz
    ├── 5cba0db55747683d30db08bee4dcc6ccebf63c00.nq.gz
    ├── 5e53d737d5e2a3d7a91ad846dad8acda14d2ccb8.nq.gz
    ├── 5e888ee837a0c1db7005d07007696e8a74ccbb60.nq.gz
    ├── 5fbd79a3791667128089e6048cade83e00499f72.nq.gz
    ├── 60a3f579c27ae31372f5bfbe92b18e5d7ad426e8.nq.gz
    ├── 62310508323aea64d5e347af4fa6be43216da44d.nq.gz
    ├── 6240f4368c06cbd8de51069b3152e9af56803a07.nq.gz
    ├── 63118640501bd2f7cf854279aa7db46db758cdbc.nq.gz
    ├── 63706663ef7120d1831fba02e14d8e15712ab222.nq.gz
    ├── 64226a402080d60104541ce888a061792ea9e0b3.nq.gz
    ├── 646195ae0a162f15f3f7d754ac0ee504cb6e981b.nq.gz
    ├── 64fa3dc2e737568b93b75443b7cdd312311d83af.nq.gz
    ├── 652b7b55f9de08df6fc968536774e752268280e7.nq.gz
    ├── 65b4cef8b0aa004edf2f38f9a2b8635482c27efb.nq.gz
    ├── 65f33e7f63e22776745f9e0f996a87a95658f81b.nq.gz
    ├── 660a484963cd243c208cd6e4b921e8abc10f9602.nq.gz
    ├── 6686edc6e8d045ff0e7a3416942101a79ac59ae7.nq.gz
    ├── 67360191ac971cae1b4551b184adac4d7858eca2.nq.gz
    ├── 67a3d4cca8622c3ee39ecebfcced6eb449af90c4.nq.gz
    ├── 67d93a7a32f9b206efa1f44e89bc917ad0a7709d.nq.gz
    ├── 680d224dba96c0d34f211a77b95430db0b1d8ead.nq.gz
    ├── 682347e10d66387fc5b1d007ed8121a71811eec0.nq.gz
    ├── 683381426fce9690833eecbd3ba4ecd956d11141.nq.gz
    ├── 68aa947361785030d4715425ccc17c23ccb34b59.nq.gz
    ├── 68c8ebecc27aa9794d26f51f96c8538618be7b20.nq.gz
    ├── 6955479320676f5be8fda6c9946ecae2692c382a.nq.gz
    ├── 6a3a9483d964c6d9361efb0b16523e255f7e92ee.nq.gz
    ├── 6df9f705d0d520e726350057ebb90106f9bbd427.nq.gz
    ├── 6ede535211399af3c0e0f4895bc3190995d6b337.nq.gz
    ├── 6f11ead60f7fac094123fe98f1493ad5eb189515.nq.gz
    ├── 6fc82416adc4aa33a97352be98e48dc73bb27f29.nq.gz
    ├── 6fcd9e2d65d4cf380a3709d5209ba1d457db2da7.nq.gz
    └── 701b4587d9dd5741e04f8c2ea816925b31ce089f.nq.gz

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

[mne-tools/mne-python](https://github.com/mne-tools/mne-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
