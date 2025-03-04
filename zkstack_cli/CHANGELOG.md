# Changelog

## [0.2.0](https://github.com/tahsintunan/zksync-era/compare/zkstack_cli-v0.1.2...zkstack_cli-v0.2.0) (2025-03-04)


### ⚠ BREAKING CHANGES

* **contracts:** gateway integration ([#1934](https://github.com/tahsintunan/zksync-era/issues/1934))
* **contracts:** integrate protocol defense changes ([#2737](https://github.com/tahsintunan/zksync-era/issues/2737))

### Features

* add `block.timestamp` asserter for AA ([#3031](https://github.com/tahsintunan/zksync-era/issues/3031)) ([069d38d](https://github.com/tahsintunan/zksync-era/commit/069d38d6c9ddd8b6c404596c479f94b9fc86db40))
* add custom DA support in external node ([#3445](https://github.com/tahsintunan/zksync-era/issues/3445)) ([1a8546d](https://github.com/tahsintunan/zksync-era/commit/1a8546ddcd6b126657a99f68576b2a837a4c416d))
* Add option to run prover images from tag ([#3120](https://github.com/tahsintunan/zksync-era/issues/3120)) ([3b532f5](https://github.com/tahsintunan/zksync-era/commit/3b532f5e363e0cb093221e6d064ce1a7d7428b52))
* base token integration tests ([#2509](https://github.com/tahsintunan/zksync-era/issues/2509)) ([8db7e93](https://github.com/tahsintunan/zksync-era/commit/8db7e9306e5fa23f066be106363e6455531bbc09))
* Compressor optimizations ([#3476](https://github.com/tahsintunan/zksync-era/issues/3476)) ([3e931be](https://github.com/tahsintunan/zksync-era/commit/3e931be6bddaacbd7d029c537db03a3c191fdc21))
* **consensus:** Added view_timeout to consensus config ([#3383](https://github.com/tahsintunan/zksync-era/issues/3383)) ([fc02a8f](https://github.com/tahsintunan/zksync-era/commit/fc02a8f1c9f0bffb438fb27769d6dced3ce14cd9))
* **consensus:** Update consensus dependencies ([#3339](https://github.com/tahsintunan/zksync-era/issues/3339)) ([aa9575f](https://github.com/tahsintunan/zksync-era/commit/aa9575fccbbc941f416d597256442afa974efd0a))
* **contract-verifier:** Adapt contract verifier API for EVM bytecodes ([#3234](https://github.com/tahsintunan/zksync-era/issues/3234)) ([4509179](https://github.com/tahsintunan/zksync-era/commit/4509179f62ead4b837dfb67760f52de76fac2e37))
* **contract-verifier:** add Etherscan contract verification ([#3609](https://github.com/tahsintunan/zksync-era/issues/3609)) ([a4ea0f2](https://github.com/tahsintunan/zksync-era/commit/a4ea0f2acae301e12338a862d6a76829899114d4))
* **contract-verifier:** Download compilers from GH automatically ([#3291](https://github.com/tahsintunan/zksync-era/issues/3291)) ([a10c4ba](https://github.com/tahsintunan/zksync-era/commit/a10c4baa312f26ebac2a10115fb7bd314d18b9c1))
* **contract-verifier:** Partial matching & automatic verification ([#3527](https://github.com/tahsintunan/zksync-era/issues/3527)) ([bf9fe85](https://github.com/tahsintunan/zksync-era/commit/bf9fe85f4fd1d739105e7b21d0eebb377f752bac))
* **contract-verifier:** Support Solidity contracts with EVM bytecode in contract verifier ([#3225](https://github.com/tahsintunan/zksync-era/issues/3225)) ([8a3a82c](https://github.com/tahsintunan/zksync-era/commit/8a3a82ca16479183e96505bc91011fc07bfc6889))
* **contracts:** gateway integration ([#1934](https://github.com/tahsintunan/zksync-era/issues/1934)) ([f06cb79](https://github.com/tahsintunan/zksync-era/commit/f06cb79883bf320f50089099e0abeb95eaace470))
* **contracts:** integrate protocol defense changes ([#2737](https://github.com/tahsintunan/zksync-era/issues/2737)) ([c60a348](https://github.com/tahsintunan/zksync-era/commit/c60a3482ee09b3e371163e62f49e83bc6d6f4548))
* **eigenda:** implement eigenDA client remaining features ([#3243](https://github.com/tahsintunan/zksync-era/issues/3243)) ([88fc971](https://github.com/tahsintunan/zksync-era/commit/88fc9714b42e3cb81dab970ec55b2bbfe0c49f52))
* **eth-watch:** Change protocol upgrade schema ([#3435](https://github.com/tahsintunan/zksync-era/issues/3435)) ([2c778fd](https://github.com/tahsintunan/zksync-era/commit/2c778fdd3fcd1e774bcb945f14a640ccf4227a2f))
* FFLONK support for compressor ([#3359](https://github.com/tahsintunan/zksync-era/issues/3359)) ([1a297be](https://github.com/tahsintunan/zksync-era/commit/1a297bedd226c56fc2ba02dc54d79129a271a1eb))
* gateway preparation ([#3006](https://github.com/tahsintunan/zksync-era/issues/3006)) ([16f2757](https://github.com/tahsintunan/zksync-era/commit/16f275756cd28024a6b11ac1ac327eb5b8b446e1))
* **gateway:** Add methods for token registration ([#3629](https://github.com/tahsintunan/zksync-era/issues/3629)) ([abf8d00](https://github.com/tahsintunan/zksync-era/commit/abf8d00266f6c482b1c48b371d391f7686f74381))
* **gateway:** Full indexing for token migration ([#3638](https://github.com/tahsintunan/zksync-era/issues/3638)) ([b5fbee6](https://github.com/tahsintunan/zksync-era/commit/b5fbee6abf6be2a7e6e8863508ce6266a12e0eb5))
* integrate gateway changes for some components ([#3274](https://github.com/tahsintunan/zksync-era/issues/3274)) ([cbc91e3](https://github.com/tahsintunan/zksync-era/commit/cbc91e35f84d04f2e4c8e81028596db009e478d1))
* make `zksync_types` thinner ([#3574](https://github.com/tahsintunan/zksync-era/issues/3574)) ([e7f93e4](https://github.com/tahsintunan/zksync-era/commit/e7f93e43dd55674a1442111cc1f08c9d229d3e22))
* Prover e2e test ([#2975](https://github.com/tahsintunan/zksync-era/issues/2975)) ([0edd796](https://github.com/tahsintunan/zksync-era/commit/0edd7962429b3530ae751bd7cc947c97193dd0ca))
* ProverJobProcessor & circuit prover ([#3287](https://github.com/tahsintunan/zksync-era/issues/3287)) ([98823f9](https://github.com/tahsintunan/zksync-era/commit/98823f95c0b95feeb37eb9086cc88d4ac5220904))
* Support stable compiler for VM (and some other crates) ([#3248](https://github.com/tahsintunan/zksync-era/issues/3248)) ([cbee99d](https://github.com/tahsintunan/zksync-era/commit/cbee99d8661b38aa6b49784c3934b8070a743fb4))
* Update EVM emulator feature in zkstack and zk ([#3397](https://github.com/tahsintunan/zksync-era/issues/3397)) ([e4848c5](https://github.com/tahsintunan/zksync-era/commit/e4848c51fb12e13f1be490b14847d15528c87171))
* **zk_toolbox:** Add EVM emulator option to `zkstack` CLI ([#3139](https://github.com/tahsintunan/zksync-era/issues/3139)) ([ffa18e1](https://github.com/tahsintunan/zksync-era/commit/ffa18e1d84a4bb1ca9b897fbc0a55b9e3ef0964c))
* **zk_toolbox:** Redesign zk_toolbox commands ([#3003](https://github.com/tahsintunan/zksync-era/issues/3003)) ([114834f](https://github.com/tahsintunan/zksync-era/commit/114834f357421c62d596a1954fac8ce615cfde49))
* **zkstack_cli:** Add --dev flag to chain init and genesis ([#3152](https://github.com/tahsintunan/zksync-era/issues/3152)) ([0aecae1](https://github.com/tahsintunan/zksync-era/commit/0aecae1e02d31d34d1ccc0ddf54617174d134e55))
* **zkstack_cli:** Add status page ([#3036](https://github.com/tahsintunan/zksync-era/issues/3036)) ([dd4b7cc](https://github.com/tahsintunan/zksync-era/commit/dd4b7cc94e324dfa5a86df09f0cf15642ea2f5c2))
* **zkstack_cli:** Autocompletion support ([#3097](https://github.com/tahsintunan/zksync-era/issues/3097)) ([b29be7d](https://github.com/tahsintunan/zksync-era/commit/b29be7d9a8c664beac5d8384548db54de0ba882f))
* **zkstack_cli:** Build dependencies at zkstack build time ([#3157](https://github.com/tahsintunan/zksync-era/issues/3157)) ([724d9a9](https://github.com/tahsintunan/zksync-era/commit/724d9a9c7f2127263845b640c843e751fd3c21ae))
* **zkstack_cli:** use docker-managed volumes ([#3140](https://github.com/tahsintunan/zksync-era/issues/3140)) ([ee73a39](https://github.com/tahsintunan/zksync-era/commit/ee73a3973b0c65b1d4acef12e4b64db8f813e77d))
* **zkstack_cli:** Use the same rust toolchain as main repo ([#3230](https://github.com/tahsintunan/zksync-era/issues/3230)) ([e69d15b](https://github.com/tahsintunan/zksync-era/commit/e69d15b6a80c36a19648a8dd90f567d1e5e108e9))
* **zkstack:** Introduce `build` and `wait` subcommands for components ([#3240](https://github.com/tahsintunan/zksync-era/issues/3240)) ([e92b806](https://github.com/tahsintunan/zksync-era/commit/e92b8068d71fec032e498793ff97e329c3d073e0))


### Bug Fixes

* add deploy timestamp asserter command ([#3252](https://github.com/tahsintunan/zksync-era/issues/3252)) ([88a8940](https://github.com/tahsintunan/zksync-era/commit/88a89405898653bf9e1a35a1374e000a8d67cf51))
* **consensus:** payload encoding protected by protocol_version ([#3168](https://github.com/tahsintunan/zksync-era/issues/3168)) ([8089b78](https://github.com/tahsintunan/zksync-era/commit/8089b78b3f2cdbe8d0a23e9b8412a8022d78ada2))
* Fix wrong in ERC20 deployment file name ([#3395](https://github.com/tahsintunan/zksync-era/issues/3395)) ([18e4307](https://github.com/tahsintunan/zksync-era/commit/18e4307324f26902ef67ba587d324bf35aa09735))
* **gateway:** correct root hash / chain creation params ([#3613](https://github.com/tahsintunan/zksync-era/issues/3613)) ([dd67d28](https://github.com/tahsintunan/zksync-era/commit/dd67d289731df993c0a345106b3d52410e675d6c))
* return back new chain creation/genesis params ([#3640](https://github.com/tahsintunan/zksync-era/issues/3640)) ([1781608](https://github.com/tahsintunan/zksync-era/commit/17816081c8965e16ec9d59e2cf2054fbe51bdd45))
* revert "fix(gateway): correct root hash / chain creation params" ([#3631](https://github.com/tahsintunan/zksync-era/issues/3631)) ([f813f9d](https://github.com/tahsintunan/zksync-era/commit/f813f9da9ec3be181d0989bffede75ccdd101d3a))
* Run `zkstack dev lint -t autocompletion` to make CI happy. ([#3196](https://github.com/tahsintunan/zksync-era/issues/3196)) ([1f8ad26](https://github.com/tahsintunan/zksync-era/commit/1f8ad26c7c9757ffa13de1a2fd045fa9e16de5f6))
* **zk_toolbox:** Fix path to prover data handler port ([#3542](https://github.com/tahsintunan/zksync-era/issues/3542)) ([e3759a2](https://github.com/tahsintunan/zksync-era/commit/e3759a27158b2d6202fca19ada5344ddff36685b))
* zkstack readme update broken links and wording ([#3375](https://github.com/tahsintunan/zksync-era/issues/3375)) ([ee117a8](https://github.com/tahsintunan/zksync-era/commit/ee117a81e7708eece5639921e32b6683fbcb2280))
* **zkstack_cli:** default core_object_store path ([#3658](https://github.com/tahsintunan/zksync-era/issues/3658)) ([4ee2f55](https://github.com/tahsintunan/zksync-era/commit/4ee2f55499e740811a31d762b2c63a2f51fd1390))
* **zkstack_cli:** make progress bar optional in non-terminal envs ([#3146](https://github.com/tahsintunan/zksync-era/issues/3146)) ([5092031](https://github.com/tahsintunan/zksync-era/commit/5092031050b30c39107df788317a15eaa921b136))
* **zkstack:** Fix loading genesis before cloning zksync-era repo ([#3271](https://github.com/tahsintunan/zksync-era/issues/3271)) ([271033f](https://github.com/tahsintunan/zksync-era/commit/271033fe58184252243b2ce7fe3a5a9be919b140))
* **zkstack:** Fix wrong missing private key message ([#3334](https://github.com/tahsintunan/zksync-era/issues/3334)) ([aaca32b](https://github.com/tahsintunan/zksync-era/commit/aaca32b6ab411d5cdc1234c20af8b5c1092195d7))
* **zkstack:** Move installation always to .local/bin ([#3108](https://github.com/tahsintunan/zksync-era/issues/3108)) ([223e4dd](https://github.com/tahsintunan/zksync-era/commit/223e4dd59414904f2b26afffc4b72bb78266b783))
* **zkstack:** shouldn't attempt to create db on migrate command ([#3468](https://github.com/tahsintunan/zksync-era/issues/3468)) ([c156e79](https://github.com/tahsintunan/zksync-era/commit/c156e791c1d8bbdea32873f43e976d35b228d38e))

## [0.1.2](https://github.com/matter-labs/zksync-era/compare/zk_toolbox-v0.1.1...zk_toolbox-v0.1.2) (2024-08-20)


### Features

* Poll the main node API for attestation status - relaxed (BFT-496) ([#2583](https://github.com/matter-labs/zksync-era/issues/2583)) ([b45aa91](https://github.com/matter-labs/zksync-era/commit/b45aa9168dd66d07ca61c8bb4c01f73dda822040))
* update base token rate on L1 ([#2589](https://github.com/matter-labs/zksync-era/issues/2589)) ([f84aaaf](https://github.com/matter-labs/zksync-era/commit/f84aaaf723c876ba8397f74577b8c5a207700f7b))
* **zk_toolbox:** Add installation script ([#2569](https://github.com/matter-labs/zksync-era/issues/2569)) ([009cd97](https://github.com/matter-labs/zksync-era/commit/009cd9771821a7ae356356f97813d74fab8512b5))
* **zk_toolbox:** Add lint command ([#2626](https://github.com/matter-labs/zksync-era/issues/2626)) ([3d02946](https://github.com/matter-labs/zksync-era/commit/3d0294695343e11b62fdc7375e6c3bc3a72ffcd9))
* **zk_toolbox:** Add observability interactive option ([#2592](https://github.com/matter-labs/zksync-era/issues/2592)) ([3aeaaed](https://github.com/matter-labs/zksync-era/commit/3aeaaedcf9b41b3a033acfa0ec08e3bf966ab4a9))
* **zk_toolbox:** Add zk_supervisor run unit tests command ([#2610](https://github.com/matter-labs/zksync-era/issues/2610)) ([fa866cd](https://github.com/matter-labs/zksync-era/commit/fa866cd5c7b1b189901b4f7ce6f91886e7aec7e4))
* **zk_toolbox:** Add zk_supervisor test l1 contracts command ([#2613](https://github.com/matter-labs/zksync-era/issues/2613)) ([931e452](https://github.com/matter-labs/zksync-era/commit/931e4529d964d01268cb5965877f3d81d32c921e))
* **zk_toolbox:** Add zk_supervisor test prover command ([#2614](https://github.com/matter-labs/zksync-era/issues/2614)) ([0fe173b](https://github.com/matter-labs/zksync-era/commit/0fe173bd8b337637f457542e0d675cf42b6ecc65))
* **zk_toolbox:** allow to run `zk_inception chain create` non-interactively ([#2579](https://github.com/matter-labs/zksync-era/issues/2579)) ([555fcf7](https://github.com/matter-labs/zksync-era/commit/555fcf79bc950f79e218697be9f1a316e4723322))
* **zk_toolbox:** Minting base token ([#2571](https://github.com/matter-labs/zksync-era/issues/2571)) ([ae2dd3b](https://github.com/matter-labs/zksync-era/commit/ae2dd3bbccdffc25b040313b2c7983a936f36aac))
* **zk_toolbox:** Run formatters and linterrs ([#2675](https://github.com/matter-labs/zksync-era/issues/2675)) ([caedd1c](https://github.com/matter-labs/zksync-era/commit/caedd1c86eedd94f8628bd2ba1cf875cad9a53d1))


### Bug Fixes

* Bump prover dependencies & rust toolchain ([#2600](https://github.com/matter-labs/zksync-era/issues/2600)) ([849c6a5](https://github.com/matter-labs/zksync-era/commit/849c6a5dcd095e8fead0630a2a403f282c26a2aa))
* **zk_toolbox:** Do not panic during mint ([#2658](https://github.com/matter-labs/zksync-era/issues/2658)) ([1a8ee90](https://github.com/matter-labs/zksync-era/commit/1a8ee90d9d6578492806bd0a337ef203db32f6c9))
* **zk_toolbox:** Get l1-network config param from flag ([#2603](https://github.com/matter-labs/zksync-era/issues/2603)) ([553d307](https://github.com/matter-labs/zksync-era/commit/553d307217282b18c2c3d7cc6f340f529bb4ade2))

## [0.1.1](https://github.com/matter-labs/zksync-era/compare/zk_toolbox-v0.1.0...zk_toolbox-v0.1.1) (2024-08-02)


### Features

* Add recovery tests to zk_supervisor ([#2444](https://github.com/matter-labs/zksync-era/issues/2444)) ([0c0d10a](https://github.com/matter-labs/zksync-era/commit/0c0d10af703d3f8958c49d0ed46d6cda64945fa1))
* add revert tests (external node) to zk_toolbox ([#2408](https://github.com/matter-labs/zksync-era/issues/2408)) ([3fbbee1](https://github.com/matter-labs/zksync-era/commit/3fbbee10be99e8c5a696bfd50d81230141bccbf4))
* add revert tests to zk_toolbox ([#2317](https://github.com/matter-labs/zksync-era/issues/2317)) ([c9ad002](https://github.com/matter-labs/zksync-era/commit/c9ad002d17ed91d1e5f225e19698c12cb3adc665))
* add zk toolbox ([#2005](https://github.com/matter-labs/zksync-era/issues/2005)) ([60a633b](https://github.com/matter-labs/zksync-era/commit/60a633b23eaf25658d86f090e7954843d4daca42))
* Adding SLChainID ([#2547](https://github.com/matter-labs/zksync-era/issues/2547)) ([656e830](https://github.com/matter-labs/zksync-era/commit/656e830e4fd60b5ace87dfc1604a102f06ae59e1))
* Base Token Fundamentals ([#2204](https://github.com/matter-labs/zksync-era/issues/2204)) ([39709f5](https://github.com/matter-labs/zksync-era/commit/39709f58071ac77bfd447145e1c3342b7da70560))
* change `zkSync` occurences to `ZKsync` ([#2227](https://github.com/matter-labs/zksync-era/issues/2227)) ([0b4104d](https://github.com/matter-labs/zksync-era/commit/0b4104dbb996ec6333619ea05f3a99e6d4f3b8fa))
* **configs:** Do not panic if config is only partially filled ([#2545](https://github.com/matter-labs/zksync-era/issues/2545)) ([db13fe3](https://github.com/matter-labs/zksync-era/commit/db13fe3550598c69f59cd66b4bb9618ebea041ca))
* **eth-watch:** Integrate decentralized upgrades ([#2401](https://github.com/matter-labs/zksync-era/issues/2401)) ([5a48e10](https://github.com/matter-labs/zksync-era/commit/5a48e1026260024c6ae2b4d1100ee9b798a83e8d))
* L1 batch signing (BFT-474) ([#2414](https://github.com/matter-labs/zksync-era/issues/2414)) ([ab699db](https://github.com/matter-labs/zksync-era/commit/ab699dbe8cffa8bd291d6054579061b47fd4aa0e))
* Minimal External API Fetcher ([#2383](https://github.com/matter-labs/zksync-era/issues/2383)) ([9f255c0](https://github.com/matter-labs/zksync-era/commit/9f255c073cfdab60832fcf9a6d3a4a9258641ef3))
* Poll the main node for the next batch to sign (BFT-496) ([#2544](https://github.com/matter-labs/zksync-era/issues/2544)) ([22cf820](https://github.com/matter-labs/zksync-era/commit/22cf820abbd14b852dffe60f6b564713fe4c8919))
* Revisit base config values ([#2532](https://github.com/matter-labs/zksync-era/issues/2532)) ([3fac8ac](https://github.com/matter-labs/zksync-era/commit/3fac8ac62cc9ac14845f32240af9241386f4034d))
* Support sending logs via OTLP ([#2556](https://github.com/matter-labs/zksync-era/issues/2556)) ([1d206c0](https://github.com/matter-labs/zksync-era/commit/1d206c0af8f28eb00eb1498d6f2cdbb45ffef72a))
* Switch to using crates.io deps ([#2409](https://github.com/matter-labs/zksync-era/issues/2409)) ([27fabaf](https://github.com/matter-labs/zksync-era/commit/27fabafbec66bf4cb65c4fa9e3fab4c3c981d0f2))
* **toolbox:** add format and clippy to zk_toolbox ci ([#2100](https://github.com/matter-labs/zksync-era/issues/2100)) ([49a5c3a](https://github.com/matter-labs/zksync-era/commit/49a5c3abb8b8eb3de0146286f9b3fffe26f545ae))
* **toolbox:** add verify to zk-toolbox ([#2013](https://github.com/matter-labs/zksync-era/issues/2013)) ([23a545c](https://github.com/matter-labs/zksync-era/commit/23a545c51b537af28c084c0f87ce2ebff5a3bbb8))
* **toolbox:** add zk supervisor database commands ([#2051](https://github.com/matter-labs/zksync-era/issues/2051)) ([f99739b](https://github.com/matter-labs/zksync-era/commit/f99739b225286ed8fae648e9a40c5311efe17648))
* **toolbox:** add zk_toolbox ci ([#1985](https://github.com/matter-labs/zksync-era/issues/1985)) ([4ab4922](https://github.com/matter-labs/zksync-era/commit/4ab492201a1654a254c0b14a382a2cb67e3cb9e5))
* **toolbox:** refactor config to its own crate ([#2063](https://github.com/matter-labs/zksync-era/issues/2063)) ([5cfcc24](https://github.com/matter-labs/zksync-era/commit/5cfcc24e92329ba8452d9cec0eb173a54b1dec2f))
* Update to consensus 0.1.0-rc.4 (BFT-486) ([#2475](https://github.com/matter-labs/zksync-era/issues/2475)) ([ff6b10c](https://github.com/matter-labs/zksync-era/commit/ff6b10c4a994cf70297a034202bcb55152748cba))
* **vlog:** New vlog interface + opentelemtry improvements ([#2472](https://github.com/matter-labs/zksync-era/issues/2472)) ([c0815cd](https://github.com/matter-labs/zksync-era/commit/c0815cdaf878afcd9c41dddd9fe56bcf8d910633))
* **zk toolbox:** External node support ([#2287](https://github.com/matter-labs/zksync-era/issues/2287)) ([6384cad](https://github.com/matter-labs/zksync-era/commit/6384cad26aead4d1bdbb606a97d623dacebf912c))
* **zk_toolbox:** Add check for zksync repo path ([#2447](https://github.com/matter-labs/zksync-era/issues/2447)) ([f1cbb74](https://github.com/matter-labs/zksync-era/commit/f1cbb74b863b6e0bcfa74ad780beef29844bac6e))
* **zk_toolbox:** Add contract verifier support for zk toolbox ([#2420](https://github.com/matter-labs/zksync-era/issues/2420)) ([d10a24b](https://github.com/matter-labs/zksync-era/commit/d10a24b3426b0eb13aef9cedfb1c38cbedfb5a7e))
* **zk_toolbox:** Add grafana support ([#2557](https://github.com/matter-labs/zksync-era/issues/2557)) ([f5aaefe](https://github.com/matter-labs/zksync-era/commit/f5aaefe51d3ff4a3365adde6120b874c7c4c68c0))
* **zk_toolbox:** Add prover generate-sk command ([#2222](https://github.com/matter-labs/zksync-era/issues/2222)) ([40e0a95](https://github.com/matter-labs/zksync-era/commit/40e0a956e86583a713d6aacdc61c625931f68e1c))
* **zk_toolbox:** Add prover init command ([#2298](https://github.com/matter-labs/zksync-era/issues/2298)) ([159af3c](https://github.com/matter-labs/zksync-era/commit/159af3c54cc9beb742b2ab43ce3b89b14c8368b7))
* **zk_toolbox:** Add prover run ([#2272](https://github.com/matter-labs/zksync-era/issues/2272)) ([598ef7b](https://github.com/matter-labs/zksync-era/commit/598ef7b73cf141007d2cf031b21fce4744eec44f))
* **zk_toolbox:** add test upgrade subcommand to zk_toolbox ([#2515](https://github.com/matter-labs/zksync-era/issues/2515)) ([1a12f5f](https://github.com/matter-labs/zksync-era/commit/1a12f5f908add42c090170a2f4fb26b731d6971b))
* **zk_toolbox:** Add update command ([#2440](https://github.com/matter-labs/zksync-era/issues/2440)) ([e2fa86f](https://github.com/matter-labs/zksync-era/commit/e2fa86fd216b04c798939f80517d7cca1a45a5a7))
* **zk_toolbox:** Allow toolbox find Zkstack.yaml in parent dirs ([#2430](https://github.com/matter-labs/zksync-era/issues/2430)) ([0957119](https://github.com/matter-labs/zksync-era/commit/095711920bc2193a8b036c9563fa89dfcea433e5))
* **zk_toolbox:** Clean command ([#2387](https://github.com/matter-labs/zksync-era/issues/2387)) ([52a4680](https://github.com/matter-labs/zksync-era/commit/52a4680ed26e755b860e3b97c79618a0c20cb696))
* **zk_toolbox:** Dev command ([#2347](https://github.com/matter-labs/zksync-era/issues/2347)) ([f508ac1](https://github.com/matter-labs/zksync-era/commit/f508ac1f0edba8d267e6b46346a4227149ac7518))
* **zk_toolbox:** Implement default upgrader deployment ([#2526](https://github.com/matter-labs/zksync-era/issues/2526)) ([6d86959](https://github.com/matter-labs/zksync-era/commit/6d8695922689de22e683fe7c318e64f5c9a2144d))
* **zk_toolbox:** resume functionality ([#2376](https://github.com/matter-labs/zksync-era/issues/2376)) ([e5e0473](https://github.com/matter-labs/zksync-era/commit/e5e047393f7cdf1105a0c65f78cd2ec605e1182d))
* **zk_toolbox:** Small adjustment for zk toolbox ([#2424](https://github.com/matter-labs/zksync-era/issues/2424)) ([ce43c42](https://github.com/matter-labs/zksync-era/commit/ce43c422fddccfe88c07ee22a2b8726dd0bd5f61))
* **zk_toolbox:** Update prover support ([#2533](https://github.com/matter-labs/zksync-era/issues/2533)) ([63c92b6](https://github.com/matter-labs/zksync-era/commit/63c92b6205fb156f4b50dee581674b814f44f874))
* **zk_toolbox:** Update reamde for toolbox  ([#2531](https://github.com/matter-labs/zksync-era/issues/2531)) ([d5ba7d8](https://github.com/matter-labs/zksync-era/commit/d5ba7d89fc8b97257b849f75ba6f7a2ad1aeb0d6))
* **zk_toolbox:** use configs from the main repo ([#2470](https://github.com/matter-labs/zksync-era/issues/2470)) ([4222d13](https://github.com/matter-labs/zksync-era/commit/4222d135b62eb4de103c4aebb35e9c302d94ad63))
* **zk_toolbox:** Use docker compose instead of docker-compose ([#2195](https://github.com/matter-labs/zksync-era/issues/2195)) ([2f528ec](https://github.com/matter-labs/zksync-era/commit/2f528ec8d49cb31ef714b409c703ae9f99cc5551))
* **zk_toolbox:** use low level command for running verbose command" ([#2358](https://github.com/matter-labs/zksync-era/issues/2358)) ([29671c8](https://github.com/matter-labs/zksync-era/commit/29671c81684d605ec3350ded1b7dd55d04ba0859))
* **zk-toolbox:** add balance check ([#2016](https://github.com/matter-labs/zksync-era/issues/2016)) ([a8b8e4b](https://github.com/matter-labs/zksync-era/commit/a8b8e4b1b1a3f91b1a52762f2fd30006d323e348))
* **zk-toolbox:** Deploy custom token ([#2329](https://github.com/matter-labs/zksync-era/issues/2329)) ([3a8fed4](https://github.com/matter-labs/zksync-era/commit/3a8fed4c295fa5c0102820fc0103306e31d03815))


### Bug Fixes

* **api:** correct default fee data in eth call ([#2072](https://github.com/matter-labs/zksync-era/issues/2072)) ([e71f6f9](https://github.com/matter-labs/zksync-era/commit/e71f6f96bda08f8330c643a31df4ef9e82c9afc2))
* disable localhost wallets on external network interaction ([#2212](https://github.com/matter-labs/zksync-era/issues/2212)) ([a00317d](https://github.com/matter-labs/zksync-era/commit/a00317dd05af115b396f2f150289e91882e99759))
* **house-keeper:** Fix queue size queries ([#2106](https://github.com/matter-labs/zksync-era/issues/2106)) ([183502a](https://github.com/matter-labs/zksync-era/commit/183502a17eb47a747f50b6a9d38ab78de984f80e))
* **toolbox:** Temporary disable fast mode for deploying l1 contracts … ([#2011](https://github.com/matter-labs/zksync-era/issues/2011)) ([2a1d37b](https://github.com/matter-labs/zksync-era/commit/2a1d37b16b9ccd1f2ce87f61a1b054cdedfd7d1e))
* update rust toolchain version ([#2047](https://github.com/matter-labs/zksync-era/issues/2047)) ([9fe5212](https://github.com/matter-labs/zksync-era/commit/9fe5212ab7b65a63bc53dcf439a212953845ed13))
* **zk_toolbox:** Add chain id for local wallet ([#2041](https://github.com/matter-labs/zksync-era/issues/2041)) ([8e147c1](https://github.com/matter-labs/zksync-era/commit/8e147c11f3ae51e9bdb0cd3e6bfa6919995b3fba))
* **zk_toolbox:** Fix error with balances ([#2034](https://github.com/matter-labs/zksync-era/issues/2034)) ([5d23a3e](https://github.com/matter-labs/zksync-era/commit/5d23a3e44dbe22f4377c6d1042c7b8c03b14c556))
* **zk_toolbox:** Fix installation guide ([#2035](https://github.com/matter-labs/zksync-era/issues/2035)) ([e9038be](https://github.com/matter-labs/zksync-era/commit/e9038bebddb6079ebd76ac01b7ed6068de4bc979))
* **zk_toolbox:** Fix protocol version ([#2118](https://github.com/matter-labs/zksync-era/issues/2118)) ([67f6080](https://github.com/matter-labs/zksync-era/commit/67f60805084de46945a1ae8dfd4aa6b0debc006d))
* **zk_toolbox:** improve readme to include containers command and cd ([#2073](https://github.com/matter-labs/zksync-era/issues/2073)) ([5e5628f](https://github.com/matter-labs/zksync-era/commit/5e5628fc841daaaad229d637202e9342acc2354f))
* **zk_toolbox:** Move l1 rpc to init stage ([#2074](https://github.com/matter-labs/zksync-era/issues/2074)) ([c127ff1](https://github.com/matter-labs/zksync-era/commit/c127ff172cdce8aa0a81887833334d88f1b2ddac))
* **zk_toolbox:** readme added dependencies section and cleaned up ([#2044](https://github.com/matter-labs/zksync-era/issues/2044)) ([78244c7](https://github.com/matter-labs/zksync-era/commit/78244c7e04813b505a9a4285403b092abd827e04))
* **zk_toolbox:** Set proper pubdata sending mode  ([#2507](https://github.com/matter-labs/zksync-era/issues/2507)) ([21fbd77](https://github.com/matter-labs/zksync-era/commit/21fbd77b8c4379b180abcd296a6c74697967acd8))
* **zk_toolbox:** Show balance ([#2254](https://github.com/matter-labs/zksync-era/issues/2254)) ([f1d9f03](https://github.com/matter-labs/zksync-era/commit/f1d9f03ba32081d34a6a24e94b63fb494a33663e))
* **zk_toolbox:** Some small nit ([#2023](https://github.com/matter-labs/zksync-era/issues/2023)) ([4e96e32](https://github.com/matter-labs/zksync-era/commit/4e96e32861337dfa56f4d3daacdc4a7d8610a331))
* **zk_toolbox:** Use both folders for loading contracts  ([#2030](https://github.com/matter-labs/zksync-era/issues/2030)) ([97c6d5c](https://github.com/matter-labs/zksync-era/commit/97c6d5c9c2d9dddf0b18391077c8828e5dc7042b))
* **zk_toolbox:** Use existing ecosystem ([#2534](https://github.com/matter-labs/zksync-era/issues/2534)) ([99fd2bd](https://github.com/matter-labs/zksync-era/commit/99fd2bd6aa2eaa3490c45dd9ac70298aae80d82f))
* **zk_toolbox:** Use slug crate instead of self written function ([#2309](https://github.com/matter-labs/zksync-era/issues/2309)) ([a61f273](https://github.com/matter-labs/zksync-era/commit/a61f273ca0806754cbad12b1cddb247f22459688))
* **zk_toolbox:** Use the same l2 address for shared and erc20 bridge ([#2260](https://github.com/matter-labs/zksync-era/issues/2260)) ([26f2010](https://github.com/matter-labs/zksync-era/commit/26f2010ea2edd1cb79d80852c626051afc473c48))
* **zk_tool:** Change some texts ([#2027](https://github.com/matter-labs/zksync-era/issues/2027)) ([a6232c5](https://github.com/matter-labs/zksync-era/commit/a6232c51c22e0f5229a0e156dd88b3f9573363c3))
* zk-toolbox integration tests ci ([#2226](https://github.com/matter-labs/zksync-era/issues/2226)) ([3f521ac](https://github.com/matter-labs/zksync-era/commit/3f521ace420d3f65e5612c2b6baf096c391ffd7c))


### Reverts

* "feat: Poll the main node for the next batch to sign (BFT-496)" ([#2574](https://github.com/matter-labs/zksync-era/issues/2574)) ([72d3be8](https://github.com/matter-labs/zksync-era/commit/72d3be87efcb059f70b4633cddd707346612c4db))
