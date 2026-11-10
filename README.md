# Repolex Knowledge Graph of dremin/RetroBar

RDF knowledge graph data for [dremin/RetroBar](https://github.com/dremin/RetroBar), parsed by [repolex](https://repolex.ai).

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
rlex download dremin/RetroBar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d2b0b8535a395f3f13578d2825ca2094845c1779
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d2b0b8535a395f3f13578d2825ca2094845c1779
│           └── chunk-001.nq.gz
└── blob
    ├── 0096c567de596b0916744894f98331af85ea3304.nq.gz
    ├── 00d679ff3d317ba331a5b4e6fbae2b82068e7766.nq.gz
    ├── 016050ce9757101dd3d34f3cdd4723f111f59592.nq.gz
    ├── 033614b13ad82f80c776cf8cae5f2f4baacfefa1.nq.gz
    ├── 047eb10001c4d16d5d67e79aae1acc9723cce9f1.nq.gz
    ├── 081c0e9eef37918e355ccfda6096eca0b670b817.nq.gz
    ├── 087d3d86c01436e5f70aa1f70b4cab0871c7c139.nq.gz
    ├── 092645f2399a56f09123ebd1d1851a2dcbe03337.nq.gz
    ├── 0979660792b27b71599cbe15fd62e53ba65cf2df.nq.gz
    ├── 09d7ec1bfb4036ff386ee4aa6e2601709dd48664.nq.gz
    ├── 0a5c4f9f2a9d8b713f2217f78a475bea77290172.nq.gz
    ├── 0aa024806d38bea4300b6490f3cf455cdd8daa98.nq.gz
    ├── 0ba2e511056d43e3e59013ca64860603afd36c62.nq.gz
    ├── 0d11f096ebea28d6a205261b23af5de08264f940.nq.gz
    ├── 0fc3c5abc71b8e2f3f75f5021ca283814c3643c3.nq.gz
    ├── 1285de7feaef6ef117f663acc44add8d1305453b.nq.gz
    ├── 129c6c68224d0e2fb6e985351f7268631c817227.nq.gz
    ├── 1386e7f13b2656215716cb66697a2f61cff8b732.nq.gz
    ├── 15b2fab9614f67ee0ad341e72fac6debe120b63c.nq.gz
    ├── 1beae7c489b252c71cbc6fe6cc795888cb3ccb55.nq.gz
    ├── 1e8e79b492f8158888abedf454496928f0626ebe.nq.gz
    ├── 1e9fd2536b7c646f2fbc3176b103103dfb83baf0.nq.gz
    ├── 1f03bed05f4cbefe59b8e7feb9c8cada52890b53.nq.gz
    ├── 1f266e78bf7d07edcb0b461c538beea4142f1b13.nq.gz
    ├── 1fb6b66532c56dbfa38760f212eae4cad3ee550a.nq.gz
    ├── 1ff0c423042b46cb1d617b81efb715defbe8054d.nq.gz
    ├── 20dbd0c2bc07571765ec2fb817f565d3961d2983.nq.gz
    ├── 237c1709a28fe201c4fb8f04f147b52c7a2e047e.nq.gz
    ├── 24e99eab48b4385d9c47a97175d726429a820944.nq.gz
    ├── 25ec9ac5206f5ca668d04eeae7b36a393d2dada0.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 276afff192878063a38af27610b8790f5253aa11.nq.gz
    ├── 27ff5f153620c4c369a4e2b8a805c5696fd9519a.nq.gz
    ├── 293d7745368425834c22ae05765702bf8345f7a2.nq.gz
    ├── 2ad9c08d97a5b396efeda6f10d1ad7d31868eb8d.nq.gz
    ├── 2bce283986c47fe2a986e9205bb2664b07f24b86.nq.gz
    ├── 2ca33b975e6d97fc6518f253ed5bba73f730a30b.nq.gz
    ├── 2dc7a77748b44922959ad9be964c9048fd909d8b.nq.gz
    ├── 2df82a0d172259c104388f6d48020f457f6af431.nq.gz
    ├── 2e778ff0f280af262466688d956b8b9c1f5b0d1d.nq.gz
    ├── 2e946d752f156006b56eb8c0210a9ffa782725cf.nq.gz
    ├── 3343f40d5205406ebf214fcfd3d280abda5aab23.nq.gz
    ├── 33a138ad55c99b326ddc88b651c2c325abaf47ed.nq.gz
    ├── 352864037967e85925ba024002c8618355b1f0ef.nq.gz
    ├── 356dce92feaa443e6994531c559fbb9934cbcefb.nq.gz
    ├── 36041ae723bfa95bcbf6e0ebb3748ad403035cbb.nq.gz
    ├── 36677f852317b5b0313ca6320511ae06149472f8.nq.gz
    ├── 3747412db81c3998569e62bc1d4778fd83352aa4.nq.gz
    ├── 37587fcc5ec208968741e92daa42e3921ec8d78d.nq.gz
    ├── 37cd0f504d9c1182c003313abe21bac7acfca641.nq.gz
    ├── 37ef5115423f89363c48f8620317a5137aa3ed4a.nq.gz
    ├── 3b1abb070fd2fc74cb22b12ef5c6dceb838579e3.nq.gz
    ├── 3b7962ed741e916e5f5507ff7e14fafb99bfe188.nq.gz
    ├── 3bf5fcc7e27d33a347918231671958fb4b0d1b46.nq.gz
    ├── 3cea9e9ad9c7049bed17ef0091cb12e88cd5eb16.nq.gz
    ├── 41abc71c35e83fe9680eac596e1f719b99393dda.nq.gz
    ├── 41b94b04ef5183aed4c413d30f02dae9bfdf4c5a.nq.gz
    ├── 4294dc39c4099c78e4340dc4586fde6124fe1fb0.nq.gz
    ├── 43b3ce1ce52823aa2b80ae36bbd721f685929985.nq.gz
    ├── 4538cd1142439d1b46b70adb35310110725e3029.nq.gz
    ├── 47f66ed1ca3b6b2c20020589eb3b218c4b07780d.nq.gz
    ├── 48b1ced02d61b81c4afdd42c18c0b79f4b3d29f2.nq.gz
    ├── 4995668ac99d06212deee8e4af6ee78741b6fd37.nq.gz
    ├── 4b490cf2d0693159a1295a8efdbbbc2624f84ff6.nq.gz
    ├── 4bf255d59355537ecbbe32d03990ab2dae3b0623.nq.gz
    ├── 4e307b32273211904985e337f8cd6a5bd26278f0.nq.gz
    ├── 4e5e7757e28579c87f1aafef03e56f6c2f9346a0.nq.gz
    ├── 4e88aaff6a11cf69bbb0fb90fd9c9412b6ccbafd.nq.gz
    ├── 4f9df9df01076ea29367efd8b3497fad1571bba6.nq.gz
    ├── 50aea161037f6cb36209f24d34a450985d0bec09.nq.gz
    ├── 550b22c3b578acc36539658cb23d577a16ded138.nq.gz
    ├── 582a7e8b04a1d9ce9ad5fe690086c77414b6f30c.nq.gz
    ├── 587fe73e62089ba751d153ff616ca750d4bd11b1.nq.gz
    ├── 5881b85c5baa3f20ab47a73aba9bd851d69ca29a.nq.gz
    ├── 593977c3a6ec7a8ce88ef6e390bc3aa9f854793e.nq.gz
    ├── 59aa885b29a46887a317e7388b4b753fb5b7a965.nq.gz
    ├── 5e20c949836646e8ff02495c8e4c18e19777a3bd.nq.gz
    ├── 5e49910b05786c298146755a558db628cefe5634.nq.gz
    ├── 5fe80fc1d5c9f94dd9273abf4d8d4cb9f57e3969.nq.gz
    ├── 62a03bd0793c9fbab20fbe6747f59988eddf9ecd.nq.gz
    ├── 6603517ad694d2ca0db7230e89928510028c3c6a.nq.gz
    ├── 67956d347ad26b084afc44d3b675f9e0c1c6d5f2.nq.gz
    ├── 67f2a3179e247453c27c2868f5a2be1a7497ba27.nq.gz
    ├── 69f06be90545a54960ff2d894deb8de51d7ab792.nq.gz
    ├── 6abc692626508866ac4e6fe1a9ec72f96a151057.nq.gz
    ├── 70da27c80bbe52d20ad90768fc555d2bd50548c0.nq.gz
    ├── 71f20f3da813961a1b2b4571828533800c7889c9.nq.gz
    ├── 7311e909c36de1d2a61a1a04eabd42c16d9e9529.nq.gz
    ├── 731e3024d129e46bce3651196ea203364533d9a7.nq.gz
    ├── 75136cf1b3db081393f84afe34730628b92f3da1.nq.gz
    ├── 75760e1efed81c17077df86edb056ed8885c805f.nq.gz
    ├── 75ea85d7a0ab536bf49c1b29f3c5b2fa2e6b2b33.nq.gz
    ├── 770f7ab866c5458907516e95c0b9648e4ce3598c.nq.gz
    ├── 777d575894cf83e8bd3bd88aed0acb4b1417e18d.nq.gz
    ├── 7787c8cd3772ce9edb3c1fb0b2b4e878b3b677cb.nq.gz
    ├── 78b27c7036a8aa0b3e06ede5ddcd75789cd7d135.nq.gz
    ├── 7c719704386527a4cee592023a407de073a70ef2.nq.gz
    ├── 7e0292ca3b15ab1fb17e498887c075a7cadec117.nq.gz
    ├── 8264b2506443a2afc3c69a121c3d09753f0a8942.nq.gz
    ├── 834dcd4007f8ae00e486afbe44f0f659a3c26305.nq.gz
    ├── 854aa2dd5b3a5e67e81e4741be6ff85071f84a93.nq.gz
    ├── 8651f7f1029c011e8db215c38f2df07b3c33d113.nq.gz
    ├── 86e9bd02b04427bfd485b53950b5eba6af088141.nq.gz
    ├── 874396965905bebdc84fac98fcf1b14931b38635.nq.gz
    ├── 87859b93bfc4087c45b57e241bf177a7158ab8b6.nq.gz
    ├── 8b5504ecfbb1bfbb008957f80ac70f8fcdab91dd.nq.gz
    ├── 90ac179c6bb1f50e6e1eaf946087c58c94454a2e.nq.gz
    ├── 912fe945df469caa44812e3b685cebfca007bd12.nq.gz
    ├── 91b75440beed469261ffde799273ba63c431c8bc.nq.gz
    ├── 946402566052551533d4cafb23cfaa2ee4cd836d.nq.gz
    ├── 94b324ff0f5358fc62a05644beb276433c4ef3e8.nq.gz
    ├── 94dae58b500cf8bc2e1b178e11fb6d694c6bc2c1.nq.gz
    ├── 9541c7121011637b0572c2c660507a8664ba63bb.nq.gz
    ├── 98ce9d240c4e75f5391ff474c5000f3e99b23732.nq.gz
    ├── 9d55b483ffcaa82f7b6777570871a38dbe47b415.nq.gz
    ├── 9e0afda0d4c60d4dc0001604014d77eac7a2a9dd.nq.gz
    ├── a02d1e132d70e99aa4337bfc9c86fd09ae990f72.nq.gz
    ├── a15a965e07fe5e3ec7295541befcb12d7d1b5203.nq.gz
    ├── a1a2ebdadbcc33a01b5e1a0853074546f4d2e23d.nq.gz
    ├── a25278cedbe3e3af970580fa6e3d665e9cddd5de.nq.gz
    ├── a256c5c51baa423e4c2abc09afe0d369ee014868.nq.gz
    ├── a2a8af576b4a55d10f5c70498edc962cec7bc3e7.nq.gz
    ├── a4a994b4a81b1f02d6bb455c4eb53e3d7696aac6.nq.gz
    ├── a58ad33d32af8d70d3bc056bf9ce52eb62a8e899.nq.gz
    ├── a6374ac5d73af087d3b15e49d957265d6c572e92.nq.gz
    ├── a85c08bc499648fb7e0fcb274a4251eb6718fbf7.nq.gz
    ├── a8de6c53aba878ede9d004e885ac16d0f0a361fd.nq.gz
    ├── a9316e42405a3bdab3f8cd4bf49451d6222cd691.nq.gz
    ├── a95b1241b16fcc570eda38c6d51bdb700386b6f1.nq.gz
    ├── aa0ae56ce72cc351f0759bb02d357d45fe966d13.nq.gz
    ├── aac68e0dcd51f8501a075ce46969daabfdb3893a.nq.gz
    ├── ab098f5fff34c998efcbf371fabcb75dc0a4e908.nq.gz
    ├── ad72b36c3fddadf6c6eee47706fd552aef52c6cc.nq.gz
    ├── adee0ed1401653eb34858a3880efab98b0ff2c44.nq.gz
    ├── b1204c5cdc6f90be59e2c2da0a5a92f664588336.nq.gz
    ├── b50978d1921d045e9a9e2a53c0e9c7c5f4ec696a.nq.gz
    ├── b6a62e07950e4964ea6127cb1b5ddc33a94a0851.nq.gz
    ├── b85e1eb86c2c448b963c51ff84b930a41ef64429.nq.gz
    ├── ba1764127118ac67e409ef59b88b82c2000bc61d.nq.gz
    ├── ba25b584db9481d935579873404189407ae1212f.nq.gz
    ├── bbc5cc223948bc5f4306bf30671caff6e33bb613.nq.gz
    ├── bc9d2e95772624d90a52eacef8c49c85ac538d00.nq.gz
    ├── bcf0bbe4606097f609a791c8422c8012250bb851.nq.gz
    ├── bd84b20b5938de844d620b9992508487a7eb9712.nq.gz
    ├── bde5a1a8a11729db9202a55fb5486ecaa0894a78.nq.gz
    ├── bebc3651ce51cc87105f9419b41c9fb14c441314.nq.gz
    ├── bec008b2580aa105b30106e7c26457a0d698b5b8.nq.gz
    ├── bff135b6cdad0e548fc511e1769c421792cbfd67.nq.gz
    ├── c294ec39b880aee738ef4383654053f2539cf08f.nq.gz
    ├── c37db6973923364da52910600bdd0a7fecf1f91e.nq.gz
    ├── c50618a3c0b0c3552bc24fc0a9d8535457700e81.nq.gz
    ├── c63f908d54afecdb6a1a9825ded71ef74676f7c8.nq.gz
    ├── c78c369ed05679205456eb5a658de6df990a9b54.nq.gz
    ├── c8cfe762c673bd4b8a346bea94147249b6429d54.nq.gz
    ├── c9a98a16bbba6b75cd688cdb132013d023db3d99.nq.gz
    ├── ccf1039af5b7f35603a899a272042875fc65eef7.nq.gz
    ├── ccf1e8c9af490a0f3154af64eaa6cc2b756ba53f.nq.gz
    ├── ccf45e8e6cdbb1650b431ee260e35a4d1f6316a5.nq.gz
    ├── d1376d881889feb863c04da2edccb393529f1948.nq.gz
    ├── d246ea3de5ee3dce87feec1c43398dd943df26c2.nq.gz
    ├── d7ef2071e25cda09eba1107df1bd385d64b34703.nq.gz
    ├── d8403809d689400a387d1bd9b53e10687aca25fe.nq.gz
    ├── d93f6f7d08aac65e434de65c86c9077f5a4e991e.nq.gz
    ├── dae07fc98cbaa222354654faa9e1b07c2b79961c.nq.gz
    ├── dc8d6ac2166b3bbc13dc3af953c92df0446860cf.nq.gz
    ├── dd10bd5f4df4d30332f2d5bc33630be37424ab8f.nq.gz
    ├── dd49d0c0aa8512c78797246145bd665eb058a785.nq.gz
    ├── de38e7935d7c6f99e52c7c472bdcfe3b2cbd85ed.nq.gz
    ├── e0906bcbfebb6dd3842a23ad84d51f2260640f9d.nq.gz
    ├── e0ffebaaa644c3c1a79df91a777c236efa5d6c41.nq.gz
    ├── e1bf37843793a47e4c8b4b5ea70583ec2d0ab62a.nq.gz
    ├── e2a72d58a3b50caf024ff652271e4f26cdda3ea5.nq.gz
    ├── e2c6fb767a6cdb0ba9e1ed698c759f054d844909.nq.gz
    ├── e308a04e451cc6c5acbe03137ba9c839240b8cb6.nq.gz
    ├── e4865b796c339ee0f8846c05ce8b30c31ce4f5fd.nq.gz
    ├── e58b4fa5d6bcd941eb43930317f5752ac1e63ef0.nq.gz
    ├── e73df7dfa1e15107e6d16ffc0bd829b1dcbabf34.nq.gz
    ├── e83d5c1506ec705dc97fa232200578305b936734.nq.gz
    ├── e990c893f37c6dd283b7bcb4f5140cd9b3ca7b84.nq.gz
    ├── e9d6d571bf6ea6b52f5b4dbd4d9d539d617420d0.nq.gz
    ├── eacf6313373af338ec6335e8707bd10d92ab7f2e.nq.gz
    ├── ecbf0cb3fd59f7407988041df5b9c2413b62d279.nq.gz
    ├── ef27a393ca396952bcfd334041029a398e038933.nq.gz
    ├── f100604d24912a136ee15ade601f6f49de54f00d.nq.gz
    ├── f188d3a3fe5e6f0987377d959ed2cbac5498c059.nq.gz
    ├── f4429529a28b05104b128f9315bd0a0130beb504.nq.gz
    ├── f58353349bfce940f661f87b7da4209b8ac330d4.nq.gz
    ├── f58a8351dc88e7296a4f82955f13a249d1e65131.nq.gz
    ├── f611bfb88b21d5ae6ca318e8a26d8ed4c32b3346.nq.gz
    ├── f61c4c44e4dc6d03825e25134cf68517074b5cce.nq.gz
    ├── f62e2d24fa7dafbe6a17598381fd549e19cc05bc.nq.gz
    ├── f7912a616413d00837a4ba257009b163426a55ed.nq.gz
    ├── f8a3038d8ff77620c0b2e27436c8522d9aa9fa9f.nq.gz
    ├── f9bfa973bd1de0d9a171b3ef1691c2671d413951.nq.gz
    ├── fb40d5252f9dea859a4a0ca89dc2262488d7f4ad.nq.gz
    ├── fb7f2e96e71c028eb2e65dfe133a21620d8c2186.nq.gz
    ├── fc93c872cdd9dddeefd255581b3e59b8496faca9.nq.gz
    └── fdebe49f3e95f67016ab22f9ed0acd960ee38213.nq.gz

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

[dremin/RetroBar](https://github.com/dremin/RetroBar)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
