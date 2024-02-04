# Changelog

## [main] - 2024-02-04

### Bug Fixes

- ✨ optional inputs of colored image ([cd32f26](cd32f26b167088d6b489e43b260c187ea5e4d223)) by @ScottNealon in #147
- 📝 adds a way to not load the imagefeed ([501c330](501c3301056b2851555cccd75ab3ff15b1ab8e0c))
- 🐛 colored image mask input ([30c4311](30c4311b69f6481a34f968cb67a9b5ce5d2e9fda))
- 🐛 handle font cache errors ([c43a661](c43a661ba31dcd7720b4f32d8e96760e6191fbd9))
- 💄 register the COLOR type even for external extensions ([12b134a](12b134ab4c937c192aaf4a3667d9885dd4fe43ca))
- ✨ mask crop output ([59a361a](59a361af5870b8ffc984c6680dd3282d3553dcf9))
- 🚑️ thread font loading ([e4da832](e4da832b99bd640b72c31b67178a3168e3238fa0))
- 📦 changed way of creating bbox from mask ([14ee9e2](14ee9e23c009ab55fa3b2fc6ec60fb683c46d57d)) by @Yurchikian in #124
- ✨ expose invert of bboxfrommask ([53cb503](53cb503866da6d83b47eaeb8073039ace2ae0a95))
- ✨ less strict csv parsing ([d5c4c5f](d5c4c5f2649ecdb4bf7b517c5b33bbf8df753047))
- 🐛 fit number regression ([c8658df](c8658dfbdd3a0ca8c3e88cd1adfddc55c7444045))
- 🐛 remove uneeded installs ([4e07450](4e07450bcabb0105b5610e52f7d4692ea07f9c1d))
- 🐛 import issue ([255ac03](255ac036bab1d776301857843d0e7a85e9a9dcb8))
- 🐛 wrong output for bbox ([8d12b59](8d12b59844958fbc696d01d51162f97262664ae9))
- 🚑️ fallback when symlink detection fails ([278f22c](278f22c2093b6eca63d2d00f7936774918707e4e))
- ✨ handle malformed styles.csv ([e6f6502](e6f65026735770df8aced4a3acb75550ff1c84da))
- 🐛 encoding ([5af2840](5af284067c65042bcdfff04a5d5a2360bf9e4af7))
- ⚡️ add the cli deps ([bb90e04](bb90e0415f6a1ececbf468815dc0f5959d9a34e8))
- 🚑️ check for symlink ([25b933c](25b933c698b250a411549d2600fae49bec225b7a))
- 🚑️ remove problematic dependencies ([5dfea51](5dfea51dd8db2a4829e559eadeda22374b51c8a4))
- 🐛 batch support ([f1ff9fc](f1ff9fc7c4684ad673c3178df3b8142dcf0b16ac))
- 🐛 automatically disable tiling if seamless is on ([4605f74](4605f74f370d4d221ab1d50f21b72910fa6909c7))
- 🐛 debug node ([dc500b7](dc500b788e885205f017956da6a71a677f822941))
- ⚡️ hack to handle prompt validation ([d49b257](d49b2578c247dcba9b09b374d99f5cc45cac172d))
- ✨ deepbump update ([87b245c](87b245c6a6895490e3612b235879fa90b62dea2b))
- 👷 user folder_paths to retrieve comfy root ([38df58a](38df58a78c363ef2657011893d4d811676b1c664))
- 🐛 typo ([90aee83](90aee83797a863cf4797cdbe187f949061cbd176))
- 🐛 do not resolve symlink for "here" ([a50b11b](a50b11bdaa66f4e805811b1676c937ade11318c2))
- ✏️ use Union to allow support for <3.10 ([88a2779](88a277968745ac990406b14d300a8ada9c575b11)) by @M1kep in #91
- ⚡️ simplify widgets cleanup ([cdd098e](cdd098e10258401402b8023c9143532cfa4a1745))
- ✨ don't assume the install was ran ([cc43654](cc43654af2987bc8860557caa99cde91e8309b21))
- 🐛 install ([616b2bf](616b2bfc6c629cef1d30cb0d717bd805c3a086aa))
- 🐛 properly escape paths ([22cac9b](22cac9b2d95910197941b73e7548735470bd3b17))
- 🐛 use relative paths in JS ([e2773ff](e2773ff22e43e7756ad618344a03d661a576cf35))
- 💄 BatchFromHistory when "listening" ([3b07984](3b07984716402fbbf5da41020bf73befd52e7ebf))
- ✨ save gif widget removal ([fe8f519](fe8f519f8860b0610d8cafcd9b843b4171c2b3d4))

### Documentation

- 📄 add note+ screenshot ([90d9636](90d96366c8b7637b55d1b4f88cb9aca217c1414b))
- 📝 add cover image ([6b993b8](6b993b84071bbb80ba1b8bd63576f31e35d05590))
- 📝 fix image size ([3e8c2fe](3e8c2fe789925e7017c2f8c8d9164c139588aba4))
- 📝 add image ([3e93ea6](3e93ea6f2c73353891b1a3f6223b5730bc69df37))
- 📝 explain optional nodes ([cea0b08](cea0b08eb044756ab1b408f630435095b8969d36))
- 📝 add the example previews from the wiki ([8f90986](8f909864bfaa9f2d0fbdcf3942eacb9d78ee8fb8))
- 📝 update node list ([4917e31](4917e31c427c74d28c830fd7b2423cab393ba0f8))
- 📝 add some deprecation warnings and recommendations ([e11df9d](e11df9d45c81d93f4334841de036b4aa3364375a))
- 📝 add a reference to SlickComfy for colab ([bb35098](bb35098c656b0b2d30909b83df0a3b65c5975f78))

### Features

- ✨ add note+ example ([90f3bc2](90f3bc2d953b299ea34e9e3a925f1a824b488855))
- 💄 node+ improvements ([4b29395](4b29395000254382882c0d1be115b2ed80cd7c99))
- 📝 add note plus ([605c8db](605c8db320e1531c6347f6888606fa50d8eb268b))
- 🚧 add playlist nodes ([cf96572](cf965727e8e7064328704d88cd0410c61f1e686e))
- 🚨 add missing node ([16c1a59](16c1a59312b1d9841f5f8a814eff93a1ddf04edb))
- ✨ Math Expression node ([142624e](142624eea616a5622387b1b641c02605455ee6f1))
- 🚀 add optional inputs to colored image ([049983d](049983dbe2dbce6b772908468c4042d2bfde5eb2))
- ✨ Add support for extra_model_paths.yaml ([d7b8ac8](d7b8ac8e0c98b0d7a2e21889d35aad9f6b093560))
- ✨ add batch shake ([af94203](af94203d1b461d934ca1c44211ca0f71a5d05d48))
- ✨ enhance concat images ([a798eb0](a798eb07d0d891cfbd47013b442ef2fa3d7cc5bc))
- 💄 add a few more batch nodes ([c1d42de](c1d42de0fcde86d2a167fb4b5e781ee987814da2))
- ✨ Batch node utilities ([cef5023](cef5023efc17366a2e937ef43944de3587707fac))
- 🚨 Image Stack node (horizontal and vertical stack) ([bb3277d](bb3277d85f4ca21735cb1f5237cb1430db88c183))
- 🚀 add seamless model hack ([21acc87](21acc87ff0a84b7588f4b5aae0aeb5ae94bbbfbe))
- 🔧 debug handle a few more types ([638498c](638498c6b47c2b2cab82f76aec1f3d46df67f263))
- 🎨 Add an editor for the styles loader ([2faa2f2](2faa2f2a148a4dbf5525e4945f688a239f244546))
- ✨ add a static assets path ([6a00d1d](6a00d1da5a8a5fa47af1bf1ab5d3cd206c599841))
- ✨ add  Interpolate Clip Sequential ([a71c273](a71c273baf450ad7e2a7e032451f015d3be3e9e9))

### Miscellaneous Tasks

- 🔖 local updates ([6c5e5d3](6c5e5d36379bdab223b4503e42b7956b55a82ab0))
- 📝 update node list ([dd27f99](dd27f990c72fa94aff205eb314a8ea360f57479e))
- ✨ update node_list ([537a0d8](537a0d8108d0caa3ab2daeafd1d25d680214ef26))
- ✨ local stuff ([9afad1a](9afad1a1680073006d946be10f8c97b75ddfe253))
- 📝 fix update issue template ([da290db](da290dbcf2952a56be9334f7bf9dc4d8fa64a21d))
- 📝 update issue template ([b949bb4](b949bb406bc1929634600465ea389eaedefe6e6f))

### Refactor

- ⚡️ small local fixes ([bcac665](bcac66508d2e788cc437da289d1ccede19465b8c))
- 🗑️ remove unused code in install script ([5b75436](5b75436610c6312adf47c6baa3e9fe9cc7d56dcf))

### Merge

- 🔀 pull request #109 from melMass/dev/0.2.0 ([87e301d](87e301d120a542d5aabe544bec10d38dbd19b2f6)) in #109
- 🔀 pull request #86 from melMass/feature/styles-editor ([cbdb816](cbdb816164900061ddaa1671f4287763d0b79ee1)) in #86

## New Contributors
* @ScottNealon made their first contribution in #147
* @Yurchikian made their first contribution in #124
* @M1kep made their first contribution in #91
## [0.1.4] - 2023-08-12

### Bug Fixes

- 🚀 pending fixes ([ea5d73d](ea5d73d48cfa4046f48a52609cff7f754d8364ed))
- 🚑️ image resize infinite loop ([30d6cfe](30d6cfe81292d0f7702544b3c2cbad1820c4a926))
- ✨ update example files ([610afe0](610afe031f21d737b2fd5128e4be7100b6666181))
- 🐛 simplify install steps ([4fc84d6](4fc84d615dd0f546442c3537f00c52366db4ca9b))
- ✨ refactor ([8523392](8523392df74c586dc940841ddbb5069943b16f7d))
- 🐛 debug rgba ([40560f8](40560f8154d3ddeabf708be4d111370648d466ac))
- 🎨 rename fun to generate ([e7f72f9](e7f72f9825da58254e3084b4ba91f76e6cf2cf5f))
- ✨ refactor existing ([1144466](11444662b9198861b62aff06a08b9c9ea01dd8bd))
- ⚡️ move getbatchfromhistory to graphutils ([2eccba4](2eccba4e33b21d1d080cb2f415f76a93488120f0))
- 🚧 wip dependency installer UI ([630b492](630b492347f75d7308b31a000061b41d7dfa4a10))
- 🐛 image feed zorder ([0fb2d4d](0fb2d4da90a7e65f82b3f9c8942a68e360456cf7))
- ⬇️ download_antelopev2 ([4dd5321](4dd532185223a1fa5978446e7bb75d32d77ebdb5))
- 🚑️ frontend pushed too early ([91f60d4](91f60d4c463c474ac10e868e8e73e13fa019856b))
- 🚑️ missing input ([84ac8ac](84ac8ac852aeb962029bfd8369fe5ed59a203977))
- 🐛 shell command bug ([3d5075f](3d5075fea2e219a179271c9810017c7e38bff6cc))
- 🚑️ remove pipe mode from the install.py ([b854a30](b854a302ce4708d2ad2dac249860308dbdcae5a6))
- ⚡️ colab install ([36d8e6b](36d8e6bdb06edab72ccfb686266d2e644a9f028c))
- 🚑️ install typo ([ffa1a87](ffa1a87b9184df5a3699a6118714b39d359bde4d))

### Documentation

- 📝 link the actual action instead of badge ([098d74a](098d74a3cd8449d836569a074995e20d775c6728))
- 📝 add action badge ([e74314b](e74314b04eb218c140482ccf704b61af06db3f4d))

### Features

- 💫 export to prores -> export with ffmpeg ([a4d99d9](a4d99d966b1207191243a9749385b998d1a9c6b1))
- 🔥 add any to string & refactor ([dbdb872](dbdb872b74e18c16feb44bd037abc3aafbb4700f))
- ✨ add UI for interpolate clip sequential ([5ec5511](5ec551143302b2a94ca82e477f684ecee23f1459))
- ✨ add portable reqs ([3f14b16](3f14b1676d28f5ffa1f47fda00b9bc244951045c))
- ✨ add border extension ([fb64484](fb644847ca434123e8e8e4991d33949fd31e3cbe))
- ✨ use PIL for gif saving ([2bc7ae8](2bc7ae88bf4cdfa575d11233c0e6f7b07f9dfd23))
- 🎨 update node list ([a54d7d5](a54d7d5346c272898dd4e67c65495de7325ab3a0))
- ✨ install fix ([512de60](512de6023e55f2cc47516bf44436efe22157273f)) in #41

### Miscellaneous Tasks

- 💄 encoding ([49c64c7](49c64c74eb3e99f456b563bbd79e3fe47a85c70d))
- 🚀 only fetch controlnet_preprocessor deps ([414beb9](414beb99a1f9bf719eca6ac139c9b2ccdfd6d743))
- 🚀 add controlnetpreprocessors to tests ([63b3aec](63b3aece2ba05adc2b655afeb41e3d47e7887b33))
- ✨ remove unused input ([d4f791d](d4f791d7a14ba9cb8abd7c95ba70b081fee5fb7c))
- ✨ use the same cwd as manager ([2ff0467](2ff04672daff773d52e1552dca1bf616bc32daa6))
- 🎨 no brace glob ([bbfcb62](bbfcb62c398de39058bcb6e18161425059d53e8e))
- 🎨 extract txt ([a22fd01](a22fd01d664276e4cd833ae1326feeece1d1deaf))
- 🎨 also push wheels_order to releases ([8e5b776](8e5b7765cc0c6730bd5517ccfd56e817ea39bd3a))
- 🚧 more info for bug reports ([3dadc11](3dadc119f44fca1029ec4b349d71ce99fb20a4b6))
- ✨ individual wheels ([346ff64](346ff649d50c9f0286ad2243938406fefb62853b))

### Refactor

- 🚧 tidy ([4f30829](4f30829e06c41b3685644bfe7bece07e0bcfb70e))
- ♻️ get batch from history ([13d255a](13d255a730b08c4903647875350b9b3dcd61b4a6))

### Revert

- 💄 use BOOLEAN instead of BOOL ([cfb3b23](cfb3b237cf64b512414a17f71e6d89c3355aa8ef))

### Testing

- 🧪 remove sha input ([c5bbe83](c5bbe83008bb194cbd6ad5e3dc70cb3850b18985))
- 🧪 ci for comfy embedded ([7b3afca](7b3afca8179760e35e8a6fbf742080dee13e4fc7))

### Merge

- 🔀 pull request #50 from melMass/dev/august-refactor ([2ecd470](2ecd4700d77c0727e6b5d2124e0a6ebd48ec96ed)) in #50

## [0.1.3] - 2023-07-29

### Bug Fixes

- 🔥 manage pip from install only, remove requirements.txt ([247fbfb](247fbfbc216b8259d607e0699d5b990b6a06ca71)) in #38
- 🎨 use image ratio for imagefeed ([f5cd56c](f5cd56ce861c8c0a931744ae6cf2b96e9c8bca06))

### Documentation

- 📝 update imagefeed preview ([cbcacbe](cbcacbe3c92ebb5f74d046b83504c3723710f130))
- 📝 fix typo and add more details ([7c020ba](7c020bab288aa7d17dc937b5f102319d43c3ebb3))

### Miscellaneous Tasks

- ✨ use wheel order if present ([9b24edd](9b24eddd9c51004af08d7ac6ff2b6473dd3ee161))
- ✨ store order of install for wheels ([5053142](505314294f02e7c19ac95e4d0ed37fd397a54b46))

## [0.1.2] - 2023-07-28

### Bug Fixes

- ✨ various small things ([0e311cf](0e311cf2c64cf2b4861d4cc612a3409390e3039a))
- 📝 last release ([889f08c](889f08c08b721be8fdb4e4d7eacc47169d5692d6)) in #36
- 📝 narrow requirements ([5d661b2](5d661b2509fecf3940c3c0fab25b16ec0eae7a2d))
- ✨ Separate FaceAnalysis model loading ([d143e83](d143e83dba3bffa16e1b98d7ad1e9cf92dc94db2))
- ⚡️ update examples to match wiki ([3dfe98c](3dfe98c7957df48723380de85e1242a424ec23de))

### Documentation

- 📝 add readme for web extensions features ([be162a2](be162a20477258627fa0d742c97a478bd085ff4f))
- 📝 link to the proper lang instructions ([232cf89](232cf8966cc20291b60c68f487dfd37bf6aa4dfa)) in #33
- 📝 update readmes ([96a0618](96a0618c5990a8559a9e2dd17c868d3465b8ca90))

### Miscellaneous Tasks

- 🎉 bump version ([9e751a2](9e751a242f4e9afee3dc5c871c414b29b9706ff6))
- 👷 remove stale example ([c237737](c2377374201fc34b107c8b7db1cdeb2f483d1e18))
- 🐛 fix size ([c0cc557](c0cc5572d8c727568eca8a3d0f116a1f540c31ff))

## [0.1.1] - 2023-07-24

### Bug Fixes

- 🎨 improve a bit the HTML response of endpoints ([50d51c7](50d51c70d04e49e9df524975c171288c0fc0b20f))
- 🐛 caching issues ([55c9736](55c9736a9b2ca036926be4b06406121bfb9ebad2))
- 🔥 remove notice ([abf1e82](abf1e82adb9fac8cd70d5c409baad55309ef6fe1))
- 🔥 use BOOL everywhere ([a393793](a393793cfa93721eac46295723076a1dda940dcd))

### Documentation

- 📝 added lang links ([bbdac97](bbdac97e49af4e90d22eeec3f63b96ecc126ffcf))
- 📝 add comfyforum example ([10d0503](10d05031b1791ab3534cf838be6eb75df638dfb6))

### Features

- 🚧 jupyter seems to require an __init__ there ([9a4eda3](9a4eda3ef573bf382c13515f67ae8a415bf61abd))
- ⚡️ use notify ([a2ecc11](a2ecc11ebde79c2403959bf09c258f3a2465894a))
- ✨ first version of Notify ([7e9c97e](7e9c97ecb48672b25e5ed17b9b35dba9208ac311))
- ⚡️ add an "actions" endpoint ([3de160a](3de160af25b516c02aaa8cc32baec16e9ef358fb))
- ✨ add Unsplash Image node ([8d3cc39](8d3cc39b72dff1b5eb61bf7e2e395753c138ec8a))
- ✨ add back Save Tensors ([7142b28](7142b284adc7fba9a1bdafd1a52621bfc168bde1))
- ✨ add TransformImage node ([11128ff](11128ff85a7e0b4a54f405548969c2478da26df6))

### Miscellaneous Tasks

- 🚀 bump version ([cf86552](cf865529ab64b350cd7af964b41160e7d130d12d))
- 🚀 Remove large files from release ([3b9190a](3b9190a69b002b8933c097fd6655bb4fe07264d2))

### Refactor

- ✨ cleaned up frontend code a bit ([3801a44](3801a443bc1e89c70fdb35ce0b1724d86fa22928))
- ⚡️ remove empty inits ([21729b2](21729b2784a50fcaf24a63ac283bdae475a53ce7))

### Merge

- 🔀 pull request #32 from melMass/dev/next ([8695cd3](8695cd3f1b6d27b5cd6c616ed1215ea2f25c5304)) in #32

## [0.1.0] - 2023-07-22

### Bug Fixes

- 🔥 properly match built wheels ([119b4d6](119b4d6e16c2a90db1664ccaac748507feb73ea0)) in #30
- ✨ also try to copy web if symlink fails ([0df55de](0df55def29fb992751010f6b8a707699f230ff37))
- ✨ install process tested in comfy-manager (embed, colab) ([b40730d](b40730ddbc3f8e3e7d5a17e9e9e4526ff37977fd))
- 🚀 try to support remote install too ([3c66de2](3c66de2500a89efd2d2e3af88fc58429af725789))
- 💄 save gif issues ([7335003](7335003346e83666c5dee631b8e6b15586d871e7))
- 🚑️ always use latest for now ([fccf313](fccf31348994ab6e344a1ab00a8f9998309f9319))
- 🐛 install logic ([7e301e2](7e301e2a067d41cba9b8ef357496dd1df94e4cdd))
- 🎉 remove tests & add missing docs ([4e6b877](4e6b87719989aa144946c5c9a43b9398c20bf11e))
- ⚡️ update node_list ([c794d6a](c794d6a071778220d654b526d2edfddcc79752fc))
- 🚑️ set debug level from endpoint ([18402e3](18402e3be1ab47e10109cfd2dff18863a1ee56f7))
- 🐛 add base64 prefix to outputs ([0950f99](0950f9914c9bbed7c89f3de33a967cb76f9d0bbb))
- 🎨 refactor and add Gif preview on node ([c2e8379](c2e83794faeb8da708c98908882e38b2a42827bd))
- ✨ Various widgets issues ([27500ca](27500ca432d686774b991045b7cffc58c0b67faf))
- 🔥 deprecate some nodes and fix image list ([9aa934f](9aa934f70ff6adf91efb26aa8e5cb21ec575196a))
- 🐛 crop nodes ([67d3783](67d3783ac9186da6bba4b7dc7e8dc3d5db5a1b0f))
- 🐛 tensor2pil ([8a59508](8a59508ff91d6b2d9ca287ef1c054ec5755337a4))
- ⚡️ a few missing __doc__ ([ab09cca](ab09ccadd905bebbf1b7b2d992e96e36fc60d68a))
- ⚡️ from tensor2np always returning a list ([6168b3a](6168b3a2ac38b5eebed3daf9e52df5742abf6813))
- 🚑️ TF by default fills vram ([c225da5](c225da5f298acb4cb2b39022382543c0c966d428))
- ✨ leftovers ([da3e6f4](da3e6f47c6073e73cf9d3a3cd23ba5ccbe1fedce))
- ✨ handle non fork gdown in model dll ([95797e8](95797e823e12e62ae8758753f60c34afbe19ec90))
- ✨ properly add the submodules ([00510ed](00510ed0b8583dd64518daa67d963582f4f029d3))
- 📌 remove sad talker for now ([1622cbc](1622cbcb9d51ddd0e1a8b4d87ba47b99327163eb))
- 🎨 narrow requirements ([1a92ef7](1a92ef734dd4271efc875856038f9e3b6b9ded6c))
- 🚀 use the comfy util to handle graph interruption ([9752f3e](9752f3e9dec9aa59cfa809aa14f0151594c03858))
- 🔥 much faster (using GPU) on windows ([2f455aa](2f455aaca55c0a044735c768b295d077b2f5b8d6))
- 🐛 uint8 to uint16 ([be5a655](be5a655cfaba1794f7b09c82d65de42e2b031720))
- ✨ add missing requirements ([b779bc3](b779bc39ac19f779aeb73c98b916671d1d16806f))
- 📝 don't propagate base logs ([7fd99c2](7fd99c25c4e50566def5c5166a9d9059b1febfa6))
- 🐛 bg upscaler in gfpgan ([fee48ad](fee48adff3d66960cb17836f3f4efbfd0c8740c4))
- 📝 separate debug / info better ([e24863d](e24863d1f9f63f367a2b392e6228ffa42927b71b))
- 🔥 change log level of the base logger ([7538c2c](7538c2c4bad8390a32226dc0a5a6ef978b00d201))
- ✨ handle externs dynamicly ([6ef308a](6ef308a87062c91e2d7249c05d96c6fb76e5a6c4))
- 🐛 separate faceswap model load ([8e267c0](8e267c0204ce5abe8e113fd401234d49f377646a))

### Documentation

- 📝 fold each comfy mode ([3c3c438](3c3c4380bd1a3f0eed5216b835e076c26fce2f88))
- 📝 add more description to examples ([46eab5c](46eab5ca2f0e04d872d87c849b11551fd219bdb9))
- 📝 add model notice ([cbe67ed](cbe67edd4befb7260be01fa09af8448e5bcf5680))
- 📝 add preview for examples ([b5176ca](b5176ca0ee489ada52b6632f68b794b4f709d5ba))
- 📝 add jp and cn (using deep translation) ([da559b9](da559b9eaf135a49c0ab9bfa45573baf0c18dfb2))
- 📝 update readme ([b0fb522](b0fb5222cb19e4004533d3367863be5c9ce8e72b)) in #15
- 📝 update README.md ([f8dc768](f8dc768635a2d21f6ff81b42c418724c432159bf))
- 📝 updated instructions ([c3b9fd4](c3b9fd4afedbb46748aef17b40e167a4cfad65f5))

### Features

- ✨ update install instructions ([7be37db](7be37dbbfac45e8038f94ced8a2fa8ec2b06fb34))
- 🚀 add install script ([dad3966](dad3966ba219c1998e4fc7f6e641864fb0e7c3e8))
- 🚧 add my CLIs ([44eaae5](44eaae5c79f4dbec344053d945e7275be5c3c0a5))
- ✨comfy_widget shared utils ([91bb95d](91bb95da914468de533b040324700c7f9707e4fb))
- 🚀 debug node ([b27b8ef](b27b8ef91fe7335b1df3766547edaf4b9625ae4d))
- ✨ add FitNumber node ([aa551eb](aa551ebe57801c69010815119fe21e19a858780c))
- 🔥 add API endpoints ([95afbdb](95afbdbf76e66897e632252d876384ada9acf153))
- ✨ categorize ([d2b3962](d2b396236a10fe620ebebabd5a22c36159921913))
- 🚀 add a few examples ([b9c1d3d](b9c1d3df7a1460fe9ffa84f6f9ea0cfb5409de1a))
- ✨ added a way to export the node list ([5f5297f](5f5297f80debc77f3fda2f0d37b3acff8419140d))
- ✨ WIP batch from history ([cde7293](cde72938d5ffd09179f5974676e12d4599a8d6ff))
- ✨ extract node names using ast ([38f6147](38f61473bc23b4c5d4efc5048d54c059565a6fa0))
- 🔥 add batch support for load image sequence ([3faadc4](3faadc4b8a5049cb8c264b8a3d50565adec405f1))
- 🎨 add support for image.size(0) == 0 ([629e2b5](629e2b5f5fbebe4e79e8b7a4cff2de6017e79225))
- ✨ image feed ([99eb5ae](99eb5ae0c7413f6ab1f24cfc8337c9b1b2d9824c))
- ✨ FILM interpolation nodes ([e04e77e](e04e77eb097735ec1369dec51238cdcc5abe39b7))
- ✨ add an headless option for model downloads ([217e8a1](217e8a1546d06b97250d99612ac6bdb5ce89e155))
- 🐛 support batch count > 1 for restore face ([8ef48a0](8ef48a013a8d6b832b8c0c7dcabc1b78c27ff207))
- 🚧 wrapper for GFPGAN bg upscaler ([88cdcc6](88cdcc6a87dae452924e8915eccdadc69d7d136e))
- ✨ add GFPGAN (FaceRestore) ([3a6e545](3a6e5450502f3b1d7c505178fc9ba337cd95c39e))

### Miscellaneous Tasks

- ✨ before categorize ([0cc54e5](0cc54e58ec86c28354cae37e14f39e831c13ea02))
- ✨ add more issue templates ([710a638](710a638a8187ef08254478f684307dccdebcded2)) in #25
- ✨ add bug report template ([f927bc7](f927bc7c9a82951e6df4763433732f20ea87e9cb))
- 🍻 create FUNDING.yml ([f634fe0](f634fe0e6b2db28138e4bd7932fbfc8606a0f033))
- 🍻 add bmc to readme ([cd1b603](cd1b603565464fe98a718e1fbaa8c7cd84057576))
- 📝 extra files from another branch ([b78be8f](b78be8fd3cd36666fd94a3ab08eca11cce526043))
- 🚀 push leftovers ([4c41fe7](4c41fe7af9f8e16d895eb06223349e1294dd4698))

### Refactor

- ♻️ removes a few nodes, moved other around ([4d8ddac](4d8ddaca320ce483640d030618e70730b3453df2))
- ♻️ remove test ([68c250e](68c250e890dacae9f627b0d266ad6dcab0fa0c8b))
- 🚧 remove color_widget ([e480d07](e480d071171cffa789930620f1e7ccc76473bf93))

### Testing

- 🔧 pipe detection ([ee17d57](ee17d57c3d6d71fda1a5acc2cf85f936c525bc87))

### Install

- 🚧 handle symlink errors ([d982b69](d982b69a58c05ccead9c49370764beaa4549992a))

### Merge

- 🔀 pull request #22 from melMass/dev/next-release ([c34de0a](c34de0ab351b2c95d7fa4fab4487155bee6bfa3a)) in #22
- 🎉 pull request #11 from dev/frame_interpolation ([1e28606](1e28606427bcc8d895b87eaa6cd4147ab6d9a11f)) in #11
- 🎉 pull request #8 from dev/small-fixes ([7585624](7585624de5895eb34c6a520d4dab18b47e64b6ca)) in #8

## [0.0.1] - 2023-06-28

### Bug Fixes

- 🤦 add missing file ([e2c4561](e2c456147c260b4e9d583662e3bb9d6d9a019a5e))
- ✨ small edits ([bcf55ca](bcf55ca9a3a07067be3319182501f7b635e5d2ba))
- ⚡️ add support for batch in roop ([2dae020](2dae02056a11ddfe1f84ee040818028177e404b5))
- 🔥 various preparing for the first tag ([793784a](793784a5fd08e8a70d670fc8edbc3bb5b6e13e67))
- 🐛 various bugs ([afd0843](afd08431458e3bbb14a25c84a87408113edf5db5))
- ⚡️ add missing controls to QRCode ([7e86b0e](7e86b0ed4d300021517f6c5cf28a45012497b5c5))

### Documentation

- 📝 add rembg screenshot ([9a2d523](9a2d52325f87ecf6342ef4897da919006755b9db))
- 📝 add a few screenshots ([e162336](e162336cd366d39cd4b96f05b3c9c68eecec3dc4))
- 📝 update readme ([7f3070d](7f3070debbc3330da50ff845621ce299894cf862))

### Features

- 💄 faceswap node using roop ([966a14b](966a14b40d88f4fccfb2eaa5ff9b222f0eedd7cb))
- ✨ sync local changes ([647bf9e](647bf9e94195c279a620c74c2253471b9c4b90f7))
- ✨ bbox from alpha ([37abf8a](37abf8aad12f4711c6d82c6be4be6fa3578e7af5))
- ✨ a111 like style loader ([f59b68e](f59b68e3ad92841a4d189d8dddf7b41e915c9b4e))
- ✨ add a color type and widget ([9a2e986](9a2e986327c34227a707beab6d9929b0a05e41e6))
- ✨ add a few nodes ([811443b](811443b92161815db1cdff81898e8834dcd6fbfa))
- ✨ add SadTalker as a submodule ([3fb8716](3fb871651b12bce62d8e911bd3884f417f80c937))
- 🚨 push local changes ([6cac344](6cac344f6fb15ebb902acee70ee71edc585ec4bc))
- ⚡️ initial commit ([1ae3bbc](1ae3bbc89ae6e0d2e8c61122485bd0df837e17c2))

### Miscellaneous Tasks

- 🚀 add gh action ([572b4d5](572b4d52bce1398660d4d7ca0c5c48c11e0128e3)) in #4

[main]: https://github.com/melMass/comfy_mtb/compare/v0.1.4..main
[0.1.4]: https://github.com/melMass/comfy_mtb/compare/v0.1.3..v0.1.4
[0.1.3]: https://github.com/melMass/comfy_mtb/compare/v0.1.2..v0.1.3
[0.1.2]: https://github.com/melMass/comfy_mtb/compare/v0.1.1..v0.1.2
[0.1.1]: https://github.com/melMass/comfy_mtb/compare/v0.1.0..v0.1.1
[0.1.0]: https://github.com/melMass/comfy_mtb/compare/v0.0.1..v0.1.0

